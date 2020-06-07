<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src=".github/banner.png"/>
</h1>

<h2 align="center">NextLevelWeek #01 - Ecoleta ♻️</h2>

## Projeto

Projeto desenvolvido para conectar as pessoas a empresas que coletam resíduos específicos. O cadastro é feito pela aplicação web e uma aplicação mobile para visualizar os pontos de coleta.

## Tecnologias

- Node.js
- React
- React Native
- TypeScript
- Expo
- Knex.js
- Axios
- SQLite

## Melhorias

Ainda precisam ser implementadas as melhorias sugeridas nas aulas.

## Como usar
Para executar este aplicativo, você precisará do Node.js + Npm instalado no seu computador.

### Back End (server)

```bash

# Instale as dependências
$ npm install

# Execute as Migrates
$ npm run knex:migrate

# Execute as Seeds
$ npm run knex:seed

# Execute a Aplicação
$ npm run dev

# O servidor inciará na porta:3333

```
### Front End (web)

```bash

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm run start

# A aplicação será executada na porta:3000
```

### Mobile (mobile) 
```bash
# Vá para a pasta da aplicação Front End
$ cd mobile

# Instale as dependências
$ npm install

# Execute a aplicação
$ expo start


# Use o App expo baixado no seu celular
```