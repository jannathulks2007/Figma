# Ex08 Event Registration Web Application
## Date:18/12/2025

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
TEMP 1

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="element" src="img/2.png" />
      <img class="SEC-logo-for-poster" src="img/SEC-logo-for-poster-white-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER NOW</div>
      <img class="screenshot" src="img/screenshot-2025-12-18-002853-removebg-preview-1.png" />
      <div class="div">Dance Program</div>
    </div>
  </body>
</html>

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
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 4946px;
  min-height: 7622px;
  position: relative;
}

.iphone-pro-max .element {
  position: absolute;
  top: 0;
  left: 0;
  width: 4946px;
  height: 7622px;
  aspect-ratio: 0.65;
}

.iphone-pro-max .SEC-logo-for-poster {
  position: absolute;
  top: 0;
  left: 0;
  width: 4946px;
  height: 1518px;
  aspect-ratio: 3.33;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 5971px;
  left: 564px;
  width: 3883px;
  height: 487px;
  background-color: #fffaf7;
  border-radius: 100px;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 6003px;
  left: 1192px;
  width: 2628px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #c80000;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 1518px;
  left: 1479px;
  width: 1987px;
  height: 1951px;
  aspect-ratio: 1.02;
  object-fit: cover;
}

.iphone-pro-max .div {
  position: absolute;
  top: 3429px;
  left: 439px;
  font-family: "Nosifer-Regular", Helvetica;
  font-weight: 400;
  color: #c80000;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}
TEMP 2

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="element" src="img/2.png" /></div>
  </body>
</html>
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
.image {
  width: 4650px;
  height: 8423px;
}

.image .element {
  position: fixed;
  top: 327px;
  left: 0;
  width: 4650px;
  height: 7622px;
  aspect-ratio: 0.55;
}

TEMP 3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="element" src="img/2.png" />
      <div class="rectangle"></div>
      <img class="img" src="img/rectangle-4.svg" />
      <div class="text-wrapper">Registration Form</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-2">Full Name</div>
      <div class="text-wrapper-3">Mobile No</div>
      <div class="text-wrapper-4">Register No</div>
      <div class="text-wrapper-5">Email Id</div>
      <div class="text-wrapper-6">Department</div>
    </div>
  </body>
</html>

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
.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 5193px;
  min-height: 7622px;
  position: relative;
}

.iphone-pro-max .element {
  position: absolute;
  top: 0;
  left: 0;
  width: 5193px;
  height: 7622px;
  aspect-ratio: 0.56;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 1715px;
  left: 551px;
  width: 3932px;
  height: 5267px;
  background-color: #fffaf7;
}

.iphone-pro-max .img {
  position: absolute;
  top: 314px;
  left: 631px;
  width: 3932px;
  height: 631px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 368px;
  left: 1053px;
  width: 3087px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #c80000;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 743px;
  left: 2394px;
  width: 100px;
  height: 100px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 2292px;
  left: 794px;
  width: 3495px;
  height: 655px;
  background-color: #c80000;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 3156px;
  left: 780px;
  width: 3495px;
  height: 655px;
  background-color: #c80000;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 4020px;
  left: 780px;
  width: 3495px;
  height: 655px;
  background-color: #c80000;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 4884px;
  left: 794px;
  width: 3495px;
  height: 655px;
  background-color: #c80000;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 5748px;
  left: 780px;
  width: 3495px;
  height: 655px;
  background-color: #c80000;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 2407px;
  left: 966px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #fffaf7;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 3264px;
  left: 966px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #fffaf7;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 4122px;
  left: 920px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #fffaf7;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 5850px;
  left: 920px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #fffaf7;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 4992px;
  left: 920px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #fffaf7;
  font-size: 350px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-18 005801.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
