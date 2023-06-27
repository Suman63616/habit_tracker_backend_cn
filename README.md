

# Access the mongodb uri below for setting this application in local environment

# .env
MONGODB_URI=mongodb+srv://suman:suman@cluster0.qpyjtjh.mongodb.net/?retryWrites=true&w=majority

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="#">
    <img src="https://cdn-icons-png.flaticon.com/512/3588/3588658.png" alt="habit-icon-common" alt="Logo" width="70" height="70">
  </a>

  <h3 align="center">Habit Traker</h3>


</div>





<!-- ABOUT THE PROJECT -->
## About The Project

This habit tracker provides a list of all the habits created by user.
User can manupulate the habit status and it stores total 60 days of the habit-details.
By default it delivers 7 days details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Sample Images
Here are some sample images of the CRUD Ops. Have a quick look

#### Habit home
![Habit home][habit-home-screenshot]

#### Habit details
![Habit details][habit-details-screenshot]

### Project Structure
```
Habit_tracker
    |-----assets
    |       |--- css
    |       |     |-- habit.css
    |       |     |-- home.css
    |       |     └-- layout.css
    |       |--- Images
    |       |     └-- Screenshots     
    |       |--- js
    |       |     |-- habit.js
    |       |     └-- moment.js
    |       |--- sass
    |             |-- habit.scss
    |             |-- home.scss
    |             └-- layout.scss
    |------ config
    |         └--- mongoose.js
    |------ controllers
    |         └--- habitControllers.js
    |------ models
    |         └--- habit.js
    |------ routers
    |         └--- index.js
    |------ views
    |         |--- habit..ejs
    |         |--- home.ejs
    |         └--- layout.ejs
    |------ .gitignore
    |------ app.js
    |------ package.json
    |------ package-lock.json
    └------ README.md
```

### Built With

This project is build with various libraries and frameworks. Some of them is listed below

* [Node Js](https://nodejs.org/en/)
* [Express Js](http://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)
* [Postman- API checking](https://www.postman.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

For start the project you need to have some prerequisites.

### Prerequisites
npm is mandatory for install and runing the project

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

Clone the project from Git and install all the required libraries for the project

1. Clone the repo
   ```sh
   git clone 
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Configure

Here you have to make some configuraiton to run this project on your system

1. Install nodemon using npm (Ignore if already Installed)
    ```
    npm install nodemon
    ```
2. Now all configurations has been completed, run below command in terminal to run the application
    ```
    npm start 
    ```

