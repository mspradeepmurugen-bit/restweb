# Ex.06 Restaurant Website
## Date:21/12/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
```
rest.html
<html>
    <head>
        <title>Home</title>
        <link href="homes.css" rel="stylesheet">


    </head>
    <body>
        <div class="header">
            <h1>SP RESTAURANT</h1>
            <div class="sub">
                <p>"The Place of Fine Food"</p>
            </div>
           
        </div>
        <div class="nav">
            <a href="menu.html"  >MENU</a>
            <a href="admin.html" >ADMIN </a>
            <a href="contact.html" >CONTACT</a>


        </div>
        <br>
        <br>

        <div class="content">
            <p>Traditional TamilNadu techniques, crafted with modern elegance.</p>
            <p>Where classic TamilNadu flavours meet modern creativity.</p>
        </div>
        <br>
        <br>
        <div class="one">
            <img src="to1.jpg">
            <img src="to.jpg">
            <img src="to3.jpg">
        </div>
        
        <footer>
            <p>&copy; pradeep .M(25009105) </p>
        </footer>
        

        

    </body>
</html>
menu.html
<html>
    <head>
        <title>
            Menu
        </title>
        <style>
            body
                {
                    background: url("4.jpg") ;
                    background-position: center;
                    background-repeat: no-repeat;
                    background-size: contain;
                    background-size: cover;
                }
            .head 
            {
                padding-left: 50;
                padding-top: 60;
                color: aliceblue;
                font: 'Cormorant Garamond',serif;
                font-size: 23;
            }
            .nav {
                margin-top: 20px;
                text-align: right;

            }
            .nav a {
                color: white;
                text-decoration: none;
                margin-right: 20px;
                font-family: 'Lora', serif;
                letter-spacing: 2px;
            }

            .nav a:hover {
                text-decoration: underline;
            }
            .spe{
                padding-left: 40;
                font-weight: bolder;
                font-size: 26;
                font-family: 'Lora', serif;
                color: aliceblue;
            }
            footer
            {
                text-align: center;
                background-color: rgba(243, 220, 195, 0.8) ;
                margin-top: 60;
                height:15;
            }
            .cont {
                display: flex;
                gap: 80px;
                padding: 0 60px;
            }
            .items {
                background:rgba(243, 220, 195, 0.8);
                width: 250px;
                border-radius: 15px;
                padding: 10px;
                text-align: center;
            }
            .items img {
                width: 100%;
                height: 130px;
                object-fit: cover;
                border-radius: 10px;
            }

            .items h3 {
                margin: 10px 0 5px;
            }

            .items p {
                font-size: 14px;
            }


            
        </style>
    </head>
    <body>
        <div class="head">
            <h1>MENU</h1>
        </div>
        <div class="nav">
            <a href="rest.html"  >HOME</a>
            <a href="admin.html" >ADMIN </a>
            <a href="contact.html" >CONTACT</a>
        </div>
        <hr>
        <div class="spe">
            <p>Today's Special</p>
        </div>
        
        
        <div class="cont">
            <div class="items">
                <img src="me.jpg">
                <h3>chickenbriyani</h3>
                <p>Rs.510</p>
            </div>
            <div class="items">
                <img src="me1.jpg">
                <h3>fish fry</h3>
                <p>Rs.400</p>
            </div>
            <div class="items">
                <img src="me3.jpg">
                <h3>full meals</h3>
                <p>Rs.500</p>
            </div>
            <div class="items">
                <img src="me4.jpg">
                <h3>Chicken Steak</h3>
                <p>Rs.320</p>
            </div>
            <div class="items">
                <img src="e.jpg">
                <h3>Classic Tiramisu</h3>
                <p>Rs.200</p>
            </div>
        

      

        </div>
        <hr>
        <br>
        <div class="spe">
            <p>Special dinner</p>
        </div>
        <div class="cont">
            <div class="items">
                <img src="me5.jpg">
                <h3>dosa</h3>
                <p>Rs.170</p>
            </div>
             <div class="items">
                <img src="me7.jpg">
                <h3>idly</h3>
                <p>Rs.150</p>
            </div>
             <div class="items">
                <img src="me8.jpg">
                <h3>poori</h3>
                <p>Rs.140</p>
            </div>

        </div>
        <hr>
        <footer>
            <p>&copy; pradeep.m(25009105) </p>
        </footer>
        
    </body>
</html>
admin.hhtml
<html>
    <head>
        <title>
            admin
        </title>
        <style>
            body {
                background-image: url("homepage.jpg");
                background-position: center;
                background-repeat: no-repeat;
                background-size: contain;
                background-size: cover;
            }
            body h1 {
                color: blanchedalmond;
                font-size: 45;
                padding-left: 60;
                padding-top: 100;
                font-weight: bolder;
            }
            .nav {
                margin-top: 20px;
                text-align: right;
                background-color: rgba(243, 220, 195, 0.8) ;

            }
            .nav a {
                color: white;
                text-decoration: none;
                margin-right: 20px;
                font-family: 'Lora', serif;
                letter-spacing: 2px;
            }

            .nav a:hover {
                text-decoration: underline;
            }
            .team {
                display: flex;
                justify-content: center;
                align-items: flex-start;
                gap: 30px;

                max-width: 1200px;
                margin: 80px auto;

                flex-wrap: wrap;   
            }

            .role {
                background: #fbf7da;
                width: 230px;
                padding: 25px 15px;
                border-radius: 12px;
                text-align: center;
            }

            .role img {
                width: 160px;
                height: 160px;
                border-radius: 50%;
                object-fit: cover;
            }
            .role h3 {
                margin-top: 15px;
            }

            .role span {
                font-size: 14px;
                color: #333;
            }

            footer
            {
                text-align: center;
                background-color: rgba(243, 220, 195, 0.8) ;
            }

            

        </style>

    </head>
    <body>
        <h1>ADMINSTRATION TEAM</h1>
        <div class="nav">
            <a href="menu.html"  >MENU</a>
            <a href="admin.html" >ADMIN </a>
            <a href="contact.html" >CONTACT</a>


        </div>
        <hr>
        <div class="team">

            <div class="role">
                <img src="m5.jpeg">
                <h3></pradeep></h3>
                <span>Founder & CEO</span>
            </div>

            <div class="role">
                <img src="m.jpg">
                <h3>Abhyankar</h3>
                <span>Executive Chef</span>
            </div>

            <div class="role">
                <img src="m6.jpg">
                <h3>Vijay</h3>
                <span>Restaurant Manager</span>
            </div>

            <div class="role">
                <img src="m8.jpg">
                <h3>abinesh</h3>
                <span>Marketing Head</span>
            </div>

            <div class="role">
                <img src="pr.jpg">
                <h3> Raganathan</h3>
                <span>HR & Staff Manager</span>
            </div>

            <div class="role">
                <img src="mam.jpg">
                <h3>Mamitha Baiju</h3>
                <span>Customer Service Manager</span>
            </div>

            
            </div>
        </div>
        <hr>
        <footer>
            <p>&copy; pradeep.m(25009105) </p>
        </footer>

    </body>
</html>
ontact.html
<html>
    <head>
        <title>
            contact
        </title>
        <style>
            body{
                background-image: url("z.jpeg");
                background-position: center;
                background-repeat: no-repeat;
                background-size: contain;
                background-size: cover;
            }
            .nav {
                margin-top: 20px;
                text-align: right;

            }
            .nav a {
                color: white;
                text-decoration: none;
                margin-right: 20px;
                font-family: 'Lora', serif;
                letter-spacing: 2px;
                font-weight: bolder;
            }

            .nav a:hover {
                text-decoration: underline;
            }
            body h1{
                font-size: 50;
                color: aliceblue;
                padding-top: 100;
                padding-left: 60;
            }
            .he {
                font-size: 30;
                color:aliceblue;
                line-height: 1;
                padding-left: 60;
                
            }
            .sub {
                font-size: 20;
                padding-left: 80;
                color: aliceblue;
                line-height: 1;
                margin: 0;
                font-weight: bolder;
                
            }
            footer
            {
                text-align: center;
                background-color: rgba(243, 220, 195, 0.8) ;
                margin-top: 190;
            }

        </style>
    </head>
    <body>
        <h1> CONTACT US</h1>
        <div class="nav">
            <a href="rest.html" >HOME</a>

            <a href="menu.html"  >MENU</a>
            <a href="admin.html" >ADMIN </a>
            

        </div>
        <hr>
        <div class="he">
            <h3>Visit Us At:</h3>
        </div>
        
        <p class="sub">'sp Restaurant'</p>
        <p class="sub">Level 1, The Grand Arcade
        <p class="sub">south Main Street, Opp. ragava store</p>
        <p class="sub">pudukkottai  570001</p>
        <p class="sub">TamilNadu, India'</p>
        
        <br>
        <div class="he">
            <h3>Phone:</h3>
        </div>
        <div class="sub">
            <p>+91 98765 43210</p>
        </div>
        <div class="he">
            <h3>Email ID:</h3>
        </div>
        <div class="sub">
            <p>sprestaurant@gmail.com</p>
        </div>
        <hr>

        <footer><p>&copy; pradeep.m (25009105) </p></footer>

    </body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2025-12-23 223730-1.png>) ![alt text](<Screenshot 2025-12-23 223851-1.png>) ![alt text](<Screenshot 2025-12-23 223925-1.png>) ![alt text](<Screenshot 2025-12-23 224008-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
