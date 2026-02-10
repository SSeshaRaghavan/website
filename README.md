# Ex.06 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mom's Munch Box - Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1400&q=80" alt="Restaurant Banner" class="banner">
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Welcome to Mom's Munch Box</h1>
    <p>A Restaurant To Relish</p>

    <section class="hero-banner">
      <h2>30% Off This Weekend!</h2>
    </section>

    <section class="features">
      <div class="feature-box">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046751.png" alt="New Menu">
        <h2>Our New Menu</h2>
        <p>Explore our latest dishes that satisfy every craving.</p>
        <a href="menu.html">See Menu</a>
      </div>

      <div class="feature-box">
        <h2>Book a Table</h2>
        <p>Reserve your spot and enjoy great dining experiences.</p>
        <a href="contact.html">Book Now</a>
      </div>

      <div class="feature-box">
        <img src="https://cdn-icons-png.flaticon.com/512/2553/2553691.png" alt="Opening Hours">
        <h2>Opening Hours</h2>
          <p>
            Mon - Fri: 2pm - 10pm<br>
            Sat: 2pm - 11pm<br>
            Sun: 2pm - 9pm
          </p>
        </div>
      </section>
    </main>
  
    <footer>
      <p>Created by S Sesha Raghavan (212224040302)</p>
    </footer>
  </body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Delish Bites</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>Contact Us</h1>
    <p>Address: 149 Arignar Anna Salai Street, Co-operative Nagar, Phase-4, Thiruverkadu, Chennai-600077</p>
    <p>Phone: +91 6366464433</p>
    <p>Email: contact@momsmunchbox.com</p>
  </main>
  <footer>
    <p>Created by S Sesha Raghavan (212224040302)</p>
  </footer>
</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Delish Bites</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>Our Menu</h1>
    <div class="menu-grid">
      <div class="menu-item">
        <img src="https://img.freepik.com/free-psd/delicious-veggie-pizza-freshly-baked-toppings-cheese-mushrooms-peppers-olives_84443-37364.jpg" alt="Pizza">
        <p>Pizza - ₹150</p>
      </div>
      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1550547660-d9450f859349?auto=format&fit=crop&w=800&q=80" alt="Burger">
        <p>Burger - ₹120</p>
      </div>
      <div class="menu-item">
        <img src="https://img.freepik.com/free-psd/delicious-pasta-spaghetti-bowl-transparent-background_84443-27509.jpg" alt="Pasta">
        <p>Pasta - ₹100</p>
      </div>
      <div class="menu-item">
        <img src="https://img.pikbest.com/origin/10/09/44/55zpIkbEsTKau.png!w700wp" alt="Fries">
        <p>Fries - ₹70</p>
      </div>
      <div class="menu-item">
        <img src="https://img.pikbest.com/png-images/20240728/salad-healthy-green-vegetable-bowl-nutritious-_10685144.png!bw700" alt="Salad">
        <p>Salad - ₹50</p>
      </div>
      <div class="menu-item">
        <img src="https://png.pngtree.com/png-vector/20240802/ourmid/pngtree-yummy-and-delicious-chicken-corn-soup-png-image_13345659.png" alt="Soup">
        <p>Soup - ₹50</p>
      </div>
      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?auto=format&fit=crop&w=800&q=80" alt="Tacos">
        <p>Tacos - ₹90</p>
      </div>
      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1501443762994-82bd5dabb892?auto=format&fit=crop&w=800&q=80" alt="Ice Cream">
        <p>Ice Cream - ₹95</p>
      </div>
      <div class="menu-item">
        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=800&q=80" alt="Cake">
        <p>Cake - ₹450</p>
      </div>
      <div class="menu-item">
        <img src="https://static.vecteezy.com/system/resources/previews/047/490/432/non_2x/colorful-fruit-smoothies-isolated-on-a-transparent-background-free-png.png" alt="Smoothie">
        <p>Smoothie - ₹165</p>
      </div>
      <div class="menu-item">
        <img src="https://www.budgetbytes.com/wp-content/uploads/2024/06/Grilled-Chicken-Overhead-500x500.jpg" alt="Grilled Chicken">
        <p>Grilled Chicken - ₹210</p>
      </div>
      <div class="menu-item">
        <img src="https://www.chefkunalkapur.com/wp-content/uploads/2022/03/paneer-kulcha-roll-scaled.jpg?v=1647833164" alt="Paneer Wrap">
        <p>Paneer Wrap - ₹140</p>
      </div>
    </div>
  </main>
  <footer>
    <p>Created by S Sesha Raghavan (212224040302)</p>
  </footer>
</body>
</html>
```
admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Mom's Munch Box</title>
  <link rel="stylesheet" href="style.css">
</head>
<body class="background">
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Our Team</h1>
    <div class="team-grid">
      <div class="team-member">
        <img src="https://images.unsplash.com/photo-1583394293214-28dea15ee548?auto=format&fit=crop&w=400&q=80" alt="Vijayalakshmi">
        <p><strong>Vijayalakshmi</strong><br>Head Chef</p>
      </div>
      <div class="team-member">
        <img src="https://images.unsplash.com/photo-1560250097-0b93528c311a?auto=format&fit=crop&w=400&q=80" alt="S Sesha Raghavan">
        <p><strong>S Sesha Raghavan</strong><br>Manager</p>
      </div>
      <div class="team-member">
        <img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?auto=format&fit=crop&w=400&q=80" alt="Ali">
        <p><strong>Ali</strong><br>Assistant Chef</p>
      </div>
      <div class="team-member">
        <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=400&q=80" alt="Kavya">
        <p><strong>Kavya</strong><br>Waitress</p>
      </div>
    </div>
  </main>

  <footer>
    <p>Created by S Sesha Raghavan (212224040302)</p>
  </footer>
</body>
</html>
```
style.css
```
* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
body { background-color: #f4f4f4; color: #333; }

header { background-color: #222; padding: 0; text-align: center; }
.banner { width: 100%; max-height: 300px; object-fit: cover; }

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  background-color: #333;
  padding: 10px 0;
}

nav ul li { margin: 0 15px; }

nav ul li a {
  color: #fff;
  text-decoration: none;
  padding: 12px 18px;
  display: inline-block;
}

nav ul li a:hover {
  background-color: #555;
  border-radius: 5px;
}

main { text-align: center; padding: 30px 20px; }
main h1 { font-size: 2.5rem; margin-bottom: 10px; }
main p { font-size: 1.2rem; margin-bottom: 30px; color: #666; }

.hero-banner {
  position: relative;
  margin-bottom: 40px;
  height: 200px;
  background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1400&q=80') center/cover;
  border-radius: 10px;
}

.hero-banner h2 {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  font-size: 2rem;
  background: rgba(0, 0, 0, 0.5);
  padding: 15px 30px;
  border-radius: 8px;
}

.features, .menu-grid, .team-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  max-width: 1200px;
  margin: 0 auto;
}

.feature-box, .menu-item, .team-member {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  width: 300px;
  padding: 20px;
  text-align: center;
}

.feature-box img, .menu-item img, .team-member img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 8px;
  margin-bottom: 15px;
}

.feature-box a {
  display: inline-block;
  margin-top: 10px;
  text-decoration: none;
  background-color: #e67e22;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
}

.feature-box a:hover { background-color: #d35400; }

footer {
  background-color: #222;
  color: #ccc;
  text-align: center;
  padding: 15px;
  margin-top: 50px;
}
```
# OUTPUT:
![alt text](<Screenshot 2026-02-10 080717.png>) 
![alt text](<Screenshot 2026-02-10 080739.png>) 
![alt text](<Screenshot 2026-02-10 080752.png>) 
![alt text](<Screenshot 2026-02-10 082328.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
