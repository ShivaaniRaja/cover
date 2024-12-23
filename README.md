# Ex.06 Book Front Cover Page Design
## Date: 06:12:2024

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
<!DOCTYPE html>
<html>

<head>
    <title>FOUNDATION TO WEB</title>
    <style>
        .bookpage{

            width: 400px;
            height: 700px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url("BOOK.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(5, 16, 16);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(5, 13, 28);
            top:350px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(14, 3, 9);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:350px;
            
        }
        .pub{
            color:rgb(8, 19, 19);
            font-size: medium;
            position: relative;
            top:320px;
            left:330px;
        }
        .ed{
            color:rgb(28, 20, 141);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:250px;
        
        }
        .subtitle{
            color:rgb(10, 11, 11);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 300px;
            left: 290px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                FWAD
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>DEVELOPMENT OF WEB</h1></div>
            <div class="subtitle">
                 BASIC OF WEB
            </div>
            <div class="subtitle">
                 top dealers of 2024
            </div>

            <div class="mypic">
                <img src="Shivaani_photo (1).jpeg" width="100" height="120" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>SHIVAANI R</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>EXCLUSIVE EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-06 083901.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
