# Odoo-bootstrap-card-component

## Objectifs

Code a custom Bootstrap Card component 

1. **Objectif A** -> Replicate the component publish the project on github.
2. **Objectif B** -> Improve the design
3. **Objectif C** -> Create a SCSS mixin defining design variations for each bootstrap contextual class
4. **Objectif D** -> Write an UX report highlighting component’s usability issues

## Prerequisites

- SASS/SCSS preprocessor
- Bootstrap v4.3 (or higher)
- Github account


## Tech I used

* Visual Studio Code
* Bootstrap v5.1.3
* [node.js]
* Npm
* Sass

## Installation

1. Create a public repository [odoo-bootstrap-card-component](https://github.com/jfvandermousen/odoo-bootstrap-card-component) on GitHub and clone it in local.
2. Install Bootstrap’s source Sass and JavaScript files via npm
```sh
npm install bootstrap
```
3. Create SASS folder and main.scss file for customize varibales, css, mixins,...
3. Import Bootstrap’s source Sass files in main.scss
```sh
@import "../node_modules/bootstrap/scss/bootstrap";
```
4. Compile sass file with live sass Compiler VsCode extension in css Folder.
 config of setings.json of live sass Compiler extension:
```sh
        {
            "format": "compressed",
            "extensionName": ".min.css",
            "savePath": "/css"
        },
```

## Works methodology


#### Code  each objectif on separates branches :

1. ##### main branch -> Objectif A

- Replicate custom card component using only utility classes, js components and custom variables
- Build loader only with html / css 
- Build svg loader on separate branch

2. ##### custom-design branch -> Objectif B

- Custom Design of card component

3. ##### mixins branch -> Objectif C

- Create mixin for contextual classes
- Separate in differents files - more maintenable - readable







> Jean-François Vandermousen


[//]: #

[node.js]: <http://nodejs.org>

[Visual Studio Code]:
[Bootstrap v5.1.3]:
[node.js]:
[Npm]:
[Sass]: