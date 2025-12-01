# Ex03 Places Around Me
## Date: 1-12-2025

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
map:
<html>
    <head>
        <title>Sample</title>
    </head>
    <body bgcolor="dodgerblue"> 
        <h1 align="center">Tiruvannamalai </h1>
        <br>
        <h3 align="center">Paramehswaran J</h3>
        <h3 align="center">(25005306)</h3>
        <hr>
        <img src="Screenshot 2025-11-26 113521.png" usemap="#image-map" align="center">
        <map name="image-map">
    <area target="" alt="Register office" title="Register office" href="register.html" coords="25,292,265,378" shape="rect">
    <area target="" alt="Government Hospital vembakkam" title="Government Hospital vembakkam" href="hospital.html" coords="372,282,98" shape="circle">
    <area target="" alt="Indian Atm" title="Indian Atm" href="atm.html" coords="831,693,859,740,991,733,978,685,880,679,851,673,850,673,851,673" shape="poly">
    <area target="" alt="Sri lakshmi mahal" title="Sri lakshmi mahal" href="mahal.html" coords="1247,533,1295,558,1338,517,1315,469,1256,485" shape="poly">
    <area target="" alt="Vembakkam Taluk office" title="Vembakkam Taluk office" href="talukoffice.html" coords="1107,442,1130,495,1272,462,1292,392,1178,398,1130,404,1108,443" shape="poly">
</map>
    </body>
</html>

register office:
<html>
    <head>
        <title>Register office</title>
    </head>
    <body bgcolor="medium sea green">
    <h1 align="center">Register Office</h1>
    <br>
    <h2 align="center">Parameshwaran (25005306) </h2>
    <hr>
    <h3>A register officce is the official address of a company, used for all official communication and legal notices from government bodies.</h3>
    <br>
    <h3>  Its primary uses are to legally establish the company's presence and jurisdiction,serve as the official point of contact for legal and government correspondence and ensure compliance with the law. </h3>

    </body>
</html>

mahal:
<html>
    <head>
        <title>mahal</title>
    </head>
    <body bgcolor="violet">
        <h1 align="center">Marriage Hall</h1>
        <h2 align="center">Parameshwaran (25005306)</h2>
        <hr>
        <h3>A marriage hall, or banquet hall, is a dedicated venue for hosting large social and business events like weddings, parties, and receptions. They provide a controlled environment with amenities such as catering, decor, and seating, and often offer additional services like parking and entertainment, making them a convenient one-stop option for hosts and guests. </h3>
    </body>
</html>

taluk office:
<html>
    <head>
        <title>taluk office</title>
    </head>
    <body bgcolor="light gray">
        <h1 align="center">Taluk Office</h1>
        <h2 align="center">Parameshwaran (25005306)</h2>
        <hr>
        
        <h3>The Taluk office is a key administrative body in India, functioning as the local government office at the sub-district level, often also referred to as a Tehsil office. It is headed by an official known as the Tahsildar (or Talukdar/Mamledar in some states), who functions as the executive magistrate for that area. </h3>
    </body>
</html>

hospital:
<html>
    <head>
        <title>
            Hospital
        </title>
    </head>
    <body bgcolor="slateblue">
     <h1 align="center">Government Hospital</h1>
     <br>
     <h2 align="center">Parameshwaran (25005306)</h2>
     <hr>
     
     <h3>Government hospital provides a range of essential healthcare services, most notably free or subsidized medical care to make treatment accessible to wide population,especially low-income individuals.</h3>
    </body>
</html>
ATM:
<html>
    <head>
        <title>ATM</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">Indian ATM</h1>
        <br>
        <h2 align="center">Parameshwaran (25005306)</h2>
        <hr>
        <h3>An ATM, or Automated Teller Machine, is an electronic banking device that allows customers to perform financial transactions like cash withdrawals, deposits, and balance inquiries without a human teller. These machines are accessible 24/7 in public places, making banking more convenient and offering self-service options like fund transfers and bill payments through the use of a debit card and PIN. </h3>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (30).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
