# react-chat

## Setup Project
Create a `.env` file inside the 'api' folder, and then add these credentials.

```
MONGO_URL='mongodb+srv://joaquimdizon:MY0myCLuhU59YkAO@cluster0.wgwj4at.mongodb.net/?retryWrites=true&w=majority'
JWT_SECRET='wjaebhwhwah43jjkabrnjkarbnajkfbajkbn3jkrbnajkfkaj'
CLIENT_URL='http://localhost:5173'
```

After setting up the `.env` run the following commands:
```bash
# Setup the Frontend
$ cd client
$ yarn install
$ yarn dev

# Setup the Backend
$ cd api
$ yarn install
$ nodemon index.js
