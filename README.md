# Ex.06 Book Front Cover Page Design
## Date:02-12-2024

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
tvk.html

<!DOCTYPE html>
<html lang="en">
<head>
    <title>WEB DESING FRAMEWORKS</title>
    <style>
        body {
            margin:120px;
            font-family:Arial, sans-serif;
            background-image: url('web back ground.jpg');
            background-size: 70%;
            background-position:center;
            background-repeat:no-repeat; 
            color:greenyellow;
            position:sticky;
    
        }

        .container {
            padding: 120px;
            text-align:center;
        }

        .expert-insight {
            
            font-size: 20px;
            font-weight: bold;
            margin-top:inherit;
            margin-bottom: 40px;
            margin-left:initial;
            color:deeppink;
        }

        .main-title {
            font-size: 40px;
            font-weight: bold;
            line-height: 1.2;
            text-transform: uppercase;
            color: rgb(103, 112, 23);
        }

        .subtitle {
            font-size: 18px;
            margin-top: 30px;
            font-weight:bold;
            color:darkgoldenrod;
        }

        .edition {
            margin-top: 50px;
            font-size: 40px;
            font-weight: bold;
            color:crimson;
        }

        .author-info {
            bottom: 40px;
            left: 100px;
            font-size: 100px;
            font-weight: bold;
            color:darkorchid;
        }
        .photo {
            position:absolute;
            align-items:normal;
            bottom: 30px;
            right: 140px;          
        }

        .photo img {
            width: 120px; 
            height: auto;
            border-radius: 10px;
            align-content:last baseline;
            box-shadow: 0 4px 8px rgba(198, 6, 6, 0.3);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="expert-insight">EXPERTS INSIGHT</div>
        <div class="main-title"><br>WEB DESING FRAMEWORKS</div>
        <div class="subtitle">Future of Web Development</div>
        <div class="edition"><br>Second Edition<br></div>
    <div class="author-info"></div>
      <div><br> SANTHA BABU .G<br></div>
       <div><br>SEC<br></div>
    
    <div class="photo"><img src="babu.png" alt="Author's Photo"> </div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](web.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
