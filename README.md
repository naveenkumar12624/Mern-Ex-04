# Exp-4 Create a Web-Layout using GridBOX.
## AIM:
To write html & css code to create Web-Layout using GridBOX.
## PROCEDURE:
### STEP 1:
Create a html code for the Web-Layout.
### STEP 2:
Make style for the Web Layout using style tag.
### STEP 3:
Include Style in the html using class and id Selector.
### STEP 4:
Verify the output by running the Web-Layout in any web browser. 
## PROGRAM:
### HTML&CSS:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Company Website</title>
  <link rel="stylesheet" href="header.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Welcome to Our Company</h1>
      <p>This is my company welcome quote</p>
      <a href="#" class="btn">Learn More</a>
    </div>
  </section>

  <section class="features">
    <div class="feature">
      <i class="fa fa-cogs"></i>
      <h2>Quality Services</h2>
      <p>this is the Quality Service done by my company</p>
    </div>
    <div class="feature">
      <i class="fa fa-users"></i>
      <h2>Expert Team</h2>
      <p>We are having a Specialized Experts team.</p>
    </div>
    <div class="feature">
      <i class="fa fa-lightbulb-o"></i>
      <h2>Innovation</h2>
      <p>We are industry 5.0 and having high end innovations in 12th gen of technology.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2023 Company Name. All rights reserved.</p>
  </footer>
</body>
</html>
```
## CSS
```css
/* Reset some default styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background-color: #000000;
  color: #fff9f9;
}

header {
  background-color: #dd0909;
  padding: 20px;
}

nav ul {
  list-style-type: none;
}

nav ul li {
  display: inline;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  padding: 10px;
}

.hero {
  background-color: #ab625e;
  padding: 60px;
  text-align: center;
}

.hero-content {
  max-width: 600px;
  margin: 0 auto;
}

.hero h1 {
  font-size: 36px;
  color: #fff;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  color: #fff;
  margin-bottom: 40px;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #fff;
  color: #333;
  text-decoration: none;
  border-radius: 5px;
}

.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 40px;
  padding: 60px;
}

.feature {
  text-align: center;
}

.feature i {
  font-size: 48px;
  color: #f8a738;
  margin-bottom: 20px;
}

.feature h2 {
  font-size: 24px;
  margin-bottom: 20px;
}

.feature p {
  font-size: 16px;
}

footer {
  background-color: #ca1c1c;
  padding: 20px;
  text-align: center;
}

footer p {
  color: #fff;
}

```
## OUTPUT:
![mern-ex4](https://github.com/naveenkumar12624/Mern-Ex-04/assets/93427235/3a08f5bc-8365-44fc-8118-f2c200839d11)

## RESULT:
html & css code to create Web-Layout using GridBOX has been created and output has been verified.
