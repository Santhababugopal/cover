# Ex.06 Book Front Cover Page Design
## Date:03-12-2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
<head>
    
    <style>
        .container {
            position:absolute;
            margin-left: 30%;
            margin-right: 50%;
            width: 300px;
            height: 300px;
            
        }
        .background-image
        {   align-items: center;
            width: 210%;
            height: 260%;
        }

        .topic {
            position: absolute;
            top: 30px;
            left: 40px;
            color:azure;
            font-style:italic;
            font-size: 20px;

        }

        .main-title {
            position:absolute;
            text-align: center;
            top: 150px;
            left: 150px;
            color:chartreuse;
            font-style:italic;
            font-size: 36px;
        }

        .subtitle {
            position: absolute;
            font-style:oblique;
            font-size: 25px;
            top: 300px;
            left: 40px;
            font-weight:bolder;
            color:hotpink;
        }

        .edition {
            position: absolute;
            bottom: -450px;
            left: 40px;
            color:orangered;
            font-style:oblique;
            font-size: 20px
        }
        .photo {
            position: absolute;
            bottom: -400px;
            right: -250px;
            width: 120px;
            height: auto;
        }
        .college{
            position:absolute;
            bottom: -500px;
            right: -200px;
            font-style:oblique ;
            font-size: 20px;
            color:azure;
        }

        .Name {
            position: absolute;
            bottom: -480px;
            right: -260px;
            color:azure;
            font-style:italic;
            font-size: 25px;
            
        }
        
    </style>
</head>
<body>
    <div class="container">
        <img  class="photo" src="photo.jpg" >
        <img class="background-image" src="web back ground.jpg">
        <p class ="topic"> EXPERTS INSIGHT</p>
        <h1 class="main-title" >WEB DESING FRAMEWORKS</h1>
        <h2 class="subtitle"> FUTURE OF WEB DEVELOPMENT</h2>
        <p class="edition" >FOURTH EDITION</p>
        <p class="Name" >SANTHA BABU .G</p>
        <p class="college" >SEC</p>
    </div>
</body>
</html>


```
## OUTPUT:

![alt text](<Screenshot (66).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
