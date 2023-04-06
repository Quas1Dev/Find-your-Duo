# Find your Duo
<div align="center">
  <img src="https://raw.githubusercontent.com/joaofmartinho/nlw-esports/main/assets/img/nlw-esports-logo.svg" alt="">
</div>

This project is a result of the one-week event Next Level Week (NLW) eSports by [Rocketseat](https://www.rocketseat.com.br/) in which a web application, a mobile app and an API has been built from scratch. 

## Description
This project is named **Find your Duo**. This is a complete platform so users may find other people to play with by publishing announcements.The announcements contain the date and time for the gaming, and contact information so that interested parties can communicate with the person who made the announcement.

## Stack and tools
* [Node.js](https://nodejs.org/en/)
* [React](https://reactjs.org/)
* [React Native](https://reactnative.dev/)
* [Expo](https://expo.dev/)
* [Figma](https://www.figma.com/)
* [Radix UI](https://www.radix-ui.com/)

## Getting Started

Here are the steps required to get you prepared to run the web app, mobile app and server on Windows 10/11. 

## Prerequisites

- You'll need to have [Node.js](https://nodejs.org/en/) intalled.
- You'll need to have [PostgreSQL](https://postgresql.org/) installed.
- You'll need to have [Git](https://git-scm.com/) installed.

Note: We'll be creating a PostgreSQL Database using the Postgres users. Therefore, you must take note of the password you set for this user.
Note: Also you will need to find the path to a folder called `data`, which is usually located at C:\Program Files\PostgreSQL\15\data.

## Setting up the project

To quickly set up the project and try out our web app, you can download our [setup.bat](https://www.dropbox.com/s/y3woh12g4zklcgt/setup.bat?dl=0) file. This Batch script will clone the project into a findyourduo folder in your Documents directory, install all dependencies for the web app, server, and mobile app, prepare a PostgreSQL database with the necessary tables, populate them with some data, and initiate the web app and server. 

To use the setup.bat file, simply double click on it and follow the prompts. You'll be asked to enter your PostgreSQL superuser password and the location of your PostgreSQL data directory (default is C:\Program Files\PostgreSQL\15\data). The script will handle the rest. 

We'll provide instructions to run the mobile app in just a moment.

## Getting to use the web app

Once you are done, you can just close all windows opened by the script. If you want execute them again, just navigate to the projects folder and execute these commands:

To run the server:
```
cd server
npm run dev
```

To run the web app:
```
cd ../web
npm run dev
```
