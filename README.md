# Job Finder 🕵🏻‍♂️

## Aplicação Web de Quadro de Empregos
Este projeto é uma aplicação web simples de quadro de empregos construída utilizando Node.js, Express.js, Sequelize ORM e o mecanismo de templates Handlebars. Ele permite aos usuários visualizar listagens de empregos e pesquisar empregos com base nos títulos.

## Funcionalidades
- Visualizar uma lista de vagas de emprego.
- Pesquisar empregos por título.
- Adicionar novas postagens de emprego.
- Editar e excluir postagens de emprego.

# Instale as dependências:
- npm install
- npm install express
- npm install express-handlebars body-parser sequelize sqlite3
- Certifique-se de ter um servidor de banco de dados SQlite em execução.
- Configure a conexão com o banco de dados em ./db/connection.js.


## Inicie a aplicação:

- npm run dev

## Possível erro

Se ocorrer um erro no console, altere a versão conforme indicado abaixo:
  

![Captura de tela 2024-03-06 142752](https://github.com/rxodrigues/Job-Finder/assets/137015987/d55e5414-7f25-4e8b-8baa-a6347ac6bd1c)



## Estrutura do Projeto
- app.js: Ponto de entrada da aplicação onde o servidor Express é configurado.
- db/connection.js: Arquivo responsável por estabelecer a conexão com o banco de dados.
- models/Job.js: Modelo Sequelize para a entidade Job.
- routes/jobs.js: Roteador Express para rotas relacionadas a empregos.
- views/: Contém os templates Handlebars para renderização de views.
- public/: Contém arquivos estáticos como folhas de estilo CSS, arquivos JavaScript do lado do cliente e imagens.
- README.md: Arquivo de documentação explicando como instalar e usar a aplicação.
Dependências
- Express.js: Framework web para Node.js.
- Sequelize: ORM Node.js baseado em promessas para MySQL, PostgreSQL, SQLite e MSSQL.
- Express Handlebars: Mecanismo de visualização Handlebars para Express.js.
- Body Parser: Middleware de análise de corpo Node.js.


## Contribuições
Contribuições são bem-vindas! Se deseja contribuir para este projeto, por favor faça um fork do repositório, crie um novo branch, faça suas alterações e submeta um pull request.

Autor: Leonardo Rodrigues

## Imagens do projeto
![Captura de tela 2024-03-06 143018](https://github.com/rxodrigues/Job-Finder/assets/137015987/a43d6f17-defb-48a6-a840-3d7db47d0328)
![Captura de tela 2024-03-06 143033](https://github.com/rxodrigues/Job-Finder/assets/137015987/48f65b95-1c44-4b16-bad5-ab74c0746f17)
![Captura de tela 2024-03-06 143151](https://github.com/rxodrigues/Job-Finder/assets/137015987/43ef100d-f5e1-45c6-aa81-d286ff9fda17)
![Captura de tela 2024-03-06 143129](https://github.com/rxodrigues/Job-Finder/assets/137015987/cdbba1b7-0c98-4f56-b09c-8b0ce1369c1e)
![Captura de tela 2024-03-06 143214](https://github.com/rxodrigues/Job-Finder/assets/137015987/bd22c3f7-6877-4f72-9499-2a1450aae6bc)
