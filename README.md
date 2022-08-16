# local-library
You don't want to write on Express JS MVC Architecture boilerplate over and over again right? just fork this repo or even download it. Feel Free
ExpressJS with MVC Architecture, Mongoose, and User Auth. templating engine: Pug. 

## Table of Contents
<details open>
<summary><b>(click to expand or hide)</b></summary>
<!-- MarkdownTOC -->

1. [Project MVCS (Model, View, Controller, and Schema) Architecture](#project-mvc)
1. [Database Class Diagram Relationship between Collections in MongoDB](#db-class-diagram)
1. [Tree of Codes](#tree-of-codes)
  
<!-- /MarkdownTOC -->
</details>

<a id="project-mvc"></a>
## Project MVCS (Model, View, Controller, and Schema) Architecture
![image](https://user-images.githubusercontent.com/57006944/184702020-bf1f73cf-b8f3-4974-a31b-da7d69ddcdcd.png)

<a id="db-class-diagram"></a>
## Database Class Diagram Relationship between Collections in MongoDB
![image](https://user-images.githubusercontent.com/57006944/184702285-06c0c72d-700a-486d-98ee-b706cb9664f0.png)

<a id="tree-of-codes"></a>
## Tree of Codes

```
.
├── README.md
├── app.js
├── bin
│   └── www
├── controllers
│   ├── authorController.js
│   ├── bookController.js
│   ├── bookinstanceController.js
│   └── genreController.js
├── models
│   ├── author.js
│   ├── book.js
│   ├── bookinstance.js
│   └── genre.js
├── package-lock.json
├── package.json
├── populatedb.js
├── public
│   └── stylesheets
│       └── style.css
├── routes
│   ├── catalog.js
│   ├── index.js
│   ├── users.js
│   └── wiki.js
└── views
    ├── error.pug
    ├── index.pug
    └── layout.pug

7 directories, 22 files
```
