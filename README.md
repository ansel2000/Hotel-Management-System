# Hotel management system using php and mysql.

#### Please go through entire readme for complete project specifications

#### [Live preview](https://alandsilva26.github.io/hotel-management-website-template/)

Semester 5 Web Development Lab Mini Project.This projects aims to create a full fleged hotel management system which can be further scaled as per requirement. It includes a modern responsive UI built using bootstrap 4. We have also made extensive use of jquery ajax to perform various network requests. This project covers the following topics

- Responsive web design
- Web apps using PHP
- Database design
- Ajax

### Resources:

- [Miniproject presentation](https://docs.google.com/presentation/d/1BsYYEompbIkKHtLUARA2gEXiMBr9GAO1wXQCur1SiHk/edit?usp=sharing)

### NOTE:

- Please note that to utilize this you need to have a database named `hotel` in your DBMS(Mysql) and a user `admin` with password `admin` with all previleges.

## Technologies used

- Frontend - HTML, CSS, JS
- Frameworks - Jquery, Sass, Bootstrap, Charts.js
- Backend - PHP, MYSQL
- PHP packages - phpmailer, mpdf
- Package managers - npm, composer

## Dependencies

- [Composer](https://getcomposer.org/)
- [npm](https://www.npmjs.com/)
- [Xampp](https://www.apachefriends.org/index.html) or seperate installation of PHP and mysql
- Text Editor([VS Code](https://code.visualstudio.com/))

# Get started

- Install frontent dependencies - `npm install`
- Install backend dependencies - `composer install`

#### Note:

All `sass` files are located in `public/scss`. If making changes here run the command `npm run watch-sass` in a seperate terminal. This command watches sass files for any changes and compiles them to css directory.\
Or you may directly edit the css file in `public/css`.\

#### Side note:

If you just require the frontend files of this project see the project [https://github.com/alandsilva26/hotel-management-website-template](https://github.com/alandsilva26/hotel-management-website-template). Installation instructions in readme.\

## To-do

- Bootstrap templating section (no css pure bootstrap)

* [x] - Client Side
    - [x] - Check in and check out date form(this redirects to reservation form)
    - [x] - Services offered(About us)
    - [x] - Featured Rooms
    - [x] - About Hotel
    - [x] - View all rooms page
    - [x] - Room details page
    - [x] - Payment form(this is temporary as an actual payment gateway will be integrated in the future)
* [x] - Auth
    - [x] - Login Page
    - [x] - Signup Page
    - [x] - User verification page
* [x] - Admin
    - [x] - Room actions(add, update, delete)
    - [x] - View all rooms
* [x] - Features
    - [x] - Book rooms
    - [x] - CRUD rooms(admin)
    - [x] - Statistics(Charts.js)
    - [x] - View my reservations

## Other

- A database export copy is included in the file `database.sql`
- Please note that to utilize this you need to have a database named `hotel` in your DBMS(Mysql) and a user `admin` with password `admin` with all previleges.
