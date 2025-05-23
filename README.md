# Ex.06 Book Front Cover Page Design
## Date:23.5.25

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
<html lang="en">
<head>
    <title>INTERNET INFRASTRUCTURE</title>
    <style>
        body {
            color: white; /* All text will be white */
            font-family: Helvetica, sans-serif;
            background-color: #f1f5f8;
            margin: 0;
            padding: 0;
        }

        .book {
            width: 726px;
            height: 820px;
            margin: auto;
            position: relative;
            background-image: url("bg.avif"); /* Background image */
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
        }

        h1 {
            font-size: 70px;
            margin: 60px;
            margin-bottom: 0px;
        }

        h3 {
            margin: 0px 0px 90px 60px;
            position: absolute;
            bottom: 80px; /* adjusted to not overlap footer */
            font-size: xx-large;
            font-weight: bold;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }

        h4 {
            font-size: 20px;
            margin: 60px;
            margin-top: 10px;
            width: 430px;
        }

        #top {
            border-bottom: 2px solid rgb(177, 178, 245);
            padding: 100px 0px 5px 30px;
            display: inline-block;
        }

        footer {
            position: absolute;
            bottom: 0;
            width: 603px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-top: 2px solid rgb(77, 79, 163);
            padding: 10px 60px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            background-color: rgba(0, 0, 0, 0.6); /* dark transparent footer */
        }

        #HASH {
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        #HASH span {
            margin: 5px 0px;
            font-size: xx-large;
            font-weight: bold;
        }

        .photo {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid white;
        }

        .photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <!-- Existing portfolio structure starts here -->
    <section class="book">
        <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
        <h1>INTERNET INFRASTRUCTURE</h1>
        <h4>Networking, Web Services, and Cloud Computing</h4>
        <h3>Second Edition</h3>  

        <footer>
            <div id="HASH" class="blue-msg">
                <span>DR.D.MEAGESWAR</span>
                <span id="end"><u>SEC</u></span>
            </div>
            <div class="photo">
                <img src="profile.img.jpg" alt="profile photo">
            </div>
        </footer>
    </section>

    <!-- Adding previous portfolio structure here (e.g., Home, Skills, Projects) -->
    <!-- Make sure the previous sections are integrated as per your design preferences -->
</body>
</html>
```

## OUTPUT:
![WhatsApp Image 2025-05-23 at 20 06 24_6e9fd603](https://github.com/user-attachments/assets/075acf14-ef7a-4431-8d4e-66a33a382d3c)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
