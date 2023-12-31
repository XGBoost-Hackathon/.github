# Meghbot

Meghbot is a smart, interactive chat application that offers AI assistance and also peer-to-peer communication between individuals. But it's not only limited to sending and receiving texts, here one can communicate via voice, and extracting information from files can also carry the chat. It also offers a file-sharing platform that can be done between peers and can be broadcasted to all the connected users also. The system additionally offers a pdf generation tool, which can generate a book from a text prompt that includes texts and images.

## Installation
Frontend:
Install the ```xgboost-bcf23-frontend``` with npm. The project is in ReactJS.
In the root directory, run the following commands:

```npm install```
```npm start```


BackEnd:
For Backend we used Express JS and Django frameworks. Follow the instruction below to install them.

Express JS - ```xgboost-bcf23-chatbot-backend```

```npm install```
```npm start```

Django - ```xgboost-bcf23-backend```

```pip install -r requirements.txt```
```python manage.py runserver```

## APIs used
| Intention | API     |
| :-------- | :------- |
| AI response | openai |
| Keyword Extraction | openai |
| Story | openai |
| Image-Text | Tesseract |
| Voice | webkitSpeechRecognition |
| Image search | openai |

Thank you!
