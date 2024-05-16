# Ex.07 Software Product Company Website
## Date:23.04.24

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
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Web Design and Development Company </title>
        <style type="text/css"> 
            * {
                margin<: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image:url("C:\Users\admin\Desktop\CHEL.png");
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
                color: #070707;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(16, 16, 16);
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
                color: rgb(8, 8, 8);
            } 
            ::placeholder {
                color: rgb(17, 16, 16);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(12, 11, 11);
                border-radius: 10px;
                background: #0f0f10;
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
                color: rgb(8, 8, 8);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(16, 15, 15);
                background-color: #111112;
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
                color: rgb(18, 17, 17);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: rgb(29, 26, 26);
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid #dcdee2;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #1d1e20;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #cdd0d5;
                color: #090909;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid #c9cbcf;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(18, 17, 17);
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #d1d3d6;
                color: #141415;
                background-color: rgb(14, 13, 13);
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: #040404;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">T<span>ech</span>D<span>evelopers</span></h1>
            <ul>
                <li><a href="home.html"> HOME </a></li>
                <li><a href="product.html"> PRODUCTS </a></li>
                <li><a href="person.html"> MEMBERS </a></li>
                <li><a href="contact.html"> CONTACTS </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> Web Design and Development Company </h2>
                <br>
                <p> Welcome to Tech Developers, "There is no such thing as a boring project." </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by JAYASURIYA J(212223230088) </center>
    </footer>
</body>
</html>
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
                background-image:url(bgimg.jpeg);
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
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
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
                color: rgb(26, 24, 24);
            } 
            ::placeholder {
                color: rgb(28, 27, 27);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(19, 18, 18);
                border-radius: 10px;
                background: #d9dbde;
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
                color: white;
                background-color: #6fa1f8;
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
                color: white;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid white;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: #6fa1f8;
            }
            footer {
                background-color: #ffffff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">T<span>ech</span>S<span>olutions</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html" class="bg-people"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src=""C:\Users\admin\Desktop\SURYA.jpeg""> </td>
                    <td> <img src=""C:\Users\admin\Desktop\SILVA.jpeg""> </td>
                    <td> <img src=""C:\Users\admin\Desktop\MESSI.jpeg""> </td>
                    <td> <img src=""C:\Users\admin\Desktop\KHOLI.jpeg""> </td>
                    <td> <img src=""C:\Users\admin\Desktop\DHONI.jpeg""> </td>
                    <td> <img src=""C:\Users\admin\Desktop\KHAN.jpeg""> </td>
                </tr>
                <tr align="center">
                    <th> SANTHA RAMANATH M</th>
                    <th>M S DHONI </th>
                    <th>SIVAKARTHIKEYAN </th>
                    <th>NELSON DILIPKUMAR </th>
                    <th>YOGI BABU </th>
                    <th>PRIYANKA MOHAN </th>                    
                </tr>
                <tr align="center">
                    <td> Manager </td>
                    <td> CEO </td>
                    <td> Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                    <td> Secretary </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by JAYASURIYA J(212223230088) </center>
    </footer>
</body>
</html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: url(bgimg.jpeg);
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
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: #6fa1f8;
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
                color: white;
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
                background: #6fa1f8;
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
                color: white;
                background-color: #6fa1f8;
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
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid #6fa1f8;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: rgb(28, 27, 27);
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid rgb(21, 18, 18);
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: rgb(17, 16, 16);
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: #6fa1f8;
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
                color: #030c1d;
                font-size: 20px;
            }
            footer {
                background-color: #ffffff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">T<span>ech</span>S<span>olutions</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html" class="bg-contact"> Contact </a></li>
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
                <h2> Contact Info </h2>
                <p> <span>Address</span> : 1187/3 Gfsdd road,
                    kanchipuram Main Road,
                    Tamil Nadu 601049</p>
                <p> <span>Email</span> : apramanath@gmail.com </p>
                <p> <span>Phone</span> : 93447788766</p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by JAYASURIYA J(212223230088) </center>
    </footer>
</body>
</html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> Product Page </title>
<style type="text/css">
    * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
    }
    .banner {
        width: 100%;
        height: 100vh;
        background-image:url(bgimg.jpeg);
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
        background-color: #6fa1f8;
        border-radius: 30px;
    }
    .logo {
        color: #6fa1f8;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
    }
    span {
        color: white;
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
        background: #6fa1f8;
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
        color: white;
        background-color: #6fa1f8;
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
        color: white;
        box-shadow: 0 5px 10px rgba(0,0,0,.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
    }
    .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
    }
    .container .box-container .box h2 {
        color: #33aa20;
        font-size: large;
        padding: 10px 0;
    }
    .container .box-container .box p {
        color: rgb(195, 73, 73);
        font-size: small;
        line-height: 1.5;
    }
    footer {
        background-color: #090101;
        margin-top: auto;
    }
</style>
</head>
<body>
<div class="banner">
<br>
<div class="navbar">
    <h1 class="logo">T<span>ech</span>S<span>olutions</span></h1>
    <ul>
        <li><a href=home.html"> Home </a></li>
        <li><a href="product.html" class="bg-product"> Products </a></li>
        <li><a href="person.html"> person </a></li>
        <li><a href="contact.html"> Contact </a></li>
    </ul>
    <form action="" method="get">
        <input type="text" placeholder="Enter to Search">
        <button type="submit"> Search </button>
    </form>
</div>
<center>
    <h1 > <font color = "lightgreen"> OUR MEMBERS WORKED COMPANIES </font> </h1>
<img src=""C:\Users\admin\Documents\PHOTO NEED .jpg"" height="500" width="800">
</center>
</div>
<footer>
<center> Designed and Developed by JAYASURIYA J(212223230088) </center>
</footer>
</body>
</html>


## OUTPUT:
![image](https://github.com/230131249/softweb/assets/150232701/a68c09d1-d86f-4ba5-bad3-478a66b460b3)
![image](https://github.com/230131249/softweb/assets/150232701/57f2b2e5-5512-4503-a31e-007f56dac1f0)
![image](https://github.com/230131249/softweb/assets/150232701/5eb830d0-ccd3-4a2e-8943-c2abc32bd114)
![image](https://github.com/230131249/softweb/assets/150232701/425eec54-fcc5-4b6f-a0b1-25239e265b0d)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
