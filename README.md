# Project Responsive Web Design using Bootstrap

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone - Bootstrap</title>

  <!-- Bootstrap CDN -->
  <link 
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" 
    rel="stylesheet">
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg bg-light shadow-sm">
  <div class="container">
    <a class="navbar-brand fw-bold text-danger" href="#">Dribbble Lite</a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" 
            data-bs-target="#navMenu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navMenu">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" href="#">Shots</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Designers</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Inspiration</a>
        </li>
        <li class="nav-item">
          <a class="btn btn-dark ms-3" href="#">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- HERO SECTION -->
<section class="py-5 text-center">
  <div class="container">
    <h1 class="fw-bold">Discover the World’s Top Designers</h1>
    <p class="lead">Explore beautiful shots, illustrations, UI concepts and more.</p>
    <button class="btn btn-danger btn-lg">Explore Shots</button>
  </div>
</section>

<!-- SHOTS GRID -->
<section class="py-4 bg-light">
  <div class="container">
    <h2 class="fw-bold mb-4 text-center">Trending Shots</h2>

    <div class="row g-4">
      <!-- Card 1 -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/400/300?1" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Creative UI Concept</h5>
            <p class="card-text">A modern clean UI shot for inspiration.</p>
          </div>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/400/300?2" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Mobile App Design</h5>
            <p class="card-text">Smooth minimal mobile interface concept.</p>
          </div>
        </div>
      </div>

      <!-- Card 3 -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/400/300?3" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Illustration Art</h5>
            <p class="card-text">Beautiful illustration for visual storytelling.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CALL TO ACTION -->
<section class="py-5 text-center">
  <div class="container">
    <h2 class="fw-bold">Join the creative community</h2>
    <p class="lead">Showcase your work and get inspired by others.</p>
    <button class="btn btn-dark btn-lg">Get Started</button>
  </div>
</section>

<!-- FOOTER -->
<footer class="bg-dark text-white text-center py-3">
  <p class="mb-0">Designed by <strong>Kailash Prabhu</strong></p>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

```
## OUTPUT:
<img width="1918" height="988" alt="image" src="https://github.com/user-attachments/assets/6132e29a-fffd-4662-9a29-72c99efc3fd3" />

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
