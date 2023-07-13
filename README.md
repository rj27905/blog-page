(HTML FILE)
<!DOCTYPE html>
<html>
<head>
  <title>Blog Page</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Categories</a></li>
        <li><a href="#">Tags</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <h1>Blog Title</h1>
    <input type="text" placeholder="Search...">
  </header>
  
  <section class="hero">
    <img src="hero-image.jpg" alt="Hero Image">
    <h2>Featured Post Title</h2>
  </section>
  
  <section class="content">
    <div class="sidebar">
      <h3>Categories</h3>
      <ul>
        <li><a href="#">Category 1</a></li>
        <li><a href="#">Category 2</a></li>
        <li><a href="#">Category 3</a></li>
      </ul>
      
      <h3>Tags</h3>
      <ul>
        <li><a href="#">Tag 1</a></li>
        <li><a href="#">Tag 2</a></li>
        <li><a href="#">Tag 3</a></li>
      </ul>
    </div>
    
    <div class="posts">
      <article>
        <h2>Post Title 1</h2>
        <p>Post content goes here...</p>
        <a href="#">Read More</a>
      </article>
      
      <article>
        <h2>Post Title 2</h2>
        <p>Post content goes here...</p>
        <a href="#">Read More</a>
      </article>
      
      <!-- More posts... -->
    </div>
  </section>
  
  <footer>
    <p>&copy; 2023 Blog Name. All rights reserved.</p>
  </footer>
</body>
</html>
