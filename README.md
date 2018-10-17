# cs-schema 
A schematics to build view components as pages on angular-cli 

## Install

```sh
npm install cs-schema
```

## Usage

Generate a page

```sh
ng generate cs-schema:page pageName

```
## Output

it generates view components

 ```sh
page-name.page.css
page-name.page.html
page-name.page.spec.ts
page-name.page.ts
UPDATE src/app/app.module.ts
```
The Goal is to achive 
*([Angular Folder Structure](https://medium.com/@motcowley/angular-folder-structure-d1809be95542))
* Structure directory (angular6-example-app [here](https://github.com/Ismaestro/angular6-example-app))
* More logical structure directory (from [here](https://itnext.io/choosing-a-highly-scalable-folder-structure-in-angular-d987de65ec7))


## License

MIT License © Cliste Software 2018