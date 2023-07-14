# Meghbot

Meghbot is a smart, interactive chat application that offers AI assistance and also peer-to-peer communication between individuals. But it's not only limited to sending and receiving texts, here one can communicate via voice, and extracting information from files can also carry the chat. It also offers a file-sharing platform that can be done between peers and can be broadcasted to all the connected users also. The system additionally offers a pdf generation tool, which can generate a book from a text prompt that includes texts and images.

## Contents

 - [Installations](#installation)
 - [Screenshots](#screenshots)
 - [Api References](#api-references)
 - [Future Extensions](#future-extensions)
 - [Acknowledgements](#acknowledgements)

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
