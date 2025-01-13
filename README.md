# Banco de Dados de Livraria
(Projeto 1 de banco de dados da Kenzie Academy)

## 1 Introdução

Nesta entrega, colocaremos em prática nossos conhecimentos, criando o banco de dados representado no diagrama abaixo:

![image](https://github.com/user-attachments/assets/61e6be36-3201-435a-9e59-bf9cc8e8c40b)

Além da criação do banco de dados e suas respectivas tabelas, será necessário também trabalharmos todos os tipos diferentes de consulta: inserção, leitura, atualização e exclusão.

## 2.1 Criação do Banco de Dados e Tabelas
Crie uma pasta nomeada "sql" em seu projeto, dentro desta pasta crie um arquivo chamado "database.sql". Em seguida, escreva o comando de criação de cada uma das tabelas, seguindo as orientações abaixo:

- Certifique-se de que todos os relacionamentos entre tabelas tenham a referência de chave estrangeira.

- Na relação entre "books" e "categories," a cláusula "ON DELETE" para ambas as chaves estrangeiras deve ser definida como "CASCADE". Isso permitirá que, caso um livro ou categoria seja excluído, o relacionamento seja excluído automaticamente.
  
- Na relação entre "authors" e "books", a cláusula "ON DELETE" deve ser definida como "SET NULL". Isso garantirá que, caso um autor seja excluído, o valor da chave de relacionamento seja alterado para null.

- Na relação entre "authors" e "contact_infos", a cláusula "ON DELETE" deve ser definida como "CASCADE". Assim, se um autor for excluído, as informações de contato relacionadas a ele também serão excluídas.
  
Após escrever todos os comandos de criação de tabela, teste cada um deles no terminal para garantir que não há erros sintáticos e que as relações estejam configuradas corretamente.
