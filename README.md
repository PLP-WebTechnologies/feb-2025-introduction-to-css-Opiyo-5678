# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styles */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
    padding: 20px;
}

/* Header Styles */
header {
    background-color: #2c3e50;
    color: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
}

/* Navigation Styles */
nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
    margin-top: 10px;
}

nav ul li a {
    color: #ecf0f1;
    text-decoration: none;
    padding: 5px 10px;
    border-radius: 4px;
    transition: background-color 0.3s;
}

nav ul li a:hover {
    background-color: #34495e;
}

/* Section Styles */
section {
    background-color: white;
    padding: 25px;
    margin-bottom: 30px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

/* Heading Styles */
h1, h2, h3 {
    font-family: 'Georgia', serif;
    color: #2c3e50;
}

h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

h2 {
    font-size: 1.8em;
    border-bottom: 2px solid #3498db;
    padding-bottom: 10px;
    margin-bottom: 20px;
}

h3 {
    font-size: 1.3em;
    margin-bottom: 15px;
}

/* Paragraph Styles */
p {
    margin-bottom: 15px;
}

/* List Styles */
ol {
    margin-left: 30px;
    margin-bottom: 20px;
}

ol li {
    padding: 5px 0;
}

/* Image Styles */
figure {
    margin-bottom: 20px;
}

img {
    max-width: 100%;
    height: auto;
    border: 3px solid #3498db;
    border-radius: 8px;
    transition: transform 0.3s ease;
}

img:hover {
    transform: scale(1.02);
}

figcaption {
    font-style: italic;
    text-align: center;
    margin-top: 10px;
    color: #7f8c8d;
}

/* Table Styles */
table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
}

caption {
    font-weight: bold;
    margin-bottom: 10px;
    font-size: 1.2em;
}

th, td {
    padding: 12px;
    text-align: left;
    border: 1px solid #ddd;
}

th {
    background-color: #3498db;
    color: white;
}

tr:nth-child(even) {
    background-color: #f2f2f2;
}

tr:hover {
    background-color: #e3f2fd;
}

/* Form Styles */
form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

form div {
    margin-bottom: 10px;
}

label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

input, select {
    width: 100%;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-family: inherit;
}

input:focus, select:focus {
    outline: none;
    border-color: #3498db;
    box-shadow: 0 0 5px rgba(52, 152, 219, 0.5);
}

fieldset {
    border: 1px solid #ddd;
    padding: 15px;
    border-radius: 4px;
    margin-bottom: 15px;
}

legend {
    font-weight: bold;
    padding: 0 10px;
}

button {
    background-color: #3498db;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #2980b9;
}

button[type="reset"] {
    background-color: #e74c3c;
}

button[type="reset"]:hover {
    background-color: #c0392b;
}

/* Multimedia Styles */
audio, video {
    width: 100%;
    margin-bottom: 20px;
}

/* Footer Styles */
footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 20px;
    border-radius: 8px;
    margin-top: 30px;
}

footer a {
    color: #3498db;
}

/* ID Selector Example */
#form-section {
    background-color: #f0f7ff;
    border-left: 5px solid #3498db;
}

/* Class Selector Example */
.required-field::after {
    content: " *";
    color: red;
}

/* Specific Element Selector Example */
input[type="checkbox"] + label {
    display: inline-block;
    margin-left: 5px;
}


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
    <link rel="stylesheet" href="style.css">
</head>
