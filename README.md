![](https://drive.google.com/uc?export=download&id=19xRXSL98_0BaB2hDFeH1UqzO_HFSTZED)

## Lynx Development Website. Front-end

#### Project structure
```
 ├── bower.json
 ├── build
 │   ├── css
 │   │   └── main.css
 │   ├── fonts
 │   ├── img
 │   ├── index.html
 │   └── js
 │       └── main.js
 ├── gulpfile.js
 ├── package.json
 ├── README.md
 └── src
     ├── fonts
     ├── img
     ├── index.html
     ├── js
     │   ├── main.js
     │   └── partials
     │       └── app.js
     ├── style
     │   ├── main.scss
     │   └── partials
     └── template
         ├── footer.html
         ├── header.html
         └── sections
```

#### Installing packages and dependencies

```sh
# clone github repo
git clone https://github.com/Lynx-Development/Lynx-Development-Front.git

# navigate to project dir
cd Lynx-Development-Front

# install dependencies listed in package.json
npm istall

# install dependencies listed in bower.json
bower install
 
```

#### Run project

```sh
# run project
gulp 
```

#### Builds commands:
```sh
# build html files
gulp html:build

# build scss files (compile and minify)
gulp style:build

# build js files (minify)
gulp js:build

# build image (compress)
gulp image:build

# build fonts 
gulp fonts:build

# (clean from build dir old deleted files)
gulp clean 

```