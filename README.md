# Documentação técnica para a configuração de uma instância de banco de dados na Azure
Este repositório contém a documentação técnica para a configuração de uma instância de banco de dados na Azure.

Para configurar uma instância de banco de dados na Azure devemos seguir os seguintes passos:

1. A partir da página inicial, clique em todos os serviços no menu lateral.

![Menu lateral](images/img_1.png)

2. Na tela de todos os serviços, selecione a categoria Banco de dados.

![Categoria banco de dados](images/img_2.png)

3. Selecione a opção Instância Gerenciada de SQL do Azure.

![Opção Instância Gerenciada de SQL do Azure](images/img_3.png)

4. Preencha os dados do formulário de configuração da instância.

![Formulário para a configuração da instância](images/img_4.png)

5. Escolha um grupo de recursos. Caso não existam grupos disponíveis, é possível criar um grupo.

![Grupo de recursos](images/img_0.png)

6. Escolha um nome para a instância.

![Nome para a instância](images/img_5.png)

7. Escolha a região.

![Região para a instância](images/img_6.png)

8. Escolha o método de autenticação.

![Método de autenticação](images/img_7.png)

9. Defina o logon de administrador da Instância Gerenciada, informando qualquer nome de usuário válido.
10. Defina a senha.
11. Confirme a senha definida.

![Logon de administrador e senha](images/img_8.png)

12. Em detalhes da instância gerenciada, selecione configurar instância gerenciada na seção Computação + armazenamento para abrir a página Computação + armazenamento.

![Configurar a Instância Gerenciada](images/img_9.png)

13. Na página Computação + armazenamento, configure a camada de serviço.

![Camada de serviço](images/img_10.png)

14. Configure o hardware de computação.

![Hardware de computação](images/img_11.png)

15. Escolha um valor para a quantidade de vcores.

![vCores](images/img_12.png)

16. Escolha um valor para o armazenamento em GB.

![Armazenamento](images/img_13.png)

17. Escolha uma licença para o SQL Server.

![Licença para o SQL Server](images/img_14.png)

18. Configure o Backup (Redundância do armazenamento de backup).

![Redundância do armazenamento de backup](images/img_15.png)

19. Clique no botão aplicar para salvar suas configurações e navegar de volta para página Criar Instância Gerenciada de SQL do Azure.

![Botão aplicar](images/img_16.png)

20. Na página Criar Instância Gerenciada de SQL do Azure, clique no botão Avançar: Rede. Preencha informações opcionais na guia Rede. Se você omitir essas informações, o portal aplicará as configurações padrão.

![Botão Avançar: Rede](images/img_17.png)

21. Na guia Segurança, deixe as configurações em seus valores padrão.

22. Selecione Revisar + criar para examinar suas escolhas antes de criar uma instância gerenciada de SQL. Ou defina mais configurações personalizadas selecionando Avançar: configurações adicionais.

23. Caso você clique em avançar para as configurações avançadas, preencha as informações opcionais na guia Configurações adicionais. Se você omitir essas informações, o portal aplicará as configurações padrão.

24. Selecione Revisar + criar para examinar suas escolhas antes de criar uma instância gerenciada de SQL. Ou, então, configure as marcas do Azure selecionando Avançar: Marcas (recomendado).

25. Caso você clique em avançar para configurar as marcas (Rótulos), adicione tags aos recursos no modelo do ARM (modelo do Azure Resource Manager). As marcas ajudam você a organizar logicamente seus recursos. Os valores de marca são mostrados nos relatórios de custo e permitem outras atividades de gerenciamento por marca. Considere pelo menos marcar sua nova instância gerenciada de SQL com a marca Proprietário para identificar quem criou e a marca Ambiente para identificar se esse sistema é Produção, Desenvolvimento etc.

26. Clique no Botão Revisar + criar para prosseguir e examine suas escolhas.

![Botão Revisar + Criar](images/img_18.png)

27. Selecione Criar para implantar sua instância gerenciada de SQL.

![Criar](images/img_19.png)