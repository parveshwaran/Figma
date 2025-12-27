# Ex08 Event Registration Web Application
## Date:26/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <div class="rectangle"></div>
      <div class="div"></div>
      <img class="image" src="img/image-1.png" />
      <div class="text-wrapper">TABLE TENNIS</div>
      <img class="images" src="img/images-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper-2">DETAILS</div>
      <div class="text-wrapper-3">LOGIN</div>
      <img class="img" src="img/rectangle-1.svg" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro {
  background-color: #00fff2;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 883px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 695px;
  left: 110px;
  width: 166px;
  height: 73px;
  background-color: #0c8976;
}

.iphone-pro .div {
  position: absolute;
  top: 570px;
  left: 113px;
  width: 163px;
  height: 83px;
  background-color: #0b8876;
}

.iphone-pro .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 61px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 154px;
  left: 89px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .images {
  position: absolute;
  top: 307px;
  left: 59px;
  width: 283px;
  height: 135px;
  aspect-ratio: 2.1;
  object-fit: cover;
}

.iphone-pro .text-on-a-path {
  position: absolute;
  top: 677px;
  left: 76px;
  width: 266px;
  height: 59px;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 700px;
  left: 142px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 594px;
  left: 154px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
g
.iphone-pro .img {
  position: absolute;
  top: 791px;
  left: 540px;
  width: 100px;
  height: 100px;
}
```

## OUTPUT:
![alt text](<Screenshot (53).png>)
![alt text](<Screenshot (54).png>)
![alt text](<Screenshot (54)-1.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
