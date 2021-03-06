# Angular Workshop

## Installing Angular CLI

Run this command once to install angular cli on your machine.

`npm install -g @angular/cli`

---
The above step needs to be done only once for installing angular cli. The below steps are to be followed everytime we create a new angular project

## Angular Apps

### Creating an angular project

`ng new your_project_name`

Where `your_project_name` is any arbitrary project name of your choice.

### Installing Bulma

[Bulma](https://bulma.io/documentation/) is a CSS framework. We use it to easily add CSS styles to our project. Bulma module has to be installed first on projects where we intent use bulma styles. 

For installing bulma, go inside the project folder and use this command:

`npm install --save bulma`

Once bulma is installed, open `angular.json` file inside the project folder and change the `styles` array to this:

```json
"styles": [
  "node_modules/bulma/css/bulma.css",
  "src/styles.css"
]
```

## Running an Angular App

For serving the app so that we can preview it, go inside the project folder and run this command:

`ng serve --open`

Here, the `--open` option opens the webbrowser after the app is served. By default, the served app is in the uri [http://locahost:4200/](http://locahost:4200/). 


---
[Angular Documentation](https://angular.io/guide/quickstart)
