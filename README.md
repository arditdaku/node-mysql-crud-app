# node-mysql-crud-app
Simple CRUD app tutorial using node by [Atauba Prince](https://dev.to/achowba/build-a-simple-app-using-node-js-and-mysql-19me)

##required modules 

- Express : used to create handle routing and proccess request from the client
- express-fileupload: Simple express file upload middleware that wraps around busboy.
- body-parser: used to parse incoming request from the client.
- mysql: Node JS driver for MySQL.
- ejs: templating engine to render html pages for the app.
- req-flash: used to send flash messages to the view
- nodemon: Installed globally. It is used to watch for changes to files and automatically restart the server


### Folder Structure 
* node-mqsql-crud-app (main directory)   
    * node_modules
    * public
        * assets 
        * img
    * routes
        * index.js
        * player.js
    * views
        * partials 
            * header.ejs
        * index.ejs
        * add-player.ejs
        * edit-player.ejs
    * app.js    
