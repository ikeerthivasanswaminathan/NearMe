# Ex04 Places Around Me

## Date : 22/03/2024

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

map.html

```
<html>
    <head>
        <title> THIRUCHIRAPPALLI </title>
    </head>
    <body bgcolor="white">
        <h1> THIRUCHIRAPPALLI </h1>
        <h3>Name : KEERTHIVASAN S</h3>
        <h3>Reg No : 212223220046</h3>
<img src="map.png" usemap="#image-map"><map name="MyCity">
    <area alt="Tiruchirappalli Central Bus Stand" title="Tiruchirappalli Central Bus Stand" href="trichycentralbusstand.html" coords="552,419,408,352" shape="rect">
    <area alt="Nalam Hospital" title="Nalam Hospital" href="nalamhospital.html" coords="864,656,1019,586" shape="rect">
    <area alt="Sona Mina Theatres" title="Sona Mina Theatres" href="sonaminatheatres.html" coords="611,347,476,280" shape="rect">
    <area alt="Mariyam Cinemas" title="Mariyam Cinemas" href="mariyamcinenemas.html" coords="759,368,924,410" shape="rect">
    <area alt="D Mart - Trichy" title="D Mart - Trichy" href="trichydmart.html" coords="910,244,1007,290" shape="rect">
</map>
</body>
</html>
```

trichycentralbusstand.html

```
<html>
<head>
    <title> THIRUCHIRAPPALLI CENTRAL BUS STAND </title>
</head>
<body bgcolor="white">
    <h1> THIRUCHIRAPPALLI </h1>
    <h2> CENTRAL BUS STAND </h2>
    <hr>
    <div style="text-align: center;">
        <img src="trichycentralbusstand.png" width="1200" height="500">
    </div>
    <p>1) It is one of the main bus stand in Tiruchirappalli, TamilNadu, India.<br>
        2) All city/state busses are available here.<br>
        3) As the name says, it is located in centre of the city.<br>
    </p>
</body>
</html>
```

nalamhospital.html

```
<html>
<head>
    <title> THIRUCHIRAPPALLI NALAM HOSPITAL </title>
</head>
<body bgcolor="white">
    <h1> THIRUCHIRAPPALLI </h1>
    <h2> NALAM HOSPITAL </h2>
    <hr>
    <div style="text-align: center;">
        <img src="trichynalamhospital.png" width="1200" height="500">
    </div>
    <p>1) It is one of the best hospital located in Tiruchirappalli, TamilNadu, India.<br>
        2) Most of the top most surgeons are available here.<br>
        3) Hygenic and well sanitized disease free environment.<br>
    </p>
</body>
</html>
```

sonaminatheatres.html

```
<html>
<head>
    <title> THIRUCHIRAPPALLI SONA MINA THEATRES </title>
</head>
<body bgcolor="white">
    <h1> THIRUCHIRAPPALLI </h1>
    <h2> SONA MINA THEATRES </h2>
    <hr>
    <div style="text-align: center;">
        <img src="trichysonaminatheatres.png" width="1200" height="500">
    </div>
    <p>1) It is one of the best theatre constructed in prime location in Tiruchirappalli, TamilNadu, India.<br>
        2) Sound effects and Screening quality are good.<br>
        3) Hygenic and well sanitized disease free environment.<br>
    </p>
</body>
</html>
```

mariyamcinemas.html

```
<html>
<head>
    <title> THIRUCHIRAPPALLI MARIYAM CINEMAS </title>
</head>
<body bgcolor="white">
    <h1> THIRUCHIRAPPALLI </h1>
    <h2> MARIYAM CINEMAS </h2>
    <hr>
    <div style="text-align: center;">
        <img src="trichymariyamcinemas.png" width="1200" height="500">
    </div>
    <p>1) It is one of the best theatre for 4K Screening and 3D movies which is located in Tiruchirappalli, TamilNadu, India.<br>
        2) Dolby Atmos audios sound effects are newly constructed.<br>
        3) Has many Parking lots for both Bikes and Cars.<br>
    </p>
</body>
</html>
```

trichydmart.html

```
<html>
<head>
    <title> THIRUCHIRAPPALLI D MART </title>
</head>
<body bgcolor="white">
    <h1> THIRUCHIRAPPALLI </h1>
    <h2> D MART </h2>
    <hr>
    <div style="text-align: center;">
        <img src="trichydmart.png" width="1200" height="500">
    </div>
    <p>1) All the shpoing things are available in D Mart which is located in Tiruchirappalli, TamilNadu, India.<br>
        2) PArking Facilities are available for both Bikes and Cars.<br>
        3) Food counters are available for customers.<br>
    </p>
</body>
</html>
```

## OUTPUT

![output - map](https://github.com/ikeerthivasanswaminathan/NearMe/assets/148937372/6c106d6e-4af6-471a-a48e-b53d89918667)

![output - trichycentralbusstand](https://github.com/ikeerthivasanswaminathan/NearMe/assets/148937372/110070d8-12bb-4522-9ac7-fd8d753e1774)

![output - trichydmart](https://github.com/ikeerthivasanswaminathan/NearMe/assets/148937372/b9cfbbf1-ab4e-4e31-b704-fe8bf9d4f4c4)

![output - trichymariyamcinemas](https://github.com/ikeerthivasanswaminathan/NearMe/assets/148937372/38af506a-a879-4443-837b-4aec153a5f46)

![output - trichynalamhospital](https://github.com/ikeerthivasanswaminathan/NearMe/assets/148937372/b78e2fee-5944-4f7c-b330-009e5900684f)

![output - trichysonaminatheatres](https://github.com/ikeerthivasanswaminathan/NearMe/assets/148937372/6663be4b-7203-42a4-b21f-d47d648ad8db)

## RESULT
The program for implementing image maps using HTML is executed successfully.
