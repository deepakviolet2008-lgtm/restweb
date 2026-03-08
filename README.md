# Ex.06 Restaurant Website
## Date:08.03.2026
# ref no:25018314

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
        <title>Taj Hotel</title>
        <style>
            .container
{
    background-image: url("taj1.jpg");
    background-size:cover;
    background-position:center;
    height: 650px;
    padding:20px;
}
.navbar
{
    background:white;
    width:420px;
    padding:10px;
    float:right;
    text-align:center;
}
.navbar a
{
    margin:15px;
    color:black;
    text-decoration:underline;
    font-weight:bold;
}
.para
{
    margin-top:120px;
    margin-left:40px;
}
.para h1
{
    color: gold;
}
.para h2
{
    color: white;
}
.quote
{
    color:yellow;
    text-align:center;
    font-style:italic;
    margin-top:30px;
}
.p1
{
    color:yellow;
    text-align:center;
    margin-top:10px;
}
.image
{
    display:flex;
    justify-content:space-evenly;
    gap:40px;
    margin-top:40px;
}
.image img
{
    width:450px;
    height:260px;
    border-radius:5px;
}
footer
{
    text-align:center;
    padding:10px;
    background:cyan;
}
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="rest.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>TAJ  HOTEL</h1>
                <h2>Taj Hotels focusing on authenticity, sustainability, and luxury.</h2>
                <h3 class="quote">"A signature warmth, legendary hospitality, and iconic, regal experiences."</h3>
                <p class="p1">Taj Hotels, founded in 1903 by Jamsetji Tata, is a renowned chain of luxury hotels and a subsidiary of the Indian Hotels Company Limited (IHCL). </p>
            </div>
            <div class="image">
                <img src="taj2.jpg">
                <img src="taj3.jpg">
            </div>
        </div>
        <footer>
            DEEPAK B (25018314)
        </footer>
    </body>
</html>

menu.html

<html>
    <head>
        <title>TAJ HOTEL</title>
        <style>
            .container
            {
                background-image: url("taj1.jpg");
                background-size:cover;
                background-position:center;
                height: 650px;
                padding:20px;
            }
            .navbar
            {
                background:white;
                width:420px;
                padding:10px;
                float:right;
                text-align:center;
            }
            .navbar a
            {
                margin:15px;
                color:black;
                text-decoration:underline;
                font-weight:bold;
            }
            .para
            {
                color: gold;
            }
            .menu-container
            {
                display:flex;
                justify-content:center;
                gap:10px;
            }
            .card
            {
                background:pink;
                padding:20px;
                border-radius:10px;
                text-align:center;
                width:200px;
                margin-top: 100px;
            }
            .card img
            {
                width:140px;
                height:120px;
                border-radius:10px;
            }
            .card h2
            {
                color:blue;
            }
            footer
            {
                text-align:center;
                padding:10px;
                background:cyan;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="rest.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>MENU</h1>
            </div>
            <div class="menu-container">
            <div class="card">
                <img src="menu1.jpeg">
                <h2>Naan</h2>
                <p>Rs.300</p>
            </div>
            <div class="card">
                <img src="menu2.jpg">
                <h2>Briyani</h2>
                <p>Rs.500</p>
            </div>
            <div class="card">
                <img src="menu3.jpg">
                <h2>Panner Masala</h2>
                <p>Rs.350</p>
            </div>
            <div class="card">
                <img src="menu4.jpg">
                <h2>Pizza</h2>
                <p>Rs.400</p>
            </div>
            <div class="card">
                <img src="menu5.jpg">
                <h2>Pan cake</h2>
                <p>Rs.300</p>
            </div>
            <div class="card">
                <img src="menu6.jpg">
                <h2>Veg meal</h2>
                <p>Rs.300</p>
            </div>
            <div class="card">
                <img src="menu7.jpg">
                <h2>Masala Dosa</h2>
                <p>Rs.250</p>
            </div>
            <div class="card">
                <img src="menu8.jpg">
                <h2>Sp Meal</h2>
                <p>Rs.700</p>
            </div>
            </div>
        </div>
    </div>
    <footer>
        DEEPAK B (25018314)
    </footer>
    </body>
</html>

admin.html

<html>
    <head>
        <title>TAJ HOTEL</title>
        <style>
            .container
            {
                background-image: url("taj1.jpg");
                background-size:cover;
                background-position:center;
                height: 650px;
                padding:20px;
            }
            .navbar
            {
                background:white;
                width:420px;
                padding:10px;
                float:right;
                text-align:center;
            }
            .navbar a
            {
                margin:15px;
                color:black;
                text-decoration:underline;
                font-weight:bold;
            }
            .para
            {
                color: gold;
            }
            .admin-container
            {
                display:flex;
                justify-content:center;
                gap:20px;
            }
            .card
            {
                background:white;
                padding:20px;
                border-radius:10px;
                text-align:center;
                width:180px;
                height:300px;
                margin-top: 100px;
            }
            .card img
            {
                width:180px;
                height:200px;
                border-radius:10px;
            }
            .card h2
            {
                color:orange;
            }
            footer
            {
                text-align:center;
                padding:10px;
                background:cyan;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="rest.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>MANAGEMENT TEAM</h1>
            </div>
            <div class="admin-container">
            <div class="card">
                <img src="deepakimg.jpeg">
                <h2>DEEPAK</h2>
                <p>CEO</p>
            </div>
            <div class="card">
                <img src="emilia-clarke.jpg">
                <h2>Emilia Clarke</h2>
                <p>manager</p>
            </div>
            <div class="card">
                <img src="vijay.jpg">
                <h2>Vijay</h2>
                <p>HR</p>
            </div>
            <div class="card">
                <img src="chef damu.webp">
                <h2>Damu</h2>
                <p>Chef</p>
            </div>
            <div class="card">
                <img src="chris.jpg">
                <h2>chris</h2>
                <p>cheif Manager</p>
            </div>
            <div class="card">
                <img src="samantha.webp">
                <h2>Samantha</h2>
                <p>Customer service manager</p>
            </div>
            </div>
        </div>
    </div>
    <footer>
        DEEPAK B (25018314)
    </footer>
    </body>
</html>

contact.html

<html>
    <head>
        <title>Taj Hotel</title>
        <style>
            .container
            {
                background-image: url("taj1.jpg");
                background-size:cover;
                background-position:center;
                height: 650px;
                padding:20px;
            }
            .navbar
            {
                background:white;
                width:420px;
                padding:10px;
                float:right;
                text-align:center;
            }
            .navbar a
            {
                margin:15px;
                color:black;
                text-decoration:underline;
                font-weight:bold;
            }
            .para h1
            {
                color:gold;
            }
            .para h2
            {
                color:aqua;
            }
            .para p
            {
                color: white;
            }
            footer
            {
                text-align:center;
                padding:10px;
                background:cyan;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="navbar">
                <a href="rest.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>
            <div class="para">
                <h1>Contact</h1>
                <h2>Visit us at:</h2>
                <p>Taj Hotel,<p>
                <p>Taj Street,</p>
                <p>Chennai</p>
                <h2>Phone:</h2>
                <p>+91 9700097555</p>
                <h2>Email ID:</h2>
                <p>Tajhotel143@gmail.com</p>
            </div>
        </div>
        <footer>
            DEEPAK B (25018314)
        </footer>
    </body>
</html>
```
## OUTPUT:

![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
