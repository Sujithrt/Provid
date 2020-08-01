# Running Website (homepage) Locally

How to run locally?
1. Install XAMPP.
2. Download and Extract file into "./xampp/htdocs"
3. Turn mysql and apache server on.
4. Type "http://localhost".
5. Go to phpMyAdmin.
6. Create a database name "user_registration".
7. Import the mysql file in "./provid/user_registration database/user_registration."
8. Go to browser and type "http://localhost/provid/Login.php".




# COVID-19 Tracker

# Realtime Chat Application

COVID-19 Tracker is being sponsored by the following tool; please help to support us by taking a look and signing up to a free trial.


### [Live Site](https://covid19statswebsite.netlify.com/)

## Introduction
This is a code repository for the corresponding video tutorial. 

In this video, we will create a full COVID-19 Tracker. We're going to use React, Charts.JS and Material UI.

By the end of this video, you will have a strong understanding of React's workflow and the use of hooks.

API used: https://covid19.mathdro.id/api

Setup:
- run ```npm i && npm start```





# News App - React

Application to view news stories from sources around the world.

Built with [React](https://reactjs.org/) as frontend JavaScript framework.

## Requirements

- [Create React App](https://github.com/facebook/create-react-app)
- [Bootstrap 4](https://getbootstrap.com/)
- [Node.js](https://nodejs.org/en/) >8.x and [npm](https://www.npmjs.com/)
- [News API](https://newsapi.org/) key

## Installation

### Clone Project

```sh
git clone https://github.com/taiyeoguns/news-app-react.git news-app-react
```

### Install dependencies

Install `npm` dependencies with Yarn:

```
yarn
```

### Get API key for News service

Head to [http://newsapi.org](http://newsapi.org), signup or login to and get an API key


### Add details in `.env.local` file

Create `.env.local` file from example `.env` file and maintain necessary details in it e.g. API key etc

```sh
cp .env .env.local
```

### Development Server
Run `yarn start` for a development server. Navigate to `http://localhost:3000/`. The app will automatically reload if you change any of the source files.


## Other

### Build

```sh
yarn build
```

Builds the app for production to the `build` folder.

### Running unit tests

```sh
yarn test
```

Runs the test watcher in an interactive mode.





# Covid-19 Detection Website Application

## Windows Installation Instructions
- Create the git repo locally and cd into it
```
git clone https://github.com/paulinawins/CovidProject.git
cd CovidProject
```
- Download or decrement to Python (below 3.7 version and 64-bit version) for TensorFlow
```
I used 3.6.8, 64-bit Python
https://www.python.org/downloads/release/python-368/
```
If you're using anaconda, update the system path and anaconda to this version of Python.
- Create & activate virtual environment 
```
python -m venv covidEnv
virtualenv covidEnv
covidEnv\Scripts\activate
```
- Install Dependencies & Packages
```
pip install flask, boto3, keras, tensorflow, Pillow
```

## Running the code 
- Activate Virtual Environment
```
covidEnv\Scripts\activate
```
- In the "flask-backend" directory:
```
python app.py
```
- Open another terminal and In the "react-frontend" directory:
```
npm install
npm start
```
