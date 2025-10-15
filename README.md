# Ex09 Event Registration Web Application
## Date:16/10/2025

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

Home Page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <img class="saveetha-logo" src="img/saveetha-logo-1-3.png" />
      <img class="img" src="img/saveetha-logo-2.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">LOGIN</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="rectangle-2" src="img/rectangle-2.svg" />
      <div class="div">REGISTER</div>
    </div>
  </body>
</html>


.iphone-plus {
  background-color: #293acc;
  overflow: hidden;
  width: 100%;
  min-width: 428px;
  min-height: 926px;
  position: relative;
}

.iphone-plus .saveetha-logo {
  position: absolute;
  top: 249px;
  left: 147px;
  width: 135px;
  height: 134px;
  aspect-ratio: 1.01;
  object-fit: cover;
}

.iphone-plus .img {
  position: absolute;
  top: 19px;
  left: 8px;
  width: 412px;
  height: 96px;
  aspect-ratio: 4.29;
  object-fit: cover;
}

.iphone-plus .rectangle {
  position: absolute;
  top: 471px;
  left: 117px;
  width: 209px;
  height: 64px;
}

.iphone-plus .text-wrapper {
  position: absolute;
  top: 491px;
  left: calc(50.00% - 49px);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-on-a-path {
  position: absolute;
  top: 586px;
  left: -190px;
  width: 214px;
  height: 54px;
}

.iphone-plus .rectangle-2 {
  position: absolute;
  top: 609px;
  left: 116px;
  width: 205px;
  height: 54px;
}

.iphone-plus .div {
  position: absolute;
  top: 616px;
  left: calc(50.00% - 76px);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000fc;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

Page 2

.iphone-plus {
  background-color: #293acc;
  overflow: hidden;
  width: 100%;
  min-width: 428px;
  min-height: 926px;
  position: relative;
}

.iphone-plus .saveetha-logo {
  position: absolute;
  top: 249px;
  left: 147px;
  width: 135px;
  height: 134px;
  aspect-ratio: 1.01;
  object-fit: cover;
}

.iphone-plus .img {
  position: absolute;
  top: 19px;
  left: 8px;
  width: 412px;
  height: 96px;
  aspect-ratio: 4.29;
  object-fit: cover;
}

.iphone-plus .rectangle {
  position: absolute;
  top: 471px;
  left: 117px;
  width: 209px;
  height: 64px;
}

.iphone-plus .text-wrapper {
  position: absolute;
  top: 491px;
  left: calc(50.00% - 49px);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-plus .text-on-a-path {
  position: absolute;
  top: 586px;
  left: -190px;
  width: 214px;
  height: 54px;
}

.iphone-plus .rectangle-2 {
  position: absolute;
  top: 609px;
  left: 116px;
  width: 205px;
  height: 54px;
}

.iphone-plus .div {
  position: absolute;
  top: 616px;
  left: calc(50.00% - 76px);
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000fc;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}


.image {
  width: 714px;
  height: 901px;
}

.image .element {
  position: fixed;
  top: 0;
  left: 288px;
  width: 426px;
  height: 901px;
  aspect-ratio: 0.79;
  object-fit: cover;
}


Page 3

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="text-on-a-path" src="img/image.svg" />
      <img class="img" src="img/text-on-a-path-2.svg" />
      <div class="rectangle"></div>
      <img class="element" src="img/97-1.png" />
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <div class="fill-the-details">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Fill&nbsp;&nbsp;the details</div>
      <img class="text-on-a-path-2" src="img/text-on-a-path.svg" />
      <div class="div">full name</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
    </div>
  </body>
</html>


.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 908px;
  position: relative;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 156px;
  left: calc(50.00% - 1431px);
  width: 264px;
  height: 31px;
}

.iphone-pro-max .img {
  position: absolute;
  top: 187px;
  left: -1221px;
  width: 271px;
  height: 36px;
}

.iphone-pro-max .rectangle {
  top: 517px;
  left: 210px;
  width: 7px;
  height: 1px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .element {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 908px;
  aspect-ratio: 0.94;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 47px;
  left: calc(50.00% - 170px);
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .fill-the-details {
  position: absolute;
  top: 76px;
  left: 0;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-on-a-path-2 {
  position: absolute;
  top: 126px;
  left: -1198px;
  width: 264px;
  height: 30px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 433px;
  left: 143px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  top: 211px;
  left: 73px;
  width: 269px;
  height: 30px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-3 {
  top: 279px;
  left: 78px;
  width: 267px;
  height: 36px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-4 {
  top: 363px;
  left: 81px;
  width: 257px;
  height: 32px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-5 {
  top: 439px;
  left: 76px;
  width: 264px;
  height: 34px;
  transform: rotate(0.14deg);
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-6 {
  top: 560px;
  left: 250px;
  width: 157px;
  height: 50px;
  position: absolute;
  background-color: #d9d9d9;
}

```
# OUTPUT:
![alt text](<Screenshot (43).png>)




## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
