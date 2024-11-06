# Nav bar
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Birth & Death Registration</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" type="text/css" href="responsive.css">
    <link rel="shortcut icon" href="img/55.ico" type="x-icon">

    <!-- Font Awesome  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <!-- Font Awesome End -->

    <!-- bootstrap-->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

      <!-- Add AOS Library for animation -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <!-- End bootstrap-->

</head>
<body>

<!-- nav bar -->
<nav class="navbar navbar-expand-lg fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand me-auto" href="#"><img src="img\logo.png" alt="logo" style="height: 65px;"></a>
<!--  ../index.html"-->
    <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasNavbarLabel"><a class="navbar-brand me-auto" href="#"><img src="img\logo.png" alt="logo" style="height: 65px;"></a></h5>
        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <ul class="navbar-nav justify-content-center flex-grow-1 pe-3">
          <li class="nav-item">
            <a class="nav-link mx-lg-2 active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mx-lg-2" href="">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mx-lg-2" href="">Facilities</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mx-lg-2" href="">Doctors</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mx-lg-2" href="">Contact</a>
          </li>
        </ul>
      </div>
    </div>
    <a href="book.html" class="login-button">Login</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  </div>
</nav>
<!-- nav bar End-->
</body>
  <script>
    // Initialize AOS Library
    AOS.init();
  </script>
 <style>
   /* nav bar start */
/* Styling for fixed navbar within section */
.fixed-navbar {
  position: fixed;
  top: 0; /* Adjust as needed */
  left: 0; /* Adjust as needed */
  width: 100%; /* Occupy full width of the viewport */
  z-index: 1000; /* Ensure the navbar stays above other content */
}

.navbar{
    background: linear-gradient(to right, #FF671F, #FFFFFF, #046A38);
    height: 80px;
    margin: 20px;
    border-radius: 18px;
    padding: 0.5rem;
    display: flex;
}

.read-more-btn{
  decoration: none;
    background-color: #087bff;
    color: #fff;
    font-size: 14px;
    padding: 8px 20px;
    border-radius: 50px;
    text-decoration: none;
    transition: 0.3s background-color;
}
.login-button {
    background-color: #087bff;
    color: #fff;
    font-size: 14px;
    padding: 8px 20px;
    border-radius: 50px;
    text-decoration: none;
    transition: 0.3s background-color;
}
.login-button2 {
    background-color: #087bff;
    color: #007bff;
    font-size: 14px;
    padding: 8px 20px;
    border-radius: 50px;
    text-decoration: none;
    transition: 0.3s background-color;
}
.login-button:hover {
    background-color: #0056b3;
}
.navbar-toggler {
    border: none;
    font-size: 1.25rem;
}
.navbar-toggler:focus, btn-close:focus {
    box-shadow: none;
    outline: none;
}
.nav-link {
    color: #666777;
    font-weight: 500;
    position: relative;
}
.nav-link:hover, .nav-link.active {
    color: #000;
}

 </style>
</html>
