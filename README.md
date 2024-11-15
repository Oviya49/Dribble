# Project Responsive Web Design using Bootstrap
## Date:14-11-2024

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
## Discover.html:
```
<html>
    <title>
        Interactive Image Gallery
    </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            background-size: cover;
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRf5cIjpqoONwpsAMYqSUDX5TIkL-pKwCxRcA&s");
        }

        h1 {
            margin-top: 20px;
            color: rgb(230, 60, 8);
            font-size: xx-large;
            font-style: italic;
        }

        .Gallery {
            display: flex;
            gap: 15px;
            max-width: 800px;
            margin-top: 20px;
            justify-content: center;
        }
    </style>

    <body>
        <h1>Interactive Image Gallery</h1>
        <div class="Gallery">
            <img src="https://next-images.123rf.com/index/_next/image/?url=https://assets-cdn.123rf.com/index/static/assets/top-section-bg.jpeg&w=3840&q=75" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://media.istockphoto.com/id/517188688/photo/mountain-landscape.jpg?s=1024x1024&w=0&k=20&c=z8_rWaI8x4zApNEEG9DnWlGXyDIXe-OmsAyQ5fGPVV8=" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://st.depositphotos.com/1718692/3934/i/450/depositphotos_39341537-stock-photo-pine-trees-near-valley-in.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://www.aaronreedphotography.com/images/xl/Sweet-Dreams-2022.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToV6AeAGjafklwyOTmhFuAR_pzUUH3CtjoTg&s" width="200" height="200" onclick="openImage(this.src)">
        </div>

        <script>
            function openImage(src) {
                window.open(src, "_blank");
            }
        </script>
    </body>
</html>
```
## About.html:
```
<html>
    <head>
        <title>about</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5 bg-light" id="about">
            <div class="container">
              <h2 class="text-center mb-4">About Us</h2>
              <p class="text-center">Dribbble Clone is a platform for designers to showcase their work and get inspired. Whether you're a graphic designer, illustrator, or UI/UX expert, our community is here to help you grow and connect with others.</p>
              <div class="row mt-4">
                <div class="col-md-6">
                  <h5>Our Mission</h5>
                  <p>To provide a space for creatives to share their work, gain feedback, and find inspiration from peers around the world.</p>
                </div>
                <div class="col-md-6">
                  <h5>Why Join Us?</h5>
                  <p>By joining Dribbble Clone, you become part of a vibrant community that celebrates creativity and innovation in design.</p>
                </div>
              </div>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by [Oviya]</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

        
</html>
```
## project.html
```
<html>
    <head>
        <title>project</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">


    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5" id="projects">
            <div class="container">
              <h2 class="text-center mb-4">Projects</h2>
              <p class="text-center">Explore various design projects contributed by our talented community members.</p>
              <div class="row">
                <div class="col-md-4">
                  <div class="card">
                    <img src="https://www.monigroup.com/sites/moni/files/2018-05/Why%20Web%20Design%20Is%20A%20Good%20Career%20Choice.jpg" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                      <h5 class="card-title">Project 1</h5>
                      <p class="card-text">A creative web design project.</p>
                    </div>
                  </div>
                </div>
                <div class="col-md-4">
                  <div class="card">
                    <img src="https://blog.tubikstudio.com/wp-content/uploads/2022/08/flower-store-app-design-tubik.jpg" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                      <h5 class="card-title">Project 2</h5>
                      <p class="card-text">An innovative mobile app design.</p>
                    </div>
                  </div>
                </div>
                <div class="col-md-4">
                  <div class="card">
                    <img src="https://www.digglescreative.com/images/blog/importance-of-brand-identity-design/intro-importance-of-brand-identity-design.jpg" class="card-img-top" alt="Project 3">
                    <div class="card-body">
                      <h5 class="card-title">Project 3</h5>
                      <p class="card-text">A branding and identity design.</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by [Oviya]</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
          

    </body>
</html>
```
## Signup.html:
```
<html>
    <head>
        <title>signup</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
              <a class="navbar-brand" href="#">Dribbble Clone</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                  <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                  <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
                  <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                  <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
                </ul>
              </div>
            </div>
          </nav>
          <section class="py-5 bg-primary text-white" id="signup">
            <div class="container">
              <h2 class="text-center mb-4">Sign Up</h2>
              <p class="text-center">Join the Dribbble Clone community and start sharing your work today!</p>
              <form class="mx-auto" style="max-width: 500px;">
                <div class="mb-3">
                  <label for="username" class="form-label">Username</label>
                  <input type="text" class="form-control" id="username" placeholder="Enter your username" required>
                </div>
                <div class="mb-3">
                  <label for="email" class="form-label">Email address</label>
                  <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                  <label for="password" class="form-label">Password</label>
                  <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
                </div>
                <button type="submit" class="btn btn-light w-100">Sign Up</button>
              </form>
            </div>
          </section>
          <footer class="bg-dark text-white py-3 text-center">
            <p>&copy; 2024 | Designed by [Oviya]</p>
          </footer>
          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    </body>
</html>
```



## OUTPUT:
## Discover.html:
![image](https://github.com/user-attachments/assets/44e1d264-1a96-4799-8c1d-53a574280558)
## About.html:
![image](https://github.com/user-attachments/assets/fac992f4-42eb-456c-85a0-279c2aebf3c2)
## Project.html:
![image](https://github.com/user-attachments/assets/aae8e796-c68f-41e6-a44a-70197a1f80ab)
## Signup.html:
![image](https://github.com/user-attachments/assets/e511dc8f-7f1c-48a2-86bc-184b498559e0)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
