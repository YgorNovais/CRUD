
# Aplicação CRUD usando Javascript, Node.js, React, HTML, CSS, MySQL e SQL.
Este repositório contém uma aplicação CRUD (Create, Read, Update, Delete) construída usando XAMPP para o backend e React para o frontend. A aplicação permite aos usuários gerenciar registros de alunos realizando operações CRUD através de uma interface simples.

## Tecnologias Utilizadas
* Node.js: Permite executar JavaScript no servidor. No contexto deste CRUD, Node.js é utilizado para criar e executar o servidor web.
* React: Usado para construir a interface do frontend da aplicação.
* axios: Um cliente HTTP baseado em promessas para fazer solicitações ao servidor backend.
* XAMPP: Fornece a infraestrutura do backend, incluindo Apache e  MySQL, para lidar com operações no lado do servidor.
## Instruções de Configuração
1. Configuração do XAMPP:
* Instale e configure o XAMPP em sua máquina local.
* Inicie os serviços do Apache e MySQL usando o painel de controle do XAMPP.
2. Configuração do Banco de Dados:
* Acesse o phpMyAdmin (geralmente disponível em http://localhost/phpmyadmin).
* Crie um novo banco de dados chamado "crud".
* Importe o arquivo SQL fornecido (database.sql) para criar a estrutura da tabela necessária.
3. Configuração do Backend:
* Clone este repositório.
* Coloque os arquivos de backend (scripts PHP) no diretório apropriado da sua instalação do XAMPP (geralmente xampp/htdocs).
4. Configuração do Frontend:
* Navegue até o diretório frontend.
* Instale as dependências executando npm install.
* Inicie o servidor de desenvolvimento do React usando npm start.
5. Acessando a Aplicação:
* Visite http://localhost:3000 em seu navegador da web para acessar a aplicação CRUD.
## Backend 
Responsável por lidar com operações CRUD no banco de dados MySQL. Esses scripts estão localizados no diretório backend.

* index.php: Define pontos de extremidade da API para operações CRUD.
* create.php: Manipula a criação de novos registros de alunos.
* read.php: Recupera todos os registros de alunos do banco de dados.
* update.php: Atualiza um registro de aluno existente.
* delete.php: Exclui um registro de aluno do banco de dados.
## Frontend 
O frontend é construído usando React e contém componentes para criar, ler, atualizar e excluir registros de alunos. Esses componentes estão localizados no diretório src.

* App.js: Componente principal que define rotas para diferentes visualizações da aplicação.
* CreateStudent.js: Componente para adicionar novos registros de alunos.
* Student.js: Componente para exibir uma lista de registros de alunos.
* UpdateStudent.js: Componente para atualizar registros de alunos existentes.
## Uso
* Navegue até a página inicial para visualizar uma lista de registros de alunos existentes.
* Clique no botão "Adicionar" para adicionar um novo registro de aluno.
* Use os botões "Atualizar" e "Excluir" para modificar ou remover registros de alunos existentes.
## Autor
[Ygor Novais]
