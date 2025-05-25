# Ex.06 Book Front Cover Page Design
# Date:04.12.24
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
'''

<!DOCTYPE html>
<html>
<head>
    <title>Music</title>
    <style>
        .bookpage{
            width: 600px;
            height: 800px;
            color:rgb(254, 25, 25);
            margin-left: auto;
            margin-right: auto;
            padding: 10px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: image("C:\Users\admin\Pictures\Screenshots\Screenshots\Screenshot 2024-10-08 181254.png");
            background-size: cover;
            background-color: rgb(181, 147, 254);
        }
            
        
        .insight{
            color:rgb(222, 9, 9);
        
        }
        
        
        .hrstyle{
            width:25px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:#6495ed;
            top:270px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(5, 81, 45);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        } 



        .Bookback{
            color:rgb(198, 16, 183);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:rgb(6, 229, 229);
            font-size: medium;
            position: relative;
            top:235px;
            left:330px;
        }
        .ed{
            color:rgb(93, 208, 208);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:190px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 150px;
            left: 300px;
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
                MONEY
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(15, 14, 13)">
            </div>
            <div class="booktitle">
                <h1>PYSICOLOGY OF MONEY</h1></div>
            <div class="subtitle">
                 *Timeless Lesson
                 
            </div>
            <div class="subtitle">
                 *Greed and happiness

            </div>
            <div class="subtitle">
                 *The importance of saving and frugality

            </div>
            <div class="subtitle">
                 *the role of luck and risk in outcomes
            <div class="Bookback">
                <h1>BOOK BY S.NITHISH KUMAR</h1></div>
            <div class="subtitle">
                    *web application(book cover)
            </div>
            <div class="mypic">
                <img src=IMG_5089.JPG width="200" height="200">
            </div>
            <div class="id">
                <hr style="color:rgb(10, 10, 10)">
            </div>
            <div class="author">
               <p><b>nithish kumar s/b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>LIMITED EDITION</b>
            </div>
        </div>
        </body>
</html>

'''
# OUTPUT:
![Screenshot 2024-12-04 220811](https://github.com/user-attachments/assets/6424e8e4-0b86-425e-b472-10a977b9cbc8)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
