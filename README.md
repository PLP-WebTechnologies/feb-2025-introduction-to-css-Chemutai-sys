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
<!DOCTYPE html>
<html lang="en">
    <head>
        <style>
            #p-main{
                color:blue;
                font-style: oblique;
                font-size: 20px;

            }
            img{
                border:5px;
                border-radius: 3px;
                margin:150px;
                display:flexbox;
                margin:200px;
                padding: 30px;
            }

    </style>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Data</title>
        <!--external styling/css-->
        <link rel="stylesheet" href="styles/style.css">
    </head>
    <body>
            <p id="p-main">This is such a cute image</p>
            <img src="https://images.pexels.com/photos/31350735/pexels-photo-31350735.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2">
            <a class="google-link" href="https://google.com">Go to google</a>
        </body>
        

</html>
 
