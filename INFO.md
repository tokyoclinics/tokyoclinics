# Clinics Information

```
.__        _____       
|__| _____/ ____\____  
|  |/    \   __\/  _ \ 
|  |   |  \  | (  <_> )
|__|___|  /__|  \____/ 
        \/             
```

## Application structure

```
.
├── .gitignore
├── package.json
├── settings.json
├── .meteor
|   └── ...
├── node_modules
|   └── ...
├── api
|   ├── methods.js
|	└── rest.js
├── imports
|   ├── startup
|	|	├── client
|	|	|	└──
|	|	└── server
|	|		└──
|   └── ui
|		├── bootstrap.min.css
|		├── bootstrap.min.js
|		├── jquery.min.js
|		└── style.css
├── lib
|   ├── router.js
|	└── collections
|		└── clinics.js
├── client
|	├── main.html
|	├── main.js
|	├── maincordova.html
|	├── maincordova.js
|	├── edit
|	|   ├── edit.html
|	|	└── edit.js
|	├── form
|	|   ├── form.html
|	|	└── form.js
|	├── list
|	|   ├── list.html
|	|	└── list.js
|	├── login
|	|   ├── logincordova.html
|	|	└── logincordova.js
|	├── map
|	|   ├── map.html
|	|	└── map.js
|	├── page
|	|   ├── page.html
|	|	└── page.js
|	└── register
|		├── registercordova.html
|		└── registercordova.js
├── server
|	└── main.js
├── .travis.yml
├── circle.yml
└── mobile-config.js
```

### Rules
* The contents of the .gitignore must be untouched. No deletions will be allowed, however new files/folders can be added to the file if absolutely necessary

## Following the structure

### Client
* All client-only code must go in the client folder
* Inside the client folder, a new folder must be made for a new template. 
