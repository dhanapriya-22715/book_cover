# Ex.06 Book Front Cover Page Design
# Date: 18-11-2024

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
book.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Design</title>
    <link rel="stylesheet" href="bc styles.css">
</head>
<body>
    <div class="cover">
        <div class="background"></div>
        <div class="content">
            <h1 class="title">The Butterfly's Garend</h1>
            <h2 class="subtitle">Discover the Unknown</h2>
            <img src="C:\Users\admin\au 1.jpg" alt="Author Photo" class="author-photo">
            <p class="author-name">By John Doe</p>
        </div>
    </div>
</body>
</html>
 bc styles.css
body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    font-family: Arial, sans-serif;
}

/* Centering the book cover */
body {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f0f0f0;
}

/* Book cover container */
.cover {
    position: relative;
    width: 500px;
    height: 800px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    overflow: hidden;
    border-radius: 10px;
}

/* Background image for the cover */
.background {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('bc\ i\ 5.jpg');
    background-size: cover;
    background-position: center;
    filter: brightness(100%);
}

/* Content on top of the background */
.content {
    position: relative;
    color: rgb(11, 9, 9);
    text-align: center;
    font-family: Georgia;
    padding: 20px;
    z-index: 1;
}

/* Title styling */
.title {
    font-size: 36px;
    margin: 50px 0 10px;
    text-transform: uppercase;
    letter-spacing: 2px;
}

/* Subtitle styling */
.subtitle {
    font-size: 18px;
    margin: 10px 0 30px;
    font-style: italic;
}

/* Author photo styling */
.author-photo {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    margin: 70px 0;
    border: 3px solid white;
}

/* Author name styling */
.author-name {
    font-size: 29px;
    font-weight: bold;
}


```
# OUTPUT:
![Screenshot (57)](https://github.com/user-attachments/assets/8a1ed57a-f713-429e-a7f9-47576f1fa12d)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
