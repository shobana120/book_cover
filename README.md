# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CODING BOOK</title>
    <style>
        .img{
            width: 400px;
            height: 600px;
            margin-left: auto;
            padding: 20px;
            background-image: url(download\ \(2\).jpg);
            margin-right: auto;
            background-size: cover;
        }
        
        .au{
            display: inline;
            position: relative;
            color: white;
            top: 50%;
            font-size: medium;
            text-align: right;
            font-family: Georgia, 'Times New Roman', Times, serif;

        }
        .title{
            color: azure;
            font-family: Roquen;
            font-size: 39px;
            text-align: left;
            position: relative;
            
        }
        .id{
            width: 400px;
            position: relative;
            top: 50%;
        }
        .ed {
            color: azure;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 45%;

        }
        .sub{
            color: azure;
            font-size: 28px;
            position: relative;
            top: 7%;
        }
        .sec h1{
            color: aliceblue;
        }
    </style>
</head>
<body>
    <div class="img">
        <div class="sec">
            <h1>SEC</h1>
        </div>
        <div class="title">
            INTRODUCTION TO COMPUTER SCIENCE
        </div>
        <div class="sub">
            Book for Beginners
        </div>
        <div class="id">
            <hr>
        </div>
        <div class="au">
            <p><b>SAFIRA BARVEEN</b></p>
        </div>
        
        <div class="ed">
                Special Edition
        </div>
        </div>
</body>
</html>
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/001486eb-a975-40fa-8217-e3ff2d99ce7b)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
