# Project Responsive Web Design using Bootstrap
## Date:16.10.2025

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
dribble.css

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dribbble Style Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: orange;
    }
    .subtext {
      color: blue;
    }
    .btn-learn {
      background-color: grey;
      color: white;
    }
    .btn-signup {
      background-color: pink;
      color: white;
    }
    .image-label {
      font-size: 1px;
      text-align: center;
      margin-top: 1px;
    }
    .navbar-brand {
      color: pink !important;
      font-weight: bold;
      font-size: 4px;
    }
  </style>
</head>
<body>
<!-- Dark Theme Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <!-- Dribbble brand on left -->


dribble.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Bootstrap Project</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-inverse">
            <div class="container-fluid">
                <div class="navbar-header">
                    <a class="navbar-brand" href="#">Dribble</a>
                </div>
                <ul class="nav navbar-nav">
                    <li><a href="#">Shots</a></li>
                    <li><a href="#">Designers</a></li>
                    <li><a href="#">Teams</a></li>
                    <li><a href="#">Community</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">...</a></li>
                </ul>
                <ul class="nav navbar-nav navbar-right">
                    <li><a href="#">Sign up</a></li>
                    <li><a href="#">Sign in</a></li>
                </ul>
                
            </div>
        </nav>
        <div class="bg-dark text-center">
            <p>What are you working on? Dribble is show and tell for designers.
                <button type="button" class="btn btn-secondary">Learn more</button>
                <button type="button" class="btn btn-danger">Sign up</button></p>
        </div>
        <nav class="navbar navbar-default">
            <div class="container-fluid">
                <ul class="nav navbar-nav">
                    <li class="dropdown"><a href="#">Popular</a>
                        <ul class="dropdown-menu" >
                			<li><a href="#">1.1</a></li>
                			<li><a href="#">1.2</a></li>
                			<li><a href="#">1.3</a></li>
                        </ul>
                    </li>
                    <li class="dropdown"><a href="#">Shots</a>
                        <ul class="dropdown-menu">
                			<li><a href="#">2.1</a></li>
                			<li><a href="#">2.2</a></li>
                			<li><a href="#">2.3</a></li>
                        </ul>
                    </li>
                    <li class="dropdown"><a href="#">Now</a>
                        <ul class="dropdown-menu">
                			<li><a href="#">3.1</a></li>
                			<li><a href="#">3.2</a></li>
                			<li><a href="#">3.3</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </nav>
        <div class="container">
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="1st img.jpg " class="card-img-top" style="height:150px; object-fit:cover;">
                </div>
            </div>
            <div class="col-md-3 ">
                <div class="card border-dark text-center">
                    <img src="2nd img.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                </div>
            </div>
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="3rd img.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                </div>
            </div>
            <div class="col-md-3 ">
                <div class="card border-dark text-center">
                    <img src="4th img.jpg" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                </div>
            </div>
          </div>
        </div>
        </div>


        
        <footer class="copyrights text-center">
            &copy; TAMILSELVI-25017628
        </footer>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (84).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
