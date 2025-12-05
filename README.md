# Ex03 Places Around Me
## Date: 05/12/2025

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
nearme.html
<html>
    <body>
        <h1 align="center"><font color="cyan">Tondiarpet-Chennai</font></h1>
        <br><br>
        <h2 align="center"><font color=red>SYED MEERAN A-(25008812)</font></h2>
        <br>
        
<img src="Screenshot 2025-12-05 084316.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Apollo Hospitals Tondiarpet" title="Apollo Hospitals Tondiarpet" href="ApolloHospitalsTondiarpet.html" coords="1147,525,1326,599" shape="rect">
    <area target="" alt="New Washermenpet Metro" title="New Washermenpet Metro" href="NewWashermenpetMetro.html" coords="1218,362,1401,404" shape="rect">
    <area target="" alt="VOC Nagar railway station" title="VOC Nagar railway station" href="VOCNagarrailwaystation.html" coords="1108,164,1231,164,1243,182,1230,230,1099,243,1101,182,1228,183,1116,181" shape="poly">
    <area target="" alt="Tondiarpet  railway station" title="Tondiarpet  railway station" href="Tondiarpet.html" coords="1004,632,64" shape="circle">
    <area target="" alt="Super Hotel O Sea View Inn" title="Super Hotel O Sea View Inn" href="SuperHotelOSeaViewInn.html" coords="1387,345,1380,289,1524,277,1550,335" shape="poly">
</map>
    </body>
</html>
ApolloHospitalsTondiarpet.html
<html>
    <head>
        <h1 align="center"><font color="red">TONDIARPET-CHENNAI</font></h1>
    </head>
    <body bgcolor="yellow">
        <h4 align="center"><font color="brown">Apollo Hospitals Tondiarpet</font></h4>
        <hr>
        Apollo Hospitals Tondiarpet Apollo Hospitals in Tondiarpet, Chennai, is a multi-specialty hospital established in 2000 to serve the North Chennai area. It is a 60-bed facility offering a wide range of services, including 24/7 emergency care, an ICU, an operating theater, and a dialysis unit. The hospital provides comprehensive care in departments like cardiology, gastroenterology, neurology, orthopedics, and trauma. 
    </body>
</html>
NewWashermenpetMetro.html
<html>
    <head>
        <h1 align="center"><font color="black">TONDIARPET-CHENNAI</font></h1>
    </head>
    <body bgcolor="pink">
        <h4 align="center"><font color="red">New Washermenpet Metro</font></h4>
        <hr>New Washermenpet Metro is a station on the Blue Line of the Chennai Metro. It is an elevated station that opened on February 14, 2021, and connects the northern suburbs like New Washermenpet with the Blue Line's southern terminals, such as Chennai International Airport. The station serves commuters with a ticketing and security area, escalators, elevators, and staircases connecting the concourse to the platform.
        
    </body>
</html>
VOCNagarrailwaystation.html
<html>
    <head>
        <h1 align="center"><font color="white">TONDIARPET-CHENNAI</font></h1>
    </head>
    <body bgcolor="black">
        <h4 align="center"><font color="red">VOC Nagar railway station</font></h4>
        <hr><font color="white">V.O.C. Nagar Railway Station (VOC) is a suburban station in Chennai, part of the Chennai Central-Gummidipoondi line, known for serving the Tondiarpet area and a large railway yard, often used by railway employees and railfans, with limited basic amenities but good bus connectivity to the city. It was formerly the Tondiarpet Marshalling Yard and is located north of Chennai Central, featuring electrified lines and platforms for local EMU services, but sees few long-distance trains.</font>
        
    </body>
</html>
Tondiarpet.html
<html>
    <head>
        <h1 align="center"><font color="black">TONDIARPET-CHENNAI</font></h1>
    </head>
    <body bgcolor="green">
        <h4 align="center"><font color="red">Tondiarpet  railway station</font></h4>
        <hr>Tondiarpet Railway Station (TNP) is a key part of the Chennai Suburban Railway Network (SR), serving the Tondiarpet area, about 5 km north of Chennai Central. It functions as a busy junction for suburban lines and has connections for city transport (buses/taxis). The area also hosts the Tondiarpet Marshalling Yard (TNPM) and a Diesel Loco Shed, making it a significant freight and operational hub within Chennai's rail network. 
        
    </body>
</html>
SuperHotelOSeaViewInn.html
<html>
    <head>
        <h1 align="center"><font color="red">TONDIARPET-CHENNAI</font></h1>
    </head>
    <body bgcolor="black">
        <h4 align="center"><font color="white">Super Hotel O Sea View Inn</font></h4>
        <hr><font color="blue">Super Hotel O Sea View Inn is a 3-star hotel in Chennai, India, that offers air-conditioned rooms, free WiFi, and a 24-hour front desk. It is located about 6.4 km from the city center and features amenities like a private bathroom, flat-screen TV, and room service. Guests have praised the hotel for its cleanliness, comfortable beds, and friendly staff. </font>
        
    </body>
</html>

```



## OUTPUT
![alt text](map-2.png)
![alt text](<apollo hospital tondiarpet-1.png>)
![alt text](<new washermenpet metro-1.png>)
![alt text](<super hotel o sea view inn-1.png>)
![alt text](<tondiarpet railway station-1.png>)
![alt text](<VOC railway station-1.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
