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

* [Visual Studio Code]
* [Bootstrap v5.1.3]
* [node.js]
* [Npm]
* [Sass]

## GITHUB REPO

1. First public repository to display the replica version:
- [odoo-bootstrap-card-component](https://github.com/jfvandermousen/odoo-bootstrap-card-component)
- [Github Page for replica](https://jfvandermousen.github.io/odoo-bootstrap-card-component/)

2. From the first repository i make a template and create the second repository to display the custom design version:
- [odoo-card-custom-design](https://github.com/jfvandermousen/odoo-card-custom-design)
- [Github Page for custom design](https://jfvandermousen.github.io/odoo-card-custom-design)



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


### Code objectifs on separates branches :

1. #### main branch -> Objectif A

- Replicate custom card component using only utility classes, js components and custom variables
- Build loader only with html / css 
- Build svg loader in comments 

2. #### Custom-design branch -> Objectif B and Objectif C

    ##### Custom Design of card component

- Separate in differents files under sass folder -> more maintenable / readable
- Create custom base styles _base.scss
- Create custom theme colors in _variables.scss
- Create each loop in colors-loop. to have light and dark variations
- Create odoocard component with mixins for card-header, card-body, card-footer and each    loop to display the diffrents variations
- Each contextual classes should be applied on the component’s main <div> and trigger the style for all inner elements.









> Jean-François Vandermousen


[//]: #

[node.js]: <http://nodejs.org>
[Visual Studio Code]: <https://code.visualstudio.com>
[Bootstrap v5.1.3]: <https://getbootstrap.com>
[Npm]: <https://www.npmjs.com>
[Sass]: <https://sass-lang.com>
