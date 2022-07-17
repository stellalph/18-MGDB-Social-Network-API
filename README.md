## 18 NoSQL: Social Network API

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The challenge task is to build an API for a social network web application where the users can share their thoughts, and create a friend list. 

This application will use Express.js for routing, a MongoDB datasbase, Mongoose ODM, and also moment.js.

The URL of the GitHub repository is **https://github.com/stellalph/18-MGDB-Social-Network-API.git.**
 
The repository name is **18-MGDB-Social-Network-API.**


## Table of Contents

* [Installation](#installation)
* [Walkthrough Videos](#walkthrough-videos)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Installation

*   This application requires the installation of node.js from the website, https//wwww.node.org.

*   Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

*  This application will use the following npm packages:-

  
         - npm install express
         - npm install mongoose
         - npm i moment

* Nodemon is installed as development dependency meaning that if our application ever goes in production, this package will not be included. The command to install for in this case is **npm i -D nodemon**. The purpose of this package is to watch for any changes in our files and restart the server instead of us having to do that manually ourselves. The screenshot show the working of the nodemon.

   ![alt text](/assets/npmstart.png)



* This project also requires MongoDB to be installed.   As would be the *USER STORY* who want an API that uses a NoSQL database, MongoDB is a general purpose NoSQL document database that uses documents to store data.  MongoDB stores data as a BSON object, making a great fit for JavaScript apps.  In this application, the user want the website to handle large mounts of unstructured data and MongoDB is a great choice for *heterogeneous data*, and scales easily. Below shows that when the server is started, the mongoose models are synced to the MongoDB database. 

    ![alt text](/assets/MongoDB1.png)
    ![alt text](/assets/MongoDB2.png)

* After the API have been created,  data would then be created through Insomnia.  The overview of data is shown below:-

    ![alt text](/assets/FindallUsers.png)

* The data created also synced to the MongoDB database.

## Walkthrough Videos

[Part 1 - Walkthrough Video Link](https://drive.google.com/file/d/18jZNciFgGTbS0WxOzTsNVzdtc8ck7oPk/view)

*   To show all of the technical acceptance criteria being met :-

        -  models (User, Thought, and index.js), 
        -  controllers (user-controller.js, thought-controller.js),
        -  api (user-routes, thought-routes, index.js), index.js,
        -  package.json showing the npm packages installed,
        -  server.js (connection URL).

*   To demonstrate the GET routes for all users and all thoughts being tested in Insomnia.

*   To demonstrate the GET routes for a single user and a single thought tested in Insomnia.

[Part 2 - Walkthrough Video Link](https://drive.google.com/file/d/18jZNciFgGTbS0WxOzTsNVzdtc8ck7oPk/view)

*   To demonstrate POST, PUT and DELETE routes for users and thoughts tested in Insomnia.

*   To demonstrate POST and DELETE routes for a user's friend list being tested in Insomnia.

*   To demonstrate POST and DELETE routes for reactions to thoughts being tested in Insomnia.

*   Overview of MongoDB and the Mongoose models are synced to the MongoDB database.



## Usage


## References


## License

This project is licensed under the terms of the MIT license.