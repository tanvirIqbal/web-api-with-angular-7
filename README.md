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
