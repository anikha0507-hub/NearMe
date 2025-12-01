# Ex03 Places Around Me
## Date: 01-12-2025

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

mappapp.html
```
<html>
    <head>
        <title>city</title>
    </head>
    <body>
        <h1>Trivandrum</h1>
        <h2>Anikha Pillai(25009524) </h2>
        <img src="Screenshot 2025-11-28 112640.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Sree Padmanabhaswamy Temple" title="Sree Padmanabhaswamy Temple" href="temple.html" coords="303,486,93,567" shape="rect">
    <area target="" alt="Fabindia Lulu Mall" title="Fabindia Lulu Mall" href="mall.html" coords="1003,487,89" shape="circle">
    <area target="" alt="RDR Conventional Centre" title="RDR Conventional Centre" href="centre.html" coords="833,318,615,245" shape="rect">
    <area target="" alt="Peyad" title="Peyad" href="place.html" coords="1239,88,1322,173,1405,85,1240,89" shape="poly">
    <area target="" alt="Thiruvanthapuram Zoo" title="Thiruvanthapuram Zoo" href="zoo.html" coords="361,110,207,127,285,222,381,244,469,236,518,148,452,116,361,110" shape="poly">
</map>
    </body>

</html>
```

centre.html
```
<html>
    <head>
        <title>tvm</title>
    </head>
    <body bgcolor='pink'>
        <h1>TRIVANDRUM</h1>
        <h2>RDR CONEVENTIONAL CENTRE</h2>
        <h3>RDR Convention Centre in Thiruvananthapuram is a large, air-conditioned venue with a capacity for up to 1,400 seated guests and 2,100 floating guests. It features a main hall, a mini hall, and two dining halls, making it suitable for a variety of events like weddings and corporate functions</h3>
    </body>
</html>
```

place.html
```
<html>
    <head>
        <title>tvm</title>
    </head>
    <body bgcolor="violet">
        <h1>TRIVANDRUM</h1>
        <h2>PEYAD-RESIDENTIAL AREA OF TVM</h2>
        <h3>Peyad is a residential suburb in the Trivandrum district of Kerala, known for being a commercial junction on the Trivandrum-Kattakkada route and for its location on the banks of the Karamana river. It offers a serene living environment with good transportation, healthcare, and schools, and is experiencing growth in its real estate market. </h3>
    </body>
</html>
```

zoo.html
```
<html>
    <head>
        <title>TVM</title>
    </head>
    <body bgcolor='lightblue'>
        <h1>TRIVANDRUM</h1>
        <h2>TRIVANDRUM ZOO</h2>
        <h3>The Thiruvananthapuram Zoo is one of India's oldest zoos, established in 1857 in Kerala's capital city, Thiruvananthapuram. It is a 55-acre park featuring a diverse range of animals, including big cats, deer, primates, and a notable reptile collection with both venomous and non-venomous snakes, as well as anacondas</h3>
    </body>
</html>
```

temple.html
```
<html>
    <head>
        <title>tvm</title>
    </head>
    <body bgcolor="yellow">
        <h1>TRIVANDRUM</h1>
        <h2>SREE PADMANABHASWAMY TEMPLE</h2>
        <h3>The Sree Padmanabhaswamy Temple in Thiruvananthapuram, Kerala, is an ancient and wealthy Hindu temple dedicated to Lord Vishnu. It is renowned for its stunning architecture, which blends Kerala and Tamil styles, and its immense treasure, estimated to be worth billions of dollars. The temple follows a strict dress code and requires visitors to adhere to specific rules regarding entry. </h3>
    </body>
</html>
```

mall.html
```
<html>
    <head>
        <title>TVM</title>
    </head>
    <body bgcolor="lightbrown"
        <h1>TRIVANDRUM</h1>
        <h2>FABINDIA LULU MALL</h2>
        <h3>There is no single "Fabindia mall" in Trivandrum, but rather multiple standalone Fabindia stores and a new fabNU outlet in various locations throughout the city. These stores offer a wide range of handcrafted ethnic wear, home decor, furniture, and accessories, with services like in-store shopping, same-day delivery, and kids' sections available at some locations. </h3>
    </body>
</html>
```

## OUTPUT
![alt text](image.png)
![alt text](<Screenshot 2025-12-01 201849.png>)
![alt text](<Screenshot 2025-12-01 201949.png>)
![alt text](<Screenshot 2025-12-01 201818.png>)
![alt text](<Screenshot 2025-12-01 201712.png>)
![alt text](<Screenshot 2025-12-01 201917.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
