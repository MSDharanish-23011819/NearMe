# Ex04: Places Around Me
## Name : Jeevan ES
## Reg no : 212223230091
## Date : 07-10-24

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
<!DOCTYPE html>
<html>
<head>
    <title>Chennai</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>Jeevan ES(212223230091)</b></font>
    </h1>
    <img src="map.png" alt="Workplace" usemap="#workmap" height="650" width="1465">
    <map name="workmap">
        <area shape="circle" coords="200,300,30" alt="Avadi" href="Avadi.html">
        <area shape="circle" coords="600,350,30" alt="Anna nagar" href="anna nagar.html">
        <area shape="circle" coords="700,450,30" alt="t nagar" href="tnagar.html">
        <area shape="circle" coords="170,500,30" alt="ponnamalle" href="Ponnamalle.html">
    </map>
</body>
</html>
```
```
<html>
    <head>
        <title>Anna nagar</title>
    </head>
    <body style="background-color: rgb(223, 222, 153);">
        <center>
            <h1 style="color: rgb(0, 255, 234);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">Anna nagar</h3>
            <hr>
            <p style="font-size: 20px;">Anna Nagar is a neighbourhood in the metropolitan city of Chennai, India. Named after former chief minister of Tamil Nadu C. N. Annadurai, it is located in the north-western part of Chennai and forms a part of the Aminjikarai taluk and the Anna Nagar Zone. It is one of the prime residential areas in Chennai and is home to several prominent doctors, lawyers and politicians</p>
        </center>
    </body>
</html>

```

```
<html>
    <head>
        <title>Avadi</title>
    </head>
    <body style="background-color: palevioletred;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">Avadi</h3>
            <hr>
            <p style="font-size: 20px;">Avadi is a western suburb of Chennai, and the headquarters of Avadi taluk located within the Thiruvallur district of Tamil Nadu, India. Situated at about 22 kilometres (14 mi) from Chennai Central Railway Station, it is one of the four municipal corporations in the Chennai Metropolitan Area and is governed by the Avadi Municipal Corporation.</p>
        </center>
    </body>
</html>
```
```
<html>
    <head>
        <title>Ponnamalle</title>
    </head>
    <body style="background-color: rgb(141, 186, 199);">
        <center>
            <h1 style="color: rgb(225, 0, 255);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">Ponnamalle</h3>
            <hr>
            <p style="font-size: 20px;">Poonamallee is a town and suburb of Chennai, India under the Chennai Metropolitan Area. It was historically called Pushpagirimangalam, later renamed in Tamil as Poovirundhavalli and now colloquially called as Poondhamalli. It is the headquarters of the Poonamallee taluk of the Tiruvallur district in the Indian state of Tamil Nadu.</p>
        </center>
    </body>
</html>
```
```
<html>
    <head>
        <title>T nagar</title>
    </head>
    <body style="background-color: rgb(130, 185, 130);">
        <center>
            <h1 style="color: rgb(0, 255, 234);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">T nagar</h3>
            <hr>
            <p style="font-size: 20px;"> Thyagaraya Nagar, commonly known as T. Nagar, and historically known as East Mambalam is a very affluent commercial and residential neighbourhood in Chennai, Tamil Nadu, India. It is surrounded by Nungambakkam in the North, Teynampet in the East, Nandanam in the South-East, C.I.T. Nagar (a part of Greater Nandanam region) in the South and West Mambalam and Kodambakkam in the West.</p>
    </body>
</html>
```


## OUTPUT

![map](https://github.com/user-attachments/assets/f601e3d9-bf92-47f2-a0d7-61ed58c55ac1)
![image](https://github.com/user-attachments/assets/0139162d-3182-4ecb-b2a1-2e109180ede4)
![image](https://github.com/user-attachments/assets/90669e45-e87c-4b19-b515-192483533721)
![image](https://github.com/user-attachments/assets/ebd9b28c-d7cb-44d1-bf88-e2a56a27d174)
![image](https://github.com/user-attachments/assets/57428dd5-e63e-454a-bcf3-d84eafdbc526)



## RESULT
The program for implementing image maps using HTML is executed successfully.
