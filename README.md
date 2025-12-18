# Ex.05 Book Front Cover Page Design
## Date:17.12.2025

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #111;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .cover {
      width: 360px;
      height: 540px;
      background: linear-gradient(135deg, #ff9800, #ff5722, #3f51b5);
      border-radius: 18px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.6);
      color: #fff;
      padding: 30px;
      box-sizing: border-box;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      position: relative;
      overflow: hidden;
    }

    .cover::before {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at top right, rgba(255,255,255,0.25), transparent 60%);
    }

    .top {
      text-align: center;
      z-index: 1;
    }

    .title {
      font-size: 32px;
      font-weight: bold;
      letter-spacing: 2px;
      margin-bottom: 10px;
    }

    .subtitle {
      font-size: 14px;
      opacity: 0.9;
    }

    .center {
      z-index: 1;
      text-align: center;
    }

    .symbol {
      width: 140px;
      height: 140px;
      margin: 0 auto;
      border-radius: 50%;
      background: rgba(255,255,255,0.15);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 64px;
      font-weight: bold;
      box-shadow: inset 0 0 20px rgba(255,255,255,0.3);
    }

    .bottom {
      z-index: 1;
      text-align: center;
    }

    .author {
      font-size: 16px;
      font-weight: 600;
      margin-bottom: 6px;
    }

    .tagline {
      font-size: 12px;
      opacity: 0.85;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="top">
      <div class="title">ANIME NINJA</div>
      <div class="subtitle">A Journey of Courage & Destiny</div>
    </div>

    <div class="center">
      <div class="symbol">忍</div>
    </div>

    <div class="bottom">
      <div class="author">By Jaiakash J</div>
      <div class="author"> Reg no: 25005912</div>
      <div class="tagline">Unleash the power within</div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-12-18 081946.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
