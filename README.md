Set up development environment : To start building MERN stack application, need to set up development environment. Install Node.js, MongoDB, and a code editor like Visual Studio Code.

Create a new Node.js project : Create a new Node.js project by running npm init in project directory. This will create a package.json file that tracks project's dependencies.

Install the required packages using the npm install command:
express - A Node.js web application framework
mongoose - A MongoDB object modeling tool
cors - A package that allows Cross-Origin Resource Sharing (CORS) in Express
dotenv - A package for managing environment variables

Set up the server : Create a new file index.js in the server directory of project. In this file, import the required packages, configure the app, and connect to MongoDB. In the model directory, create a new file userModel.js In this file, define the schema for data and export a model that can be used to interact with the database.

Set up the API routes : In the routes directory, create a new file userRoute.js In this file, define the API routes for application.

Connect the API routes to the server : In the index.js file, import the API routes and use them in your app using the app.use() method.

Create the frontend : Create a new directory called client in the root directory of project. In the client directory, run npx create-react-app to create a new React application.

Set up the frontend dependencies : In the client directory, install the following packages using the npm install command:
axios - A package for making HTTP requests
react-router-dom - A package for handling client-side routing in React
react-hot-toast - Use to push notification

Set up the frontend components : In the src directory of the client directory, create a new directory called components.
In the components directory, create a new directory adduser, getuse, updateuser after that
In this directory create a new files Add.js, add.css, User.js, user.css, Edit.js , create a React component that displays the files data.

Set up the frontend routes : In the src directory of the client directory, create a new file App.js. In this file, set up the client-side routing using react-router-dom.

Test the application : 
In the root directory of project, start the backend server by running node index.js.
In a new terminal window, navigate to the client directory and run npm start to start the frontend server.
In web browser, go to http://localhost:3000 to view the application.
