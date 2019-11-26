# devlogger

npm install -g @angular/cli

ng g c components/posts --spec=false

ngOnInit OnInit
lifecycle method
initialize as constructor

npm install bootstrap
npm install bootstrap@4.0.B beta.2 jquery popper.js
npm install bootstrap jquery popper.js

angular.json
"styles": [
              "src/styles.css",
              "../angularapp/node_modules/bootstrap/dist/css/bootstrap.css",
	      "../clientpanel/node_modules/font-awesome/css/font-awesome.css"
            ],
            "scripts": [
              "../angularapp/node_modules/jquery/dist/jquery.js",
              "../angularapp/node_modules/popper.js/dist/umd/popper.js",
              "../angularapp/node_modules/bootstrap/dist/js/bootstrap.js"
            ]


npm install font-awesome --save

ng g s services/post --module=app.module --spec=false

ng g m app-routing --flat --module=app


https://github.com/ngx-translate/core
https://www.primefaces.org/primeng/#/
https://www.npmjs.com/package/ng2-toasty

https://pages.github.com/


npm install primeng --save
npm install primeicons --save

"dependencies": {
  //...
  "primeng": "^7.0.0",
  "primeicons": "^1.0.0"
},

"styles": [
  "node_modules/primeicons/primeicons.css",
  "node_modules/primeng/resources/themes/nova-light/theme.css",
  "node_modules/primeng/resources/primeng.min.css",
  //...
],


Build & deploy to Github
-------------------------
ng build
ng build --prod
(which creates dist folder)

In Github create repository 'username.github.io'

Create a folder in local storage and navigate to that
cd <filename>
git clone https://github.com/username/username.github.io

Copy contents of /dist folder to newly created folder,
username.github.io
and navigate to it,
cd username.github.io

git add --all
git commit -m "Initial commit"
git push -u origin master
