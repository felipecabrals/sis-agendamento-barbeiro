# Aplicativo de Agendamento para Barbeiros

**Tecnologias Utilizadas**

- ExpressJs
- Sequelize
- Templates Engines NJK
- Docker
- PostgresSql
- Yarn
- MVC

**Como usar**

- Instalar o docker
- Fazer a instalação do DB, pelo terminal usando `docker run --name database -p 5432:5432 -d -t kartoza/postgis`
- Criar uma database
- No projeto usar `yarn install` para instalar todas as dependências do projeto.
- Além disso, `npx sequelize db:migrate` , para criar a base de dados.
- Após, executar `yarn start`.
