# Ex04 Places Around Me
# Date:04/10/2025

# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>


<body>
    
    <img src= "map (2).png" usemap="#mapapp" height="50% width=100%">
    <map name="mapapp">
    <area title="VELLORE" href="vellore.html" coords="206,608,352,708" shape="rect">
    <area title="ARAKKONAM" href="arakkonam.html" coords="793,483,78" shape="circle">
    <area title="PALLIPATTU" href="pallipattu.html" coords="493,186,663,287" shape="rect">
    <area title="KANCHIPURAM" href="kanchi.html" coords="813,716,72" shape="circle">
    <area title="PONNAI" href="ponnai.html" coords="332,394,465,484" shape="rect">
</body>
</html>


vellore.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        background: #eef45a;
    }
    .photo{
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
</style>
<body>
    <h1 align="center">VELLORE</h1>
    <img src="vellore.jpg" alt="vellore image" width="50%" class="photo">

    <p align="center" style="width: 100%;line-height: 1cm;font-size: x-large;">
         Vellore is a historic and culturally rich city in Tamil Nadu, known for its remarkable blend of heritage, education, and modern development.
         Famous for the iconic Vellore Fort, the city carries the legacy of the Chola, Vijayanagara, and British eras through its architecture and history.
         It is also home to prestigious institutions like Christian Medical College (CMC) and VIT University, which have given Vellore national and global recognition. 
         Nestled amid gentle hills and a warm climate, the city reflects a balance of tradition and progress. With its spiritual centers, traditional crafts,
         and historical landmarks, Vellore continues to stand as a symbol of pride, culture, and growth in South India.
    </p>
</body>
</html>

kanchi.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        background: #76abec;
    }
    .photo{
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
</style>
<body>
    <h1 align="center">KANCHIPURAM</h1>
    <img src="kanchipuram.jpg" alt="kanchi image" width="50%" class="photo">

    <p align="center" style="width: 100%;line-height: 1cm;font-size: x-large;">
         Kanchipuram, often called the “City of Thousand Temples,” is one of the most ancient and sacred cities in Tamil Nadu.
         Renowned for its stunning Dravidian architecture, it is home to magnificent temples like Ekambareswarar, Kailasanathar,
         and Varadharaja Perumal, which reflect centuries of art, devotion, and dynastic heritage. The city is equally famous
         for its exquisite Kanchipuram silk sarees, handwoven with vibrant colors and rich zari work, making it a hub of traditional craftsmanship.
         As one of the seven Moksha-puris in India, Kanchipuram holds immense spiritual significance for devotees and travelers alike. Blending culture, 
         religion, and artistic legacy, the city stands as a timeless symbol of Tamil heritage and devotion.
    </p>
</body>
</html>

pallipattu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        background: #ee4b9a;
    }
    .photo{
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
</style>
<body>
    <h1 align="center">PALLIPATTU</h1>
    <img src="pallipattu 2.jpg" alt="pallipattu image" width="50%" class="photo">

    <p align="center" style="width: 100%;line-height: 1cm;font-size: x-large;">
          Pallipattu is a quiet and scenic town known for its rural charm, greenery, and close-knit communities. 
          Located near the Tamil Nadu–Andhra Pradesh border, it is surrounded by farms, small villages,
          and natural landscapes that reflect a peaceful way of life. Agriculture plays an important role in the region, 
          and the town preserves its traditional culture through local festivals, temples, and everyday practices. 
          Though modest in size, Pallipattu carries a sense of heritage and simplicity, making it a meaningful place 
          for the people who live in and around the area.  
    </p>
</body>
</html>

ponnai.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        background: #79e954;
    }
    .photo{
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
</style>
<body>
    <h1 align="center">PONNAI</h1>
    <img src="ponnai 2.gif" alt="ponnai image" width="50%" class="photo">

    <p align="center" style="width: 100%;line-height: 1cm;font-size: x-large;">
         Ponnai is a peaceful town known for its natural surroundings, rural charm, and cultural roots. 
         Located near the Andhra–Tamil Nadu border, it is surrounded by small villages, farmlands, 
         and gentle landscapes. The Ponnai River adds to the beauty of the region and supports agriculture 
         and daily life. The town reflects a blend of tradition and simplicity, with local temples, festivals, 
         and community life forming its identity. Though small in size, Ponnai holds a quiet significance for 
         the people in and around Vellore district, offering a calm and connected way of living.



        
    </p>
</body>
</html>

arakkonam.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        background: #f408dc;
    }
    .photo{
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
</style>
<body>
    <h1 align="center">ARAKKONAM</h1>
    <img src="arakkonam.jpg" alt="arakkonam image" width="50%" class="photo">

    <p align="center" style="width: 100%;line-height: 1cm;font-size: x-large;">
         Arakkonam is a significant railway town in Tamil Nadu, known for its strategic location 
         and well-connected transport network. One of the oldest railway junctions in South India, 
         it serves as an important link between major cities like Chennai, Bangalore, and Tirupati. 
         Beyond its transport identity, Arakkonam has a blend of residential areas, local markets, 
         and traditional neighborhoods that reflect the lifestyle of the region. The town is also 
         home to the INS Rajali naval air station, one of the largest airbases in Asia, adding to 
         its importance. With its growing infrastructure, cultural roots, and connectivity, 
         Arakkonam continues to play a key role in the region’s development. 
    </p>
</body>
</html>

```

# OUTPUT
![alt text](<Screenshot 2025-10-04 104331.png>)
![alt text](<Screenshot 2025-10-04 104456.png>)
![alt text](<Screenshot 2025-10-04 104536.png>)
![alt text](<Screenshot 2025-10-04 104602.png>)
![alt text](<Screenshot 2025-10-04 104701.png>)
![alt text](<Screenshot 2025-10-04 104840.png>)



# RESULT
The program for implementing image maps using HTML is executed successfully.
