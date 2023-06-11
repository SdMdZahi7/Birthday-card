# EXP 09 - BIRTHDAY CARD
## AIM:
To create a Birthday card using HTML and CSS

## ALGORITHM:
Set up the basic structure of your HTML document and include the CSS stylesheet.

Design the layout of your birthday card using HTML elements such as < div >, < h1 >, < p >, < img >, and < span >.

Add a container < div > to hold the entire birthday card content.

Use paragraph tag to disply the personalised greeting. Add an image element to display a birthday-themed image.

## CODE:
### BIRTHDAY.HTML:
~~~
<!DOCTYPE html>
<html>
    <head>
        <style>
            .card-image
             {
                background-image: url("pink.png");
                height:750px;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
                position: relative;
             }

            .card-text
             {
                 text-align: left;
                 position: absolute;
                 top: 50%;
                 left: 50%;
                 line-height: 0.5;
                 transform: translate(-50%, -50%);
                 
            }
        </style>
    </head>
    <body>
    <div class="card-image">
    <div class="card-text">
        <h1 style="text-align:center; font-family:cursive;">To my special one</h1>
        <h1 style="font-size:70px ;color: rgb(120, 51, 126);text-align: center">HAPPY BIRTHDAY </h1>
        <h1 style="text-align:center; font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
            Today is your big day.
        </h1>
        <h1 style="text-align:center;font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">
            I wish all happy and fun celebration.
        </h1>
    </div>
    </div>
    </body>
</html>
~~~
## OUTPUT:
### Background image:
![WhatsApp Image 2023-06-11 at 19 15 13](https://github.com/SdMdZahi7/Birthday-card/assets/94187572/559b89e8-8c4a-40db-b315-1cada3e810d8)
## Final Output:
![WhatsApp Image 2023-06-11 at 19 15 13](https://github.com/SdMdZahi7/Birthday-card/assets/94187572/4d6ed173-a8af-401f-8aba-d2e2c66b46a2)


## RESULT
So, a birthday card is created using CSS and HTML.
