# Ex04 Places Around Me
## Date: 22-03-24

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
# Map.html
```
<html>
    <head>
        <title>MAP APP</title>
    </head>
<body>
        <h1 align="center" bgcolor="Violet">NELLORE</h1>
        <h2 align="center" bgcolor="Violet">Kayyuru Tharani(212221040080)</h2>


<center>
<img src="map.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="Hotel Southern suites Nellore" title="Hotel Southern suites Nellore" href="hotel.html" coords="832,385,988,437" shape="rect">
    <area target="" alt="Medicover Hospitals" title="Medicover Hospitals" href="hospital.html" coords="1139,203,1247,225,1291,259,1222,312,1073,310,1103,244" shape="poly">
    <area target="" alt="Santhapet" title="Santhapet" href="village.html" coords="620,693,59" shape="circle">
    <area target="" alt="Rainbow School" title="Rainbow School" href="school.html" coords="1248,759,1059,820" shape="rect">
    <area target="" alt="Priyadarshini College of Engineering" title="Priyadarshini College of Engineering" href="college.html" coords="1053,633,108" shape="circle">
    </center>
</map>
</body>
</html>

```
# School.html

```
<!DOCTYPE html>
<html>
<head>
<title>Rainbow School
</title>
</head>
<body bgcolor="blue">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Rainbow School</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Rainbow has well-trained teachers with high class Infrastructure<br>
2)The school is completely under their purview and follow the tried and tested methodology of the teaching – learning process.<br>
</p>
</body>
</html>
```
#College.html

```
<!DOCTYPE html>
<html>
<head>
<title>Priyadarshini College of Engineering</title>
</head>
<body bgcolor="yellow">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Priyadarshini College of Engineering</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Priyadarshini College of Engineering has been awarded with an A+ grade status with CGPA 3.45 by NAAC for a term of 5 years upto 2027.<br>
2)PCE is a private autonomous engineering college affiliated to RTMNU, Nagpur.<br>
</p>
</body>
</html>

```
# Hospital.html
```
<!DOCTYPE html>
<html>
<head>
<title>Medicover Hospitals</title>
</head>
<body bgcolor="cyan">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Medicover Hospitals </b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Medicover hospitals has the most advanced medical technology<br>
2)24 hours Emergency Services and Critical Care facilities are available<br>
3)Advanced world-class Intensive Care Unit and Operation Theaters.<br>
</p>
</body>
</html>
```
# Hotel.html

```
<!DOCTYPE html>
<html>
<head>
<title>Hotel Southern suites</title>
</head>
<body bgcolor="pink">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Hotel Southern suites</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Hotel Southern suites is one of the famous hotel in nellore<br>
2) It has a pre-booking offer to book the rooms in prior <br>
</p>
</body>
</html>
```
# village.html
```
<!DOCTYPE html>
<html>
<head>
<title>Santhapet </title>
</head>
<body bgcolor="lavender">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>Santhapet</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Santhapet is a Locality in Spsr Nellore City in Andhra Pradesh State, India. It belongs to Andhra region .
 Santhapet Pin code is 524001 and postal head office is Nellore .<br>
 
 2)Ranganaykulapet , Phoga Thota , Ramamurthy Nagar , Lakshmipuram , Weavers Colony are the nearby Localities to Santhapet.<br>
 
 3)Nellore , Gudur , Kavali , Venkatagiri are the nearby Cities to Spsr Nellore.<br>
</p>
</body>
</html>
````



## OUTPUT

![alt text](<Screenshot (267)-1.png>)

![alt text](<Screenshot (266).png>)

![alt text](<Screenshot (265).png>)

![alt text](<Screenshot (264).png>)

![alt text](<Screenshot (268).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
