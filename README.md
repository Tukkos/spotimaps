# Spotimaps

Spotimaps is an easy randon playlist maker, that create a playlist based on what you want to hear and how much time you have to make a choosen path.

![Spotimaps](https://i.imgur.com/DecfSxP.gif)

### More info and content will be added and updated.

## About

This is a full-stack web app project to easily create randon playlists. The implemented features are:

* Sign-up;
* Login;
* Randon music array creation based on time available;
* List of playlists created;
* List of musics of that playlist;
* Option to change playlist name;
* Option to delete playlist;

Next features to be implemented:

* Spotify API to change artists you want to make a randon playlist;
* Google Maps API so it calculates route time based on where you want to go;

## Technologies

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![eslint](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![jwt](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify-1ED760?&style=for-the-badge&logo=spotify&logoColor=white)

## Attention

This project dont have a deploy, but soon it will have an AWS server running. But its possible to run it locally by:

## Getting started with Docker

This project was bootstrapped with ![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white). If you have docker installed, you can run it by cloning this repository and run:

### `docker-compose up --build`

and after you can delete the container with: 

### `docker-compose down -v`

## Getting Started with npm

First clone frontend repository and run:

### `npm i`

Create an .env with your infos and in the project directory, you can run:

### `npm start`

Then clone backend repository and run: 

### `npm i`

Create an .env with your infos and in the project directory, you can run:

### `npm run dev nodemon src/app.ts`
