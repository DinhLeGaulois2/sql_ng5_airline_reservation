# Airline Reservation with Angular 5 and MySQL-Sequelize

## Aim
Building a project based on an EER (Enhanced Entity-Relationship). 

> This project is one of about 30-35 others building by mixing:
>   * Front-End: **jQuery**, **ReactJS**, **React-Redux**, **Angular** (2-5), **Ionic3**, **View.js**
>   * Back-End: 5 APIs (2 with **MongoDB** and 3 with **MySQL**)
> 
> These are **3-tier Architecture** projects. Everything is started (almost) from scratch (the diagrams for the databases come from the Internet - with link to to source on each picture - with errors which were fixed)
>
> The **Front-End** are NOT the most beautiful because not much work on it. The goal is to use very different technologies on very different purposes.


>  * Complexe management to allow to book airplane's ticket.
>  * **Transaction** is used to ensure that if the WHOLE processus (**insert**, **update** and **delete**) is NOT successful then NOTHING will be done (**Rollback** function will take care of it).
>  * The **insertion** of a **booking** is very complex:
>   - request information from all **collection**
>   - setup a very complex **formular** to get data in some order
>   - insertion - using **transaction** - to be sure that the insertion is successful for the WHOLE processus

---------------

## Technologies
> * **Front End**: ***Angular 5***
> * **Back End**: ***Express/Node.js*** + ***Sequelize*** (ORM)
> * **Database**: ***MySQL***

---------------

## Enhanced Entity-Relationship

![alt text](assets/img/airlinebooking.jpg)

---------------

## Author
* Dinh HUYNH - All Rights Reserved!
* dinh.hu19@yahoo.com