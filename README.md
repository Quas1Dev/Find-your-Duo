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

- You'll need to have [Node.js](https://nodejs.org/en/) intalled on your machine.
- You'll need to have [PostgreSQL](https://postgresql.org/) installed on your machine.
- You'll need to have [Git](https://git-scm.com/) installed installed on your machine.
- You'll need to have [Expo GO](https://expo.dev/client) installed in some smartphone (required to run the mobile version).

Note: We'll be creating a PostgreSQL Database using the Postgres users. Therefore, you must take note of the password you set for this user.
Note: Also you will need to find the path to a folder called `data`, which is usually located at C:\Program Files\PostgreSQL\15\data.

## Setting up the project

To quickly set up the project and try out our web app, you can download our [setup.bat](https://www.dropbox.com/s/b8hev74kxpzz75u/setup.bat?dl=0) file. This Batch script will clone the project into a findyourduo folder in your Documents directory, install all dependencies for the web app, server, and mobile app, prepare a PostgreSQL database with the necessary tables, populate them with some data, and initiate the web app and server. 

To use the setup.bat file, simply double click on it and follow the prompts. You'll be asked to enter your PostgreSQL superuser password and the location of your PostgreSQL data directory (default is C:\Program Files\PostgreSQL\15\data). The script will handle the rest. 

We'll provide instructions to run the mobile app in just a moment.

## Getting to use the web app

With both the web app and server running, open any browser you want and navigate to localhost:3000. At this point you should be seing the home page for the application.

## Closing everything and getting back
Once you are done, you can just close all windows opened by the script. All runing process that we started in the process will be terminated.

If you want execute the web app again again, just navigate to the projects folder and execute these commands:

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

## Running the mobile app
Navigate to the project's folder using CMD, and then run the follwoing:

To start the server:
```
cd server
npm run dev
```

To start the mobile application:
```
cd ../mobile
npm start
```
Note that a QR code will appear on screen for you.

In your smartphone, open up ExpoGO, and click on Scan QR code. Aim the camera at the QR code, and it should start the connection. Now you can enjoy your React Native app.
