# Project Responsive Web Design using Bootstrap
## Date: 10/05/24

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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

### web.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - PharmaCare+</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .navbar {
      background-color: #28a745; /* Change header color to green */
    }
    body{
        background-image: url(./img/360_F_410193012_UjVMvuwzFkn8a3qdvSkOCBq9ykMXpay9.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        color: aliceblue;
    }
    footer {
      position: fixed;
      bottom: 0;
      width: 100%;
      background-color: #343a40; /* Change footer color to dark */
      color: white; /* Change text color to white */
      padding: 10px 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">PharmaCare+</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="web.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to PharmaCare+</h1>
        <p>Welcome to PharmaCare+, your trusted source for high-quality pharmaceutical products. We are dedicated to improving the health and well-being of our customers by providing safe and effective medications.</p>
        <p>At PharmaCare+, we offer a wide range of prescription and over-the-counter medications to meet your healthcare needs. Whether you're managing a chronic condition or simply looking for relief from minor ailments, we have the products you need.</p>
        <p>In addition to medications, we also carry a variety of healthcare products and accessories, including vitamins, supplements, first aid supplies, and more. Our knowledgeable staff is here to assist you with any questions you may have and to ensure you find the right products for your needs.</p>
        <p>Thank you for choosing PharmaCare+ for your healthcare needs. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="./img/download (2).jpeg" class="img-fluid" alt="Pharmacy Image" style="size: 50px;">
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center">
    <div class="container">
      <p>&copy; 2024 PharmaCare+. All rights reserved. BY HARIHARAN A(212223110013)</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - PharmaCare+</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body style="background-color: #949595;">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">PharmaCare+</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>PharmaCare+</h2>
        <address>
          <strong>Address:</strong><br>
          123 Dubai main road,Dubai street, Dubai<br>632007<br><br>
          <strong>Email:</strong><br>
          info@pharmacare+.com<br><br>
          <strong>Phone:</strong><br>
          +91 9360167882
        </address>
      </div>
    </div>
  </div>
  <body background="a.png" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5 ">
    <p>&copy; 2024 PharmaCare+. All rights reserved.  BY HARIHARAN A(212223110013)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

### product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - PharmaCare+</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      margin: 0;
      padding: 0;
      background: url(./img/digital-tablet-laboratory-equipment-laboratory-ai-generated_964845-21.avif) no-repeat center center fixed;
      background-size: cover;
    }
    .content {
      flex: 1;
    }
    footer {
      background-color: rgba(0, 0, 0, 0.8); /* Dark background color with opacity */
      color: white; /* Text color */
      text-align: center;
      padding: 20px 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">PharmaCare+</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5 content">
    <div class="row">
      <div class="col-md-12">
        <h1 style="color: aliceblue;">Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="./img/images.jpeg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">Everherb Karela Jamun Juice - Helps Maintains Healthy Sugar Levels -Helps In Weight Management - 1l.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="./img/download.jpeg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Calcimax Forte Plus Strip Of 30 Tablets.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="./img/download (1).jpeg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Healthkart Calcium Tablets For Men & Women With Vitamin D3 For Complete Bone Health & Joint (60 No).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2024 PharmaCare+. All rights reserved. BY HARIHARAN A(212223110013)</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

### about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About PharmaCare+</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    *{
        color: black;
    }
    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      background-color: #949595;
    }
    .content {
      flex: 1;
    }
    footer{
      background-color: #343a40; /* Dark background color */
      color: white; /* Text color */
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">PharmaCare+</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5 content">
    <div class="row">
      <div class="col-md-12">
        <h1>About PharmaCare+</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>Our vision is to be a leading provider of innovative healthcare solutions that improve the quality of life for people around the world.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission is to develop and deliver safe, effective, and affordable medications that address the healthcare needs of our customers.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <ul>
            <li>Quality: We are committed to maintaining the highest standards of quality in everything we do.</li>
            <li>Integrity: We conduct our business with honesty, transparency, and ethical behavior.</li>
            <li>Innovation: We strive to continuously innovate and improve our products and services to better serve our customers.</li>
            <li>Customer Focus: We are dedicated to understanding and meeting the needs of our customers.</li>
            <li>Teamwork: We work together as a team to achieve our goals and deliver exceptional results.</li>
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2024 PharmaCare+. All rights reserved. BY HARIHARAN A(212223110013)</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:
### web.html
![web](<Screenshot 2024-05-10 234025.png>)

### product.html
![alt text](<Screenshot 2024-05-10 234050.png>)

### contact.html
![alt text](<Screenshot 2024-05-10 234100.png>)

### about.html
![about](<Screenshot 2024-05-10 234038.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
