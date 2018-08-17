# mean_todo_app
poc on a mean stack project

MEAN stands for mongodb, Express, Angular and Node JS

1. create account on mlab for mongo db remote DB
2. 
Express Js Installation

1. npm init ==> to initialize node js project
2. npm install express mongojs ejs body-parser --save  ==> to setup below

==> 
express
monogojs to use mongo as db
ejs for java templates
body-parser

3. open server.js and configure express and bodyparser, also set the view engine as EJS

4. create views and routes folders, and create  index.js and todos.js files in routes folder

5. initialize express and router in both the files and export it to module

6. node server ==> to run the application

7. If server , you should see INDEX on http://localhost:3000/ and TODOS on http://localhost:3000/api/v1/todos

8. create index.ejs file in views folder, this is not important as we do not load this page, we will work on client side. we create it just in case

9. Initialize remote mongo db using mlab credentials and set up the server side resful API in todos.js

10. Now set up front end using angular

11. create a folder named client and let the server know it is the folder that has all the static content

12. copy files from angular site ==> package.json,tsconfig.json, typings.json, systemjs.config.js

13. Go to client folder from commmand prompt and run ==> npm install

14. copy index.html file from angular site and replace out index file from views folder

15. create a empty file named style.css in our client folder

16. create an app folder for angular and copy files ==> app.module.ts, app.component.ts and main.ts

17. configure the appcomponent in app module file and also the bootstrap.

18. Install Bower on the client side, It is like a npm manager on the client side

19. npm install bower -g  ==> Install Bower globally, then add .bowerc file to the project

20. npm install bootstrap --save  ==> install bootstrap using bower

21. npm rum tsc -w ==> Compile Angular code







