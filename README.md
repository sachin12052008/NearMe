# Ex04 Places Around Me
## Date: 25/09/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
sm.html

<html>
<head>
    <title>Salem</title>
    <link rel="stylesheet" href="style.css">        
</head>
<body>
    <h1 align="center">SALEM</h1>
 <h2 align="center">SACHIN JM(25007184)</h2>
<img src="Screenshot 2025-09-22 092140.png" usemap="#image-map">

<map name="image-map">
    <area shape="rect" coords="571,474,719,525" href="elampillai.html" alt="elampillai">
    <area shape="rect" coords="868,703,973,759" href="rasipuram.html" alt="rasipuram">
    <area shape="circle" coords="307,220,74" href="mettur.html" alt="mettur">
    <area shape="poly" coords="737,58,863,46,875,106,729,117" href="kadayampatti.html" alt="kadayampatti">
    <area shape="circle" coords="1009,185,97" href="kiliyur.html" alt="kiliyur falls">
</map>

</body>
</html>

style.css

        body
        {<h1>SACHIN  J M(25007184)</h1>
            background-color: red;
            color: red;
        }

        h2
        {
            color: red;
        }

 elampilai.html

 <html>

<head>
    <style>
        body {
            background-color: blanchedalmond;
        }
    </style>
</head>
<center>
<body>
    <h1 align="center">SALEM <br>Ellampillai</h1>


    <h2>Elampillai is a significant center for handloom weaving and textile manufacturing in the Salem region.<br>
    Salem silk sarees and related silk/semi-silk/soft silk materials are made in this area.<br>
    Elampillai and the surrounding area have a lot of handlooms and weaving units in their community

    </h2>
</body>
</center>


</html>

kiliyur.html

<html>

<head>
    <Style>
        body {
            background-color: rgb(255, 0, 166);
        }
    </Style>
</head>
<center>

    <body>

        <h1 align="center"> SALEM <br>Kiliyur falls </h1>
        <h2> The falls are formed by waters overflowing from Yercaud Lake, atop the Servaroyan (or Shevaroyan) hills,
        which are part of the Eastern Ghats.<br>
        The water plunges into the Kiliyur Valley from a height of about 300 feet.
        </h2>
    </body>
</center>



</html>

kadayampatti.html

<html>

<head>
    <Style>
        body {
            background-color: rebeccapurple;
        }
    </Style>
</head>
<center>

    <body>
        <h1 align="center"> SALEM <br>Kadayampatti </h1>
        <h2> Its one of the unique place in salem because it has the mountain with falls where the water comes from yercadu.<br>
        the place we called as "Moongil Forest"because the mountain contains many bamboo and the water strikes the bamboo and the water hence the water become more cold.

        </h2>
    </body>
</center>



</html>

mettur.html

<html>

<head>
    <Style>
        body {
            background-color: red;
        }
    </Style>
</head>
<center>

    <body>
        <h1 align="center">SALEM <br> Mettur Dam </h1>
        <h2>Mettur is an industrial town: chemical factories, power plants, and aluminum works are some of the keyindustries.<br>
        The presence of Mettur Thermal Power Station and chemical industries (e.g. bleach, caustic soda, etc.) make it economically important.
        </h2>
    </body>

</center>


</html>

rasipuram.html

<html>

<head>
    <Style>
        body {
            background-color: aqua;
        }
    </Style>
</head>
<center>
    <body>
    <h1 align="center">SALEM 
        <br> 

        
        Rasipuram </h1>
    <h2>
        The Arulmigu Kailasanathar temple is very significant due to its significance as the only temple with a 5-tier
        Rajagopuram, to its advanced state through the still unique gold-plated threshold, as well as the Vanni tree as
        it's sthala viruksham etc.<br>
        Festival celebrations are still important, apparent in the holding of 63 Nayanmars festival, as well as the
        Nithya Sumangali Mariamman temple festival which is celebrated in the month of Aippasi, etc...
    </h2>
</body>
</center>




</html>

```


## OUTPUT

![alt text](<Screenshot 2025-09-27 231330.png>)
![alt text](<Screenshot 2025-09-27 231410.png>) 
![alt text](<Screenshot 2025-09-27 231353.png>)
![alt text](<Screenshot 2025-09-27 231424.png>) 
![alt text](<Screenshot 2025-09-27 231438.png>)
![alt text](<Screenshot 2025-09-27 231505.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
