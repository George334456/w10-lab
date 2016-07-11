Installation
============

    npm install express sqlite3 bcryptjs path nunjucks body-parser express-session
    npm install -g nodemon
    nodemon app.js

If you want to reinitialize the database, you can use this command:

    sqlite3 db.sqlite < schema.sql
