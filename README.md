# Ex04 Places Around Me
## Date: 

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
<html>
<head>
<title>My HomeTown</title>
<style>
  img {
    display: block;
    margin: 0 auto; /* Centers the image */
    position: relative;
    left: -20px; /* Adjust this value to move the map slightly left */
  }
</style>
</head>
<body>
<h1 align="center">
<font color="red"><b>THIRUVANNAMALAI</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>BALAMURUGAN (24005335)</b></font>
</h2>
<img src="MAP.jpg" usemap="#image-map" alt="Map of Tiruvannamalai">
<map name="image-map">
<area target="" alt="VENGIKKAL" title="VENGIKKAL" href="vengikkal.html" coords="410,360,36" shape="circle">
<area target="" alt="THIRUVANNAMALAI Annamalaiyar Temple" title="THIRUVANNAMALAI Annamalaiyar Temple" href="TEMPLE.html" coords="560,498,36" shape="circle">
<area target="" alt="Sri Hara Theertheswarar Temple" title="Sri Hara Theertheswarar Temple" href="shttemple.html" coords="770,90,36" shape="circle">
</map>
</body>
</html>
temple.html
<html>
<head>
<title>THIRUVANNAMALAI Annamalaiyar Temple</title>
</head>
<body bgcolor="LightSeaGreen">
<h1 align="center">
<font color="MediumVioletRed"><b>THIRUVANNAMALAI</b></font>    
</h1>
<h3 align="center">
<font color="MediumVioletRed"><b>THIRUVANNAMALAI Annamalaiyar Temple</b></font>    
</h3>
<hr size="3" color="Moccasin">
<p align="justify">
<front face="Georgia" size="S">
    The Annamalaiyar Temple, also known as the Arunachalesvara Temple, is a magnificent Hindu temple located at the base of the Arunachala Hill in Tiruvannamalai, Tamil Nadu. It is dedicated to Lord Shiva, worshipped as Arunachalesvara, and Goddess Parvati, worshipped as Unnamalai.
    This temple is one of the Pancha Bhoota Sthalas, representing the element of fire (Agni). It is renowned for its Dravidian architecture, featuring towering gopurams (gateway towers), intricate carvings, and a sprawling complex covering 10 hectares. The eastern tower, standing at 66 meters, is one of the tallest temple towers in India.
    The temple hosts several annual festivals, with Karthika Deepam being the most prominent. During this festival, a massive beacon is lit atop the Arunachala Hill, symbolizing the union of fire and sky, attracting millions of devotees.
    
</body>
</html>
vengikkal.html
<html>
<head>
<title>THIRUVANNAMALAI Annamalaiyar Temple</title>
</head>
<body bgcolor="LightSeaGreen">
<h1 align="center">
<font color="MediumVioletRed"><b>THIRUVANNAMALAI</b></font>    
</h1>
<h3 align="center">
<font color="MediumVioletRed"><b>THIRUVANNAMALAI Annamalaiyar Temple</b></font>    
</h3>
<hr size="3" color="Moccasin">
<p align="justify">
<front face="Georgia" size="S">
    The Annamalaiyar Temple, also known as the Arunachalesvara Temple, is a magnificent Hindu temple located at the base of the Arunachala Hill in Tiruvannamalai, Tamil Nadu. It is dedicated to Lord Shiva, worshipped as Arunachalesvara, and Goddess Parvati, worshipped as Unnamalai.
    This temple is one of the Pancha Bhoota Sthalas, representing the element of fire (Agni). It is renowned for its Dravidian architecture, featuring towering gopurams (gateway towers), intricate carvings, and a sprawling complex covering 10 hectares. The eastern tower, standing at 66 meters, is one of the tallest temple towers in India.
    The temple hosts several annual festivals, with Karthika Deepam being the most prominent. During this festival, a massive beacon is lit atop the Arunachala Hill, symbolizing the union of fire and sky, attracting millions of devotees.
    
</body>
</html>
```


## OUTPUT
![Screenshot 2025-04-28 211053](https://github.com/user-attachments/assets/54ce049d-84c9-4f1d-b2f0-569178cf219d)
![Screenshot 2025-04-28 211608](https://github.com/user-attachments/assets/48f3405e-d8ed-40fa-9d28-4a0a972b46a7)

![Screenshot 2025-04-28 211000](https://github.com/user-attachments/assets/d3250a3d-defc-40f0-a5e5-35f86f436ea6)








## RESULT
The program for implementing image maps using HTML is executed successfully.
