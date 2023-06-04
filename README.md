# CSS_Task5
README for Horizontal Navbar in HTML with CSS
----------------------------------------------

This README provides instructions on how to create a horizontal navbar in HTML using CSS. Follow these steps to set up and customize your horizontal navbar:

1. HTML Structure:
   - Begin by opening the HTML file where you want to create the horizontal navbar.
   - Inside the `<body>` element, create a `<nav>` element to represent the navbar.
   - Within the navbar element, add `<a>` elements to create the navigation links.
   - Use appropriate IDs or classes for the navbar and links to apply CSS styling later.

2. CSS Styling:
   - Open your CSS file or create a new one.
   - Select the navbar element using its ID or class and apply desired styling. For example:
     ```css
     #navbar {
       background-color: #f2f2f2;
       padding: 20px;
     }
     ```
   - Style the navigation links within the navbar using their IDs or classes. For example:
     ```css
     .nav-link {
       display: inline-block;
       padding: 10px;
       text-decoration: none;
       color: #333;
     }
     ```
   - Customize the styles further by adding properties like font size, font color, hover effects, or other desired attributes.

3. Apply CSS to HTML:
   - In your HTML file, link the CSS file by adding the following line of code within the `<head>` section:
     ```html
     <link rel="stylesheet" href="path/to/your/css-file.css">
     ```
   - Replace `"path/to/your/css-file.css"` with the actual path to your CSS file.

4. Add Navbar to HTML:
   - In your HTML file, within the `<nav>` element representing the navbar, add the desired navigation links using the `<a>` element. For example:
     ```html
     <nav id="navbar">
       <a href="#" class="nav-link">Home</a>
       <a href="#" class="nav-link">About</a>
       <a href="#" class="nav-link">Services</a>
       <a href="#" class="nav-link">Contact</a>
     </nav>
     ```

5. Save and Preview:
   - Save both your HTML and CSS files.
   - Open the HTML file in a web browser to see the horizontal navbar with the applied CSS styles.

Congratulations! You have successfully created and styled a horizontal navbar in HTML using CSS. Feel free to customize the navbar further by adding additional links, adjusting the styles, or incorporating any desired features to suit your project's requirements.
