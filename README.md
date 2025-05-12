# Ex.07 Restaurant Website
## Date:11-03-2025
## NAME: GOWTHAM N
## REG NO:212222220013

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - BITE ME</title>
</head>
<body style="margin:0; font-family:sans-serif; background: linear-gradient(to right, #071258, #329faf); color:white;">

  <header style="padding:20px; text-align:center;">
    <h1 style="margin-bottom:10px; font-size:36px;">Welcome to BITE ME</h1>
    <nav>
      <a href="index.html" style="margin:10px; color:white; text-decoration:none;">Home</a>
      <a href="menu.html" style="margin:10px; color:white; text-decoration:none;">Menu</a>
      <a href="admin.html" style="margin:10px; color:white; text-decoration:none;">Administration</a>
      <a href="contact.html" style="margin:10px; color:white; text-decoration:none;">Contact Us</a>
    </nav>
  </header>
  <br>
  <br>

  <main style="display:flex; flex-direction:column; align-items:center; justify-content:center; height:70vh;">
    <img src="biteme.png" alt="Foodie's Hub" style="width:300px; height:auto; display:block; margin-bottom:20px;">
    <h2>Your one-stop destination for delicious food</h2>
    <center><p style="max-width:600px; font-size:16px;">Explore our curated menu and meet the amazing people behind the scenes. Whether you're craving comfort or exotic food — we’ve got you covered.</p></center>

    <div style="margin-top:30px; background:white; padding:20px 40px; border-radius:15px; box-shadow: 0 5px 15px rgba(0,0,0,0.3);">
      <h3 style="color:#05082d;">🛒 Start your flavor journey today!</h3>
      <a href="menu.html" style="margin-top:10px; display:inline-block; padding:10px 20px; background:#b02147; color:white; border-radius:20px; text-decoration:none; font-weight:bold;">View Menu</a>
    </div>
  </main>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Foodie's Hub</title>
</head>
<body style="margin:0; font-family:sans-serif; background: linear-gradient(to right, #d46c0b, #a57829); color:rgb(30, 31, 26);">

  <header style="padding:20px; text-align:center;">
    <h1>Our Delicious Menu</h1>
    <nav>
      <a href="index.html" style="margin:10px; color:white; text-decoration:none;">Home</a>
      <a href="menu.html" style="margin:10px; color:white; text-decoration:none;">Menu</a>
      <a href="admin.html" style="margin:10px; color:white; text-decoration:none;">Administration</a>
      <a href="contact.html" style="margin:10px; color:white; text-decoration:none;">Contact Us</a>
    </nav>
  </header>

  <main style="padding:30px;">
    <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(180px, 1fr)); gap:20px;">
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Pizza</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Burger</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Pasta</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Sushi</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Tacos</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Fried Chicken</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Noodles</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Paneer Tikka</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Salad Bowl</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Biryani</div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">Ice Cream</div>
      <div style="background:white
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Foodie's Hub</title>
</head>
<body style="margin:0; font-family:sans-serif; background: linear-gradient(to right, #0b0e0f, #26002a); color:white;">

  <header style="padding:20px; text-align:center;">
    <h1>Meet Our Team</h1>
    <nav>
      <a href="index.html" style="margin:10px; color:white; text-decoration:none;">Home</a>
      <a href="menu.html" style="margin:10px; color:white; text-decoration:none;">Menu</a>
      <a href="admin.html" style="margin:10px; color:white; text-decoration:none;">Administration</a>
      <a href="contact.html" style="margin:10px; color:white; text-decoration:none;">Contact Us</a>
    </nav>
  </header>

  <main style="padding:30px;">
    <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(200px, 1fr)); gap:20px; text-align:center;">
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">
        <img src="person1.jpg" alt="Vijay" style="width:100px; height:100px; border-radius:50%;"><br>
        <h3>Vijay</h3><p>Manager</p>
      </div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">
        <img src="person2.jpeg" alt="Kamal" style="width:100px; height:100px; border-radius:50%;"><br>
        <h3>Kamal</h3><p>Chef</p>
      </div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">
        <img src="person3.jpeg" alt="Samantha" style="width:100px; height:100px; border-radius:50%;"><br>
        <h3>Samantha</h3><p>Operations</p>
      </div>
      <div style="background:white; color:#333; padding:20px; border-radius:10px;">
        <img src="person4.jpeg" alt="Jennie" style="width:100px; height:100px; border-radius:50%;"><br>
        <h3>Jennie</h3><p>Marketing</p>
      </div>
    </div>
  </main>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Foodie's Hub</title>
</head>
<body style="margin:0; font-family:sans-serif; background: linear-gradient(to right, #3d020a, #081b5c); color:white;">

  <header style="padding:20px; text-align:center;">
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html" style="margin:10px; color:white; text-decoration:none;">Home</a>
      <a href="menu.html" style="margin:10px; color:white; text-decoration:none;">Menu</a>
      <a href="admin.html" style="margin:10px; color:white; text-decoration:none;">Administration</a>
      <a href="contact.html" style="margin:10px; color:white; text-decoration:none;">Contact Us</a>
    </nav>
  </header>

  <main style="padding:30px; text-align:center;">
    <p><strong>📍 Address:</strong> 123 Food Street, Flavor Town, India</p>
    <p><strong>📞 Phone:</strong> +91-9876543210</p>
    <p><strong>📧 Email:</strong> contact@foodieshub.com</p>
  </main>

</body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/48481ee3-5cd2-441f-accf-0f742a5d701b)
![image](https://github.com/user-attachments/assets/38219db9-977a-48d2-8a32-a763aae95aac)
![image](https://github.com/user-attachments/assets/4d1c07d5-5b87-45b4-988b-7a3e23112308)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
