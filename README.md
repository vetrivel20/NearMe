# Ex03 Places Around Me
## Date: 28.11.2025

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

~~~
map.html

<html>
    <head>
        <title>My map</title>
    </head>
    <body bgcolor="black">
        <h1 style="text-align: center; color: white;">CHENNAI</h1>
        <h4 style="text-align: center; color: white;">M.VETRIVEL(25011461)</h4>

        <img src="Screenshot 2025-11-26 135029.png" usemap="#image-map"1>

<map name="image-map">
    <area target="" alt="Aakash Hospital" title="Aakash Hospital" href="hospital.html" coords="627,713,821,786" shape="rect">
    <area target="" alt="AYYA TEMPLE" title="AYYA TEMPLE" href="temple.html" coords="629,146,98" shape="circle">
    <area target="" alt="thiruvotriyur Metro" title="Thiruvotriyur Metro" href="metro.html" coords="942,331,1128,399" shape="rect">
    <area target="" alt="Royal Enfield Motor" title="Royal Enfield Motor" href="motor.html" coords="1364,73,1488,142,1489,223,1272,242,1258,147" shape="poly">
    <area target="" alt="Vannam Kulam" title="Vannam Kulam" href="kulam.html" coords="250,788,96" shape="circle">
</map>
    </body>
</html>

kulam.html

<html>
    <head>
        <title>Kulam</title>
    </head>
    <body bgcolor="pink">
        <h1 style="text-align: center;">Vannam Kulam</h1>
        <hr>
        <img src="Pichavaram-Mangrove-Forest.jpg" style="padding-left: 250;">
        <p style="font-size: 25;"><b>Vannankulam is a small Village/hamlet in Kamudi Block in Ramanathapuram District of Tamil Nadu State, India. It comes under K Veppankulam Panchayath. It is located 51 KM towards west from District head quarters Ramanathapuram. 533 KM from State capital Chennai

Vannankulam Pin code is 623115 and postal head office is Perunali .

Vannankulam is surrounded by Tiruchuli Block towards west , Narikudi Block towards North , Mudukulathur Block towards East , Kadaladi Block towards South .

Paramakudi , Aruppukkottai , Sattur , Ramanathapuram are the near by Cities to Vannankulam</b></p>
    </body>
</html>

motor.html

<html>
    <head>
        <title>Motor bike</title>
    </head>
    <body>
        <h1 style="text-align: center;">Royal Enfield Motor</h1>
        <hr>
        <img src="maxresdefault.jpg" height="500" style="padding-left: 275;">
        <h4 style="font-size: 20;">Royal Enfield is an Indian motorcycle manufacturer, headquartered and manufactured in Chennai.[1] Royal Enfield is the oldest motorcycle brand in continuous production.[2]

The first Royal Enfield motorcycle was built in 1901 by The Enfield Cycle Company of Redditch, Worcestershire, England, the company was responsible for the design and original production of the Royal Enfield Bullet, the longest-lived motorcycle design in history.[3] Licensed from the original English Royal Enfield by Madras Motors, the company is now a subsidiary of Eicher Motors, an Indian automaker.[4] The company makes classic-looking motorcycles, including the Royal Enfield Bullet, Classic 350, Royal Enfield Thunderbird, Meteor 350, Classic 500, Interceptor 650, Continental, and Hunter 350. Royal Enfield also makes adventure and off-road motorcycles like the Royal Enfield Himalayan. Their motorcycles are equipped with single-cylinder and twin-cylinder engines.[5]</h4>
    </body>
</html>

metro.html

<html>
    <head>
        <title>Metro</title>
    </head>
    <body bgcolor="silver">
        <h1 style="text-align: center;">Thiruvotriyur Metro</h1>
        <hr>
        <img src="Tiruvottriyur_metro_station.jpg" style="padding-left: 150;">
        <h2 style="text-align: center;">Chennai Metro Rail Limited</h2>
        <p style="font-size: 35;">The Government of Tamil Nadu created a Special Purpose Vehicle (SPV) for implementing the Chennai Metro Rail Project.

This SPV named as “Chennai Metro Rail Limited” was incorporated on 03.12.2007 under the Companies Act. It has now been converted into a Joint Venture of Government of India and Government of Tamil Nadu with equal equity holding.</p>
    </body>
</html>

temple.html

<html>
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="black">
        <h1 style="text-align: center; color: white;">AYYA TEMPLE</h1>
        <hr>
        <img src="ayya-vaikundar-nizhal.jpg" alt="error" style="padding-left: 350;" height="500">
        <br>
        <br>
        <p style="color: white; padding-left: 25;font-size: 25;">AYYA TEMPLE VAIGUNDA LOGAM is located at 58F3+CFG, Maanickam Nagar, Rettai Malai Srinivasan Nagar, Jeevan Lal Nagar, Tiruvottiyur, Chennai, Tamil Nadu 600019, India.
What is the contact number for AYYA TEMPLE VAIGUNDA LOGAM?
The contact number for AYYA TEMPLE VAIGUNDA LOGAM is +91 74011 19785
What is the nearest metro station from AYYA TEMPLE VAIGUNDA LOGAM?
AYYA TEMPLE VAIGUNDA LOGAM is nearly 0.14 kilometers away from Tiruvottiyur Metro Station. You can go to this metro station by using the Metro MRT Blue Line.
What is the nearest railway station from AYYA TEMPLE VAIGUNDA LOGAM?
Tiruvottiyur railway station is the nearest railway station to AYYA TEMPLE VAIGUNDA LOGAM. It is nearly 0.32 kilometers away from it.</p>
    </body>
</html>

hospital.html

<html>
    <head>
        <title>Aakash Hospital</title>
    </head>
    <body>
        <h1 style="text-align: center;">Aakash Hospital</h1>
        <hr>
        <img src="Screenshot 2025-11-26 140245.png" style="padding-left: 450;">
        <br>
        <br>
        <h1 style="text-align: center;">Welcome to Aakash Hospital,</h1>
        
        <p style="font-size: 20;">Aakash Hospital stands as a beacon of excellence in multi-specialty healthcare services and laparoscopic surgical care within the vibrant city of Chennai. As an institution dedicated to providing top-notch medical care, we are proud to hold the following prestigious certifications: ISO 9001:2015 (IAF) certification, NABH certification (QCI), KAYAKALP certification and Swatchh Bharat certification.

Our journey began humbly, with just five beds, but through unwavering dedication to service and commitment to quality, we have grown into a sprawling 75,000 sq. ft. facility. Today, Aakash Hospital is equipped with 150 beds, including an 18-bed ICU, and houses 33 specialized departments.

Nestled in the heart of North Chennai, in close proximity to the revered Aathipureeswarar temple, our hospital has become a pillar of healthcare excellence in the region. We attribute this success not only to our state-of-the-art infrastructure but also to our passionate team of experienced doctors, surgeons, nurses, and supporting staff.

At Aakash Hospital, we believe in delivering healthcare that is both affordable and accessible without compromising on the quality of diagnosis and treatment. This mission drives us to be available round the clock, ensuring that our patients receive the care they need when they need it.

We take great pride in our well-coordinated team, cutting-edge technology, and advanced medical diagnostic and treatment facilities. Combined with our relentless pursuit of excellence, has earned us the reputation of being one of the most renowned healthcare centers in the city.

Whether it’ is routine medical care or complex surgical procedures, at Aakash Hospital, patients can trust us to provide compassionate, comprehensive, and world-class healthcare services. We are committed to continually raising the bar and setting new standards of excellence in healthcare delivery.</p>
    </body>
</html>
~~~

## OUTPUT

![alt text](<Screenshot (16).png>)

![alt text](<Screenshot (17).png>)

![alt text](<Screenshot (18).png>)

![alt text](<Screenshot (19).png>)

![alt text](<Screenshot (20).png>)

![alt text](<Screenshot (21).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
