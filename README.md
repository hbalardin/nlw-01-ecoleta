<!-- banner -->
<h1 align="center">
  Ecoleta<br><br>
  <img alt="BannerEcoleta" title="BannerEcoleta" src="./github/banner.png">
</h1>

<!-- descrição -->
<p align="center">
  Next Level Week 1.0 🚀
</p>

<!-- badges -->
<p align="center">
  <img src="https://img.shields.io/github/repo-size/hbalardin/nlw-01-ecoleta"/>
  <image src="https://img.shields.io/github/last-commit/hbalardin/nlw-01-ecoleta"/>
  <img alt="GitHub license" src="https://img.shields.io/github/license/hbalardin/nlw-01-ecoleta">
</p>

<!-- index -->
<p align="center">
  <a href="#-sobre">Sobre</a> •
  <a href="#-funcionalidades">Funcionalidades</a> •
  <a href="#-tecnologias">Tecnologias</a> •
  <a href="#-executando-o-projeto">Executando o projeto</a> •
  <a href="#-licença">Licença</a>
</p>

---

## 📄 Sobre

O objetivo do **ecoleta** é conectar empresas de coleta de resíduos, com pessoas que precisam de um local adequado para o descarte de lixo.

Este projeto foi desenvolvido durante a primeira **NLW (Next Level Week)**. 

A NLW é um evento de uma semana,  disponibilizado pela **RocketSeat**, com o foco em por a mão na massa. O conteúdo fica disponível apenas durante o evento.

---

## 🔝 Funcionalidades

Para uma empresa se cadastrar, basta acessar a plataforma web e preencher o formulário.

Pelo aplicativo, os usuários podem navegar pelo mapa e encontrar pontos de coleta na sua região, além de entrar contato com as empresas através do whatsapp ou email.

<!-- gifs -->
<p align="center">
  <img width="60%" alt="DemonstracaoWeb" title="DemonstracaoWeb" src="./github/webdemonstration.gif">
  <img width="15%" alt="DemonstracaoMobile" title="DemonstracaoMobile" src="./github/mobiledemonstration.gif">
</p>

---

## 🔨 Tecnologias

Estas são as principais tecnologias utilizadas na construção do projeto:

- [Typescript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)

---

## 🚀 Executando o projeto

O projeto é dividido em três pastas:

1. server (back-end)
2. web (front-end)
3. mobile (mobile)

Antes de qualquer coisa, você deve ter instalado na sua máquina o [git](https://git-scm.com) e o [Node.js](https://nodejs.org/en/). Feito isso, você já pode seguir adiante.

---

### 📁 Clonando repositório

```bash
# Clonando o repositório:
$ git clone https://github.com/hbalardin/nlw-01-ecoleta

# Entrando na pasta do projeto:
cd nlw-01-ecoleta
```

---

### 📂 Instalando dependências

```bash
# Entrando na pasta server:
cd server

# Instalando as depêndencias:
npm install

# Entrando na pasta web:
cd ../web

# Instalando as depêndencias:
npm install

# Entrando na pasta mobile:
cd ../mobile

# Instalando as depêndencias:
npm install

# Voltando para a pasta do projeto:
cd ..
```

---

### 💾 Rodando o servidor (back-end)

Antes de rodar o servidor pela primeira vez, você precisa configurar o banco de dados.

```bash
# Entrando na pasta server:
cd server

# Instanciando o banco de dados:
npm run knex:migrate

# Preenchendo as tabelas:
npm run knex:seed

# Executando o server em modo de desenvolvimento:
npm run dev
```

---

### 💻 Rodando a aplicação web (front-end)

Com o servidor rodando, abra um novo terminal e entre na pasta do projeto.

```bash
# Entrando na pasta web:
cd web

# Executando o site em modo de desenvolvimento:
npm run start
```
Caso a página não abrir automaticamente, acesse: http://localhost:3000

---

### 📱 Rodando a aplicativo (mobile)

Há duas formas de rodar o aplicativo:

1. Através de um emulador.
2. Através de seu smartphone.

Para quem quiser instalar o emulador, segue um vídeo da RocketSeat com o passo a passo: 

<p align="center">
  <a href="https://www.youtube.com/watch?v=eSjFDWYkdxM">
    <img src="https://img.shields.io/badge/Acessar%20v%C3%ADdeo-Emulando%20Android%20e%20IOS-blue"></img>
  </a>
</p>

Com o servidor rodando e com o emulador aberto, abra um novo terminal e entre na pasta do projeto.

```bash
# Entrando na pasta mobile:
cd web

# Esta linha é necessária apenas para emuladores.
# Criando aplicação android (ou IOS)
npm run android # (ou IOS)

# Executando o aplicativo em modo de desenvolvimento:
npm run start
``` 

## 📋 Licença

Esse repositório está sobe a licença MIT.

Desenvolvido por Henrique Balardin dos Santos 🚀 [Entre em contato!](https://www.linkedin.com/in/hbalardin)