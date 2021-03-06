![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 04: HTML Templating w/HandlebarsJS
===
## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/simple-validation-of-a-username-with-regex) and follow the submission instructions from Lab 01.

## Lab 04 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[Handlebars Docs](http://handlebarsjs.com/)

[Arrow Functions MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

## Configuration
_Your repository must include:_

```
04-templating
└── starter-code
└── driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── README.md
  ├── index.html
  ├── scripts
  │   ├── article.js
  │   ├── articleView.js
  │   └── blogArticles.js
  ├── styles
  │   ├── base.css
  │   ├── layout.css
  │   └── modules.css
  └── vendor
      └── styles
          ├── fonts
          │   ├── icomoon.eot
          │   ├── icomoon.svg
          │   ├── icomoon.ttf
          │   └── icomoon.woff
          ├── icons.css
          └── normalize.css
  └── PULL_REQUEST_TEMPLATE.md
  └── README.md
```

## User Stories and Feature Tasks

*As a user, I want my app to render articles with consistent formatting so that I can visit the site often and have the same experience each time.*

- Include the Handlebars.js CDN in your project to replace the `$.clone()` template.

*As a developer, I want to utilize the Handlebars library to dynamically render the articles using a template so that I can easily edit the way articles are rendered.*

- Convert your existing HTML template into a Handlebars template.
- Update the `Article.prototype.toHtml()` method to utilize the Handlebars template.

*As a developer, I want to utilize modern JavaScript features so that my code is up to date with industry standards.*

- Refactor the functions and methods in your code to use ES6 arrow functions when possible.

### Stretch Goal
*As a developer, I want to use Handlebars to build my filters so that my code is more DRY.*

- Look at all that duplicated markup inside your `#filter` list items! Looks like a good opportunity to use a template. Make a small template for each filter, and re-render the list once you have data to populate it.

## Documentation
_Your README.md must include:_

```md
# 04-Templating

**Authors**: Rhiannon Mortensen & Stephen Harper
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
We built an application that utilized handlebars.js CDN to replace our cloning method of templating our articles. Then we converted our existing HTML template to fit the bill of our newer method of templating, then updated the .toHtml() method to render stuff via the handlebars template. Also, refactored out traditional jQuery functions and methods in our code to ES6 arrow fuhnctions when we could. 

## Getting Started
Use the resources from the OrigiREADME.md, and do their best to follow along with the starter-code instructions.

## Architecture
Languages Used :
Handlebars, jQuery, JavaScript, CSS for web page design, and HTML for the structure.

## Change Log

04-13-2018 10:56AM - Application now has everything that a web page needs to be.

## Credits and Collaborations
--> 
for our commented answer:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort

John Cokos, our instructor (well one of them)

Oh, and us (Stephen and Rhiannon)
```
