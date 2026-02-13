# Ex03 Places Around Me
## Date: 13/2/2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center" >
            Chidambaram
        </h1>
        <h3 align="center">
            Abinaya A P(25014971)
        </h3>
        <img src="Screenshot (26).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Chidambaram" title="Chidambaram" href="chidambaram.html" coords="1378,448,1523,538" shape="rect">
    <area target="" alt="Pichavaram" title="Pichavaram" href="pichavaram.html" coords="1815,425,55" shape="circle">
    <area target="" alt="Bhuvanagiri" title="Bhuvanagiri" href="bhuvanagiri.html" coords="1276,270,1205,308,1203,367,1325,364,1337,299" shape="poly">
    <area target="" alt="Parangipettai" title="Parangipettai" href="parangipettai.html" coords="1659,16,1803,78" shape="rect">
    <area target="" alt="Sethiathoppu" title="Sethiathoppu" href="sethiathoppu.html" coords="794,366,77" shape="circle">
</map>


<html>
    <head>
        <title>Bhuvanagiri</title>
        Bhuvanagiri
    </head>
    <body bgcolor="pink">
        <br>
        <br>
        Bhuvanagiri is a Taluka in the Cuddalore district of the Indian state of Tamil Nadu. It is the birthplace of a South Indian saint, Sri Raghavendra Swami.
    </body>
</html>

<html>
    <head>
        <title>Chidambaram</title>
        Chidambaram
        <br>
        Natarajar Temple
    </head>
    <br>
    <br>
    <body bgcolor="pink">
        Thillai Nataraja Temple, also referred as the Chidambaram Nataraja Temple, is a Hindu temple dedicated to Nataraja, the form of Shiva as the lord of dance (cosmic dancer)
    </body>
</html>

<html>
    <head>
        <title>Pichavaram</title>
        Pichavaram
    </head>
    <br>
    <br>
    <br>
    <body bgcolor="pink">
        Pichavaram consists of a number of islands interspersing a vast expanse of water covered with mangrove forest.The Pichavaram mangrove Forest is one of the largest mangrove forests in India .
    </body>
</html>

<html>
    <head>
        <title>Parangipettai</title>
        Parangipettai
    </head>
    <br>
    <br>
    <body bgcolor="pink">
        Parangipettai historically called Porto Novo ("New Port" in Portuguese), is a coastal panchayat town in Cuddalore district in the Indian state of Tamil Nadu.
    </body>
</html>

<html>
    <head>
        <title>Sethiathoppu</title>
        Sethiathoppu
    </head>
    <br>
    <br>
    <body bgcolo="pink">
        Sethiathoppu is a panchayat town in Bhuvanagiri, Tamil Nadu. It is situated on a crossroads of the Chennai–Thanjavur (National Highway 24) highway. 
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (27).png>) 
![alt text](<Screenshot (28).png>)
 ![alt text](<Screenshot (29).png>) 
 ![alt text](<Screenshot (30).png>) 
 ![alt text](<Screenshot (31).png>) 
 ![alt text](<Screenshot (32).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
