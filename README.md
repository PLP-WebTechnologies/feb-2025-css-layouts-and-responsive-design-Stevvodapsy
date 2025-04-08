# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.

- SOLUTION
- HTMLE FILE
- <!DOCTYPE html>

 <html lang="en">
 <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Responsive Webpage</title>
        <link rel="stylesheet" href="styles.css">
 

</head>
 

<body>
    <h1>Navigation Bar</h1>
 <nav class="navbar">
    <ul>
         <li><a href="#">Home</a></li>
         <li><a href="#">About</a></li>
         <li><a href="#">Services</a></li>
         <li><a href="#">Contact</a></li>
    </ul>
 </nav>
 


 

  <!-- Main Content -->
 

  <div class="content">
 

    <header>
 

      <h1>Welcome to My Website</h1>
 

    </header>
 

    <section>
 

      <p>This is a section of the page.</p>
 

      <!-- Adding the Image from the URL -->
 

      <img src="https://images.pexels.com/photos/31527881/pexels-photo-31527881/free-photo-of-dramatic-black-and-white-coastal-landscape.jpeg?auto=compress&cs=tinysrgb&w=400&lazy=load" 
 

           alt="dramatic-black-and-white-coastal-landscape" 
 

           style="width:100%; height:auto;">
 

    </section>
 

  </div>
 


 

  <!-- Footer -->
 

  <footer>
 

    <p>&copy; 2025 My Website</p>
 

  </footer>
 

</body>
 

</html>


CSS FILE
/* Basic Styles */
 

body {
 

    font-family: Arial, sans-serif;
 

    margin: 0;
 

    padding: 0;
 

  }
 

  
 

  .navbar {
 

    background-color: #cf1111;
 

  }
 

  
 

  .navbar ul {
 

    list-style-type: none;
 

    padding: 0;
 

    margin: 0;
 

    display: flex;
 

    justify-content: space-around;
 

  }
 

  
 

  .navbar li {
 

    padding: 14px 20px;
 

  }
 

  
 

  .navbar a {
 

    color: rgb(13, 35, 228);
 

    text-decoration: none;
 

  }
 

  
 

  .content {
 

    display: flex;
 

    flex-direction: column;
 

    padding: 20px;
 

  }
 

  
 

  footer {
 

    background-color: #333;
 

    color: rgb(18, 214, 165);
 

    text-align: center;
 

    padding: 10px;
 

  }
 

  
 

  /* Media Queries */
 

  @media (max-width: 768px) {
 

    .navbar ul {
 

      flex-direction: column;
 

      align-items: center;
 

    }
 

  
 

    .content {
 

      flex-direction: column;
 

    }
 

  }
 

  
 

  @media (max-width: 480px) {
 

    .navbar li {
 

      padding: 10px 15px;
 

    }
 

  
 

    .content {
 

      padding: 10px;
 

    }
 

  }
- Test across different screen sizes.

Happy Coding! 💻✨
