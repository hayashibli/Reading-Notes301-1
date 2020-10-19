# Read:03 Flexbox and Templating.

## Javascript Templating

Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.

Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object, it is often referred to as **logic-less** because there are no if statments, else clauses, or for loops.

```javascript
Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn
```

In the above, we see two braces around {{ name }}. This is Mustache syntax to show that it is a placeholder. When Mustache compiles this, it will look for the ‘name’ property in the object we pass in, and replace {{ name }} with the actual value, e,g, “Sherlynn”.

## Mustache-Express

        $ npm install mustache --save

Configure mustache-express in your server.js/app.js/index.js file:

```javascript
var mustacheExpress = require("mustache-express");

app.engine("html", mustacheExpress());
app.set("view engine", "html");
app.set("views", __dirname + "/src/views");
```

---

## Why Flexbox?

For a long time, the only reliable cross browser-compatible tools available for creating CSS layouts were things like floats and positioning. These are fine, and they work, but in some ways they are also rather limiting and frustrating.

The following simple layout requirements are either difficult or impossible to achieve with such tools, in any kind of convenient, flexible way:

Vertically centering a block of content inside its parent.
Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

Flexbox Froggy
=======

Flexbox Froggy is a game for learning CSS flexbox. Check it out at [flexboxfroggy.com](https://flexboxfroggy.com).


![img](https://github.com/thomaspark/flexboxfroggy/blob/gh-pages/images/screenshot.png?raw=true)
