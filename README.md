Prerequisites :
Make sure you have the LTS version of Node installed.
Install git for version control.
Install MongoDB locally. (Resource)


Installation :
Step 1: Fork this repo.
Step 2: Clone your forked version of this repo locally. To clone, go to your command line / terminal, cd over to an appropriate directory and type in git clone https://github.com/<your username>/URL-shortener.git.
Step 3: cd URL-shortener
Step 4: While in the URL-shortener directory, install the frontend dependencies using npm install or yarn.
Step 5: cd server
Step 6: While in the server directory, instlal the backend dependencies using npm install.
Step 7: Run the mongodb server on port: 27017 using mongod.
Step 8: While mongod is still running, open a new tab and again cd inside the server directory and run the backend server using node server.js or using nodemon - nodemon server.js. The backend server will start on localhost:5000.
Step 9: While backend server is still running, open a new tab on the terminal and cd to the main project directory i.e. URL-shortener.
Step 10: Finally start the react app using npm start. The app will start on port 3000 which can be accessed through http://localhost:3000/.
