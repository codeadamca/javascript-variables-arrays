# javascript-variables-arrays

Variables and arrays are used to store data to use within your code. A variable can store one piece of data whle an array can store multiple values. 

## Using Variables

To create a variable use the `var`, `let`, or `const` commands.

Open up a new HTML file, name it variables.html, add the standard HTML elements, and then add the following code to the `body` tag:

```html
<script>

var firstName = "Peter";
var lastName = "Smith";
    
document.write( "<p>Hello " + firstName + " " + lastName + "</p>" );

</script>
```

Inside a `document.write()` command, text in between quotes is treated as plain text, while text outside of quotes is treated as a variable, array, or other JavaScript command.

Open the the file using a browser. The `body` section should include a greeting.

## Trying it Out

Create an HTML file and add the following code:

```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <title>JavaScript Variables Exercise</title>
    </head>
    <body>
    
        <script>

        var linkName = "W3Schools";
        var linkLogo = "http://www.w3schools.com/images/w3schools.png";
        var linkURL = "http://www.w3schools.com/";
        var linkDescription = "W3Schools is a web developer information website, with tutorials and references relating to web development topics such as HTML, CSS, JavaScript and PHP.";
        
        </script>

    </body>
</html>
```

Use `document.write()` and the provided variables to display the link information using well formatted HTML. For example, the first variable may look like this:

```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <title>JavaScript Variables Exercise</title>
    </head>
    <body>
    
        <script>

        var linkName = "W3Schools";
        var linkLogo = "http://www.w3schools.com/images/w3schools.png";
        var linkURL = "http://www.w3schools.com/";
        var linkDescription = "W3Schools is a web developer information website, with tutorials and references relating to web development topics such as HTML, CSS, JavaScript and PHP.";
        
        document.write("<h1>" + linkName + "</h1>");

        </script>

    </body>
</html>
```

When you have completed the goal, the `body` tag will only include one `script` tag, the four provided variables, and a number of document.write()` commands outputting the variables with HTML. 

## Varables and Math

Open up a new HTML file, name it variables.html, add the standard HTML elements, and then add the following code to the `body` tag:

```html
<script>

var x = 5;
var y = 10;
    
document.write( "<p>Five plus ten is " + x + y + "</p>" );
document.write( "<p>Five times ten is " + x * y + "</p>" );

</script>
```

Open the the file using a browser. The `body` section should contain a series of math answers.

## Using Arrays

To create an array, use the same syntax as a variable, except the type of variable with be an array:

```javascript
var colours = new Array();
```

Then populate the array using keys:

```javascript
colours[0] = 'Red';
colours[1] = 'Blue';
colours[2] = 'Green';
```

Outputting an array value is similar to outputting a variable, except the variable is followed by a key:

```javascript
document.write("<p>My favourtie colour is " + colours[0] + ".</p>");
```

## Trying it Out

Create an array list of items. Then use a series of `document.write()` commands to display the list.

## Tutorial Requirements:

* [Visual Studio Code](https://code.visualstudio.com/) or [Brackets](http://brackets.io/) (or any code editor)

Full tutorial URL: https://codeadam.ca/learning/javascript-variables-arrays.html

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
