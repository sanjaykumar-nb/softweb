# Ex.07 Software Product Company Website
## Date: 25-4-2024

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
### HOME.HTML
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(255, 255, 255, 0.75),rgba(0, 170, 255, 0.75));
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
                color:#000000;
                font-size: 50px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(187, 184, 184);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(4, 250, 41, 0.2);
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
                font-size: 20px;
                color: rgb(102, 103, 102);
            } 
            ::placeholder {
                color: rgb(0, 0, 0);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: #ffffff;
                border-radius: 10px;
                background:#6e4ad2;
                cursor: pointer;
            }
            .navbar li {
                font-size: 30px;
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(0, 0, 0);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(255, 255, 255);
                background-color: #19c6d6;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: rgb(0, 0, 0);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: rgb(0, 0, 0);
                text-transform: capitalize;
                font-size: 25px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid#000000;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(9, 9, 9);
                border-radius: 30px;
                background-color:#06c7ee;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid#ffffff;
                color:#fbfbfb;
                background-color: rgb(0, 0, 0);
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid#010505;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(0, 0, 0);
                border-radius: 30px;
                background-color:#06c7ee;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid#ffffff;
                color:#ddbbbb;
                background-color: rgb(0, 0, 0);
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color:#ffffff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">AI Smart</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> Software Development Company </h2>
                <br>
                <p>AI Smart is a cutting-edge company specializing in AI-powered software solutions. They’re at the forefront of AI innovation, impacting various industries with their smart platforms.</p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center>Designed and Developed by SANJAYKUMAR N B(212223230189) &copy; 2024</center>
    </footer>
</body>
</html>
```
### CONTACT.HTML
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Us Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(255, 255, 255, 0.941),rgba(1, 181, 246, 0.75));
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
                color: gray;
                background-color:#08f03e;
                border-radius: 30px;
            }
            .logo {
                color:#000000;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: gray;
            }
            .navbar form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(0, 0, 0, 0.2);
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
                color: rgb(0, 0, 0);
            } 
            ::placeholder {
                color: gray;
            }
            .navbar form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(253, 253, 253);
                border-radius: 10px;
                background:#00a6ff;
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
                color: rgb(0, 0, 0);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(11, 6, 117);
                background-color:#00ffff;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid rgb(12, 12, 12);
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid#141314;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: rgb(0, 0, 0);
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid rgb(16, 10, 10);
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: rgb(6, 4, 4);
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: rgb(10, 8, 8);
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid rgb(14, 5, 5);
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: rgb(7, 3, 3);
                border-radius: 30px;
                background:#00ffff;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: rgb(0, 0, 0);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: rgb(6, 1, 1);
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color:#000000;
                font-size: 20px;
            }
            footer {
                background-color:#f3fcff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">AI Smart</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address</span> : 11/1,kannaiah street,kondithope,chennai-600001</p>
                <p> <span>Email</span> : sanjay3664@gmail.com </p>
                <p> <span>Phone</span> : 9677179915</p>
            </div>
        </div>
    </div>
    <footer>
        <center>Designed and Developed by SANJAYKUMAR N B(212223230189) &copy; 2024</center>
    </footer>
</body>
</html>
```
### PRODUCT.HTML
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(255, 255, 255, 0.941),rgba(1, 181, 246, 0.75));
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
                color: gray;
                background-color:#08e8f0;
                border-radius: 30px;
            }
            .logo {
                color:#050505;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: gray;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(4, 250, 41, 0.2);
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
                color: rgb(0, 2, 0);
            } 
            ::placeholder {
                color: rgb(6, 6, 6);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(4, 4, 4);
                border-radius: 10px;
                background:#01a8fb;
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
                color: rgb(1, 1, 10);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(11, 6, 117);
                background-color:#00ccff;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: rgb(11, 1, 1);
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 10px;
                background: transparent;
                border: 1px solid rgb(30, 7, 243);
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 200px;
                border-radius: 10px;
            }
            .container .box-container .box h3 {
                color:#030303;
                font-size: large;
                padding: 50px 10;
            }
            .container .box-container .box p {
                color: gray;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color:#ffffff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">AI Smart</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/homepage.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/products.html" class="bg-product"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact us</a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container" align="center">
              
                
                <div class="box">
                    <h3 align="center">Gen AI</h3>
                    <image src="genai.jpeg" width="150" height="500" align="center"></image>
                </div>
                <div class="box">
                    <h3 align="center"> NLP </h3>
                    <image src="nlp.jpeg" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">ML Solutions</h3>
                    <image src="mlsol.jpeg" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">AI-Driven Automation</h3>
                    <image src="ai driven.jpeg" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">AI Security</h3>
                    <image src="ai security.jpeg" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">Customer enterprise</h3>
                    <image src="enterprise.jpeg" width="150" height="500"></image>
                </div>

            </div>
              
            </div>
        </div>
    </div>
    <footer>
        <center>Designed and Developed by SANJAYKUMAR N B(212223230189) &copy; 2024</center>
    </footer>
</body>
</html>
```
## PEOPLE.HTML
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(255, 255, 255, 0.75),rgba(0, 247, 255, 0.75));
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
                color: rgb(250, 125, 0);
                background-color:#00e1ff;
                border-radius: 30px;
            }
            .logo {
                color:#320be1;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: gray;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(4, 250, 41, 0.2);
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
                color: gray;
            } 
            ::placeholder {
                color: gray;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: gray;
                border-radius: 10px;
                background:#6e4ad2;
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
                color: rgb(11, 6, 117);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(26, 12, 221);
                background-color:#00b3ff;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: rgb(56, 10, 244);
                position: relative;
                left: 100px;
            }
            .image table img {
                height: 250px;
                width: 250px;
                border: 2px solid gray;
                padding: 40px;
                border-radius: 50%;
            }
            .image table td {
                color:#0a0208;
            }
            footer {
                background-color:#ffffff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">AI Smart</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">\
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="myself.jpg"> </td>
                    <td> <img src="vijay.jpeg"> </td>
                    <td> <img src="dhanush.jpeg"> </td>
                    <td> <img src="suriya.jpeg"> </td>
                    <td> <img src="ajith.jpeg"> </td>
                </tr>
                <tr align="center">
                    <th>SANJAYKUMAR N B</th>
                    <th>Vijay</th>
                    <th>Dhanush</th>
                    <th>Suriya</th>
                    <th>Ajith</th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center>Designed and Developed by SANJAYKUMAR N B(212223230189) &copy; 2024</center>
    </footer>
</body>
</html>
```

## OUTPUT:
![WhatsApp Image 2024-04-25 at 14 05 40_a6203e4d](https://github.com/sanjaykumar-nb/softweb/assets/154039979/d1b83be9-d2ab-4ee6-b39e-d73e2921de44)

![WhatsApp Image 2024-04-25 at 14 05 40_feb8e933](https://github.com/sanjaykumar-nb/softweb/assets/154039979/5ddb4686-6bff-4357-82f4-269e75cdc665)

![WhatsApp Image 2024-04-25 at 14 05 41_a738054f](https://github.com/sanjaykumar-nb/softweb/assets/154039979/8197d3af-6df4-413c-b29e-9ed1e6aeb74a)

![WhatsApp Image 2024-04-25 at 14 05 40_0d6b402f](https://github.com/sanjaykumar-nb/softweb/assets/154039979/6ce12012-c062-4804-b723-4846d7ea2d47)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
