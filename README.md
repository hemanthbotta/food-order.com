<!DOCTYPE html>
<html lang="en">
<head>
  <title>Web Design</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
   <!--Font Awesome-->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous">
  <!--Reference CSSStyle.css sheet-->
  <link rel="stylesheet" href="CSS/CssStyle.css">
  <!--Bootstrap Installation-->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <style>
    .bgcolor{
      background-color: black;
    }
    .bg-dark {
    background-color: cornsilk!important;
}

.dropdown-menu{
  background-color: white;
}
.dropdown-item{
  color:red;font-family: 'Roboto Slab', serif;
}
.dropdown-item:hover{
  color:white;background-color:orangered;
}
.active{color:red!important}

  </style>
  <script>
    window.onscroll = function() {scrollFunction()};
    function scrollFunction(){
      if(document.body.scrollTop > 50 || document.documentElement.scrollTop > 50){
        document.getElementById("header").style.width="100%";
			  document.getElementById("header").style.left="0%";
			  document.getElementById("header").style.top="0%";
			  document.getElementById("header").style.transition="0.5s";
			  
        
      }
      else{
        document.getElementById("header").style.width="80%";
        
			  document.getElementById("header").style.left="10%";
			  document.getElementById("header").style.top="4%";
			  document.getElementById("header").style.transition="0.5s";
			  
         
      }
    }

    //Form Validation Java Script
  function myFunction() {
  //Name Validation
  var name=document.getElementById("name").value;
    if(name==""){
      document.getElementById("name_error1").style.display="block";
    return false;
  }
  if(!/^[a-zA-Z]*$/g.test(name)){
    document.getElementById("name_error2").style.display="block";
    return false;
  }
  //Phone Number Validation
  var name=document.getElementById("number").value;
    if(name==""){
      document.getElementById("number_error1").style.display="block";
    return false;
  }
  if(/^[6789]\d{9}$/g.test(number)){
    document.getElementById("number_error2").style.display="block";
    return false;
  }
  //Email Validation
  var name=document.getElementById("email").value;
    if(name==""){
      document.getElementById("email_error1").style.display="block";
    return false;
  }
  if(!/^([A-Za-z0-9_\-\.])+\@([A-Za-z0-9_\-\.])+\.([A-Za-z]{2,4})$/g.test(email)){
    document.getElementById("email_error2").style.display="block";
    return false;
  }

function clear_name_err(){
  document.getElementById("name_error1").style.display="none";
  document.getElementById("name_error2").style.display="none";
}
function clear_number_err(){
  document.getElementById("number_error1").style.display="none";
  document.getElementById("number_error2").style.display="none";
}
function clear_email_err(){
  document.getElementById("email_error1").style.display="none";
  document.getElementById("email_error2").style.display="none";
}
}
  </script>
</head>
<body class="bgcolor">
<div id="header">
  <div class="container">
<nav class="navbar navbar-expand-md ">
  <a class="navbar-brand" href="#"><img src="https://www.paradisefoodcourt.in/images/logos/Paradise-Logo3.png" alt ="paradise logo" style="width:100px;"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="collapsibleNavbar">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link active" href="WebDesign.html">Home</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="About.html">AboutUs</a>
      </li>
    
    <li class="nav-item">
      <a class="nav-link" href="Menu.html">Menu</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="Gallery.html">Gallery</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="Contact.html">ContactUs</a>
    </li>    
    </ul>
  </div>  
</nav>
</div>
</div>
<br>

<div class="container">
  <div class="row">
    <div class="col-sm-6">
      <div class="text1">Paradise</div><br><br>
      <div class="text2">Well known for feeding the minds, bodies and soul of our guests through an attitude of serving tasty food. Paradise Restaurant has brought the global approach of dinning with focus on authentic Indian food as well as serving Punjabi, Chinese and Mexican.</div>
    </div>
    <div class="col-sm-6">
      <img src="Images/ChickenNoodles.png" width="100%">
    </div>
  </div>
  <div class="topup"><a href="Menu.html"><button class="btn btn-warning">Menu</button></a></div><br>
  <div class="row">
    <div class="col-sm-6">
      <img src="Images/NoodlesFork.jpeg" width="100%">
    </div>
    <div class="col-sm-6">
    <div class="text3">Paradise Since 1953</div>
    <div class="text2">The world-famous Paradise brand has its origins in a small Canteen and a Café in a cinema theatre called Paradise in Secunderabad in the Year 1953.The tradiational and culture of flavours close to their art and history of making chefs at place.</div><br><br>
    <div class="text-center topup"><a href="about.html"><button class="btn btn-warning">ABOUT US</button></a></div><br>
  </div>
</div>
</div>

<div class="row" style="background-color: cornsilk;">
  <div class="col-sm-6">
    <div class="text3 text4" >Menu</div><br><br>
    <div class="text2 text4" >Well known for feeding the minds, bodies and soul of our guests through an attitude of serving tasty food. Paradise Restaurant has brought the global approach of dinning with focus on authentic Indian food as well as serving Punjabi, Chinese and Mexican.</div><br><br><br><br>
    <div class="container row">
    <div class="col-sm-6"><img src="Images/Mealsimg.png" width= "50px" class="img"><span class="textimg">Meals</span></div><br>
    <div class="col-sm-6"><img src="Images/soupimg.png" width= "50px" class="img"><span class="textimg">Soups</span></div><br>
    </div><br><br><br><br>
    <div class="container row">
    <div class="col-sm-6"><img src="Images/Noodlesimg.png" width= "50px" class="img"><span class="textimg">Noodles</span></div><br>
    <div class="col-sm-6"><img src="Images/SpringRolls.png" width= "50px" class="img"><span class="textimg">Spring Rolls</span></div><br>
    </div><br><br><br><br>
    <div class="container row">
      <div class="col-sm-6"><img src="Images/BiryanisImg.png" width= "50px" class="img"><span class="textimg">Biryanis</span></div><br>
      <div class="col-sm-6"><img src="Images/FastFoods.png" width= "50px" class="img"><span class="textimg">Fast Foods</span></div><br>
      </div><br><br><br><br>
      <div class="topup"><a href="Menu.html"><button class="btn btn-warning">SEE FULL MENU</button></a></div><br>
  </div>
  <div class="col-sm-6">
    <img src="Images/PlatesMenu.jpeg" width="100%">
  </div>
</div><br>

<div class="container">
  <h1 style="color: wheat; margin-left: 100px;">Gallery</h1>
  <div class="row">
    <div class="col-sm-6">
      
      <img src="Images/ParadiseBiryani.jpeg" width="100%">
    </div>
    <div class="col-sm-6">
      <div class="container row">
        <div class="col-sm-6"><img src="Images/dining.jpeg" width= "100%" ></div><br>
        <div class="col-sm-6"><img src="Images/Dining2.jpeg" width= "100%" ></div><br>
        </div>
        <div class="container row">
          <div class="col-sm-6"><img src="Images/BiryaniChickenPiece.jpeg" width= "100%" ></div><br>
          <div class="col-sm-6"><a href="Gallery.html"><img src="Images/Dining3.jpeg" width= "100%" style="opacity: 0.5;"><div class="content">View Gallery</div></a></div>
          
          </div>
  </div>
</div>
<div class="container row">
  <div class="col-sm-6" style="color: red;font-size: 49px;">Ratings from Customers</div>
  <div class="col-sm-6 imgcontent"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2">
    <div class="imgcontent">Average customer rating 4.2 (245 votes)</div>
  </div>

</div>
</div>
<!--FormValidation-->
<div class="container mt-5">
  <div>
    <form class="bg-white p-5">
      <div class="form-group">
        <label>Name: </label>
        <input type="text" id="name" placeholder="enter the name" class="form-control" onfocus="clear_name_err">
        <span style="color: red; display: none;" id="name_error1">Please Enter name</span>
        <span style="color: red; display: none;" id="name_error2">Please Enter valid name</span>
      </div>
      <div class="row">
        <div class="col-sm-6">
          
        
        <div class="form-group">
          <label>Email: </label>
          <input type="text" id="email" placeholder="enter the email" class="form-control" onfocus="clear_email_err">
          <span style="color: red; display: none;" id="email_error1">Please Enter email</span>
          <span style="color: red; display: none;" id="email_error2">Please Enter valid email</span>
        </div>
        <div class="form-group">
          <label>Subject: </label>
          <input type="text" id="name" placeholder="enter the Subject" class="form-control" >
        </div>
        
        </div>
        <div class="col-sm-6">
          <div class="form-group">
            <label>Phone Number: </label>
            <input type="text" id="number" placeholder="enter the number" class="form-control" onfocus="clear_number_err">
            <span style="color: red; display: none;" id="number_error1">Please Enter phone number</span>
            <span style="color: red; display: none;" id="name_error1">Please Enter valid phone number</span>
          </div>
          
       
    <div class="form-group">
   <label>Message:</label><br>
   <textarea rows="4" cols="50" class="form-control">
   </textarea></div><br>
   
        </div>
      </div>
      <div class="container btn-warning text-center btncontent">Send a Message</div>
      </div>
    </form>
  </div>

<!-- Footer -->
<div style="background-color: cornsilk;">
<footer class="page-footer font-small elegant-color">

    
  
    <!-- Footer Links -->
    <div class="container-fluid bg-dark text-center text-md-left pt-4 pt-md-5">
  
      <!-- Grid row -->
      <div class="row foot1 mt-1 mt-md-0 mb-4 mb-md-0">
  
        <!-- Grid column -->
        <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
  
          <!-- Links -->
          <h5>About me</h5>
          <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
  
          <p class="foot-desc mb-0">Here you can use rows and columns to organize your footer content. Lorem
            ipsum dolor sit amet,
            consectetur
            adipisicing elit.</p>
  
        </div>
        <!-- Grid column -->
  
        <hr class="clearfix w-100 d-md-none">
  
        <!-- Grid column -->
        <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
  
          <!-- Links -->
          <h5>Items</h5>
          <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
  
          <ul class="list-unstyled foot-desc">
            <li class="mb-2">
              <a href="https://paradisebiryanimi.com/">Biryanis</a>
            </li>
            <li class="mb-2">
              <a href="https://asianfoodnetwork.com/en/recipes/cuisine/chinese/paradise-fried-rice-special.html">Fried Rice</a>
            </li>
            <li class="mb-2">
              <a href="https://order.paradisefoodcourt.in/welcome">Meals</a>
            </li>
            <li class="mb-2">
              <a href="https://www.zomato.com/sydney/noodle-paradise-campbelltown/menu">Noodles</a>
            </li>
            <li class="mb-2">
              <a href="https://paradiseindiancuisine.com/menu-starters.html">Starters</a>
            </li>
          </ul>
  
        </div>
        <!-- Grid column -->
  
        <hr class="clearfix w-100 d-md-none">
  
        <!-- Grid column -->
        <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
  
          <!-- Links -->
          <h5>Useful links</h5>
          <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
  
          <ul class="list-unstyled foot-desc">
            <li class="mb-2">
              <a href="#!">bottahemanthkumar@gmail.com</a>
            </li>
            <li class="mb-2">
              <a href="#!">Become an Affiliate</a>
            </li>
            <li class="mb-2">
              <a href="#!">Shipping Rates</a>
            </li>
            <li class="mb-2">
              <a href="#!">Help</a>
            </li>
          </ul>
  
        </div>
        <!-- Grid column -->
  
        <hr class="clearfix w-100 d-md-none">
  
        <!-- Grid column -->
        <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
  
          <!-- Links -->
          <h5>Contacts</h5>
          <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
  
          <ul class="fa-ul foot-desc ml-4">
            <li class="mb-2"><span class="fa-li"><i class="far fa-map"></i></span>GF D NO 30-15-135, 29-8-1, Waltair, Uplands, VISHAKAPATNAM :- 530020
            </li>
            <li class="mb-2"><span class="fa-li"><i class="fas fa-phone-alt"></i></span>042 876 836 908</li>
            <li class="mb-2"><span class="fa-li"><i class="far fa-envelope"></i></span>paradisefoodcourt@gmail.com</li>
            <li><span class="fa-li"><i class="far fa-clock"></i></span>Monday - Friday: 10-17</li>
          </ul>
  
        </div>
        <!-- Grid column -->
  
      </div>
      <!-- Grid row -->
  
    </div>
    <!-- Footer Links -->
  
    
    <div>
        <div class="container">
    
          <!-- Grid row-->
          <div class="row py-4 d-flex align-items-center">
    
            <!-- Grid column -->
            <div class="col-md-6 col-lg-5 text-center text-md-left mb-4 mb-md-0">
              <h6 class="mb-0 foot1">Get connected with us on social networks!</h6>
            </div>
            <!-- Grid column -->
    
            <!-- Grid column -->
            <div class="col-md-6 col-lg-7 text-center text-md-right">
    
              <!-- Facebook -->
              <a class="fb-ic">
                <i class="fab fa-facebook-f white-text mr-4"> </i>
              </a>
              <!-- Twitter -->
              <a class="tw-ic">
                <i class="fab fa-twitter white-text mr-4"> </i>
              </a>
              <!-- Google +-->
              <a class="gplus-ic">
                <i class="fab fa-google-plus-g white-text mr-4"> </i>
              </a>
              <!--Linkedin -->
              <a class="li-ic">
                <i class="fab fa-linkedin-in white-text mr-4"> </i>
              </a>
              <!--Instagram-->
              <a class="ins-ic">
                <i class="fab fa-instagram white-text"> </i>
              </a>
    
            </div>
            <!-- Grid column -->
    
          </div>
          <!-- Grid row-->
    
        </div>
      </div>
  </footer>
  <!-- Footer -->
  <!-- Copyright -->
  <div class="footer-copyright text-center py-3">© 2021 Copyright:
    <a href="https://www.paradisefoodcourt.in/restaurants-in-vizag.html">Paradise</a> All rights reserved.
  </div>
  <!-- Copyright -->
</div>
</body>
</html>

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>AboutUs</title>

  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
	<!--Font Awesome-->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous">
  
	<link rel="stylesheet" href="CSS/CssStyle.css">
    <style>
        .bgcolor{
      background-color: black;
    }
        .bg2{
            background-color: black;width: 100%;height:150px;
        }
        .content2{
            color: wheat;font-size: 60px;margin-top: 200px;margin-left: 200px;
        }
        .text6{
            color: orangered;font-size: 60px;margin-top: 100px;margin-left: 100px;
        }
        .text5{
            color: orange;font-size: large;margin-left: 100px;
        }
        .parallax {
  /* The image used */
  background-image: url("Images/Dishes.jpeg");

  /* Set a specific height */
  min-height: 500px; 

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
    </style>
    <script>
        window.onscroll = function() {scrollFunction()};
    function scrollFunction(){
      if(document.body.scrollTop > 50 || document.documentElement.scrollTop > 50){
        document.getElementById("header").style.width="100%";
			  document.getElementById("header").style.left="0%";
			  document.getElementById("header").style.top="0%";
			  document.getElementById("header").style.transition="0.5s";
			  
        
      }
      else{
        document.getElementById("header").style.width="80%";
        
			  document.getElementById("header").style.left="10%";
			  document.getElementById("header").style.top="4%";
			  document.getElementById("header").style.transition="0.5s";
			  
         
      }
    }

    </script>
</head>

<body class="bgcolor">
	<div id="header">
        <div class="container">
      <nav class="navbar navbar-expand-md ">
        <a class="navbar-brand" href="#"><img src="https://www.paradisefoodcourt.in/images/logos/Paradise-Logo3.png" alt ="paradise logo" style="width:100px;"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link " href="WebDesign.html">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link active" href="About.html">AboutUs</a>
            </li>
          
          <li class="nav-item">
            <a class="nav-link" href="Menu.html">Menu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Gallery.html">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Contact.html">ContactUs</a>
          </li>    
          </ul>
        </div>  
      </nav>
      </div>
      </div>
      <br>
	<div class="bg2">
        <div class="content2">ABOUT US</div>
    </div>
    <div class="container-fluid">
    <div class="row" style="background-color: cornsilk;">
        <div class="col-sm-6">
          <img src="Images/MaleChef.jpeg" width="100%">
        </div>
        <div class="col-sm-6">
        <div class="text6">Paradise Since 1953</div>
        <div class="text5">The world-famous Paradise brand has its origins in a small Canteen and a Café in a cinema theatre called Paradise in Secunderabad in the Year 1953.The tradiational and culture of flavours close to their art and history of making chefs at place.
          Here, guests can discover authentic Hyderabadi cuisine made from natural ingredients by classically-trained Chefs. Everything tastes as it should – sublime.

          
          
        </div><br><br>
        
      </div>
    </div>
</div>

<div style="height:300px;background-color:black;color:orange;padding-left: 100px;font-size:36px"><p>The bright décor and comfortable seating make it ideal for a relaxed meal, while cordial service elevates your dining experience. If you are in a hurry, go straight to our Takeaway and walk out with your favourite dishes from a menu of over 70 varieties covering the best of Kebabs, Curries, Biryanis and Desserts.</p></div>

<div class="parallax"></div>

<div style="height:300px;background-color:black;color:orange;padding-left: 100px;font-size:36px">
  Chefs bring the exquisite culinary marvels from the royal courts of Nizams to people around the world. Our signature dishes are celebrated for their unforgettable purity and taste. Come experience dining at its best.
</div>

  <div class="container row">
    <div class="col-sm-6" style="color: red;font-size: 49px;">Ratings from Customers</div>
    <div class="col-sm-6 imgcontent"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2"><img src="Images/RatingStar.png" width= "25px" class="img2">
      <div class="imgcontent">Average customer rating 4.2 (245 votes)</div>
    </div>
  
  </div>
  <!-- Footer -->
<div style="background-color: cornsilk;">
    <footer class="page-footer font-small elegant-color">
    
        
      
        <!-- Footer Links -->
        <div class="container-fluid bg-dark text-center text-md-left pt-4 pt-md-5">
      
          <!-- Grid row -->
          <div class="row foot1 mt-1 mt-md-0 mb-4 mb-md-0">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>About me</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <p class="foot-desc mb-0">Here you can use rows and columns to organize your footer content. Lorem
                ipsum dolor sit amet,
                consectetur
                adipisicing elit.</p>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Items</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="list-unstyled foot-desc">
                <li class="mb-2">
                  <a href="https://paradisebiryanimi.com/">Biryanis</a>
                </li>
                <li class="mb-2">
                  <a href="https://asianfoodnetwork.com/en/recipes/cuisine/chinese/paradise-fried-rice-special.html">Fried Rice</a>
                </li>
                <li class="mb-2">
                  <a href="https://order.paradisefoodcourt.in/welcome">Meals</a>
                </li>
                <li class="mb-2">
                  <a href="https://www.zomato.com/sydney/noodle-paradise-campbelltown/menu">Noodles</a>
                </li>
                <li class="mb-2">
                  <a href="https://paradiseindiancuisine.com/menu-starters.html">Starters</a>
                </li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Useful links</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="list-unstyled foot-desc">
                <li class="mb-2">
                  <a href="#!">bottahemanthkumar@gmail.com</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Become an Affiliate</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Shipping Rates</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Help</a>
                </li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Contacts</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="fa-ul foot-desc ml-4">
                <li class="mb-2"><span class="fa-li"><i class="far fa-map"></i></span>GF D NO 30-15-135, 29-8-1, Waltair, Uplands, VISHAKAPATNAM :- 530020
                </li>
                <li class="mb-2"><span class="fa-li"><i class="fas fa-phone-alt"></i></span>042 876 836 908</li>
                <li class="mb-2"><span class="fa-li"><i class="far fa-envelope"></i></span>paradisefoodcourt@gmail.com</li>
                <li><span class="fa-li"><i class="far fa-clock"></i></span>Monday - Friday: 10-17</li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
          </div>
          <!-- Grid row -->
      
        </div>
        <!-- Footer Links -->
      
        
        <div>
            <div class="container">
        
              <!-- Grid row-->
              <div class="row py-4 d-flex align-items-center">
        
                <!-- Grid column -->
                <div class="col-md-6 col-lg-5 text-center text-md-left mb-4 mb-md-0">
                  <h6 class="mb-0 foot1">Get connected with us on social networks!</h6>
                </div>
                <!-- Grid column -->
        
                <!-- Grid column -->
                <div class="col-md-6 col-lg-7 text-center text-md-right">
        
                  <!-- Facebook -->
                  <a class="fb-ic">
                    <i class="fab fa-facebook-f white-text mr-4"> </i>
                  </a>
                  <!-- Twitter -->
                  <a class="tw-ic">
                    <i class="fab fa-twitter white-text mr-4"> </i>
                  </a>
                  <!-- Google +-->
                  <a class="gplus-ic">
                    <i class="fab fa-google-plus-g white-text mr-4"> </i>
                  </a>
                  <!--Linkedin -->
                  <a class="li-ic">
                    <i class="fab fa-linkedin-in white-text mr-4"> </i>
                  </a>
                  <!--Instagram-->
                  <a class="ins-ic">
                    <i class="fab fa-instagram white-text"> </i>
                  </a>
        
                </div>
                <!-- Grid column -->
        
              </div>
              <!-- Grid row-->
        
            </div>
          </div>
      </footer>
      <!-- Footer -->
      <!-- Copyright -->
      <div class="footer-copyright text-center py-3">© 2021 Copyright:
        <a href="https://www.paradisefoodcourt.in/restaurants-in-vizag.html">Paradise</a> All rights reserved.
      </div>
      <!-- Copyright -->
    </div>
</body>
</html>


<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>AboutUs</title>

  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
	<!--Font Awesome-->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous">
  
	<link rel="stylesheet" href="CSS/CssStyle.css">
    <style>
        .bgcolor{
      background-color: black;
    }
        .bg2{
            background-color: black;width: 100%;height:200px;
        }
        .content2{
            color: wheat;font-size: 60px;margin-top: 200px;margin-left: 200px;
        }
        .text6{
            color: orangered;font-size: 60px;margin-top: 100px;margin-left: 100px;
        }
        .text5{
            color: orange;font-size: large;margin-left: 100px;
        }
        .parallax {
  /* The image used */
  background-image: url("Images/Dishes.jpeg");

  /* Set a specific height */
  min-height: 500px; 

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
    </style>
    <script>
        window.onscroll = function() {scrollFunction()};
    function scrollFunction(){
      if(document.body.scrollTop > 50 || document.documentElement.scrollTop > 50){
        document.getElementById("header").style.width="100%";
			  document.getElementById("header").style.left="0%";
			  document.getElementById("header").style.top="0%";
			  document.getElementById("header").style.transition="0.5s";
			  
        
      }
      else{
        document.getElementById("header").style.width="80%";
			  document.getElementById("header").style.left="10%";
			  document.getElementById("header").style.top="4%";
			  document.getElementById("header").style.transition="0.5s";
			  
         
      }
    }

    //Form Validation Java Script
  function myFunction() {
  //Name Validation
  var name=document.getElementById("name").value;
    if(name==""){
      document.getElementById("name_error1").style.display="block";
    return false;
  }
  if(!/^[a-zA-Z]*$/g.test(name)){
    document.getElementById("name_error2").style.display="block";
    return false;
  }
  //Phone Number Validation
  var name=document.getElementById("number").value;
    if(name==""){
      document.getElementById("number_error1").style.display="block";
    return false;
  }
  if(/^[6789]\d{9}$/g.test(number)){
    document.getElementById("number_error2").style.display="block";
    return false;
  }
  //Email Validation
  var name=document.getElementById("email").value;
    if(name==""){
      document.getElementById("email_error1").style.display="block";
    return false;
  }
  if(!/^([A-Za-z0-9_\-\.])+\@([A-Za-z0-9_\-\.])+\.([A-Za-z]{2,4})$/g.test(email)){
    document.getElementById("email_error2").style.display="block";
    return false;
  }

function clear_name_err(){
  document.getElementById("name_error1").style.display="none";
  document.getElementById("name_error2").style.display="none";
}
function clear_number_err(){
  document.getElementById("number_error1").style.display="none";
  document.getElementById("number_error2").style.display="none";
}
function clear_email_err(){
  document.getElementById("email_error1").style.display="none";
  document.getElementById("email_error2").style.display="none";
}
}
    </script>
</head>

<body class="bgcolor">
	<div id="header">
        <div class="container">
      <nav class="navbar navbar-expand-md ">
        <a class="navbar-brand" href="#"><img src="https://www.paradisefoodcourt.in/images/logos/Paradise-Logo3.png" alt ="paradise logo" style="width:100px;"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="WebDesign.html">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="About.html">AboutUs</a>
            </li>
          
          <li class="nav-item">
            <a class="nav-link" href="Menu.html">Menu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Gallery.html">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="Contact.html">ContactUs</a>
          </li>    
          </ul>
        </div>  
      </nav>
      </div>
      </div>
      <br>
	<div class="bg2">
        <div class="content2">CONTACT US</div>
    </div>
    



  <!--FormValidation-->
<div class=" mt-5" style="background-color: wheat;">
    <div>
      <form class="bg-white p-5">
        <div class="form-group">
          <label>Name: </label>
          <input type="text" id="name" placeholder="enter the name" class="form-control" onfocus="clear_name_err">
          <span style="color: red; display: none;" id="name_error1">Please Enter name</span>
          <span style="color: red; display: none;" id="name_error2">Please Enter valid name</span>
        </div>
        <div class="row">
          <div class="col-sm-6">
            
          
          <div class="form-group">
            <label>Email: </label>
            <input type="text" id="email" placeholder="enter the email" class="form-control" onfocus="clear_email_err">
            <span style="color: red; display: none;" id="email_error1">Please Enter email</span>
            <span style="color: red; display: none;" id="email_error2">Please Enter valid email</span>
          </div>
          <div class="form-group">
            <label>Subject: </label>
            <input type="text" id="name" placeholder="enter the Subject" class="form-control" >
          </div>
          
          </div>
          <div class="col-sm-6">
            <div class="form-group">
              <label>Phone Number: </label>
              <input type="text" id="number" placeholder="enter the number" class="form-control" onfocus="clear_number_err">
              <span style="color: red; display: none;" id="number_error1">Please Enter phone number</span>
              <span style="color: red; display: none;" id="name_error1">Please Enter valid phone number</span>
            </div>
            
         
      <div class="form-group">
     <label>Message:</label><br>
     <textarea rows="4" cols="50" class="form-control">
     </textarea></div><br>
     
          </div>
        </div>
        <div class="container btn-warning text-center btncontent">Send a Message</div>
        </div>
      </form>
    </div>

    <div class="bg2">
        <div class="text-center" style="color: cornsilk;">Reservation</div>
        <div class="text-center" style="color: cornsilk;font-size: 70px;">Book a table</div>
        <div class="container btn-danger text-center " style="width: 300px;height: 50px;padding-top: 10px;color: cornsilk;">Make a Reservation</div>
    </div>
  <!-- Footer -->
<div style="background-color: cornsilk;">
    <footer class="page-footer font-small elegant-color">
    
        
      
        <!-- Footer Links -->
        <div class="container-fluid bg-dark text-center text-md-left pt-4 pt-md-5">
      
          <!-- Grid row -->
          <div class="row foot1 mt-1 mt-md-0 mb-4 mb-md-0">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>About me</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <p class="foot-desc mb-0">Here you can use rows and columns to organize your footer content. Lorem
                ipsum dolor sit amet,
                consectetur
                adipisicing elit.</p>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Items</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="list-unstyled foot-desc">
                <li class="mb-2">
                  <a href="https://paradisebiryanimi.com/">Biryanis</a>
                </li>
                <li class="mb-2">
                  <a href="https://asianfoodnetwork.com/en/recipes/cuisine/chinese/paradise-fried-rice-special.html">Fried Rice</a>
                </li>
                <li class="mb-2">
                  <a href="https://order.paradisefoodcourt.in/welcome">Meals</a>
                </li>
                <li class="mb-2">
                  <a href="https://www.zomato.com/sydney/noodle-paradise-campbelltown/menu">Noodles</a>
                </li>
                <li class="mb-2">
                  <a href="https://paradiseindiancuisine.com/menu-starters.html">Starters</a>
                </li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Useful links</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="list-unstyled foot-desc">
                <li class="mb-2">
                  <a href="#!">bottahemanthkumar@gmail.com</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Become an Affiliate</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Shipping Rates</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Help</a>
                </li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Contacts</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="fa-ul foot-desc ml-4">
                <li class="mb-2"><span class="fa-li"><i class="far fa-map"></i></span>GF D NO 30-15-135, 29-8-1, Waltair, Uplands, VISHAKAPATNAM :- 530020
                </li>
                <li class="mb-2"><span class="fa-li"><i class="fas fa-phone-alt"></i></span>042 876 836 908</li>
                <li class="mb-2"><span class="fa-li"><i class="far fa-envelope"></i></span>paradisefoodcourt@gmail.com</li>
                <li><span class="fa-li"><i class="far fa-clock"></i></span>Monday - Friday: 10-17</li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
          </div>
          <!-- Grid row -->
      
        </div>
        <!-- Footer Links -->
      
        
        <div>
            <div class="container">
        
              <!-- Grid row-->
              <div class="row py-4 d-flex align-items-center">
        
                <!-- Grid column -->
                <div class="col-md-6 col-lg-5 text-center text-md-left mb-4 mb-md-0">
                  <h6 class="mb-0 foot1">Get connected with us on social networks!</h6>
                </div>
                <!-- Grid column -->
        
                <!-- Grid column -->
                <div class="col-md-6 col-lg-7 text-center text-md-right">
        
                  <!-- Facebook -->
                  <a class="fb-ic">
                    <i class="fab fa-facebook-f white-text mr-4"> </i>
                  </a>
                  <!-- Twitter -->
                  <a class="tw-ic">
                    <i class="fab fa-twitter white-text mr-4"> </i>
                  </a>
                  <!-- Google +-->
                  <a class="gplus-ic">
                    <i class="fab fa-google-plus-g white-text mr-4"> </i>
                  </a>
                  <!--Linkedin -->
                  <a class="li-ic">
                    <i class="fab fa-linkedin-in white-text mr-4"> </i>
                  </a>
                  <!--Instagram-->
                  <a class="ins-ic">
                    <i class="fab fa-instagram white-text"> </i>
                  </a>
        
                </div>
                <!-- Grid column -->
        
              </div>
              <!-- Grid row-->
        
            </div>
          </div>
      </footer>
      <!-- Footer -->
      <!-- Copyright -->
      <div class="footer-copyright text-center py-3">© 2021 Copyright:
        <a href="https://www.paradisefoodcourt.in/restaurants-in-vizag.html">Paradise</a> All rights reserved.
      </div>
      <!-- Copyright -->
    </div>
</body>
</html>


<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>AboutUs</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
	<!--Font Awesome-->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous">
  
	<link rel="stylesheet" href="CSS/CssStyle.css">
  <style>
      .bgcolor{
      background-color: black;
    }
        .bg2{
            background-color: black;width: 100%;height:150px;
        }
        .content2{
            color: wheat;font-size: 60px;margin-top: 200px;margin-left: 200px;
        }
        .text6{
            color: orangered;font-size: 60px;margin-top: 100px;margin-left: 100px;
        }
        .text5{
            color: orange;font-size: large;margin-left: 100px;
        }
  .parallax {
  /* The image used */
  background-image: url("Images/Dishes.jpeg");

  /* Set a specific height */
  min-height: 500px; 

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.col-sm-4{
	padding: 10px ;
  }
  #myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation */
.modal-content, #caption {  
  -webkit-animation-name: zoom;
  -webkit-animation-duration: 0.6s;
  animation-name: zoom;
  animation-duration: 0.6s;
}

@-webkit-keyframes zoom {
  from {-webkit-transform:scale(0)} 
  to {-webkit-transform:scale(1)}
}

@keyframes zoom {
  from {transform:scale(0)} 
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}
    </style>
    <script>
     window.onscroll = function() {scrollFunction()};
    function scrollFunction(){
      if(document.body.scrollTop > 50 || document.documentElement.scrollTop > 50){
        document.getElementById("header").style.width="100%";
			  document.getElementById("header").style.left="0%";
			  document.getElementById("header").style.top="0%";
			  document.getElementById("header").style.transition="0.5s";
			  
        
      }
      else{
        document.getElementById("header").style.width="80%";
        
			  document.getElementById("header").style.left="10%";
			  document.getElementById("header").style.top="4%";
			  document.getElementById("header").style.transition="0.5s";
			  
         
      }
    }
//ZoomIn ZoomOut Javascript
    function get_big_image()
            {
               var width=document.getElementById("img_id").width="500";
               var height=document.getElementById("img_id").height="500";

               var w=width=50;
               var h=height=50;
               if(w>500 && h>500) {
                   alert("too big cannot displayed");
               }
               else{
                   document.getElementById("img_id").width=w;
                   document.getElementById("img_id").height=h;
               }
            }
            function get_normal_image()
            {
                var width2=document.getElementById("img_id").width="200";
                var height2=document.getElementById("img_id").height="200";

                var w2=width2=20;
                var h2=height2=20;
                if(w<200 && h<200) {
                   alert("too small cannot displayed");
               }
               else{
                   document.getElementById("img_id").width2=w2;
                   document.getElementById("img_id").height2=h2;
               }
            }

//Modal
            // Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}
    </script>
</head>

<body class="bgcolor">
  <div id="header">
    <div class="container">
  <nav class="navbar navbar-expand-md ">
    <a class="navbar-brand" href="#"><img src="https://www.paradisefoodcourt.in/images/logos/Paradise-Logo3.png" alt ="paradise logo" style="width:100px;"></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="collapsibleNavbar">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link " href="WebDesign.html">Home</a>
        </li>
        
        <li class="nav-item">
          <a class="nav-link active" href="About.html">AboutUs</a>
        </li>
      
      <li class="nav-item">
        <a class="nav-link" href="Menu.html">Menu</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="Gallery.html">Gallery</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="Contact.html">ContactUs</a>
      </li>    
      </ul>
    </div>  
  </nav>
  </div>
  </div>
      <br>
	<div class="bg2">
        <div class="content2">Gallery</div>
    </div>
    <div class="container" style="background-color: cornsilk;">
        <div class="row">
            <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/ChickenNoodles.png" width="100%" height="350px" >
                <!-- The Modal -->
            <div id="myModal" class="modal">
                <span class="close">&times;</span>
                <img class="modal-content" id="img01">
                <div id="caption"></div>
              </div>
             </div></div>
            <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/paneer-tikka.jpeg" width="100%" height="350px">
            <!-- The Modal -->
            <div id="myModal" class="modal">
                <span class="close">&times;</span>
                <img class="modal-content" id="img01">
                <div id="caption"></div>
              </div></div></div>
            <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/ChickenSoup.jpeg" width="100%" height="350px">
            <!-- The Modal -->
            <div id="myModal" class="modal">
                <span class="close">&times;</span>
                <img class="modal-content" id="img01">
                <div id="caption"></div>
              </div></div></div>
    </div>
    <div class="row">
        <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/ParadiseBiryani.jpeg" width="100%" height="350px">

            <!-- The Modal -->
            <div id="myModal" class="modal">
              <span class="close">&times;</span>
              <img class="modal-content" id="img01">
              <div id="caption"></div>
            </div></div></div>
        <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/rolls.jpeg" width="100%" height="350px">
            <!-- The Modal -->
            <div id="myModal" class="modal">
                <span class="close">&times;</span>
                <img class="modal-content" id="img01">
                <div id="caption"></div>
              </div></div>
        </div>
        <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/Strawberry Cocktail.jpg" width="100%" height="350px">
        <!-- The Modal -->
        <div id="myModal" class="modal">
            <span class="close">&times;</span>
            <img class="modal-content" id="img01">
            <div id="caption"></div>
          </div></div></div>
    </div>
    <div class="row">
        <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/BiryaniChickenPiece.jpeg" width="100%" height="350px">
        <!-- The Modal -->
        <div id="myModal" class="modal">
            <span class="close">&times;</span>
            <img class="modal-content" id="img01">
            <div id="caption"></div>
          </div></div></div>
        <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/ChilliChicken.jpeg" width="100%" height="350px">
        <!-- The Modal -->
        <div id="myModal" class="modal">
            <span class="close">&times;</span>
            <img class="modal-content" id="img01">
            <div id="caption"></div>
          </div></div></div>
        <div class="col-sm-4"><div onmouseover="get_big_image()" onmouseleave="get_normal_image()"><img id="myImg" src="Images/Loaded-Chopped-Veggie-Salad.jpeg" width="100%" height="350px">
        <!-- The Modal -->
        <div id="myModal" class="modal">
            <span class="close">&times;</span>
            <img class="modal-content" id="img01">
            <div id="caption"></div>
          </div></div></div>
    </div>
    </div>

    <div class="bg2">
        <div class="text-center" style="color: cornsilk;">Reservation</div>
        <div class="text-center" style="color: cornsilk;font-size: 70px;">Book a table</div>
        <div class="container btn-danger text-center " style="width: 300px;height: 50px;padding-top: 10px;color: cornsilk;">Make a Reservation</div>
    </div><br><br>
   <!-- Footer -->
<div style="background-color: cornsilk;">
  <footer class="page-footer font-small elegant-color">
  
      
    
      <!-- Footer Links -->
      <div class="container-fluid bg-dark text-center text-md-left pt-4 pt-md-5">
    
        <!-- Grid row -->
        <div class="row foot1 mt-1 mt-md-0 mb-4 mb-md-0">
    
          <!-- Grid column -->
          <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
    
            <!-- Links -->
            <h5>About me</h5>
            <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
    
            <p class="foot-desc mb-0">Here you can use rows and columns to organize your footer content. Lorem
              ipsum dolor sit amet,
              consectetur
              adipisicing elit.</p>
    
          </div>
          <!-- Grid column -->
    
          <hr class="clearfix w-100 d-md-none">
    
          <!-- Grid column -->
          <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
    
            <!-- Links -->
            <h5>Items</h5>
            <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
    
            <ul class="list-unstyled foot-desc">
              <li class="mb-2">
                <a href="https://paradisebiryanimi.com/">Biryanis</a>
              </li>
              <li class="mb-2">
                <a href="https://asianfoodnetwork.com/en/recipes/cuisine/chinese/paradise-fried-rice-special.html">Fried Rice</a>
              </li>
              <li class="mb-2">
                <a href="https://order.paradisefoodcourt.in/welcome">Meals</a>
              </li>
              <li class="mb-2">
                <a href="https://www.zomato.com/sydney/noodle-paradise-campbelltown/menu">Noodles</a>
              </li>
              <li class="mb-2">
                <a href="https://paradiseindiancuisine.com/menu-starters.html">Starters</a>
              </li>
            </ul>
    
          </div>
          <!-- Grid column -->
    
          <hr class="clearfix w-100 d-md-none">
    
          <!-- Grid column -->
          <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
    
            <!-- Links -->
            <h5>Useful links</h5>
            <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
    
            <ul class="list-unstyled foot-desc">
              <li class="mb-2">
                <a href="#!">bottahemanthkumar@gmail.com</a>
              </li>
              <li class="mb-2">
                <a href="#!">Become an Affiliate</a>
              </li>
              <li class="mb-2">
                <a href="#!">Shipping Rates</a>
              </li>
              <li class="mb-2">
                <a href="#!">Help</a>
              </li>
            </ul>
    
          </div>
          <!-- Grid column -->
    
          <hr class="clearfix w-100 d-md-none">
    
          <!-- Grid column -->
          <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
    
            <!-- Links -->
            <h5>Contacts</h5>
            <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
    
            <ul class="fa-ul foot-desc ml-4">
              <li class="mb-2"><span class="fa-li"><i class="far fa-map"></i></span>GF D NO 30-15-135, 29-8-1, Waltair, Uplands, VISHAKAPATNAM :- 530020
              </li>
              <li class="mb-2"><span class="fa-li"><i class="fas fa-phone-alt"></i></span>042 876 836 908</li>
              <li class="mb-2"><span class="fa-li"><i class="far fa-envelope"></i></span>paradisefoodcourt@gmail.com</li>
              <li><span class="fa-li"><i class="far fa-clock"></i></span>Monday - Friday: 10-17</li>
            </ul>
    
          </div>
          <!-- Grid column -->
    
        </div>
        <!-- Grid row -->
    
      </div>
      <!-- Footer Links -->
    
      
      <div>
          <div class="container">
      
            <!-- Grid row-->
            <div class="row py-4 d-flex align-items-center">
      
              <!-- Grid column -->
              <div class="col-md-6 col-lg-5 text-center text-md-left mb-4 mb-md-0">
                <h6 class="mb-0 foot1">Get connected with us on social networks!</h6>
              </div>
              <!-- Grid column -->
      
              <!-- Grid column -->
              <div class="col-md-6 col-lg-7 text-center text-md-right">
      
                <!-- Facebook -->
                <a class="fb-ic">
                  <i class="fab fa-facebook-f white-text mr-4"> </i>
                </a>
                <!-- Twitter -->
                <a class="tw-ic">
                  <i class="fab fa-twitter white-text mr-4"> </i>
                </a>
                <!-- Google +-->
                <a class="gplus-ic">
                  <i class="fab fa-google-plus-g white-text mr-4"> </i>
                </a>
                <!--Linkedin -->
                <a class="li-ic">
                  <i class="fab fa-linkedin-in white-text mr-4"> </i>
                </a>
                <!--Instagram-->
                <a class="ins-ic">
                  <i class="fab fa-instagram white-text"> </i>
                </a>
      
              </div>
              <!-- Grid column -->
      
            </div>
            <!-- Grid row-->
      
          </div>
        </div>
    </footer>
    <!-- Footer -->
    <!-- Copyright -->
    <div class="footer-copyright text-center py-3">© 2021 Copyright:
      <a href="https://www.paradisefoodcourt.in/restaurants-in-vizag.html">Paradise</a> All rights reserved.
    </div>
    <!-- Copyright -->
  </div>
</body>
</html>


<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Menu</title>

  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
	<!--Font Awesome-->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous">
  
	<link rel="stylesheet" href="CSS/CssStyle.css">
    <style>
        .bgcolor{
      background-color: black;
    }
        .bg2{
            background-color: black;width: 100%;height:200px;
        }
        .content2{
            color: wheat;font-size: 60px;margin-top: 200px;margin-left: 200px;
        }
        .text6{
            color: orangered;font-size: 60px;margin-top: 100px;margin-left: 100px;
        }
        .text5{
            color: orange;font-size: large;margin-left: 100px;
        }
        
    </style>
    <script>
        window.onscroll = function() {scrollFunction()};
    function scrollFunction(){
      if(document.body.scrollTop > 50 || document.documentElement.scrollTop > 50){
        document.getElementById("header").style.width="100%";
			  document.getElementById("header").style.left="0%";
			  document.getElementById("header").style.top="0%";
			  document.getElementById("header").style.transition="0.5s";
			  
        
      }
      else{
        document.getElementById("header").style.width="80%";
        
			  document.getElementById("header").style.left="10%";
			  document.getElementById("header").style.top="4%";
			  document.getElementById("header").style.transition="0.5s";
			   
         
      }
    }

    </script>
</head>

<body class="bgcolor">
	<div id="header">
        <div class="container">
      <nav class="navbar navbar-expand-md ">
        <a class="navbar-brand" href="#"><img src="https://www.paradisefoodcourt.in/images/logos/Paradise-Logo3.png" alt ="paradise logo" style="width:100px;"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="collapsibleNavbar">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="WebDesign.html">Home</a>
            </li>
            
            <li class="nav-item">
              <a class="nav-link" href="About.html">AboutUs</a>
            </li>
          
          <li class="nav-item">
            <a class="nav-link active" href="Menu.html">Menu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Gallery.html">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="Contact.html">ContactUs</a>
          </li>    
          </ul>
        </div>  
      </nav>
      </div>
      </div>
      <br>
	<div class="bg2">
        <div class="content2">MENU</div>
    </div>
    <div>
        <div class="row" >
          <div class="col-sm-6">
            <div class="text3">Starters</div><br><br>
            <div class="text2">Starters are meant to be visually and gastronomically appetizing. They are served with attractive garnishes and often with a selection of salads and chutneys.</div>
          </div>
          <div class="col-sm-6">
            <img src="Images/ParadiseBiryani.jpeg" width="100%">
          </div>
        </div>
        <br><br>
        <div class="row" >
          <div class="col-sm-6">
            <img src="Images/ChickenTandooriBiryani.jpeg" width="100%">
          </div>
          <div class="col-sm-6">
          <div class="text3">Meals</div>
          <div class="text2">serves every Food lover with delicious choices of fresh cooked multiple varieties of Indian authentic veg, non-veg , biryani delicacies and sweets. </div>
          </div><br><br>
          <div class="row" >
            <div class="col-sm-6">
              <div class="text3">Curries</div><br><br>
              <div class="text2">Foodcarry choose from the wide range of options in every category the best quality. </div>
            </div>
            <div class="col-sm-6">
              <img src="Images/chickenReciepe.png" width="100%">
            </div>
          </div>
          <br><br>
        </div>
      </div>
      </div>



  <!-- Footer -->
<div style="background-color: cornsilk;">
    <footer class="page-footer font-small elegant-color">
    
        
      
        <!-- Footer Links -->
        <div class="container-fluid bg-dark text-center text-md-left pt-4 pt-md-5">
      
          <!-- Grid row -->
          <div class="row foot1 mt-1 mt-md-0 mb-4 mb-md-0">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>About me</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <p class="foot-desc mb-0">Here you can use rows and columns to organize your footer content. Lorem
                ipsum dolor sit amet,
                consectetur
                adipisicing elit.</p>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Items</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="list-unstyled foot-desc">
                <li class="mb-2">
                  <a href="https://paradisebiryanimi.com/">Biryanis</a>
                </li>
                <li class="mb-2">
                  <a href="https://asianfoodnetwork.com/en/recipes/cuisine/chinese/paradise-fried-rice-special.html">Fried Rice</a>
                </li>
                <li class="mb-2">
                  <a href="https://order.paradisefoodcourt.in/welcome">Meals</a>
                </li>
                <li class="mb-2">
                  <a href="https://www.zomato.com/sydney/noodle-paradise-campbelltown/menu">Noodles</a>
                </li>
                <li class="mb-2">
                  <a href="https://paradiseindiancuisine.com/menu-starters.html">Starters</a>
                </li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Useful links</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="list-unstyled foot-desc">
                <li class="mb-2">
                  <a href="#!">bottahemanthkumar@gmail.com</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Become an Affiliate</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Shipping Rates</a>
                </li>
                <li class="mb-2">
                  <a href="#!">Help</a>
                </li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
            <hr class="clearfix w-100 d-md-none">
      
            <!-- Grid column -->
            <div class="col-md-3 mx-auto mt-3 mt-md-0 mb-0 mb-md-4">
      
              <!-- Links -->
              <h5>Contacts</h5>
              <hr class="color-primary mb-4 mt-0 d-inline-block mx-auto w-60">
      
              <ul class="fa-ul foot-desc ml-4">
                <li class="mb-2"><span class="fa-li"><i class="far fa-map"></i></span>GF D NO 30-15-135, 29-8-1, Waltair, Uplands, VISHAKAPATNAM :- 530020
                </li>
                <li class="mb-2"><span class="fa-li"><i class="fas fa-phone-alt"></i></span>042 876 836 908</li>
                <li class="mb-2"><span class="fa-li"><i class="far fa-envelope"></i></span>paradisefoodcourt@gmail.com</li>
                <li><span class="fa-li"><i class="far fa-clock"></i></span>Monday - Friday: 10-17</li>
              </ul>
      
            </div>
            <!-- Grid column -->
      
          </div>
          <!-- Grid row -->
      
        </div>
        <!-- Footer Links -->
      
        
        <div>
            <div class="container">
        
              <!-- Grid row-->
              <div class="row py-4 d-flex align-items-center">
        
                <!-- Grid column -->
                <div class="col-md-6 col-lg-5 text-center text-md-left mb-4 mb-md-0">
                  <h6 class="mb-0 foot1">Get connected with us on social networks!</h6>
                </div>
                <!-- Grid column -->
        
                <!-- Grid column -->
                <div class="col-md-6 col-lg-7 text-center text-md-right">
        
                  <!-- Facebook -->
                  <a class="fb-ic">
                    <i class="fab fa-facebook-f white-text mr-4"> </i>
                  </a>
                  <!-- Twitter -->
                  <a class="tw-ic">
                    <i class="fab fa-twitter white-text mr-4"> </i>
                  </a>
                  <!-- Google +-->
                  <a class="gplus-ic">
                    <i class="fab fa-google-plus-g white-text mr-4"> </i>
                  </a>
                  <!--Linkedin -->
                  <a class="li-ic">
                    <i class="fab fa-linkedin-in white-text mr-4"> </i>
                  </a>
                  <!--Instagram-->
                  <a class="ins-ic">
                    <i class="fab fa-instagram white-text"> </i>
                  </a>
        
                </div>
                <!-- Grid column -->
        
              </div>
              <!-- Grid row-->
        
            </div>
          </div>
      </footer>
      <!-- Footer -->
      <!-- Copyright -->
      <div class="footer-copyright text-center py-3">© 2021 Copyright:
        <a href="https://www.paradisefoodcourt.in/restaurants-in-vizag.html">Paradise</a> All rights reserved.
      </div>
      <!-- Copyright -->
    </div>
</body>
</html>




