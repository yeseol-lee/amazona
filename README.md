# MERN AMAZONA

# Lessons

1. Introduction
2. Install Tools
3. Create React App
4. Create Git Repository
5. List products
   1. create products array
   2. add product images
   3. render products
   4. style products
6. Add routing
   1. npm i react-router-dom
   2. create router for home screen
   3. craete router for product screen
      useParams()
      Link: just change address
      a href: initialize state and remove components -> should not use
7. Create Node.JS Server
   1. run npm init in root folder
   2. Update package.json set type: module
      can use import instead of require
   3. Add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move product.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. run npm start
8. Fetch Products From Backend
   1. set proxy in package.json
      This allows the app to "pretend" it is making requests from the same port of the server
      프록시: 네트워크에 긴접적으로 접속할 수 있게 해주는 프로그램
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook
9. Manage State By Reducer Hook
   1. define reducer
   2. update fetch data
   3. get state from useReducer
      useReducer: useState보다 복잡한 상태에 사용함.
10. Add bootstrap UI Framework
    1. npm install react-bootstrap bootstrap
    2. update App.js
11. Create Product and Rating Component
    1. create Rating component
    2. create Product component
       bootstrap Card 사용
    3. Use Rating component in Product Component
