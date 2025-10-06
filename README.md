# Ex09 Event Registration Web Application
## Date:6/10/2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
index1.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="global1.css" />
    <link rel="stylesheet" href="style1.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="logo" src="img/logo-1.png" />
      <img class="SEC-logo" src="img/SEC-logo-1-1.png" />
      <div class="text-wrapper">Event Day-2</div>
      <div class="rectangle"></div>
      <div class="div">Login</div>
      <img class="img" src="img/rectangle-2.svg" />
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Register</div>
      <div class="designed-by-harish">Designed by<br />Harish(25015017)</div>
    </div>
  </body>
</html>

global1.css

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

style1.css

.android-medium {
  background-color: #b3ecf9;
  overflow: hidden;
  border: 5px solid;
  border-color: #000000;
  width: 100%;
  min-width: 416px;
  min-height: 740px;
  position: relative;
}

.android-medium .logo {
  position: absolute;
  top: 40px;
  left: 11px;
  width: 393px;
  height: 59px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-medium .SEC-logo {
  position: absolute;
  top: 115px;
  left: 41px;
  width: 334px;
  height: 322px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 437px;
  left: 110px;
  width: 195px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 30px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 509px;
  left: 88px;
  width: 236px;
  height: 42px;
  background-color: #d9d9d9;
  border-radius: 4px;
  border: 2px solid;
  border-color: #000000;
  box-shadow: 0px 4px 4px #00000040, 0px 4px 4px #00000040;
}

.android-medium .div {
  position: absolute;
  top: 513px;
  left: 165px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 30px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .img {
  position: absolute;
  top: 516px;
  left: 25px;
  width: 100px;
  height: 100px;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 583px;
  left: 88px;
  width: 236px;
  height: 42px;
  background-color: #d9d9d9;
  border-radius: 4px;
  border: 2px solid;
  border-color: #000000;
  box-shadow: 0px 4px 4px #00000040, 0px 4px 4px #00000040;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 586px;
  left: 144px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 30px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .designed-by-harish {
  position: absolute;
  top: 663px;
  left: 208px;
  width: 277px;
  font-family: "Inter-MediumItalic", Helvetica;
  font-weight: 500;
  font-style: italic;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}



index2.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="global2.css" />
    <link rel="stylesheet" href="style2.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="bg" src="img/bg-1.png" />
      <div class="text-wrapper">Events</div>
      <div class="ellipse"></div>
      <div class="div">Meme Mania</div>
      <div class="ellipse-2"></div>
      <div class="text-wrapper-2">Eco-chronicles</div>
      <div class="ellipse-3"></div>
      <div class="text-wrapper-3">Ideathon</div>
      <div class="ellipse-4"></div>
      <div class="text-wrapper-4">Eco Hunt</div>
      <div class="ellipse-5"></div>
      <div class="text-wrapper-5">Fun-O-Quiz</div>
      <div class="designed-by-harish">Designed by <br />Harish(25015017)</div>
    </div>
  </body>
</html>

global2.css

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

style2.css

.android-medium {
  background-color: #99fff3;
  overflow: hidden;
  border: 4px solid;
  border-color: #000000;
  width: 100%;
  min-width: 416px;
  min-height: 740px;
  position: relative;
}

.android-medium .bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 416px;
  height: 740px;
  aspect-ratio: 0.9;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 52px;
  left: 138px;
  width: 239px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse {
  top: 251px;
  position: absolute;
  left: 67px;
  width: 15px;
  height: 17px;
  background-color: #ffffff;
  border-radius: 7.5px / 8.5px;
}

.android-medium .div {
  position: absolute;
  top: 230px;
  left: 99px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-2 {
  top: 315px;
  position: absolute;
  left: 67px;
  width: 15px;
  height: 17px;
  background-color: #ffffff;
  border-radius: 7.5px / 8.5px;
}

.android-medium .text-wrapper-2 {
  top: 294px;
  position: absolute;
  left: 102px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-3 {
  top: 373px;
  position: absolute;
  left: 67px;
  width: 15px;
  height: 17px;
  background-color: #ffffff;
  border-radius: 7.5px / 8.5px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 352px;
  left: 102px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-4 {
  top: 437px;
  position: absolute;
  left: 67px;
  width: 15px;
  height: 17px;
  background-color: #ffffff;
  border-radius: 7.5px / 8.5px;
}

.android-medium .text-wrapper-4 {
  top: 416px;
  position: absolute;
  left: 102px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ellipse-5 {
  top: 501px;
  position: absolute;
  left: 67px;
  width: 15px;
  height: 17px;
  background-color: #ffffff;
  border-radius: 7.5px / 8.5px;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 480px;
  left: 104px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .designed-by-harish {
  position: absolute;
  top: 608px;
  left: 171px;
  width: 306px;
  font-family: "Italianno-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

index3.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="global3.css" />
    <link rel="stylesheet" href="style3.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="screenshot" src="img/screenshot-55-1.png" />
      <div class="text-wrapper">Registeration form</div>
      <div class="rectangle"></div>
      <div class="div">Name</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-2">Dept</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-3">Email</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="img" src="img/image.svg" />
      <div class="rectangle-5"></div>
      <div class="text-wrapper-4">Register</div>
      <div class="text-wrapper-5">Ref no</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">Phone no</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-7">Event</div>
      <div class="designed-by-harish">Designed by <br />Harish(25015017)</div>
    </div>
  </body>
</html>

global3.css

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

style3.css

.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  border: 4px solid;
  border-color: #000000;
  width: 100%;
  min-width: 430px;
  min-height: 760px;
  position: relative;
}

.android-medium .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 430px;
  height: 760px;
  aspect-ratio: 1.33;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 54px;
  left: 39px;
  width: 334px;
  -webkit-text-stroke: 2px #000000;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 142px;
  left: 41px;
  width: 308px;
  height: 42px;
  background-color: #ffffff;
  border-radius: 10px;
}

.android-medium .div {
  position: absolute;
  top: 142px;
  left: 54px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #979797;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 213px;
  left: 41px;
  width: 308px;
  height: 42px;
  background-color: #ffffff;
  border-radius: 10px;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 284px;
  left: 41px;
  width: 308px;
  height: 42px;
  background-color: #ffffff;
  border-radius: 10px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 280px;
  left: 54px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #979797;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 358px;
  left: 41px;
  width: 308px;
  height: 42px;
  background-color: #ffffff;
  border-radius: 10px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 355px;
  left: 54px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #979797;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 419px;
  left: -6px;
  width: 308px;
  height: 42px;
}

.android-medium .img {
  position: absolute;
  top: 490px;
  left: -6px;
  width: 308px;
  height: 42px;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 593px;
  left: 71px;
  width: 248px;
  height: 48px;
  background-color: #424fff;
  border-radius: 5px;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 591px;
  left: 119px;
  -webkit-text-stroke: 2px #000000;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 211px;
  left: 54px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #979797;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 427px;
  left: 41px;
  width: 308px;
  height: 42px;
  background-color: #ffffff;
  border-radius: 10px;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 427px;
  left: 54px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #979797;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-7 {
  position: absolute;
  top: 508px;
  left: 41px;
  width: 308px;
  height: 42px;
  background-color: #ffffff;
  border-radius: 10px;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 507px;
  left: 54px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #979797;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .designed-by-harish {
  position: absolute;
  top: 650px;
  left: 157px;
  width: 320px;
  -webkit-text-stroke: 2px #000000;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 28px;
  letter-spacing: 0;
  line-height: normal;
}


```

## OUTPUT:
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (57).png>)
![alt text](<Screenshot (58).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
