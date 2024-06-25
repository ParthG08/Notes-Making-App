This is a Notes app that i made by watching tuorials online

## You need th following libraries for it work:
- Database (MongoDB)
- Google Console Account to create the API Auth Key's

## Create .env file
Create a .env file to store your credentials. Example below:

```
MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere
GOOGLE_CLIENT_ID= YOUR_GOOGLE_ID_HERE
GOOGLE_CLIENT_SECRET= YOUR_GOOGLE_CLIENT_SECRET_HERE
GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback

```

## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm start
```

I have taken help of the tutorial of Raddys youtube channel to make this project

##SOURCE
https://www.youtube.com/watch?v=BDo1lgaZuII&pp=ygUMcmFkZHkgbm9kZWpz
