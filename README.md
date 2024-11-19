# Ex.05 CREATE A BOOK COVER
## Date:19/11/24

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

## index.html:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lobster&family=Montserrat:wght@300;600&family=Roboto+Serif:wght@300&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 20;
      padding: 20;
      background-color: #cccec9;
      font-family: 'Comic Sans MS', sans-serif;
    }

    .book-cover {
      width: 500px;
      height: 700px;
      border-radius: 15px;
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
      margin: 50px auto;
      position: relative;
      overflow: hidden;
    }

    /* Main Image */
    .book-cover .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top: 0;
      left: 0;
      opacity: 100%;
    }
     

    /* Main Title */
    .book-cover .title1 {
      position: absolute;
      top: 100px;
      left: 35px;
      font-family: 'Lobster',cursive;
      font-size: 42px;
      font-weight: 600;
      color:  #ec6f03;
      letter-spacing: 2px;
      text-transform: uppercase;
    }
    /* Horizontal Line 1 */
    .book-cover .line1 {
      position: absolute;
      top: 143px;
      left: 35px;
      width: 427px;
    }
    

    /* Subtitle 1 */
    .book-cover .subtitle1 {
      position: absolute;
      top: 190px;
      left: 100px;
      font-size: 18px;
      font-family: 'allura', cursive;
      font-weight: 600;
      color: #2298f3;
    }

    /* Subtitle 2 */
    .book-cover .subtitle2 {
      position: absolute;
      top: 210px;
      left: 80px;
      font-size: 18px;
      font-family: 'allura', cursive;
      font-weight: 600;
      color: #2298f3;
    }

    /* Subtitle 3 */
    .book-cover .subtitle3 {
      position: absolute;
      top: 230px;
      left: 70px;
      font-size: 18px;
      font-family: 'allura', cursive;
      font-weight: 600;
      color:  #2298f3;
    }

    /* Horizontal Line 3 */
    .book-cover .line3 {
      position: absolute;
      bottom: 30px;
      left: 20px;
      width: 350px;
    }

    /* Author Image */
    .book-cover .mypic {
      position: absolute;
      top: 570px;
      left: 380px;
      width: 100px;
      height: 100px;
      border-radius: 30%;
      border: 3px solid  #7DF9FF;
    }

    .book-cover .mypic img {
      width: 100%;
      height: 100%;
      border-radius: 50%;
    }

    /* 2024 Text */
    .book-cover .end {
      position: absolute;
      bottom: 5px;
      left: 20px;
      font-size: 18px;
      color: #1F51FF;
      font-weight: 600;
    }

    /* Author Name */
    .book-cover .author {
      position: absolute;
      bottom: 5px;
      right: 16px;
      font-size: 14px;
      color: #6ee2f7;
      font-family: 'Montserrat', sans-serif;
      font-weight: 600;
    }

    hr {
      border: none;
      height: 3px;
      background-color:  #7DF9FF;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="img.jpeg" alt="Book Cover Image" class="image">
    <div class="insight">SCI-FI</div>
    <div class="line1"><hr></div>
    <div class="title1">INTRODUCTION TO CODING</div>
    <div class="line2"><hr></div>
    <div class="subtitle2">CODING IN ALL LANGUAGE</div>
    <div class="line3"><hr></div>
    <div class="end">2024    SCI-FIC</div>
    <div class="author">ASWINI M</div>
  </div>
</body>

</html>
```

## OUTPUT:
![alt text](<Screenshot (223).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
