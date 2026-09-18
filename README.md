# ToDo App

Eine einfache ToDo Applikation, entwickelt mit Node.js und containerisiert mit Docker.

## Projektbeschreibung

Diese Anwendung ermöglicht das Erstellen und Verwalten einfacher ToDo Einträge. Sie basiert auf Node.js und wird im Rahmen der Abschlussaufgabe "Development Fundamentals" mit Docker containerisiert.

## Voraussetzungen

* [Node.js](https://nodejs.org/) (Version 24 oder neuer)
* [Docker](https://www.docker.com/)
* [Git](https://git-scm.com/)

## Repository klonen

```bash
git clone https://github.com/DEIN-BENUTZERNAME/docker-nodejs-sample.git
cd docker-nodejs-sample
```

## Pakete installieren

```bash
npm install
```

## Anwendung lokal starten

```bash
npm start
```

Die Anwendung ist danach unter `http://localhost:3000` erreichbar.

## Docker Image erstellen

```bash
docker build -t todo-app .
```

## Anwendung mit Docker starten

```bash
docker run --name todo-container -p 3000:3000 todo-app
```

## Anwendung mit Docker Compose starten

```bash
docker compose up --build
```

## Anwendung stoppen

```bash
docker stop todo-container
docker rm todo-container
```

Oder bei Docker Compose:

```bash
docker compose down
```