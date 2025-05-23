# Ex.06 Book Front Cover Page Design
## Date: 23-05-2025

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Learn Web Development - Book Cover</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      height: 100vh;
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .cover {
      width: 350px;
      height: 500px;
      position: relative;
      background: url('BG.jpg') no-repeat center center/cover;
      color: white;
      border-radius: 15px;
      border: 1.5px solid #ffffff80; /* Thin semi-transparent white border */
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.6);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      padding: 30px 20px;
      text-align: center;
      overflow: hidden;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 15px;
      z-index: 0;
    }

    .content {
      position: relative;
      z-index: 1;
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 2rem;
      font-weight: bold;
      margin-top: 80px;
    }

    .subtitle {
      font-size: 1rem;
      margin-top: 10px;
      font-style: italic;
      color: #ccc;
    }

    .author {
      display: flex;
      align-items: center;
      gap: 10px;
      justify-content: center;
      margin-bottom: 10px;
    }

    .author img {
      width: 50px;
      height: 50px;
      object-fit: cover;
      border-radius: 50%;
      border: 2px solid white;
    }

    .author-name {
      font-size: 1rem;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="overlay"></div>
    <div class="content">
      <div>
        <div class="title">Learn Web Development</div>
        <div class="subtitle">A beginner's guide to building modern websites</div>
      </div>
      <div class="author">
        <img src="Profile1.png" alt="Author" />
        <div class="author-name">By Balasuriya M</div>
      </div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (132).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
