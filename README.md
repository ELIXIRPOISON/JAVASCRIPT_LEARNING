# DOM Manipulation Example

This project demonstrates basic DOM manipulation using JavaScript. The HTML file contains a `div` element whose styles are dynamically changed using JavaScript.

## Project Structure

## Contents

- `index.html`: The main HTML file containing the `div` element and the JavaScript code to manipulate its styles.
- `README.md`: This file, providing an overview of the project.

## HTML File

The `index.html` file includes a `div` element with the text "Hello, Jai Mata Di!" and a script that modifies its styles.

### index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DOM Manipulation</title>
</head>
<body>

<div id="myDiv">Hello, Jai Mata Di!</div>

<script>
var divElement = document.getElementById("myDiv");
divElement.style.color = "blue";            
divElement.style.backgroundColor = "yellow"; 
divElement.style.margin = "20px";           
divElement.style.padding = "10px";        
divElement.style.fontSize = "18px";         
divElement.style.fontWeight = "bold";      
divElement.style.height = "200px";          
divElement.style.width = "300px";          
</script>

</body>
</html>

