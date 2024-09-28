<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> PORTFOLIO</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #caf881;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 20px;
    }

    header {
      background-color: #fff;
      padding: 10px 20px;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #333;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
    }

    nav li {
      display: inline-block;
      margin-right: 20px;
    }

    nav a {
      text-decoration: none;
      color: #333;
    }

    nav a:hover {
      color: #000;
    }

    .hero {
      text-align: center;
      padding-top: 50px;
      padding-bottom: 50px;
    }

    .profile-pic {
      border-radius: 50%;
      width: 200px;
      height: 200px;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    h3 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    .btn {
      background-color: #007bff;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 20px;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }

    .project-card {
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .project-card img {
      width: 100%;
      border-radius: 5px;
      margin-bottom: 10px;
    }

    .skills-list {
      list-style: none;
      padding: 0;
    }

    .skills-list li {
      margin-bottom: 5px;
    }

    footer {
      text-align: center;
      padding: 10px;
      background-color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <nav class="container">
      <a href="#" class="logo"></a>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero container">
      <img src="C:\Users\Lakshith H L\OneDrive\Pictures\pics\image.jpg" alt="LAKSHITH H L- Profile Picture" class="profile-pic">
      <h1>LAKSHITH H L</h1>
      <h3>CSE[AI&ML] Student</h3>
      <p>4KV22CI027</p>
       <p> 2023-2024</p>


    
      <a href="#projects" class="btn">See My Work</a>
    </section>

    <section id="about" class="container">
      <h2>About Me</h2>
      <p>*I Like TO Experience New Things Everyday

      </p>
      <p>*Playing Games Is My Hobby</p>
      <p>*Coding etc......</p>
      <a href="https://www.instagram.com/lakshith..hulimane?igsh=ZDlrYjlqN3JtNGlk">Instagram ID</a>
    </section>

    <section id="projects" class="container">
      <h2>Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <a href="C:\Users\Lakshith H L\OneDrive\Pictures\Screenshots\Screenshot 2024-06-18 080924.png">Project Pic</a>
          
          <h3>PORTFOLIO</h3>
          <p>[The Portfolio consists of a small amount of detalis about me]</p>
       
        </div>
        </div>
    </section>

    <section id="skills" class="container">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>Skill 1.Basic HTML & CSS</li>
        <li>Skill 2.Basic JAVA & c</li>
        <li>Skill 3.Know how to use AI</li>
        </ul>
    </section>

    <section id="contact" class="container">
      <h2>Contact</h2>
      <p>Feel free to reach out to me!</p>
      <ul>
        <li><a href="mailto:lakshithhulimanel@gmail.com">Email</a></li>
        <li><a href="https://www.linkedin.com/in/lakshith-hl-4b4439249?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=windows">Linkedin</a></li>
        </ul>
    </section>

  </main>

  <footer class="container">
    <p>&copy; LAKSHITH HL 2nd year</p>
  </footer>

</body>
</html>
