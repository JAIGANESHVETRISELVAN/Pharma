# Project Responsive Web Design using Bootstrap
## Date:10/05/2024

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
```
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HOME</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-image: url("back.webp");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 15px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: hsl(176, 70%, 44%); 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">JAI Pharmaceutical Company </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
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
        </ul>
    </div>
  </nav>
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>WELCOME TO JAI Pharmaceutical Company</h1>
        <p>Welcome to Pharmaceutical Company.We provide you the best quality of MEDICINE.Customers well being is what we wish always.</p>
        <p>At Our Pharmaceutical Company, we provide you all kind of medicine.</p>
        <p>Thank you for choosing and trusting our Pharmaceutical Company.</p>
      </div>
      <div class="col-md-5">
        <img src="pha.jpeg" width="300" height="300">
      </div>
      <div class="col-md-4">
        <img src="pharma.jpeg" width="300" height="300">
      </div>
        </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; JAI Pharmaceutical Company-JAIGANESH(212221040063).All rigths reserved.</p>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```
ABOUT.HTML

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-image: url("back.webp");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 15px;
    }
    footer{
    position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #343a40; 
      color: white;
      text-align: center;
      padding: 0px 0; 
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">JAI Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
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
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About JAI SPORTS SHOP</h1>
        <div >
            <h2>Specialization</h2>
           <p>JAI Pharmaceutical Company specializes in the development of therapeutic solutions across a spectrum of critical medical areas, including oncology, neurology, and cardiovascular diseases. Through our relentless pursuit of innovation, we continuously push the boundaries of scientific discovery.</p>
        </div>
        <div >
          <h2>Innovation</h2>
          <p> JAI Pharmaceutical Company has been at the forefront of innovation in the pharmaceutical industry. Committed to improving global healthcare standards, our mission is to provide cutting-edge solutions that address unmet medical needs</p>
        </div>
        <div >
          <h2>Recent Achievements </h2>
          <p>In recent years, JAI Pharmaceutical Company has achieved significant milestones, including the successful launch of groundbreaking medications and the initiation of promising clinical trials. These accomplishments reflect our unwavering commitment to scientific excellence and patient-centric values. </p>
        </div>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; JAI Pharmaceutical Company -JAIGANESH(212221040063).All rigths reserved.</p>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

```
CONTACT.HTML

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-image: url("back.webp");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 15px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: hsl(73, 87%, 48%); 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">JAI Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
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
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any queries please fill the form given below.</p>
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
        <h2>JAI Pharmaceutical Company</h2>
        <address>
          <strong>Address:</strong><br>
          2.233/2 cross street,pavithramanickam,chennai<br>
          <br>
          <strong>Email:</strong><br>
            jaiganesh9604@gmail.com<br><br>
          <strong>Phone:</strong><br>
          9360246488
        </address>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; JAI Pharmaceutical Company-JAIGANESH(212221040063).All rigths reserved.</p>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

```
PRODUCT.HTML



<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products</title>
   <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-image: url("back.webp");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 10px;
    }
    img{

        width: 25px;
        height: 200px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #343a40; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">JAI Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
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
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="tab.jpeg" class="card-img-top" >
            <div class="card-body">
              <h5 class="card-title">TABLET</h5>
              <p class="card-text">Dolo 650 for fever is available</p>
               </div>
          </div>
          <div class="card">
            <img src="oin.jpeg" class="card-img-top">
            <div class="card-body">
              <h5 class="card-title">Ointment</h5>
              <p class="card-text">For all disease we have ointment</p>
            </div>
          </div>
          <div class="card">
            <img src="syrup.jpeg" class="card-img-top" >
            <div class="card-body">
              <h5 class="card-title">Syrup</h5>
              <p class="card-text">For cough we have a special syrup</p>    
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; JAI Pharmaceutical Company-JAIGANESH(212221040063).All rigths reserved.</p>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-05-13 134910.png>)
 ![alt text](<Screenshot 2024-05-13 134831.png>)
![alt text](<Screenshot 2024-05-13 133429.png>)
![alt text](<Screenshot 2024-05-13 133439.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
