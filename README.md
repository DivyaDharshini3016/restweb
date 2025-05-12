# Ex.07 Restaurant Website
## Date:10.04.2025

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
# index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="styles2.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <!-- Updated to show only the image -->
            <img src="logo.png" alt="Little Lemon Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Promotional Banner -->
        <section class="promo-banner">
            <h2>30% Off This Weekend</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
        </section>

        <!-- Content Columns -->
        <section class="content-columns">
            <article class="column">
                <h3>Our New Menu</h3>
                <img src="lemonrice.jpeg" alt="New Menu">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
                <a href="#">See our new menu</a>
            </article>

            <article class="column">
                <h3>Book a Table</h3>
                <img src="watermelon.jpeg" alt="Book a Table">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
                <a href="#">Book your table now</a>
            </article>

            <article class="column">
                <h3>Opening Hours</h3>
                <img src="chief.jpeg" alt="Opening Hours">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris.</p>
                <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
            </article>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <div class="footer-logo">
            <img src="small logo.png" alt="Little Lemon Logo">
        </div>
        <div class="footer-text">
            <p>© 2024 Little Lemon</p>
        </div>
    </footer>
</body>
</html>
```
# styles.css
```
/* General Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    color: #333;
}

header, footer {
    background-color: #fff;
    padding: 20px;
    border-bottom: 1px solid #ddd;
}

/* Logo Section */
.logo {
    display: flex;
    align-items: center;
    justify-content: center; /* Center the logo */
    padding: 20px;
}

.logo img {
    max-width: 450px; /* Adjust the logo size as needed */
    height: auto;
}

/* Navigation Styling */
nav {
    background-color: #000; /* Black background */
    display: flex;
    justify-content: center; /* Center the content inside the nav */
    border-radius: 10px; /* Rounded corners */
}

nav ul {
    list-style: none;
    display: flex;
    padding: 0;
    margin: 0;
}

nav li {
    flex: none; /* Do not stretch menu items */
}

nav a {
    display: block;
    text-decoration: none;
    color: #fff; /* White text color */
    padding: 10px 20px;
    text-align: center;
    transition: background-color 0.3s;
}

nav a:hover {
    background-color: #333; /* Slightly darker hover effect */
}

/* Full-width Black Box Stretch */
header {
    width: 100%;
}

main {
    padding: 20px;
}

/* Promotional Banner */
.promo-banner {
    background: url("promo\ banner.jpeg") center/cover no-repeat;
    color: #fff;
    text-align: center;
    padding: 50px 20px;
    margin-bottom: 20px;
    border-radius: 10px;
}

/* Content Columns */
.content-columns {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.column {
    flex: 1;
    background-color: #ffcd7c;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.column img {
    width: 70%;
    height: auto;
    border-radius: 10px;
    margin-bottom: 10px;
}

.column h3 {
    margin-top: 10px;
    font-size: 1.2em;
}

.column a {
    display: inline-block;
    margin-top: 10px;
    text-decoration: none;
    color: #0066cc;
    transition: color 0.3s;
}

.column a:hover {
    color: #004d99;
}

/* Footer */
footer {
    display: flex;
    justify-content: space-between;
    padding: 20px;
}

.footer-logo img {
    width: 100px;
}

.footer-text {
    display: flex;
    align-items: center;
    color: #777;
}
```
## OUTPUT:
![Screenshot 2025-04-20 053026](https://github.com/user-attachments/assets/d3855d7c-d2c6-4875-9c53-dfa58bdc7444)

![Screenshot 2025-04-20 053603](https://github.com/user-attachments/assets/eaa2195b-04a4-44a8-a9b9-0b132498161b)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
