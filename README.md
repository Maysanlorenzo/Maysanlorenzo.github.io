<!DOCTYPE html>
<html>
  <head>
    <title>Tourist Attration</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <meta charset="utf-8">
    <style>  
     * {box-sizing: border-box;}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #e9e9e9;
}

.topnav a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #2196F3;
  color: white;
}

.topnav .login-container {
  float: right;
}

.topnav input[type=text] {
  padding: 6px;
  margin-top: 8px;
  font-size: 17px;
  border: none;
  width:120px;
}

.topnav .login-container button {
  float: right;
  padding: 6px 10px;
  margin-top: 8px;
  margin-right: 16px;
  background-color: #555;
  color: white;
  font-size: 17px;
  border: none;
  cursor: pointer;
}

.topnav .login-container button:hover {
  background-color: rgba(7, 20, 7, 0.493);
}

@media screen and (max-width: 600px) {
  .topnav .login-container {
    float: none;
  }
  .topnav a, .topnav input[type=text], .topnav .login-container button {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .topnav input[type=text] {
    border: 1px solid #ccc;  
  }
}

    </style>
    <style>

      header{
        background-image: url("https://w0.peakpx.com/wallpaper/1015/983/HD-wallpaper-beautiful-place-nature-landscape.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    
      }
    </style>
  </head>
  <body>
    
    <div class="topnav">
      <a class="active" href="#home">Home</a>
      <a href="#touristdestination">Tourist Destination</a>
      <a href="#contact">Contact</a>
      <a href="signup">Sign Up</a>
      <div class="login-container">
        <form action="/action_page.php">
          <input type="text" placeholder="Username" name="username">
          <input type="text" placeholder="Password" name="psw">
          <button type="submit">Sign in</button>
        </form>
      </div>
    </div>

    
    <header class="jumbotron jumbotron-fluid text-white">
      <div class="container text-center">
        <h1>Discover the Beauty of the Philippines</h1>
        <p>Explore the world through our beautiful photos</p>
        <a class="btn btn-success btn-lg" href="#" role="button">Book us Now!</a>
      </div>
    </header>
 
    <section id="about" class="container mt-5">
      <h2 class="text-center mb-5">About Us</h2>
      <div class="row">
        <div class="col-md-6">
          <p>Travel takes us out of our comfort zones and inspires us to see, taste and try new things. It constantly challenges us, not only to adapt to and explore new surroundings, but also to engage with different people, to embrace adventures as they come and to share new and meaningful experiences with friends and loved ones.</p>
        </div>
        <div class="col-md-6">
          <p>The Philippines is a tropical paradise in the Pacific Ocean made up of more than 7,000 islands that offer a natural playground for your inner explorer. Collectively, its landscapes feature an array of natural wonders, from volcanoes and rice terraces to underwater rivers and limestone caves, along with beautiful beaches.</p>
        </div>
      </div>
    </section>

 
    <section id="gallery" class="container mt-5">
      <h2 class="text-center mb-5">Gallery</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="https://www.planetware.com/photos-large/PHI/philippines-puerto-princesa-underground-river-tour.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h2 class="card-title"> Underground River Tour, Puerto Princesa</h2>
              <p class="card-text">Taking a river tour of the Underground River in Puerto Princesa is one of the most awe-inspiring things to do in the Philippines.</p>
              </div>
              </div>
              </div>
              <div class="col-md-4">
              <div class="card">
              <img src="https://www.worldatlas.com/r/w960-q80/upload/f4/5a/c6/shutterstock-584864689.jpg" class="card-img-top" alt="...">
              <div class="card-body">
              <h2 class="card-title">Boracay Island</h2>
              <p class="card-text">The island of Boracay may be small, but it is one of the best places to visit in the Philippines.</p>
              </div>
              </div>
              </div>
              <div class="col-md-4">
              <div class="card">
              <img src="https://www.planetware.com/wpimages/2020/02/philippines-top-attractions-manila-historical-sightseeing-tour.jpg" class="card-img-top" alt="...">
              <div class="card-body">
              <h2 class="card-title"> Manila Historical Sightseeing Tour</h2>
              <p class="card-text">This will give you a better appreciation for Manila. You can see the famous San Agustin Church and monuments at Rizal Park and Fort Santiago, each bearing a significant influence on Manila that is best shared by a guide.</p>
              </div>
              </div>
              </div>
              </div>
              </section>


 
     <div class="container fluid">
      <p></p>
      <p></p>
     </div>
              <section>
  
<!-- Carousel wrapper -->
<div
  id="carouselVideoExample"
  class="carousel slide carousel-fade"
  data-mdb-ride="carousel"

  <!-- Inner -->
  <div class="carousel-inner">
    <!-- Single item -->
    <div class="carousel-item active">
      <video class="img-fluid" autoplay loop muted>
        <source src="https://mdbcdn.b-cdn.net/img/video/Tropical.mp4" type="video/mp4" />
      </video>
      <div class="carousel-caption d-none d-md-block">
        
      </div>
    </div>

 </section>
 <div class="container fluid">
<p></p>
<p></p>
 </div>


<footer class="bg-dark text-white text-center p-3">
  <p>&copy; 2023 Tourist Attration</p>
</footer>
</body>
</html>
