# planilhadequest-es
Controle sua questões através de uma planilha automática.
1. Faça uma cópia da planilha disponível no link e altere a pontuação para a quantidade de pontos da sua prova:
https://docs.google.com/spreadsheets/d/1npFzOAQ7_7iMh-JV86Vr406iYXDlctCPm4d3F48hJOk/edit?usp=sharing
![Captura de Tela (46)](https://github.com/user-attachments/assets/e88f89d8-b764-4a71-b1c2-405450a494c9)
2. Insira o link do filtro de questões e o nome para indentificação na aba 'Apostilas':
![Captura de Tela (48)](https://github.com/user-attachments/assets/9fe9c713-9df7-48d0-a710-fc34590b91b6)
Obs: Pode ser feita qualquer divisão desde que tenha um filtro como link.
3. Insira uma estimativa de pontuação para cada matéria.
![Captura de Tela (50)](https://github.com/user-attachments/assets/6c746ea0-7806-477a-b2a3-8cfc020909bd)
4. Acesse a aba Apps Script:
![Captura de Tela (52)](https://github.com/user-attachments/assets/2359d7e2-7df2-4210-a69b-aef38f95c9b2)
5. Adicione um acionador automático de script 'passar_valores' ao editar:
![Captura de Tela (54)](https://github.com/user-attachments/assets/ae07d37e-77b9-469b-950a-2fd92ba28837)
6. Conceda as permissões necessárias:
![Captura de Tela (55)](https://github.com/user-attachments/assets/49d2ea36-7dae-4653-9ccb-9aa77f3cda53)
Obs.: Essa fase é importante pois nem todos os aspectos da planilha são transferidos ao copiar.
8. Permita a execução automática de prompt:
![Captura de Tela (56)](https://github.com/user-attachments/assets/d1c12027-a12c-42a7-b75b-02afedf3647d)
9. Insira um acionador diário para a macro 'conferenciaRevisão':
![Captura de Tela (57)](https://github.com/user-attachments/assets/3e21449e-e0d4-46e0-a970-489fde0f0e7f)
10. Insira o link da questão resovida na célula 'H14' da planilha 'Apostila em Questões' e permita acesso a conteúdo externo:
![Captura de Tela (58)](https://github.com/user-attachments/assets/3742eaad-ea66-4891-8784-ae32c49735a8)
11. Depois de feito isso os link de filtro serão abertos automáticamente em ordem:
![Captura de Tela (59)](https://github.com/user-attachments/assets/95b34d23-36f0-43f5-87e0-88ed77df9e0f)

Após esses passos a planilha estará pronta. Algumas considerações finais:
1. Caso sua prova não tenha diferença de pontuação, a valor atribuido a pontuação deverá ser igual ao número de questões.
2. O código pode ser visto em script, após realizar a cópia da planilha:
![Captura de Tela (60)](https://github.com/user-attachments/assets/23382d34-e86a-4967-b115-45287185d841)
3. A revisão será feita automáticamente de acordo com a quantidades média de questões que realiza por dia e de acordo com a data da prova inserida na planilha 'Planejamento'.
4. A revisão pode ser forçada. Trata-se de refazer as questões que errou.
5. Caso as questões de alguma matéria acabem se inicia um novo ciclo de novas questões.
