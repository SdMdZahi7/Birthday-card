# EXP 09 - BIRTHDAY CARD

## AIM:

To create a Birthday card using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document and include the CSS stylesheet.

2. Design the layout of your birthday card using HTML elements such as < div >, < h1 >, < p >, < img >, and < span >. 

3. Add a container < div > to hold the entire birthday card content.
  
4. Use paragraph tag to disply the personalised greeting. Add an image element to display a birthday-themed image.

## CODE:

### BIRTHDAY.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <link href='https://fonts.googleapis.com/css?family=Merienda' rel='stylesheet'>
    <style>
        body {
         font-family: 'Merienda';
         font-size: 22px;
         color: #58a287;
        }
    </style>
    <title>Birthday Greeting</title>
</head>
<body background="bg2.png" style="background-size: 100%;">
    <div style="border:2px solid #932269; margin-top:25px; margin-left: 430px; margin-right: 430px;"> 
    <img src="banner.png" height="80" width="655">
    <center><h1>HAPPY<br>19<sup>th</sup><br>BIRTHDAY</h1></center>
    <center><img src="cake.png" height="250"></center>
    <center>
    <a href="birthday2.html"><button type="button"><img src="balloonclick.png" height="50" width="50" /></button></a>
    </center>
    </div>
</body>
</html>


### BIRTHDAY2.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <link href='https://fonts.googleapis.com/css?family=Aclonica' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Kalam' rel='stylesheet'>
    <title>Birthday Greeting</title>
    <style>
        .container {
          position: relative;
          text-align: center;
        }    
        .centered {
          position: absolute;
          top: 20%;
          left: 50%;
          transform: translate(-50%, -50%);
          font-size: 35px;
          color: #324c81;
          font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .fonts{
            padding-top: 10px;
            font-family: 'Kalam';
            font-size: 30px;
            position:fixed;
            color: #83783a;
        }
    </style>
</head>
<body style="background-color: rgb(240, 223, 234);">
    <div style="border:2px solid #932269; margin-top: 30px; margin-left: 430px; margin-right: 430px; padding-bottom: 2px;"> 
        <div class="container">
            <img src="wallpaper3.png" width="100%" height="650">
            <div class="centered">
                <table>
                    <tr>
                        <td><img src="balloonbutton.png" height="200" width="180"></td>
                        <td><i><b>Happy Birthday You!!!</b></i></td>
                        <td><img src="balloonbutton.png" height="200" width="180"></td>
                    </tr>
                </table>
                <div class="fonts">
                    This birthday, I wish you abundant happiness and love. May all your dreams turn into reality. Happy birthday to one of the sweetest people I’ve ever known.
                    <br>
                    <img src="vector.png" height="50px" width="450px">
                    <center>
                    <table>
                        <tr>
                            <td>With love,</td>
                            <td><a href="https://open.spotify.com/track/5RjUtRlDonw3TBgGGMLC5b?si=c3be36463db0466a"><img src="music.png" height="70" width="90"></a></td>
                        </tr>
                    </table>
                    <center></center>
                    <img src="vectorb.png" height="50px" width="450px">
                </div>
            </div>
        </div>
    </div>   
</body>
</html>


## OUTPUT:
![image](https://github.com/Aashima02/Birthday-Card/assets/93427086/c8c7973a-def4-4328-9e45-687bbc6cc3bf)

![image](https://github.com/Aashima02/Birthday-Card/assets/93427086/b4677557-f78d-4139-8c79-e3423bf04b9a)



## RESULT

So,  a birthday card is created using CSS and HTML.
