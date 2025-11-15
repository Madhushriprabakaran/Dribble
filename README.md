# Project Responsive Web Design using Bootstrap
## Date:15-11-25

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
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dribbble Clone</title>
  <!-- Bootstrap CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-white shadow-sm fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navmenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link text-danger fw-semibold" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="text-center py-5 mt-5 bg-light">
    <div class="container">
      <h1 class="fw-bold display-5">Discover the World’s Top Designers</h1>
      <p class="lead text-muted mt-3">Join the largest community for creatives to share, grow, and get inspired.</p>
      <a href="#" class="btn btn-danger mt-3 px-4">Explore Now</a>
    </div>
  </section>

  <!-- Trending Shots Section -->
  <section class="container py-5">
    <h2 class="text-center fw-bold mb-4">Trending Shots</h2>
    <div class="row g-4">
      <div class="col-md-4 col-sm-6">
        <div class="card border-0 shadow-sm">
          <img src="images/b.png" class="card-img-top" alt="Design 1">
          <div class="card-body text-center">
            <h5 class="card-title">Modern UI Design</h5>
            <p class="text-muted mb-0">By Designer A</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card border-0 shadow-sm">
          <img src="images/bb.png" class="card-img-top" alt="Design 2">
          <div class="card-body text-center">
            <h5 class="card-title">E-commerce Dashboard</h5>
            <p class="text-muted mb-0">By Designer B</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-6">
        <div class="card border-0 shadow-sm">
          <img src="images/bbb.png" class="card-img-top" alt="Design 3">
          <div class="card-body text-center">
            <h5 class="card-title">Creative App Concept</h5>
            <p class="text-muted mb-0">By Designer C</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Join Section -->
  <section class="py-5 bg-danger text-white text-center">
    <div class="container">
      <h2 class="fw-bold">Join our community today!</h2>
      <p class="mt-3">Showcase your creativity and get noticed by top brands and companies.</p>
      <a href="#" class="btn btn-light px-4 mt-2">Sign Up Free</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-3 b

```
## OUTPUT:

![alt text](<Screenshot (151).png>)

![alt text](<Screenshot (152).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
