# Ex09 Event Registration Web Application
## Date:22/12/2024

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

home page

<div class="i-phone-13-14-1">
  <img class="image-1" src="image-10.png" />
  <img class="image-2" src="image-20.png" />
  <div class="sports-day-event">sports day event</div>
  <div class="group-1">
    <div class="group-3">
      <div class="rectangle-1"></div>
    </div>
  </div>
  <div class="rectangle-2"></div>
  <div class="login">login</div>
  <div class="register">register</div>
</div>

.i-phone-13-14-1,
.i-phone-13-14-1 * {
  box-sizing: border-box;
}
.i-phone-13-14-1 {
  background: #ff2828;
  border-radius: 65px;
  height: 844px;
  position: relative;
  overflow: hidden;
}
.image-1 {
  width: 401px;
  height: 859px;
  position: absolute;
  left: -11px;
  top: -15px;
  object-fit: cover;
}
.image-2 {
  width: 536px;
  height: 82px;
  position: absolute;
  left: -11px;
  top: 31px;
  object-fit: cover;
}
.sports-day-event {
  color: #000000;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: var(--body-large-line-height, 24px);
  font-weight: 400;
  position: absolute;
  left: 82px;
  top: 329px;
  width: 287px;
  height: 85px;
}
.group-2 {
  position: absolute;
  inset: 0;
}
.group-1 {
  width: 164px;
  height: 47px;
  position: static;
}
.group-3 {
  width: 164px;
  height: 47px;
  position: static;
}
.rectangle-1 {
  background: #ff2828;
  border-radius: 65px;
  width: 164px;
  height: 47px;
  position: absolute;
  left: 114px;
  top: 406px;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}
.group-4 {
  position: absolute;
  inset: 0;
}
.rectangle-2 {
  background: #5805ff;
  border-radius: 65px;
  width: 164px;
  height: 47px;
  position: absolute;
  left: 114px;
  top: 480px;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}
.login {
  color: #ffffff;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 129px;
  top: 414px;
  width: 136px;
  height: 32px;
}
.register {
  color: #ffffff;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 135px;
  top: 489px;
  width: 124px;
  height: 27px;
}


EVENTS PAGE

<div class="i-phone-13-14-2">
  <img class="image-1" src="image-10.png" />
  <img class="image-2" src="image-20.png" />
  <div class="sports-day-event">sports day event</div>
  <div
    class="cricket-football-hockey-badmitton-table-tennis-chess-running-race-long-jump-kabadi-jockey-fi-racing"
  >
    *CRICKET
    <br />
    <br />
    *FOOTBALL
    <br />
    <br />
    *HOCKEY
    <br />
    <br />
    *BADMITTON
    <br />
    <br />
    *TABLE TENNIS
    <br />
    <br />
    *CHESS
    <br />
    <br />
    *RUNNING RACE
    <br />
    <br />
    *LONG JUMP
    <br />
    <br />
    *KABADI
    <br />
    <br />
    *JOCKEY
    <br />
    <br />
    *FI RACING
  </div>
</div>


.i-phone-13-14-2,
.i-phone-13-14-2 * {
  box-sizing: border-box;
}
.i-phone-13-14-2 {
  background: #ff2828;
  border-radius: 65px;
  height: 844px;
  position: relative;
  overflow: hidden;
}
.image-1 {
  width: 401px;
  height: 859px;
  position: absolute;
  left: -11px;
  top: -15px;
  object-fit: cover;
}
.image-2 {
  width: 536px;
  height: 82px;
  position: absolute;
  left: -11px;
  top: 31px;
  object-fit: cover;
}
.sports-day-event {
  color: #000000;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: var(--body-large-line-height, 24px);
  font-weight: 400;
  position: absolute;
  left: 51px;
  top: 123px;
  width: 287px;
  height: 85px;
}
.cricket-football-hockey-badmitton-table-tennis-chess-running-race-long-jump-kabadi-jockey-fi-racing {
  color: #f41010;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 71px;
  top: 50%;
  translate: 0 -50%;
  width: 248px;
  height: 519px;
  -webkit-text-stroke: 1px #000000;
}


EVENT REGISTRATION

.i-phone-13-14-2,
.i-phone-13-14-2 * {
  box-sizing: border-box;
}
.i-phone-13-14-2 {
  background: #ff2828;
  border-radius: 65px;
  height: 844px;
  position: relative;
  overflow: hidden;
}
.image-1 {
  width: 401px;
  height: 859px;
  position: absolute;
  left: -11px;
  top: -15px;
  object-fit: cover;
}
.image-2 {
  width: 536px;
  height: 82px;
  position: absolute;
  left: -11px;
  top: 31px;
  object-fit: cover;
}
.sports-day-event {
  color: #000000;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: var(--body-large-line-height, 24px);
  font-weight: 400;
  position: absolute;
  left: 51px;
  top: 123px;
  width: 287px;
  height: 85px;
}
.cricket-football-hockey-badmitton-table-tennis-chess-running-race-long-jump-kabadi-jockey-fi-racing {
  color: #f41010;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 71px;
  top: 50%;
  translate: 0 -50%;
  width: 248px;
  height: 519px;
  -webkit-text-stroke: 1px #000000;
}


.i-phone-13-14-3,
.i-phone-13-14-3 * {
  box-sizing: border-box;
}
.i-phone-13-14-3 {
  background: #ff2828;
  border-radius: 65px;
  height: 844px;
  position: relative;
  overflow: hidden;
}
.image-1 {
  width: 401px;
  height: 859px;
  position: absolute;
  left: -11px;
  top: -15px;
  object-fit: cover;
}
.image-2 {
  width: 536px;
  height: 82px;
  position: absolute;
  left: -11px;
  top: 31px;
  object-fit: cover;
}
.rectangle-3 {
  background: #d9d9d9;
  width: 342px;
  height: 54px;
  position: absolute;
  left: 33px;
  top: 175px;
}
.rectangle-4 {
  background: #d9d9d9;
  width: 342px;
  height: 52px;
  position: absolute;
  left: 33px;
  top: 245px;
}
.reg-no {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 30px;
  top: 259px;
  width: 322px;
  height: 29px;
}
.name {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 34px;
  top: 191px;
  width: 322px;
  height: 29px;
}
.rectangle-5 {
  background: #d9d9d9;
  width: 342px;
  height: 47px;
  position: absolute;
  left: 33px;
  top: 310px;
}
.name2 {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 34px;
  top: 448px;
  width: 322px;
  height: 29px;
}
.department {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 34px;
  top: 326px;
  width: 322px;
  height: 29px;
}
.rectangle-6 {
  background: #d9d9d9;
  width: 342px;
  height: 55px;
  position: absolute;
  left: 33px;
  top: 368px;
}
.name3 {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 33px;
  top: 454px;
  width: 322px;
  height: 29px;
}
.rectangle-7 {
  background: #d9d9d9;
  width: 342px;
  height: 55px;
  position: absolute;
  left: 33px;
  top: 436px;
}
.rectangle-8 {
  background: #d9d9d9;
  width: 342px;
  height: 59px;
  position: absolute;
  left: 33px;
  top: 504px;
}
.mail {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 34px;
  top: 516px;
  width: 322px;
  height: 29px;
}
.rectangle-9 {
  background: #d9d9d9;
  width: 342px;
  height: 57px;
  position: absolute;
  left: 33px;
  top: 576px;
}
.age {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 34px;
  top: 588px;
  width: 322px;
  height: 29px;
}
.group-4 {
  position: absolute;
  inset: 0;
}
.rectangle-2 {
  background: #5805ff;
  border-radius: 65px;
  width: 164px;
  height: 47px;
  position: absolute;
  left: 108px;
  top: 665px;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}
.group-5 {
  width: 124px;
  height: 27px;
  position: static;
}
.register {
  color: #ffffff;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 128px;
  top: 675px;
  width: 124px;
  height: 27px;
}
.frame-1 {
  width: 100px;
  height: 100px;
  position: absolute;
  left: 64px;
  top: 175px;
  overflow: hidden;
}
.events-to-reg {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 33px;
  top: 454px;
  width: 322px;
  height: 29px;
}
.mobile-no {
  color: #000000;
  text-align: left;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 34px;
  top: 386px;
  width: 322px;
  height: 29px;
}


THANKYOU PAGE

<div class="i-phone-13-14-4">
  <img class="image-1" src="image-10.png" />
  <img class="image-2" src="image-20.png" />
  <div class="sports-day-event">sports day event</div>
  <div
    class="we-all-are-eagerly-waiting-for-your-participation-in-the-events-thankyou"
  >
    WE ALL ARE EAGERLY WAITING FOR YOUR PARTICIPATION IN THE EVENTS
    <br />
    <br />
    <br />
    <br />
    <br />
    Thankyou
  </div>
</div>


.i-phone-13-14-4,
.i-phone-13-14-4 * {
  box-sizing: border-box;
}
.i-phone-13-14-4 {
  background: #ff2828;
  border-radius: 65px;
  height: 844px;
  position: relative;
  overflow: hidden;
}
.image-1 {
  width: 401px;
  height: 859px;
  position: absolute;
  left: -11px;
  top: -15px;
  object-fit: cover;
}
.image-2 {
  width: 536px;
  height: 82px;
  position: absolute;
  left: -11px;
  top: 31px;
  object-fit: cover;
}
.sports-day-event {
  color: #000000;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: var(--body-large-line-height, 24px);
  font-weight: 400;
  position: absolute;
  left: 46px;
  top: 129px;
  width: 287px;
  height: 85px;
}
.we-all-are-eagerly-waiting-for-your-participation-in-the-events-thankyou {
  color: #000000;
  text-align: center;
  font-family: "Righteous-Regular", sans-serif;
  font-size: 32px;
  line-height: 24px;
  font-weight: 400;
  position: absolute;
  left: 69px;
  top: 259px;
  width: 238px;
  height: 402px;
}





```

## OUTPUT:
![alt text](<Screenshot 2024-12-22 221248.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
