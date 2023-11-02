# Java-script learning documentation

# History

- JavaScript and Java are completely different languages, both in concept and design.
- JavaScript was invented by Brendan Eich in 1995, and became an ECMA standard in 1997.
- ECMA-262 is the official name of the standard. ECMAScript is the official name of the language.

## Why Study javascript?

`JavaScript` is one of the 3 languages all web developers must learn:

- HTML to define the content of web pages
- CSS to specify the layout of web pages
- JavaScript to program the behavior of web pages

> `NB:` it is also call as `trinity`.

## This tutorial covers every version of javascript:

- The Original JavaScript ES1 ES2 ES3 (1997-1999)
- The First Main Revision ES5 (2009)
- The Second Revision ES6 (2015)
- All Yearly Additions (2016, 2017, 2018, 2019, 2020)

## Where to write javascript

- The `<script></script>` tag
  > In HTML, JavaScript code is inserted between <script> and </script> tags.
- example

```sh
<script>
      document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```

- The `<head></head>` tag
  > In this example, a JavaScript function is placed in the <head> section of an HTML page.<br>
  > The function is invoked (called) when a button is clicked:

```sh
<!DOCTYPE html>
<html>
      <head>
            <script>
            function myFunction() {
            document.getElementById("demo").innerHTML = "Paragraph changed.";
            }
            </script>
      </head>
      <body>
      <h2>Demo JavaScript in Head</h2>
      <p id="demo">A Paragraph</p>
      <button type="button" onclick="myFunction()">Try it</button>

      </body>
</html>
```

- The `<body></body>` tag
  > In this example, a JavaScript `function` is placed in the `<body></body>` section of an HTML page.<br> The function is invoked (called) when a button is clicked:

> `NB:` Placing scripts at the bottom of the <body> element improves the display speed, because script interpretation slows down the display.

## JavaScript Display Possibilities
`JavaScript can "display" data in different ways:`
- Writing into an HTML element, using innerHTML.
- Writing into the HTML output using document.write().
- Writing into an alert box, using window.alert().
- Writing into the browser console, using console.log().

## Basics in Java script

- javaScript accepts both `double and single` quotes
- attributes : a collection of objects that belong to a built-in Attr class, with name and value properties.
- javascript can change HTML style (css)

```sh
document.getElementById("demo").style.fontSize = "35px";
```

- javascript can hide HTML elements

```sh
document.getElementById("demo").style.display = "none";
```
