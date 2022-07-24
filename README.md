## React.js CRUD App with Json Server Using Axios

Build a React.js CRUD Application to consume Web API, display and modify data with Router, Axios & Naterial UI.

React Tutorial Application in that:

    Add User
    Update User
    Delete User
    View Users


# Project setup

In the project directory, you can run:
  
    npm install
     or
    yarn install

or
Compiles and hot-reloads for development

    npm start
     or
    yarn start


Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.

//Json Server Start//

json-server
json-server --watch src/Database/db.json --host 127.0.0.1 --port 3003
dev
concurrently "npm start" "npm run json-server"
build
react-scripts build
eject
react-scripts eject
