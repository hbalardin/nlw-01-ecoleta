<!-- banner -->
<h1 align="center">
  <img alt="BannerEcoleta" title="BannerEcoleta" src="./github/banner.png">
</h1>

<!-- title -->
<h1 align="center">
  ♻️ Ecoleta
</h1>

<!-- description -->
<h2 align="center">
  Your waste collection marketplace. We help people find collection points efficiently.
</h2>

<!-- badges -->
<p align="center">
  <img src="https://img.shields.io/github/repo-size/hbalardin/nlw-01-ecoleta"/>
  <image src="https://img.shields.io/github/last-commit/hbalardin/nlw-01-ecoleta"/>
  <img alt="GitHub license" src="https://img.shields.io/github/license/hbalardin/nlw-01-ecoleta">
</p>

<!-- status -->
<p align="center"><b>Status: Finished ✅</b></p>

---

<!-- index -->
<p align="center">
  <a href="#-about">About</a> •
  <a href="#-features">Features</a> •
  <a href="#-technologies">Technologies</a> •
  <a href="#-running-the-project">Running the project</a> •
  <a href="#-license">License</a> •
  <a href="#-readme-versions">README Versions</a>
</p>

---

## 📄 About

The purpose of **Ecoleta** is to connect waste collection companies with people who need a appropriate place for waste disposal.

This project was developed in the first **NLW (Next Level Week)**. 

The **NLW** is a one week online event,  provided by **RocketSeat**, focused on getting our hands dirty. The content is only available during the event.

---

## 🔝 Features

Companies can register themselves via the web platform, is just fill out the form.

Via app, users can browse the map and find collection points in your area, being able to contact companies via whatsapp or email.

<!-- gifs -->
<p align="center">
  <img width="60%" alt="DemonstracaoWeb" title="DemonstracaoWeb" src="./github/webdemonstration.gif">
  <img width="15%" alt="DemonstracaoMobile" title="DemonstracaoMobile" src="./github/mobiledemonstration.gif">
</p>

---

## 🔨 Technologies

These are the main technologies used in the construction of the project:

- [Typescript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)

---

## 🚀 Running the project

First of all, you need to have [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/) installed on your machine. After that, you can proceed.

### 📂 Installing the dependencies

```bash
# Clone this repository:
$ git clone https://github.com/hbalardin/nlw-01-ecoleta

# Access the project folder:
cd nlw-01-ecoleta

# Go to the server folder:
cd server

# Install the dependencies:
npm install

# Go to the web folder:
cd ../web

# Install the dependencies:
npm install

# Go to the mobile folder:
cd ../mobile

# Install the dependencies:
npm install

# Back to the project folder:
cd ..
```

---

### 💾 Running the server (back-end)

Before to run the server for the first time, you need to create the database.

```bash
# Go to the server folder:
cd server

# Create the database:
npm run knex:migrate

# Fill out the tables:
npm run knex:seed

# Run the server in development mode:
npm run dev
```

---

### 💻 Runnig the web application (front-end)

With the server running, open a new terminal and go to the project folder.

```bash
# Go to the web folder:
cd web

# Run the site in development mode:
npm run start
```
If the page does not open automatically, access: http://localhost:3000

---

### 📱 Running the app (mobile)

You can choose to download the expo app on **your smartphone** or install an **emulator** 

- Watch this video (in portuguese) made by RocketSeat with a step by step to install an emulator: 

- <a href="https://www.youtube.com/watch?v=eSjFDWYkdxM">
  <img src="https://img.shields.io/badge/Go%20t0%20video-Setting%20Expo-blue"></img>
</a>

With the server and emulator running, open a new terminal and go to the project folder.

```bash
# Go to the mobile folder:
cd web

# <<If you are using an emulator>>.
# Create a android (or IOS) application:
npm run android # (or IOS)

# <<If you are using your smartphone>>.
# Run the application in development mode:
npm run start
``` 

PS: For the mobile app to work correctly, you need to [configure the project with the IP of your machine](-setting-ip). 

---

#### ⚙️ Setting IP

<p align="center">
  <img width="60%" alt="DemonstracaoIP" title="IPDemonstracaoIP" src="./github/ipdemonstration.gif">
</p>

Like in the gif above, replace the **"localhost"** with **your machine's IP address** in the files:

1. mobile -> src -> services -> api.ts
2. web -> src -> services -> api.ts
3. server -> src -> controllers -> ItemsController.ts
4. server -> src -> controllers -> PointsController.ts
5. server -> src -> controllers -> PointsController.ts

---

## 📋 License

This project is under the license [MIT](https://github.com/hbalardin/nlw-01-ecoleta/blob/master/LICENSE.md).

Developed by Henrique Balardin dos Santos 🚀 [Get in touch!](https://www.linkedin.com/in/hbalardin)

---

## 🚩 README Versions

- [English](https://github.com/hbalardin/nlw-01-ecoleta/blob/master/README-en.md) | [Portuguese](https://github.com/hbalardin/nlw-01-ecoleta/blob/master/README.md)