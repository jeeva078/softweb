# Ex.07 Software Product Company Website
## Date:

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
### home.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    header{
        background-color: black;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                        <a href="home.html" title="Home" style="color: green; font-size: large; text-decoration: none; padding-left: 150px; padding-right: 150px;"><b>Home</b></a>
                        <a href="product.html" title="Products" style="color: green; font-size: large; text-decoration: none; padding-left: 150px; padding-right: 150px;"><b>Products</b></a>
                        <a href="people.html" title="People" style="color:green; font-size: large; text-decoration: none; padding-left: 150px; padding-right: 150px;"><b>People</b></a>
                        <a href="contact.html" title="Contact Us" style="color:green; font-size: large; text-decoration: none; padding-left: 150px; padding-right: 150px;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title" style="text-align: center; background-color: yellowgreen;">
                    <h1>JEEVA Network Company </h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Less invensment more benifites</b></marquee>
                    <p style="color:purple; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our Fancy Store</p>
                    </div>
                    <p>this is teaching from online for Men or Women from <span style="background-color:lime">JEEVA Network Company</span>
                         any lanuages  | any doubts you asking online whenever cleared | teaching days for 6 | extra code  | learn python, etc programming</p>
                    <br>
                <center>
                    <img src="/sree/softwebapp/static/images/1.jpg">
                    <img src="/sree/softwebapp/static/images/2.jpg">
                    <img src="/sree/softwebapp/static/images/3.jpg">
                    <img src="/sree/softwebapp/static/images/4.jpg">
                    <img src="/sree/softwebapp/static/images/5.jpg">
                    <img src="/sree/softwebapp/static/images/6.jpg">
                    <img src="/sree/softwebapp/static/images/7.jpg">
                </center>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by JEEVANANDAM M</footer></div>
            </div>
        </div>
    </body>
</html>
```
### product.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
        <style link rel="stylesheet">
        .home{
            height: 1555px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid red;
            background-color: white;
            width:98%;
            height:1190px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(https://th.bing.com/th/id/OIP.146KT0gacYdSQBkPBLYCSAHaFU?w=277&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7) ;
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:28%;
            position:relative;
            left: 50px;
        }
        .l1{
            color: gold;
            position:relative;
            right:380px;
            
            
        }
        .ph2{
            background-image: url(https://th.bing.com/th/id/OIP.6JfZJLhyNdrtT5fOe7Cw5wHaD1?w=314&h=179&c=7&r=0&o=5&dpr=1.3&pid=1.7);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:28%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color: sandybrown;
            position:relative;
            right:380px;
        }
        .ph3{
            background-image: url(https://history-computer.com/wp-content/uploads/2022/03/C-language.jpg);
            background-size: 400px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l3{
            color: burlywood;
            position:relative;
            right:380px;
        }
        .ph4{
            background-image: url(https://th.bing.com/th/id/OIP.49i-Cf_j6FHy75GEkJTtSAHaE8?w=247&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7);
            background-position-x: center;
            border:1px solid black;
            height:200px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 400px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: burlywood;
            position:relative;
            left:270px;
            bottom: 930px;
        }
    
        .ph5{
            background-image: url(https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191217202846/Programming-for-Beginners-10-Best-HTML-Coding-Practices-You-Must-Know.png);
            background-position-x: center;
            border:1px solid black;
            height:200px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 400px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: cadetblue;
            position:relative;
            left:270px;
            bottom: 930px;
        }

        .ph6{
            background-image: url(https://1001tricks.com/wp-content/uploads/2011/05/css3-1068x563.jpg);
            background-position-x: center;
            border:1px solid black;
            height:200px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 400px;
            background-repeat: no-repeat;
            
            
        }
        .l6{
            color: crimson  ;
            position:relative;
            left:270px;
            bottom: 930px;
        }
        .bot{
            text-align:center;
            font-size:larger;
            color:magenta;

        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                        <a href="home.html" title="Home" style="color: green; font-size: large; text-decoration: none; padding-left: 125px; padding-right: 125px;"><b>Home</b></a>
                        <a href="product.html" title="Products" style="color: green; font-size: large; text-decoration: none; padding-left: 125px; padding-right: 125px;"><b>Products</b></a>
                        <a href="people.html" title="People" style="color:green; font-size: large; text-decoration: none; padding-left: 125px; padding-right: 125px;"><b>People</b></a>
                        <a href="contact.html" title="Contact Us" style="color:green; font-size: large; text-decoration: none; padding-left: 100px; padding-right: 125px;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the products that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>python<br> Price: 1999.00</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>c<br> Price: 1899.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>C++<br> Price: 1999.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>java<br> Price: 6999.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>html<br> Price: 3999.00</b><br><br><br><br></p></div>
                    <div class="ph6"></div>
                    <div class="l6"><p align="center"><b>css<br> Price: 5999.00</b><br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To apply Online: Call 95 70 75 2009</p></div>

                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by JEEVANANDAM M</footer></div>
            </div>
        </div>
    </body>
</html>
```
### people.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid red;
            background-color:lime;
            width:98%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(https://th.bing.com/th/id/OIP.7NgFUS5jUQyXXnj5YLCjSQAAAA?pid=ImgDet&rs=1);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid gold;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: black;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(https://i.pinimg.com/originals/20/aa/11/20aa1115b81faa383e4d991881e9a6f1.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:180px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: red;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(https://th.bing.com/th/id/OIP.5M3wfXww9rNLDDaUOmTsdAHaFi?w=283&h=213&c=7&r=0&o=5&dpr=1.3&pid=1.7);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:180px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: red;
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(https://th.bing.com/th/id/OIP.sXqt7QTSqjgZPV85BAzJZgHaEJ?w=322&h=181&c=7&r=0&o=5&dpr=1.3&pid=1.7);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:140px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: red;
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(https://th.bing.com/th/id/OIP.Ev_ad3Jyb1BcyPApoJjqCwHaEK?w=304&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:140px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: red;
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(https://th.bing.com/th/id/OIP.y0wkjsYH2GK_W9dvdRKH4AHaEW?pid=ImgDet&rs=1);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:140px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color: red;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                        <a href="home.html" title="Home" style="color: green; font-size: large; text-decoration: none; padding-left: 125px; padding-right: 125px;"><b>Home</b></a>
                        <a href="product.html" title="Products" style="color: green; font-size: large; text-decoration: none; padding-left: 125px; padding-right: 125px;"><b>Products</b></a>
                        <a href="people.html" title="People" style="color:green; font-size: large; text-decoration: none; padding-left: 125px; padding-right: 125px;"><b>People</b></a>
                        <a href="contact.html" title="Contact Us" style="color:green; font-size: large; text-decoration: none; padding-left: 100px; padding-right: 125px;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>JEEVANANDAM M</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>GOJO</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>NOBITA</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>NARUTO</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>KAKASHI</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2>OBITO</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our online courses had made you more B-E-A-UTIFUL!</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by JEEVANANDAM M</footer></div>
            </div>
        </div>
    </body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    .home{
        height: 700px;
        width: 85%;
        border: 12px solid red;
        padding-left:10px;
        padding-right:10px;
        margin-left: auto;
        margin-right:auto;
        background-color:cyan;
    }
    .content{
        border:1px solid whitesmoke;
        background-color: white;
        width:95%;
        height:1190px;
        padding:10px;
        margin-left:auto;
        margin-right:auto;
    }
    .header{
        height: 128px;
        width:100%;
        background-image: url(/static/images/header.jpg);
        background-size: cover;
        
    }
    .logo{
        height:18%;
        width: 10%;
        position:absolute;
        background-image: url(/static/images/icon.png);
        background-size:cover;
        
    }
    .prod{
        height:auto;
        width:auto;
        position:relative;
        bottom:10px;
        left:550px;
        border:4px solid transparent;
        text-align:center;
        display: inline;
        padding:15px;
        font-family:'Gill Sans MT';
        font-size: large;  
    }
    .prod:hover{
        background-color:red;
    }
    .people{
        height:auto;
        width:auto;
        position:relative;
        bottom:10px;
        left:700px;
        border:4px solid transparent;
        text-align:center;
        display: inline;
        padding:15px;
        font-family:'Gill Sans MT';
        font-size: large;  
    }
    .people:hover{
        background-color:red;
    }
    .contact{
        height:20px;
        width:10%;
        position:relative;
        bottom:45px;
        left:1000px;
        border:4px solid transparent;
        text-align:center;
        padding:15px;
        font-family:'Gill Sans MT';
        font-size: large;  
    }
    .contact:hover{
        background-color:red;
    }
            
    .h{
        height:20px;
        width:10%;
        position:relative;
        top:30px;
        left:200px;
        border:4px solid transparent;
        text-align:center;
        
        padding:15px;
        font-family:'Gill Sans MT';
        font-size: large;  
    }
    .h:hover{
        background-color:red;
        overflow:hidden;
    }
    .footer{
        border: 15px solid red;
        width:98%;
        height:10px;
        position:relative;
        bottom: 1px;
        background-color:red;
        text-align:center;

    }
    .title{
        border:2px solid pink;
        background-color:yellow;
        padding:1px;
        width:99.7%;
        height: 70px;
        text-align:center;
        font-family:'Impact';
        margin-left:auto;
        margin-right: auto;
        
    }
    .content{
        border:1px solid red;
        background-color: white;
        width:98%;
        height:400px;
        padding:10px;
        margin-left:auto;
        margin-right:auto;

    }
    
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         Chennai, TamilNadu, India.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 1234567890</li>
                        <li><b>Mobile</b>: 6374663434</li>
                        <li><b>Facebook</b>: fb/SJsoft</li>
                        <li><b>Email Id:</b>jeeva8124@gmail.com</li>
                    </ul>
                    <div style="text-align: center;color:violet;font-size:20px;"><b>Use our services and code Yourself!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by JEEVANANDAM M</footer></div>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:
### home.html
![Screenshot (12)](https://github.com/jeeva078/softweb/assets/147048597/73198a50-eb1b-4e6f-ab8a-330d5187c290)
### product.html
![Screenshot (13)](https://github.com/jeeva078/softweb/assets/147048597/72157373-c5a1-4960-9f19-ca0fff3b071a)
### people.html
![Screenshot (14)](https://github.com/jeeva078/softweb/assets/147048597/2fe53169-5072-41dc-b4c9-672a1f8b9460)
### contact.html
![Screenshot (15)](https://github.com/jeeva078/softweb/assets/147048597/d5b774fa-59d1-4700-8c2e-5cce681e88cf)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
