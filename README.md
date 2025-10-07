# Ex.07 Restaurant Website
## Date:07-10-2025

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
~~~
restaurant.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>World Wonders - Home</title>
  <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        background: #e43f0d;
        color: #504343; 
    }
    header {
        background: #e30721;
        color: white;
        padding: 20px;
        text-align: center;
    }
    nav a {
        color: white;
        margin: 0 15px;
        text-decoration: none;
        font-weight: bold;
   }
    nav a:hover { 
        text-decoration: underline;
   }
    main {
        padding: 20px;
        text-align: center;
     }
    footer { 
        background: #2c3e50;
        color: white;
        text-align: center;
        padding: 10px;
     }
  </style>
</head>
<body>
  <header>
    <h1>World Wonders</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact Us</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>
  <main>
    <h2>Welcome to World Wonders!</h2>
    <p>The joy that food brings.</p>
  </main>
  <footer>
    <p>&copy; 2025 World Wonders</p>
  </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>World Wonders - Menu</title>
  <style>
    body { font-family: Arial; margin: 0; background: #fffaf2; color: #333; }
    header { background: #22e6e3; color: white; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    .menu-items { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; padding: 40px; }
    .dish { background: #fce5cd; width: 250px; padding: 15px; border-radius: 10px; text-align: center; }
    .dish img { width: 100%; height: 160px; object-fit: cover; border-radius: 8px; }
    footer { background: #066162; color: white; text-align: center; padding: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>World Wonders</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact Us</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>
  <h2>Our menu</h2>
  <div class="menu-items">
    <div class="dish">
      <img src="Screenshot 2025-10-07 190943.png" alt="Killi Parotta" />
      <h3>KIlli Parotta </h3>
      <p> Tasty and spicy - ₹250</p>
    </div>
    <div class="dish">
      <img src="Screenshot 2025-10-07 191150.png" alt="Masala Dosa" />
      <h3>Masala Dosa</h3>
      <p> soft and tasty - ₹180</p>
    </div>
    <div class="dish">
      <img src="c:\Users\KANISHKA\OneDrive\Pictures\Screenshots\Screenshot 2025-10-07 201100.png" alt="Biryani" />
      <h3>Chicken Biryani</h3>
      <p> Hot and spicy - ₹200</p>
    </div>
    <div class="dish">
      <img src="Screenshot 2025-10-07 194627.png" alt="Tomato Soup" />
      <h3>Tomato Soup</h3>
      <p>hot and spicy - ₹40</p>
    </div>
  </div>
  <footer>
    <p>&copy; 2025 World Wonders</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>World Wonders - Contact</title>
  <style>
    body { 
        font-family: Arial; 
        margin: 0; 
        background: #fffaf2; 
        color: #333; 
    }
    header { 
        background: #07b0b0; 
        color: white; 
        padding: 20px; 
        text-align: center;
     }
    nav a { 
        color: white; 
        margin: 0 15px; 
        text-decoration: none; 
        font-weight: bold;
     }
    nav a:hover { 
        text-decoration: underline; 
    }
    main {
        padding: 20px; 
        max-width: 500px; 
        margin: auto;
     }
    form {
        margin-top: 20px; 
        }
    label, input, textarea {
        display: block; 
        width: 100%; 
        margin-bottom: 15px; 
    }
    input, textarea {
        padding: 8px; 
        border: 1px solid #ccc; 
        border-radius: 4px; 
    }
    button { 
        background: #e67e22; 
        color: white; 
        padding: 10px 20px; 
        border: none; 
        cursor: pointer;
     }
    button:hover {
        background: #00a9d3;
     }
    footer {
        background: #0e70ad; 
        color: white; 
        text-align: center; 
        padding: 10px;
     }
  </style>
</head>
<body>
  <header>
    <h1>World Wonders</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact Us</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>
  <main>
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" required>

      <label for="message">Message:</label>
      <textarea id="message" rows="5" required></textarea>

      <button type="submit">Send</button>
    </form>
  </main>
  <footer>
    <p>&copy; 2025 World Wonders</p>
  </footer>
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Login - World Wonders</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #fffaf2;
      color: #333;
    }
    header {
      background: #2206c3;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 40px;
      max-width: 400px;
      margin: auto;
      background: #ffffff;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 10px;
      margin-top: 60px;
    }
    h2 {
      text-align: center;
      margin-bottom: 30px;
    }
    label {
      font-weight: bold;
      display: block;
      margin-bottom: 5px;
    }
    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      width: 100%;
      background: #1409b3;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #1215d0;
    }
    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Earth Kitchen</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact Us</a>
      <a href="admin.html">Admin</a>
    </nav>
  </header>

  <main>
    <h2>Admin Login</h2>
    <form>
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>

      <button type="submit">Login</button>
    </form>
  </main>

  <footer>
    <p>&copy; 2025 World Wonders</p>
  </footer>
</body>
</html>
~~~
## OUTPUT:

![alt text](<Screenshot 2025-10-07 201446-1.png>)

![alt text](<Screenshot 2025-10-07 201507.png>)

![alt text](<Screenshot 2025-10-07 201621.png>)

![alt text](<Screenshot 2025-10-07 201655.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
