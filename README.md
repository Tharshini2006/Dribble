# Project Responsive Web Design using Bootstrap
## Date:20.05.2025

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
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .bgimage{
            background-image: url("homepage.jpeg");
            background-size: cover;
            height: 100vh;
        }
    </style>
</head>
<body>
    <div class="bgimage">
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#" style="font-family: fantasy; color: aliceblue;">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="glow.html" style="color: aliceblue;">ABOUT US</a></li>
          <li class="nav-item"><a class="nav-link" href="menu.html" style="color: aliceblue;">PRODUCTS</a></li>
          <li class="nav-item"><a class="nav-link" href="administration.html" style="color: aliceblue;">FAMOUS ARTIST</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html" style="color: aliceblue;">CONTACT US</a></li>
        </ul>
      </div>
    </div>
  </nav>
    <footer align="center" id="copywrite">
        <h3>Designed and devloped by Tharshini &copy 2025</h3>
    </footer>
   </div>
</body>
</html>
```
```c
<html lang="en">
<head>
    <style>
        body
        {
            background-color: rgba(109, 104, 104, 0.733);
        }
        #container
        {
            background-color: rgb(107, 96, 96);
            display: flex;
            justify-content: center;
            border: 5px solid aquamarine;
            height: 600px;
            width: auto;
            justify-content: space-evenly;
            
        }
        #main
        {
            border: 2px solid black;
        }
        .box
        {
            position: relative;
            display: inline-block;
            top: 150px;
            height: 250px;
            width: 200px;
            border: 2px solid black;
            background-color: pink;
            
        }
        #title
        {
            text-align: center;
            font-size: 50px;
            font-family:Georgia, 'Times New Roman', Times, serif;
            font-weight: 700;
            background-size:cover ;
        }
        
        #chef1
        {
            position: absolute;
            bottom: 170px;
            left: 100px;
            font-weight: 600;
            font-size: large;
            font-style:italic;
        }
        #chef2
        {
            position: absolute;
            bottom: 170px;
            left: 370px;
            font-weight: 600;
            font-size: large;
            font-style: italic;
        }
        #chef3
        {
            position: absolute;
            bottom: 170px;
            left: 600px;
            font-weight: 600;
            font-size: large;
            font-style: italic;
        }
        #chef4
        {
            position: absolute;
            bottom: 170px;
            left: 900px;
            font-weight: 600;
            font-size: large;
            font-style: italic;
        }
        
    </style>
    
</head>
<body>
    <div align="center" id="title">ARTIST</div>
    <div id="container">

            <div ><img src="Puneet B Saini.jpeg" alt="" class="box"></div>
            <div ><img src="Namrata Soni.jpeg" alt="" class="box"></div>
            <div ><img src="Mickey Contractor.jpeg" alt="" class="box"></div>
            <div ><img src="Daniel Bauer.webp" alt="" class="box"></div>
            

    </div>
    
</body>
</html>
```
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        pre{
            padding: 25px;
            font-size: large;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            
        }
       #order
        {
                display: inline;
                margin-left: 10px;
                color:rgb(64, 49, 39);
        }
        #h
        {
            text-align: center;
            font-style:inherit;
            margin-top: 10px;
            padding: 25px;
            position: relative;
            top: 50px;
            left: 0px;
            background-color:aqua;
        }
        body
        {
            background-color:darksalmon;

        }
    </style>
</head>
<body >
    
    <h1 id="h">ABOUT US</h1>
    <pre>
        

<b>WELCOME TO GLOW GARDEN</b>

<i>A Glow garden is a place where people go to get beauty treatments, especially for hair, skin, and nails.</i>

<b>What's special about as?</b>
<i>The special thing about a parlour—especially in the context of a beauty parlour—is that it offers a dedicated space for self-care, transformation, and relaxation.</i>

<b>What we focus on?</b>
 <i>Use an appointment system to reduce waiting time.Respect clients’ time and be punctual.</i>
    </pre>

</body>
</html>
```
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body{
            background-color:rgb(126, 63, 18);
        }
         
        img
        {
                margin-top: 110px;
                height: 240px;
                width: 240px;
                margin-left: 25px;

        } 
        
    </style>
</head>
<body>
    <div id="body">
    <h1 align="center">Order Now</h1>
    <div>
        <table>
            <tr>
        <td><img src="lipstick.jpeg"><h1>LIPSTICK</h1></td>
        <td><img src="facewash.webp"><h1>FACEWASH</h1></td>
        <td><img src="foundation.jpg"><h1>FOUNDATION</h1></td>
        <td><img src="eyeliner.webp"><h1>EYELINER </h1></td>
        <td><img src="concealer.webp"><h1>CONCEALER</h1></td>
    </tr>
    </table>
    </div>
    </div>
</body>
</html
```
```c
<html>
    <head>
        <title>Contact Us|GLOW GARDEN</title>
        <style>
     nav {
      background-color: black;
      color: white;
      padding: 10px;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }
    .heading{
        background-color: rgba(0, 0, 0, 0.384);
        color: rgba(219, 235, 8, 0.719);
        font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        font-style:italic;
        text-align:center;
    }
    .text1{
        height:500px;
        width:500px;
        background-color: rgba(8, 117, 81, 0.815);
        color:black;
        text-align: left;
        border-radius:5px;
        border-width: 10px solid black;
   
    }
    .align{
        text-align: center;
        display: flex;
        justify-content: center;
    }
    .text2{
        background-color: green;
        color: white;
        height:30px;
        width:500px;
    }
    .text3{
        text-align: center;
    }
    .btn{
        background-color: green;
        color:white;
        border-radius: 5px;
        border-width: 5px;
        border-color: black;
        height:50px;
        width:90px;
    }
    .btn-align{
        text-align: center;
    }
     body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #03471893;
}
        </style>
    </head>
    <body>
  <div class="heading">
    <h1>GLOW GARDEN</h1>
  </div>
  <div class="align">
    <div class="text1">
    <div class="text2">
       <h3 class="text3"> Contact Us </h3></div>
    <form>
        <br>
        Name:
        <input type="text" ><br><br>
        Email Id:
        <input type="text" ><br><br>
        Phone no:
        <input type="text"><br><br>
        Message:
        <input type="textarea"><hr color="black"><br><br>
       <div class="btn-align"><button class="btn">
        Submit</button></div> 
    </form>
    <center><h3><i>For any further details or queries contact us at 
        www.tharsh.com or through an email tharsh@gmail.com
        For booking Purposes you can place your order by calling
        the below number 8100 8800 7569
    </i></h3></center>

    </div>
  </div>
 
    </body>
</html>
```

## OUTPUT:
![alt text](<WhatsApp Image 2025-05-20 at 21.43.38_90a5555b.jpg>)

![alt text](<WhatsApp Image 2025-05-20 at 21.43.54_507b905e.jpg>)

![alt text](<WhatsApp Image 2025-05-20 at 21.51.25_963b0c0b.jpg>)

![alt text](<WhatsApp Image 2025-05-20 at 21.49.53_8face621.jpg>)

![alt text](<WhatsApp Image 2025-05-20 at 21.44.46_0ee8e45b.jpg>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
