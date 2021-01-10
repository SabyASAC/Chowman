<html>
<title> Chowman </title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body, html {
  height: 100%;
  font-family: "Calibri", sans-serif;
}

.bgimg {
  background-position: center;
  background-size: cover;
  min-height: 75%;
}

.menu {
  display: none;
}
</style>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-grey">HOME</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-black">ABOUT</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-grey">MENU</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-black">WHERE</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
    <span class="w3-tag">Open from 11am to 10 pm</span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white" style="font-size:90px">Chowman </span>
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
    <span class="w3-text-white">144 A, Prince Gholam Hussian Saha road, Kolkata </span>
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">About Chowman </span></h5>
    <p> Chowman, a chinese fast food chain was formed by Debaditya Chowdhury to visuaise his plans on offering affortable five star services to the general public. It now has many outlets all over india including quite a few at kolkata .</p>
    
    <div class="w3-panel w3-leftbar w3-light-grey">
    
      <p>Chef, Founder : Debabitya Chowdhury </p>
    </div>
   
    <p><strong>Opening hours:</strong> 11 am to 10 pm.</p>
    <p><strong>Address:</strong> 144 A, Prince Gholam Hussian Saha road, Kolkata  </p>
  </div>
</div>

Some of the items in the menu are listed below :

<!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">THE MENU</span></h5>
  
    <div class="w3-row w3-center w3-card w3-padding">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Vegetables');" id="myLink">
        <div class="w3-col s6 tablink">Vegetables</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Soup');">
        <div class="w3-col s6 tablink">Soup</div>
      </a>
    </div>

    <div id="Vegetables" class="w3-container menu w3-padding-48 w3-card">
      <h5>Chilli Garlic Babycorn and Button Murshroom</h5> 
    
      <h5>Hunan Paneer</h5>
  
      <h5>Chilli Potato </h5>
    
      <h5>Mixed Vegetables in White sauce </h5>
      
      <h5>GArlic Paneer</h5>
      
    </div>

    <div id="Soup" class="w3-container menu w3-padding-48 w3-card">
      <h5>Sweet Corn Soup </h5>
    
    
      <h5>Clear Soup </h5>
   
      <h5>Tom Yum Soup </h5>
     
      <h5>Lemon Pepper Soup</h5>
      
      <h5>Wonton Soup </h5>
    
    </div>  
   
  </div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">WHERE TO FIND US</span></h5>
    <p>Find us at some address mentioned above</p>
 
    
    <p><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
    Send your responses <a href="https://forms.gle/1kMhg7TFfXXP7ret8">here!</a>
<!-- End page content -->
</div>


