# Ex.06 Restaurant Website
## Date:24-12-2025

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
home.html
```
<html>
<head>
    <title>Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="heading">ADHITYA BHAVAN</h1>

    <p style="margin-left:60px;font-size:24px;">The taste of india!</p>
    <p style="margin-left:60px;font-size:18px;max-width:800px;">
        Welcome to Adhitya Bhavan, a vibrant space where authentic Indian flavors come alive.
Our signature Butter Chicken steals the spotlight with its creamy, spiced perfection.
Crispy Masala Dosa and smoky Paneer Tikka add variety to your feast.
Fragrant Hyderabadi Biryani brings tradition to every plate.
And for a sweet finale, melt in your mouth Gulab Jamun awaits.
    </p>

    <div class="cards">
        <div class="card">
            <img src="HOME 1.jpg">
        </div>
        <div class="card">
            <img src="HOME 3.JPEG">
        </div>
    </div>

    <div class="footer">
        © R P yuvan raj r - (25014899)
    </div>

</div>
</body>
</html>
```
menu.html
```
<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="heading">MENU</h1>

    <div class="cards">
        <div class="card">
            <img src="butterchi.jpg">
            <h3>butter Chicken</h3>
            <p>Rs. 290</p>
        </div>

        <div class="card">
            <img src="masaladosa.jpg">
            <h3>masala dosa</h3>
            <p>Rs. 80</p>
        </div>

        <div class="card">
            <img src="gulab.jpeg">
            <h3>gulab jamun</h3>
            <p>Rs. 200</p>
        </div>

        <div class="card">
            <img src="biryani.jpg">
            <h3>hyderabad biriyani</h3>
            <p>Rs. 220</p>
        </div>
    </div>

    <div class="footer">
        © R P yuvan raj r - (25014899)
    </div>

</div>
</body>
</html>
```
admin.html
```
<html>
<head>
    <title>Admin</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h2 class="heading">ADMINISTRATION TEAM</h2>

    <div class="cards">
        <div class="card">
            <img src="tezm ceo.jpeg">
            <h3>yuvan raj R</h3>
            <p>CEO</p>
        </div>

        <div class="card">
            <img src="team1.jpeg">
            <h3>MADHAN GOWRI</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="card">
            <img src="team2.jpg">
            <h3>OMESHWAR</h3>
            <p>Operations Manager</p>
        </div>

        <div class="card">
            <img src="team3.jpeg">
            <h3>NIRANJAN</h3>
            <p>HR Manager</p>
        </div>
    </div>

    <div class="footer">
        © R P yuvan raj r - (25014899)
    </div>

</div>
</body>
</html>
```
contact.html
```
<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">

    <div class="navbar">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </div>

    <h1 class="heading">CONTACT</h1>

    <div style="margin-left:60px;font-size:20px;background-color: cornsilk;color: brown;">
        <p><b>Visit us at:</b></p>
        <p>Adhitya Bhavan<br>
           23,german street,<br>
           nazi state road,koyambedu.<br>
           India</p>

        <p><b>Phone:</b><br>+91 98765 43210</p>
        <p><b>Email ID:</b><br>adihbhav123@gmail.com</p>
    </div>

    <div class="footer">
       © R P yuvan raj r - (25014899)
    </div>

</div>
</body>
</html>
```
styles.css
```
body {
    margin: 0;
    font-family: Georgia, serif;
    background-color: #000;
}


.hero {
    background-image: url("BG 2.JPEG"); 
    background-size: cover;
    background-position: center;
    min-height: 100vh;
    color: #fff;
    position: relative;
}


.navbar {
    position: absolute;
    top: 20px;
    right: 40px;
    background: #f5f9ff;
    padding: 15px 40px;
    border: 2px solid #000;
}

.navbar a {
    margin: 0 20px;
    text-decoration: underline;
    color: purple;
    font-weight: bold;
}


.heading {
    font-size: 50px;
    color: #023232;
    margin: 120px 0 20px 60px;
    letter-spacing: 4px;
    background-color: blanchedalmond;
}


.cards {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin-top: 40px;
}


.card {
    background: #f8f6dc;
    width: 220px;
    padding: 20px;
    border-radius: 15px;
    text-align: center;
}

.card img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
}


.card h3 {
    margin: 15px 0 5px;
    color: #140101;
}

.card p {
    margin: 0;
    color: #140101;
}


.footer {
    position: absolute;
    bottom: 10px;
    width: 100%;
    text-align: center;
    font-size: 14px;
    color: #140101;
    background-color: burlywood;
}
```


## OUTPUT:
home
![alt text](<Screenshot 2025-12-26 104709.png>)

menu
![alt text](<Screenshot 2025-12-26 104725.png>)
admin team
![alt text](<Screenshot 2025-12-26 104742.png>)
contact
![alt text](<Screenshot 2025-12-26 104801.png>)

## RESULT:
The program for designing RESTAURANT website using HTML and CSS is completed successfully.
