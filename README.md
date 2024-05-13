# Ex.07 Software Product Company Website
## Date: 13-05-2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~
home.html
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Software Development Company</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(9, 2, 2, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(BG\ ex6.jpg);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .logo {
        color: #0bfbdf;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: rgb(24, 150, 196);
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: rgb(11, 109, 154);
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: #00d5ff;
        cursor: pointer;
      }
      #search.hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #0ef;
        color: #081b29;
        box-shadow: 0 0 20px #0ef;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: red;
        color: #081b29;
        box-shadow: 0 0 20px red;
      }
      .content {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-align: center;
      }
      .text h2 {
        color: white;
        font-weight: 800;
        font-size: 50px;
        letter-spacing: 3px;
      }
      .text p {
        color: white;
        text-transform: capitalize;
        font-size: 15px;
        margin-bottom: 30px;
        word-spacing: 2px;
        letter-spacing: 1px;
      }
      .login {
        margin: 0px 10px;
        border: 2px solid hwb(240 0% 0% / 0.673);
        padding: 13px 35px;
        letter-spacing: 1px;
        color: white;
        border-radius: 30px;
        background-color: #0008ffaa;
        text-decoration: none;
      }
      .login:hover {
        border: 2px solid rgba(0, 149, 255, 0.595);
        color: rgba(183, 255, 0, 0.615);
        background-color: white;
        transition: 0.5s;
        cursor: pointer;
      }
      .signup {
        margin: 0px 10px;
        border: 2px solid green;
        padding: 13px 35px;
        letter-spacing: 1px;
        color: white;
        border-radius: 30px;
        background-color: green;
        text-decoration: none;
      }
      .signup:hover {
        border: 2px solid green;
        color: green;
        background-color: white;
        transition: 0.5s;
        cursor: pointer;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #9500ff9d;
        color: #081b29;
        box-shadow: 0 0 20px rgba(144, 0, 255, 0.516);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">W<span>EB</span>T<span>ECH</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html"> Products </a></li>
          <li><a href="people.html"> People </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button id="search" type="submit">Search</button>
        </form>
      </div>
      <div class="content">
        <div class="text">
          <h2>
            It's Time to Create Your Business Website 
          </h2>
          <br />

          <br />
          <div>
            <a href="#" class="login"> Log In </a>
            <a href="#" class="signup"> Sign Up </a>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY SHYAM </center>
    </footer>
  </body>
</html>

product.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(BG\ ex6.jpg);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-product {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: #e100ff;
        border-radius: 30px;
      }
      .logo {
        color: hsl(247, 97%, 51%);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: #1eb0d1;
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: red;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: red;
        color: #081b29;
        box-shadow: 0 0 20px red;
      }
      .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
      }
      .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 100px;
      }
      .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
      }
      .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
      }
      .container .box-container .box h3 {
        color: red;
        font-size: large;
        padding: 20px 0;
      }
      .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #9d00ffaa;
        color: #081b29;
        box-shadow: 0 0 20px #9d00ffaa;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">W<span>EB</span>T<span>ECH</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html" class="bg-product"> Products </a></li>
          <li><a href="people.html"> People </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="container">
        <div class="box-container">
          <div class="box">
            <h3>C++</h3>
            <p>
              Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development
            </p>
          </div>
          <div class="box">
            <h3>C</h3>
            <p>
              Crafting Performance: Where Precision Meets C Programming.
            </p>
          </div>
          <div class="box">
            <h3>JAVASCRIPT</h3>
            <p>
              Scripting Success: Unleashing the Power of JavaScript.
            </p>
          </div>
          <div class="box">
            <h3>PHP</h3>
            <p>
              PHP is a server side scripting language that is embedded in HTML.
            </p>
          </div>
          <div class="box">
            <h3>PYTHON</h3>
            <p>
              Unlocking Innovation: Python Paving the Way to Progress.
            </p>
          </div>
          <div class="box">
            <h3>SQL</h3>
            <p>
              SQL is a standard language for accessing and manipulating
              databases.
            </p>
          </div>
          <div class="box">
            <h3>SHELL</h3>
            <p>
              Shell can be accessed by users using a command line interface.
            </p>
          </div>
          <div class="box">
            <h3>RUBY</h3>
            <p>
              Ruby: Where Simplicity Meets Power in Programming
            </p>
          </div>
          <div class="box">
            <h3>TYPESCRIPT</h3>
            <p>
              Empower Your Code: Embrace the Future with TypeScript
            </p>
          </div>
          <div class="box">
            <h3>F#</h3>
            <p>
              F# is an Open-source programming language with a lot of features.
            </p>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and DEVELOPED BY SHYAM </center>
    </footer>
  </body>
</html>

people.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>people page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(BG\ ex6.jpg);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-people {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: rgba(0, 255, 247, 0.489);
        border-radius: 30px;
      }
      .logo {
        color: #6efb09e0;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: hwb(78 34% 4% / 0.601);
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background:red;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: red;
        color: #081b29;
        box-shadow: 0 0 20px red;
      }
      .image {
        position: relative;
        border: 0;
        top: 100px;

        background: transparent;
      }
      .image table {
        border: 0;
        color: white;
        position: relative;
        left: 50px;
        border: 10PX;
        padding-left: 10px;
      
      }
      .image table img {
        height: 140px;
        width: 140px;
        border: 2px solid white;
        padding: 5px;
        border-radius: 50%;
      }
      .image table td {
        color:red;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #9d00ffaa;
        color: #081b29;
        box-shadow: 0 0 20px #9d00ffaa;
      }
      .space{
        padding-left: 30px;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">W<span>EB</span>T<span>ECH</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html"> Products </a></li>
          <li><a href="people.html" class="bg-people"> People </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="image">
        <table cellspacing="65" >
          <tr align="center">
            <td><img src="varsha.jpg" /></td>
            <td><img src="ratan tata.jpeg"></td>
            <td><img src="steve.jpeg" /></td>
            <td><img src="sundar.avif" /></td>
            <td><img src="walt.jpeg" /></td>
            <td><img src="elonn.jpeg" /></td>
          </tr>
          <tr align="center" class="space">
            <th>VARSHA A</th>
            <th>RATAN TATA</th>
            <th>STEVE JOBS</th>
            <th>SUNDAR PICHAI</th>
            <th>WALT DISNEY</th>
            <th>ELON MUSK</th>
          </tr>
          <tr align="center">
            <td>CEO</td>
            <td>CEO,Co-Founder</td>
            <td>CTO,Co-Founder</td>
            <td>DIRECTOR</td>
            <td>Asst.Director</td>
            <td>Dy.Director</td>
          </tr>
        </table>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY SHYAM </center>
    </footer>
  </body>
</html>

contact.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(BG\ ex6.jpg);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-contact {
        border: 1px;
        padding: 10px;
        color: white;
        background-color:#b7ff00dd;
        border-radius: 30px;
      }
      .logo {
        color: hsl(274, 100%, 50%);
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      .navbar form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      .navbar form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: rgb(140, 6, 180);
      }
      ::placeholder {
        color: white;
      }
      .navbar form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: red;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #00ffd9a3;
        color: #081b29;
        box-shadow: 0 0 20px hsla(47, 97%, 54%, 0.753);
      }
      .box {
        display: flex;
        column-gap: 40px;
        background: transparent;
        position: relative;
        top: 50px;
        width: 220px;
      }
      .box-1 {
        height: 400px;
        width: 400px;
        border: 3px solid #bfff00;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 250px;
      }
      .box-2 {
        height: 400px;
        width: 400px;
        border: 3px solid #bfff00;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 300px;
      }
      .box-1 form {
        display: flex;
        color: white;
        background: transparent;
        padding: 10px;
        font-size: 15px;
        position: relative;
        top: 15px;
      }
      .box-1 form input {
        background: transparent;
        display: flex;
        border: 1px solid white;
        border-radius: 10px;
        padding: 15px 30px;
        font-size: 15px;
        color: white;
        position: relative;
        top: 30px;
      }
      .box-1 form textarea {
        background: transparent;
        color: white;
        padding: 15px 10px;
        position: relative;
        top: 30px;
        left: 20px;
        border: 1px solid white;
        border-radius: 10px;
        width: 300px;
      }
      .box-1 form button {
        border: 0;
        outline: none;
        padding: 10px 20px;
        color: white;
        border-radius: 30px;
        background: #00eaffc5;
        cursor: pointer;
        position: relative;
        top: 50px;
      }
      .box-2 h2 {
        color: white;
        position: relative;
        top: 25px;
        left: 50px;
        font-size: 30px;
      }
      .box-2 p {
        color: white;
        position: relative;
        top: 50px;
        padding: 10px 80px;
      }
      .box-2 span {
        color: red;
        font-size: 20px;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: #9d00ffaa;
        color: #081b29;
        box-shadow: 0 0 20px #9d00ffaa;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">W<span>EB</span>T<span>ECH</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html"> Products </a></li>
          <li><a href="people.html"> People </a></li>
          <li><a href="contact.html" class="bg-contact"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="box">
        <div class="box-1">
          <form>
            <center>
              <h1>Contact Us</h1>
              <input type="text" placeholder="Your Name" />
              <br />
              <input type="email" placeholder="Your Email" />
              <br />
              
              <br />
              <button type="submit">Submit</button>
            </center>
          </form>
        </div>
        <div class="box-2">
          <h2>Contact Information</h2>
          <p>
            <span>Address</span> :Techknow building, Door no 51, 7th Floor,
            Anna Nagar 4th street, Web Solutions HR IN 357206
          </p>
          <p><span>Email</span> : webtech.official@gmail.com</p>
          <p><span>Phone</span> : 7214960348</p>
        </div>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY SHYAM</center>
    </footer>
  </body>
</html>
~~~

## OUTPUT:
![Screenshot 2024-05-13 184210](https://github.com/shivanshyam79/softweb/assets/151513860/b27d5600-03af-4db1-a022-514819213f71)

![Screenshot 2024-05-13 184734](https://github.com/shivanshyam79/softweb/assets/151513860/2ee35078-ea94-449c-9ea8-e7a73bb3962d)

![Screenshot 2024-05-13 183923](https://github.com/shivanshyam79/softweb/assets/151513860/6146935f-7dc3-4092-b12c-b973ab04fe47)

![Screenshot 2024-05-13 184349](https://github.com/shivanshyam79/softweb/assets/151513860/7fe30649-9a12-4170-913b-8de48162ea0a)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
