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
/* General styling for the body */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
    text-align: center;
}

/* Styling for a header using an ID */
#main-header {
    background-color: #333;
    color: white;
    padding: 20px;
    font-size: 24px;
    border-bottom: 5px solid #ff6600;
}

/* Styling for a paragraph using a class */
.text-box {
    color: #555;
    font-size: 18px;
    margin: 20px;
    padding: 15px;
    border: 2px solid #ccc;
    background-color: white;
    border-radius: 10px;
}

/* Styling an image */
.image-style {
    width: 300px;
    height: auto;
    border: 5px solid #ff6600;
    margin: 20px;
    padding: 10px;
    border-radius: 15px;
}

/* A button style */
.button {
    background-color: #ff6600;
    color: white;
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.button:hover {
    background-color: #cc5500;
}
