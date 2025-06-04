# atividade-
-Para essa atividade vou explicar como funciona os botões e uma breve introdução de como o projeto funciona:
1- Botão de Entrar:
Verifica se o usuário e a senha estão corretos.
Se estiverem certos, faz o login.
Se estiverem errados, mostra um aviso.

2- Botão de Cadastrar:
Cria um novo usuário com a senha informada.
Se o nome de usuário já existir, mostra um erro.
Se for novo, salva no banco de dados.

3- Botão de Alterar:
Atualiza a senha de um usuário já existente.
Você precisa informar o nome de usuário e a nova senha.
Pede confirmação antes de fazer a alteração.

4-Botão de Deletar:
Apaga um usuário do banco de dados.
Você informa o nome do usuário.
Pede confirmação antes de apagar.

5- Botão de Registro:
Mostra todos os usuários cadastrados.
Exibe a lista na tabela da tela.

Introdução ao Projeto – Sistema de Login e Cadastro (Java + MySQL)
Objetivo

Permitir que usuários:
-Se cadastrem
-Façam login
-Visualizem a lista de usuários
-Alterem senhas
-Apaguem usuários

Como funciona?
1- Ao abrir o programa, ele tenta se conectar ao banco de dados.

2- O usuário pode digitar seu nome e senha nos campos de texto.

3- Com os botões, ele pode:

-Entrar com seu login
-Cadastrar um novo usuário
-Visualizar registros já cadastrados
-Alterar a senha de um usuário
-Deletar um usuário

-Banco de dados
-Tabela chamada conta
-Campos: login (nome de usuário) e senha

 Tecnologias usadas:
1- Java (com Swing para a interface)
2- JDBC (para conectar com o banco)
3- MySQL (armazenamento dos dados)
