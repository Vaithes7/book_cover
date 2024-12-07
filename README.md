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
1.BOOKCOVER.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A4 Responsive Web Design Poster</title>
    <link rel="stylesheet" href="book.css">
</head>
<body>
    <div class="poster">
        <div class="circle"></div>
        <div class="first">
            <div class="header">EXPERT INSIGHT</div>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <p class="subtitle">Develop future-proof responsive websites using the latest HTML5 and CSS techniques</p>
        </div>
        
        <div class="last">
            <img src="c:\Users\admin\Downloads\Author.jpg" alt="Author Image" class="author-img " width="500" height="">
            <div class="edition">Third Edition</div>
            <div class="author-section">
                <p class="author">Ben Frain</p>
            </div>
            <div class="branding">Packt</div>
            
        </div>
        <div class="wave"></div>
            <div class="decorations">
                <div class="triangle"></div>
                <div class="square"></div>
            </div>
    </div>
</body>
</html>
```

2.BOOK.CSS
```
body {
 margin: 0;
 font-family: Arial, sans-serif;
 background: linear-gradient(135deg, #1a1a1a, #333);
 color: white;
 display: flex;
 justify-content: center;
 align-items: center;
 height: 100vh;
 overflow: hidden;
}

.poster {
 background-color: #2b2b2b;
 padding: 200px;
 width: 100%;
 max-width: 280px;
 border-radius: 15px;
 text-align: center;
 position: relative;
 overflow: hidden;
 box-shadow: 0 4px 20px rgba(0, 0, 0, 0.4);
 display: flex;
 justify-content: center;
 flex-direction: column;
 align-items: center;
}

.header {
 font-size: 14px;
 color: #ffa500;
 letter-spacing: 1px;
 margin-bottom: 20px;
 z-index: 2;
 position: relative;
}

h1 {
 font-size: 28px;
 font-weight: bold;
 margin: 10px 0;
 line-height: 1.3;
 z-index: 2;
 position: relative;
}

.subtitle {
 font-size: 16px;
 color: #cccccc;
 margin: 10px 0 20px;
 z-index: 2;
 position: relative;
}

.edition {
 font-size: 18px;
 color: #ff6600;
 font-weight: bold;
 margin-bottom: 20px;
 z-index: 2;
 position: relative;
}

.author-section {
 display: flex;
 align-items: center;
 justify-content: center;
 margin-top: 20px;
 z-index: 2;
 position: relative;
}

.author-img {
 width: 95px;
 height: 95px;
 border-radius: 50%;
 margin-right: 10px;
 border: 2px solid #ff6600;
 position: relative;
 top: -100px;
}


.author {
 font-size: 18px;
 font-weight: bold;
 color: #ffffff;
}

.branding {
 font-size: 24px;
 color: #ffffff;
 font-weight: bold;
 margin-top: 30px;
 z-index: 2;
 position: relative;
}

.wave {
 position: absolute;
 bottom: 0;
 left: 0;
 width: 100%;
 height: 100px;
 background: linear-gradient(90deg, #00ffcc, #0099ff, #ff66cc);
 opacity: 0.8;
 clip-path: polygon(0 50%, 25% 70%, 50% 50%, 75% 70%, 100% 50%, 100% 100%, 0% 100%);
 z-index: 1;
}

.circle {
 position: absolute;
 top: -50px;
 left: -50px;
 width: 120px;
 height: 120px;
 background: linear-gradient(45deg, #ff6600, #ffcc00);
 border-radius: 50%;
 z-index: 0;
}

.triangle {
 position: absolute;
 top: 20px;
 right: -30px;
 width: 0;
 height: 0;
 border-left: 50px solid transparent;
 border-right: 50px solid transparent;
 border-bottom: 70px solid #00ffcc;
 transform: rotate(20deg);
 z-index: 1;
}

.square {
 position: absolute;
 bottom: 30px;
 left: 30px;
 width: 50px;
 height: 50px;
 background: linear-gradient(135deg, #ff33cc, #6600ff);
 transform: rotate(15deg);
 z-index: 1;
}


.first {
 position: relative;
 top: -100px;
 width: 500px;
}

.last {
 position: relative;
 bottom: -100px;
}
```

# OUTPUT:

![Screenshot (47)](https://github.com/user-attachments/assets/cfb3bb5d-e83d-4d30-9791-2180572ca96a)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
