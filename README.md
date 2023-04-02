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
12. Create Product Details Screen
    1. fetch product from backend
    2. create 3 columns for image, info and action
13. Create Loading and Message Component
    1. create Loading Component
    2. use spinner component
    3. create message component
    4. create utils.js to define getError function
       props.children: special prop, automatically passed to every component. 태그와 태그 사이의 모든 내용을 표시하기 위해 사용되는 특수한 props
14. Implement Add To Cart
    1. Create React Context
    2. define reducer
    3. create store provider
    4. implement add to cart button click handler
       리액트 context는 앱의 모든 컴포넌트에서 사용할 수 있는 데이터를 전달할 때 유용합니다.
       리액트 context는 리액트 컴포넌트를 위한 전역 변수와 같다고 생각하면 됩니다.
