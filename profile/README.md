# Project Title

A brief description of what this project does and who it's for


## Installation
Frontend:
Install my-project with npm

bash
  cd my-project
  npm install 
  npm start


BackEnd:
For Backend we used Express JS framework Django framework

Express JS
bash
  cd my_project
  npm init -y
  npm install express
  node server.js

Django 
bash
 cd my_project 
 python manage.py runserver



## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## API Reference

#### Get all items

http
  GET /api/items


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | *Required*. Your API key |

#### Get item

http
  GET /api/items/${id}


| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | *Required*. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.
