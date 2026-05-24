1. We will intialize the new node project by npm init -y and -y for all answer to be yes.

2. Than we will install express and nodemon to our project.

3. Then we will require our needs as express and than we will listen on any standard port to Live our server(generally 3000).

4. Than we will use middlewares
    1. app.set('view engine', 'ejs');
    2. app.use(express.json());
    3. app.use(express.static(path.join(__dirname, "public"))); => acces public folder's file directly to browser;

6. We have to require the path as we are using it

5. We will create an views folder in which an file index.ejs and it will store our html code.

6. we will render this in our api and send to our browser.

7. now install ejs and open server on browser

8. <script src="https://cdn.tailwindcss.com"></script> add this in our ejs to link the tailwind

9. main div.
10. inside divs to create taks 
    1. forms
    2. tasks

11. forms , we created a form tag in which two tags more
    1. input
    2. textare

12. input for title
13. text are for content

14. we have wrritten our <%%> ejs code if files.length  > 0 than for EAch loop will run else no files