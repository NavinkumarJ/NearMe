# Ex04 Places Around Me
## DATE:24.10.23
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
### map.html :
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body bgcolor="gray">
<center><table border="1px">
    <tr><th><font face="Tahoma" size="10" border="10px">PORUR</font></th></tr>
    <tr><th><font face="Tahoma" size="5" >NAVIN KUMAR J (212222240071)</font></th></tr>
</table></center>
    
<center>
<img src="map1.png" usemap="#MyCity" height="590" width="1490">

<map name="MyCity">
    <area target="_blank" alt="porurlake" title="porurlake" href="lake.html" coords="500,300,650,400" shape="rect">
    <area target="_blank" alt="porurjunction" title="porurjunction" href="jun.html" coords="700,500,600,300" shape="rect">
    <area target="_blank" alt="Commerzone" title="Commerzone" href="com.html" coords="700,900,600,300" shape="rect">

</map>
</center>
</body>
</html>
```
### lake.html :
```
<!DOCTYPE html>
<html>
    <head>
        <title>PORUR LAKE</title>
    </head>
    <body bgcolor="lightblue">
        <center>
            <h1 style="font-family: Tahoma;">PORUR LAKE!</h1>
            <hr color="black" size="10">
            <img align="left" src="lake1.jpg" width="500" height="300">
            <img align="center" src="lake.jpg" width="450" height="300">
            <img align="right" src="lake2.jpg" width="500" height="300">
            <hr color="black" size="10">
            <p style="font-family: Verdana, Geneva, Tahoma, sans-serif; font-size: large; text-align: left;">Porur Lake is located on the fringes of Porur in south-west Chennai and is a primary water resource for people residing in Chennai. It is a temporary catchment area connected with Chembarambakkam Lake. It is spread over 200 acres with a capacity of 46 million cubic feet (mcft).

                There are four filters working 24x7 to pump water to K. K. Nagar double tank distribution point.[citation needed] Bathing, washing and/or swimming is currently prohibited in this lake from 1995.[citation needed] A better view of the lake can be appreciated from the Chennai bypass.[citation needed]
                
                In 2012, the Water Resources Department initiated a project to increase the capacity the tank along with two other lakes in the city at a cost of ₹ 130 crore. This would deepen the lake by at least 1 m and increases the capacity to 70 mcft.[1][2]</p>
        </center>
        
    </body>
</html>
```
### com.html :
```
<!DOCTYPE html>
<html>
    <head>
        <title>COMMERZONE</title>
    </head>
    <body bgcolor="pink">
        <center>
            <h1 style="font-family: Tahoma; color: rgb(0, 0, 0);">COMMERZONE!</h1>
            <hr color="black" size="10">
        <img align="left" src="com.jpg" width="500" height="300">
        <img align="center" src="com1.jpg" width="450" height="300">
        <img align="right" src="com2.jpg" width="500" height="300">
            <hr color="black" size="10">
            <p style="font-family: Verdana, Geneva, Tahoma, sans-serif; font-size: large; text-align: left;">Chennai is a bustling metropolis and has become one of the most important technological zones in the country. In the middle of this booming city is Commerzone Chennai, one of the top IT parks in Chennai developed by K Raheja. The Commerzone Chennai is one of the largest IT parks in Chennai and includes a number of amenities, living spaces and recreational areas in addition to prime office spaces. It located in Porur, one of the best connected localities in Chennai. Because of its location advantage, Commerzone Chennai is located close to the best colleges, schools and healthcare centres in the city.

                Commerzone Chennai is among the most renowned IT parks in Chennai because of its superior connectivity to many important facilities. Families working here can find quality residential spaces at a cost lower than other metro cities. There are also a number of prestigious schools and colleges, so your children are sure to receive a world-class education. Porur is located in close proximity to the Chennai airport, making it easily accessible by road and air. If you are interested in Commerzone Chennai, contact K Raheja to learn more about one of the best IT parks the city of Chennai has to offer.</p>
        </center>
        
    </body>
</html>
```

### jun.html :
```
<!DOCTYPE html>
<html>
    <head>
        <title>PORUR JUNCTION</title>
    </head>
    <body bgcolor="gray">
        <center>
            <h1 style="font-family: Tahoma;">PORUR JUNCTION!</h1>
            <hr color="black" size="10">
        <img align="left" src="junction1.jpg" width="500" height="300">
        <img align="center" src="junction.jpg" width="450" height="300">
        <img align="right" src="junction2.jpg" width="500" height="300">
            <hr color="black" size="10">
            <p style="font-family: Verdana, Geneva, Tahoma, sans-serif; font-size: large; text-align: left;">Porur Junction: Porur Junction, located in the western part of Chennai, is a prominent and vibrant locality that has witnessed significant development in recent years. Its strategic location, excellent connectivity, and numerous amenities make it a favored choice for residents and visitors alike. This article will provide an in-depth overview of Porur Junction, highlighting its educational institutions, emergency contacts, key features in a table, intriguing listacles, and a comprehensive FAQ section.Porur Junction is well-connected via road networks, and the Porur Bus Terminus offers regular bus services to various parts of Chennai. Additionally, taxis and auto-rickshaws are readily available.</p>
        </center>
        
    </body>
</html>
```

## OUTPUT
### Map :
![img](out%20(1).png)
### Commerzone :
![img](out%20(2).png)
### Porur junction :
![img](out%20(3).png)
### Porur lake :
![img](out%20(4).png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
