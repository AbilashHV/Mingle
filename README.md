  # Mingle

A Social Networking web app similar to Instagram.



## Features

* SignUp / SignIn.
* Forgot password.
* Google Oauth Login.
* edit / delete your profile.
* Follow / Unfollow users.
* create / edit / delete posts.
* create / delete comments.
* Like / Unlike posts.
* Personal chat with users.



## To run the project locally


* Inside /server directory create a .env file and add these
    - `MONGO_URI=your-mongodb-url`
    - `PORT=8080`
    - `JWT_SECRET=any-random-string-of-any-length`
    - `CLIENT_URL=http://localhost:3000`
* Inside /client directory create a .env file and add
    - `REACT_APP_API_URL=http://localhost:8080`
* Change the directory to /server in the terminal and run:
    - `npm install`
    - `node app.js`
* Change the directory to /client in the terminal and run:
    - `npm install`
    - `npm start`
* Open your browser and enter url `http://localhost:3000`

## Tech Stack of this Project

* Frontend: Reactjs, Bootstrap Material
* Backend: Nodejs
* Framework: Expressjs
* Database: MongoDB




