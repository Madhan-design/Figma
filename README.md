# Ex09 Event Registration Web Application
# Date:21-11-2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
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
      <div class="overlap-group-wrapper">
        <div class="overlap-group">
          <img class="image" src="img/image-2.png" />
          <div class="rectangle"></div>
          <img class="sec-logo" src="img/sec-logo-01as-2048x412-1.png" />
          <img class="img" src="img/image-1.png" />
          <div class="rounded-rectangle"></div>
          <div class="text-wrapper">View Event</div>
        </div>
      </div>
    </div>
  </body>
</html>
.iphone-pro-max {
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.iphone-pro-max .overlap-group-wrapper {
  background-color: #ffffff;
  overflow: hidden;
  width: 440.0px;
  height: 956px;
}

.iphone-pro-max .overlap-group {
  position: relative;
  width: 450px;
  height: 956px;
  left: -10px;
}

.iphone-pro-max .image {
  width: 440px;
  height: 956px;
  top: 0;
  left: 10px;
  position: absolute;
  transform: rotate(180deg);
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  width: 450px;
  height: 79px;
  top: 816px;
  left: 0;
  background-color: #fdfff9;
  transform: rotate(180deg);
}

.iphone-pro-max .sec-logo {
  position: absolute;
  width: 308px;
  height: 62px;
  top: 827px;
  left: 54px;
  transform: rotate(180deg);
  object-fit: cover;
}

.iphone-pro-max .img {
  width: 228px;
  height: 221px;
  top: 465px;
  left: 25px;
  position: absolute;
  transform: rotate(180deg);
  object-fit: cover;
}

.iphone-pro-max .rounded-rectangle {
  position: absolute;
  width: 143px;
  height: 42px;
  top: 329px;
  left: 54px;
  background-color: #ec8f36;
  border-radius: 34px;
  transform: rotate(180deg);
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  width: 85px;
  top: 328px;
  left: 83px;
  transform: rotate(180deg);
  font-family: "Inknut Antiqua-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}
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
      <div class="overlap-group-wrapper">
        <div class="overlap-group">
          <div class="text-wrapper">Sports Day Events</div>
          <div class="badmintion-cricket">
            &gt;Badmintion<br /><br />&gt;Cricket<br /><br />&gt;Foot Ball<br /><br />&gt;Volley Ball<br /><br />&gt;Kabaddi
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
.iphone-pro-max {
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.iphone-pro-max .overlap-group-wrapper {
  background-color: #ffffff;
  width: 440px;
  height: 956px;
}

.iphone-pro-max .overlap-group {
  position: relative;
  height: 956px;
  background-image: url(./img/image-3.png);
  background-size: cover;
  background-position: 50% 50%;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  width: 173px;
  top: 87px;
  left: 139px;
  font-family: "Karantina-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .badmintion-cricket {
  position: absolute;
  top: 211px;
  left: 70px;
  font-family: "Jersey 20-Regular", Helvetica;
  font-weight: 400;
  color: #c40c0c;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}
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
      <div class="div">
        <div class="overlap-group">
          <div class="text-wrapper">Event Registration Form</div>
          <div class="overlap"><div class="text-wrapper-2">Name</div></div>
          <div class="overlap-2">
            <div class="rectangle"></div>
            <div class="text-wrapper-3">Register No</div>
          </div>
          <div class="div-wrapper"><div class="text-wrapper-4">Gender</div></div>
          <div class="overlap-3">
            <div class="rectangle"></div>
            <div class="text-wrapper-5">Department</div>
          </div>
          <div class="overlap-4"><div class="text-wrapper-2">Age</div></div>
          <div class="overlap-5"><div class="text-wrapper-6">View Event</div></div>
        </div>
        <img class="text-on-a-path" src="img/text-on-a-path.svg" />
        <img class="img" src="img/image.svg" />
      </div>
    </div>
  </body>
</html>
.iphone-pro-max {
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.iphone-pro-max .div {
  background-color: #ffffff;
  overflow: hidden;
  width: 440px;
  height: 956px;
  position: relative;
}

.iphone-pro-max .overlap-group {
  position: absolute;
  width: 440px;
  height: 956px;
  top: 0;
  left: 0;
  background-image: url(./img/image-3.png);
  background-size: cover;
  background-position: 50% 50%;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 90px;
  left: 73px;
  font-family: "Jockey One-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .overlap {
  position: absolute;
  width: 250px;
  height: 28px;
  top: 195px;
  left: 92px;
  background-color: #d9d9d9;
  border-radius: 36px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 1px;
  left: 31px;
  font-family: "JetBrains Mono-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .overlap-2 {
  position: absolute;
  width: 250px;
  height: 29px;
  top: 261px;
  left: 95px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  width: 250px;
  height: 28px;
  top: 1px;
  left: 0;
  background-color: #d9d9d9;
  border-radius: 36px;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 0;
  left: 28px;
  font-family: "JetBrains Mono-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div-wrapper {
  position: absolute;
  width: 250px;
  height: 28px;
  top: 329px;
  left: 95px;
  background-color: #d9d9d9;
  border-radius: 36px;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 1px;
  left: 28px;
  font-family: "JetBrains Mono-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .overlap-3 {
  position: absolute;
  width: 250px;
  height: 29px;
  top: 395px;
  left: 92px;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 0;
  left: 31px;
  font-family: "JetBrains Mono-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .overlap-4 {
  position: absolute;
  width: 250px;
  height: 28px;
  top: 462px;
  left: 92px;
  background-color: #d9d9d9;
  border-radius: 36px;
}

.iphone-pro-max .overlap-5 {
  position: absolute;
  width: 143px;
  height: 42px;
  top: 549px;
  left: 141px;
  background-color: #ec8f36;
  border-radius: 34px;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 7px;
  left: 25px;
  font-family: "Joan-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  width: 250px;
  height: 28px;
  top: 45px;
  left: -1019px;
}

.iphone-pro-max .img {
  position: absolute;
  width: 143px;
  height: 42px;
  top: 73px;
  left: -973px;
}
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
      <div class="overlap-group-wrapper">
        <div class="overlap-group">
          <div class="text-wrapper">THANK YOU</div>
          <div class="contact-us-email">Contact us:<br />email:saveetha.ac.in<br />P.no:0154789</div>
        </div>
      </div>
    </div>
  </body>
</html>
.iphone-pro-max {
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.iphone-pro-max .overlap-group-wrapper {
  background-color: #ffffff;
  width: 440px;
  height: 956px;
}

.iphone-pro-max .overlap-group {
  position: relative;
  height: 956px;
  background-image: url(./img/image-4.png);
  background-size: cover;
  background-position: 50% 50%;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 97px;
  left: 115px;
  font-family: "Jersey 15-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .contact-us-email {
  position: absolute;
  top: 268px;
  left: 25px;
  font-family: "JejuMyeongjo-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
```
# OUTPUT:
![Screenshot 2025-05-13 110444](https://github.com/user-attachments/assets/d3ee4509-0ab2-4843-8e47-8b381d348972)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
