# CSS

### Objectives
* Become familiar with CSS and Frameworks that make styling web applications faster and easier
* How to customize css when using a framework
* Discuss best practices
* How to incorporate Google Fonts
* Collect helpful resources


* What is HTML?
Hypertext Markup Language - HTML is the language for describing the structure of Web pages

* What is CSS?
Cascading Style Sheets - describes how HTML elements are to be displayed on screen

### Why CSS is important
* Adds your own style to your projects
* `<a href="http://www.csszengarden.com/">Zen Garden</a>`

### Key Principles of CSS
* Types of CSS (in relation to HTML)
  - Inline ```<p style="color: red">in line!</p>```
  - Internal ```<head> <style> p {color: red;}</style> </head>```
  - External ```<link rel="stylesheet" type="text/css" href="./stylesheet.css"/>```

* The Box Model
  * Padding: distance from the inside of the `div` or the `content` to the border
  * Border: border around `div`
  * Margin: distance from exterior content to the `div`


* CSS Ruleset
  * Selector (the HTML element/elements you want to target)
  * Declaration Block (everything inside the curly bois)
    * Property Key/Value Pair (each key/value pair, as separated by a colon and ending in a semicolon, is a    declaration in the declaration block)
      * Property (property name)
      * Value (property) Value

  ```
  .main-container {
    color: #555555;
    font-size: 16px;
  }
  ```

* How CSS declarations Cascade
  * "Cascading" means that styles can fall (or cascade) from one style sheet to another, enabling multiple style sheets to be used on one HTML document
  * CSS hierarchy of importance
    * most specific to most general
  * Style is inherited if not explicitly defined
  * Will always look to nearest definition, if style is declared multiple times.



### CSS Frameworks
* Semantic UI, Material UI, Bootstrap - CSS Frameworks that provide easy ways to style content
* Google Fonts - Library of fonts that can be imported to enhance style of markup
