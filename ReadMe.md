<h1  align="center">
    <br><img src="github/assets/logo-full.svg" alt="Logo" width="480"><br><br>
    LaunchStore
</h1>

<div>
    <p  align="center">
        <a  href="https://www.linkedin.com/in/yuri-silva99/"  target="_blank">
            <img  src="https://img.shields.io/static/v1?label=Author&message=Yuri&color=00ff99&style=for-the-badge&logo=LinkedIn"  alt="Author: Yuri">
        </a>
        <a  href="#">
            <img  src="https://img.shields.io/static/v1?label=Language&message=Javascript&color=yellow&style=for-the-badge&logo=JavaScript"  alt="Language: Javascript">
        </a>
        <a  href="#">
            <img  src="https://img.shields.io/static/v1?label=Template&message=Nunjucks&color=green&style=for-the-badge&logo=Ghost"  alt="Language: Nunjucks">
        </a>
        <a  href="#">
            <img  src="https://img.shields.io/static/v1?label=Language&message=CSS&color=blue&style=for-the-badge&logo=CSS3"  alt="Language: CSS">
        </a>
    </p>
</div>

<p  align="center">
    <img src="github/assets/home.png" alt="Home" width="480">
</p>

## Table of Contents

<!--ts-->

* [About](#about)

* [Features](#features)

* [Revised Concepts](#revised-concepts)

* [Installation](#installation)

* [Getting Started](#getting-started)

* [Technologies](#technologies)

* [License](#license)

<!--te-->

## About
<div>

<p  align="center">

LaunchStore is a project developed to create an application to manage a virtual store, with administration of the product and user registration areas. Made with Express, Nunjucks, CSS and PostGres.

</p>

</div>

## Features

- 🎁 Buy and sell various products.

- 🆙 Through an administrative platform, manage users and their products.

- 💻 Login and Logout of users.

## Revised Concepts

- ❌ Blocking routes for users unregistered.

- 🌐 Global Variables.

- 🖼️ Multer to upload images

- 🔑 Bcrypt for passwords

- 📧 Nodemailer

## Installation

**You must have already installed**

- <a  href="https://nodejs.org/en/download/"> Node.JS </a>

- <a  href="https://www.postgresql.org/"> Postgresql </a>

**Let's divide it into 4 steps.**

1. Clone this repository
2. Install dependencies
3. Create database
4. Feed the database

  ---
#### 1. Clone this repository
```
$ git clone https://github.com/Yuri-stack/Launchstore.git
```
---
#### 2. Install the dependencies

1.  Run the code below
```
npm install
```
*Make sure your internet is stable, as this may take a while*

  ---
#### 3. Create the database
  
1.  Run the code below in your project's main directory.
```
npm run createdatabase
```
2. The following `Postgres user` message will appear. Enter your Postgres username
3. `Password for user postgres:` will appear twice. Type your database password and hit enter.
4. **Important**: You will need to have the `psql` variable in your machine's environment variables.

---
#### 4. Feed the database
1. First, check that your `src / config / db.js` file has the correct credentials for your Postgres.
2. Run the code below in your project's main directory.
```node seed.js```
3. **Inportant Information:** All fictional users have the password `1111`

## Getting Started

1. Run the code below in your project's main directory.
```
npm run start
```
2. Now, open your browser and navigate to: http://localhost:5000

## Technologies

- [Javascript](https://www.javascript.com/)

- [Nunjucks](https://mozilla.github.io/nunjucks/)

- [Node.js](https://nodejs.org/en/)

## License

Released in 2021.

This project is under the [MIT license](https://github.com/Yuri-stack/ReadMe/blob/main/LICENSE).

Made with love by [Yuri Oliveira](https://github.com/Yuri-stack) 🚀.