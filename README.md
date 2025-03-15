<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  </head>
  <body>
<!-- start navbar -->
<nav class="navbar navbar-expand-lg bg-danger">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="logo.png" style="height: 50px;" alt="">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="#Gallery">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="#Team">Our Florists</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="Text">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
<!-- end navbar -->
<!-- start carousel -->
<div id="carouselExampleCaptions" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="c1.jpg" class="d-block w-100" style="height: 700px;" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5></h5>
          <p></p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="c2.jpg" class="d-block w-100" style="height: 700px;" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5></h5>
          <p></p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="c3.jpg" class="d-block w-100" style="height: 700px;" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5></h5>
          <p></p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
 
<!-- end carousel -->
 <!-- Gallery -->
<div class="container text-center py-5">
    <h2 id="Gallery" class="text-center p-3 rounded">GALLERY</h2>
        <script>
    setInterval(() => {
        const colors = ["primary", "secondary", "success", "danger", "warning", "info", "dark"];
        const texts = ["Gallery", "Visual Wonders", "Gallery Hub", "Creative Showcase"];
        const title = document.getElementById("gallery-title");
        title.textContent = texts[Math.floor(Math.random() * texts.length)];
        title.className = `text-center p-3 rounded bg-${colors[Math.floor(Math.random() * colors.length)]} text-white`;
    }, 2000);
</script>
    <div class="row">
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a1.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Allamanda</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a2.jfif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Daisy</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a3.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Rose</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a4.jfif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Sun Flower</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a5.jfif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Dandelion</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a6.jfif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Lotus</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a7.jfif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Carnation</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a8.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Bell flower</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a9.jfif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Tulips</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a10.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Orchid</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a11.jfif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Iris</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="a12.webp" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Anemone</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">Order now</a>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- End Gallery -->
<!-- My Team -->
<div class="container text-center py-2">
    <h2 id="Team" text-center p-3 rounded bg-primary text-white">MEET OUR FLORISTS</h2>
    <div class="row justify-content-center">
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="B1.jpg" class="card-img-top" alt="Team Member 1">
                <div class="card-body">
                    <h5 class="card-title">Ken Carson</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">View Profile</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="b2.jpg"card-img-top" alt="Team Member 2">
                <div class="card-body">
                    <h5 class="card-title">Molly Santana</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">View Profile</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="b3.jpg" class="card-img-top" alt="Team Member 3">
                <div class="card-body">
                    <h5 class="card-title">Clairo Batumbakal</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">View Profile</a>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card" style="width: 18rem;">
                <img src="b4.jpg" class="card-img-top" alt="Team Member 4">
                <div class="card-body">
                    <h5 class="card-title">Faye Webster</h5>
                    <p class="card-text"></p>
                    <a href="#" class="btn btn-primary">View Profile</a>
                </div>
            </div>
        </div>
    </div>
 
 
<!-- my team end -->
<!-- Contact Section -->
<div class="container text-center py-5">
    <h2 id="text" class="text-center p-3 rounded bg-danger text-white">CONTACT US</h2>
    <div class="row">
        <!-- Contact Form -->
        <div class="col-md-6">
            <form> 
                <div class="mb-3">
                    <label for="name" class="form-label">Full Name</label>
                    <input type="text" class="form-control" id="name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" required>
                </div> 
                <p class="fw-bolder">TEL. 4555-782</p>
 
