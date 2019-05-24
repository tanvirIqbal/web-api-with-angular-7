# web-api-with-angular-7

This is a simple Employee Registration project with asp.net web api and angular 7

## Enabling CROS

* Open Packege Console Manager
* Run ```Install-Package Microsoft.AspNet.WebApi.Cors```
* Go to ```WebApiConfig``` File
* add this code ```config.EnableCors(new EnableCorsAttribute("http://localhost:4200", headers: "*", methods: "*"));```

## Angular Command

* ```ng new WebAPIWithAngular```
* ```cd .\WebAPIWithAngular\```
* ```ng serve --o```
* ```ng g c employees```
* ```ng g c employees/employee```
* ```ng g c employees/employee-list```
* ```ng g s shared/employee```
* ```ng g cl shared/employee --type=model```

### ngx-toastr

* ```npm install ngx-toastr --save```
* ```npm install @angular/animations --save``` // Do not run this if ```angular/animations``` already exists in the project. Check the ```package.json``` file.
* import ```BrowserAnimationsModule``` and ```ToastrModule.forRoot()``` in the ```app.module.ts``` file.
* add reference ```"node_modules/ngx-toastr/toastr.css"``` to ```angular.json``` in ```styles``` array.
* now you can use ```ngx-toastr```
* <https://www.npmjs.com/package/ngx-toastr>
