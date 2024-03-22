# Ex04 Places Around Me
## Date: 22/03/2024

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
        <title>sample</title>
    </head>
    <h1 align="center">NAMAKKAL</h1>
    <h2 align="center">Nirosha M (212223110032)</h2>
    <body bgcolor="cyan">
        <img src="namakkal.png" height="1300" width="3100" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="hotel sanu international" title="hotel sanu international" href="hotel.html" coords="1004,455,872,423" shape="rect">
            <area target="" alt="samy hotel" title="samy hotel" href="hotel.html" coords="" shape="poly">
            <area target="" alt="hotel sree saravana bhavana " title="hotel sree saravana bhavana " href="hotel.html" coords="1173,744,NaN" shape="circle">
            <area target="" alt="anna nagar" title="anna nagar" href="nagar.html" coords="684,536,835,501" shape="rect">
            <area target="" alt="namakkal sree aanjaneyar temple" title="namakkal sree aanjaneyar temple" href="temple" coords="NaN" shape="circle">
        </map>
    </map>
    </body>
</html>

```

## OUTPUT
![alt text](<img map.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
