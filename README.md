# Ex.06 Book Front Cover Page Design
# Date: 28.10.2024
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
    <title>Book Cover</title>
    <style>
        body, html{
        margin:0;
        padding: 0;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        background-color:rgb(45, 44, 44);  
        }
        .book-cover {
        width: 400px;
        height: 600px;
        background-color:azure;  
        color:rgb(67, 2, 67);
        text-align: center;
        padding: 40px 20px;
        border-radius: 1px;
        box-shadow: 0 10px 20px rgba(0,0,0,3);
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;


        }
        .book-title{
            font-size: 56px;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif ;
            margin-bottom: 10px;
           
        }
        .book-subtitle{
        font-size: 20px;
        font-style: italic;
        
        }
        .author-name{
            font-size: 18px;
            margin-top: 10px;
        }
        .cover-image img {
        max-width: 70%;
        height: auto;
        border-radius: 8px;
        }
       




    </style>
</head>
<body>
    <div class="book-cover">
    <h1 class="book-subtitle">8 Ways for Self-Acceptance</h>
    <h2 class="book-title">The REBIRTH of YOU</h2>
    
    <div class="cover-image">
        <img src="book-cover-image1.png" alt="book cover image">
    </div>
    <div class="author-name">MEAGAN AUSTIN</div>
    </div>
</body>
</html>

```
# OUTPUT:

![alt text](<vijay/Screenshot (44).png>)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
