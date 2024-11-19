# Ex.07 interative photo gallery
## Date:12/11/24

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
    <title>Responsive Web Design Book Cover</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="cover-container">
        <div class="content">
            <p class="insight">EXPERT INSIGHT</p>
            <h1>Responsive Web Design with<br>HTML5 and CSS</h1>
            <p class="subtitle">Develop future-proof responsive websites<br>using the latest HTML5 and CSS techniques</p>
            <p class="edition">Third Edition</p>
            <p class="author">HARINI R - CSE(CS)</p>
            <p class="publisher">SEC</p>
        </div>
    </div>
</body>
</html>
```
## style.css:
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #1081f2;
    font-family: Arial, sans-serif;
  }
  
  .cover-container {
    width: 700px;
    height: 700px;
    padding: 20px;
    background-image: url('bg.jpeg'); /* Ensure the path is correct */
    background-size: cover;
    background-position: center;
    color: #0f0f0f;
    text-align: left;
    border-radius: 5px;
    position: relative;
    overflow: hidden;
  }
  

.insight {
  font-size: 35px;
  color: #ff6b35;
  font-weight: bold;
  margin-bottom: 10px;
}

h1 {
  font-size: 50px;
  font-weight: bold;
  line-height: 1.2;
  margin-bottom: 20px;
}

.subtitle {
  font-size: 20px;
  color:black;
  line-height: 1.5;
  margin-bottom: 30px;
}

.edition {
  font-size: 25px;
  color: #fe4704;
  font-weight: bold;
  margin-bottom: 40px;
}

author {
  font-size: 30px;
  font-weight: bold;
  color:#0d0c0c;
  margin-bottom: 5px;
}

.publisher {
    font-size: 30px;
    font-weight: bold;
    color: #fbf4f4;
    position: absolute;
    bottom: 20px;
    right: 20px; 

}

.cover-container::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120"><path d="M0,0 C300,100 900,0 1200,100 V120 H0 Z" fill="%23ffffff" opacity="0.2"/></svg>') no-repeat center center;
  background-size: cover;
  z-index: 1;
  opacity: 0.5;
}
```


## OUTPUT:


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
