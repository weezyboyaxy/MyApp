# MyApp
Simple Node.js Application , a experimental one :p 

Follow the bellow steps !

npm install express-generator -g

the following creates an Express app named myapp in the current working directory.

express myapp

next install the dependencies 

npm install

On Windows, use this command to debug ur application :

set DEBUG=myapp & node .\bin\www

The generated app directory structure looks like the following.

.
├── app.js
├── bin
│   └── www
├── package.json
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets
│       └── style.css
├── routes
│   ├── index.js
│   └── users.js
└── views
    ├── error.jade
    ├── index.jade
    └── layout.jade

7 directories, 9 files


Then load http://localhost:3000/ in your browser to access the app.

