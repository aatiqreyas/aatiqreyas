<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Profile</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
    }

    #header {
      background-color: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    #profile-img {
      border-radius: 50%;
      width: 150px;
      height: 150px;
      object-fit: cover;
    }

    #about-me {
      background-color: #fff;
      padding: 20px;
      margin: 20px auto;
      max-width: 600px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    #skills {
      text-align: center;
    }

    .skill-badge {
      margin: 5px;
    }

    #contact {
      background-color: #fff;
      padding: 20px;
      margin: 20px auto;
      max-width: 600px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    #contact ul {
      list-style-type: none;
      padding: 0;
    }

    #contact ul li {
      margin-bottom: 10px;
    }

    #contact ul li a {
      text-decoration: none;
      color: #333;
    }

    #contact ul li a:hover {
      color: #007bff;
    }
  </style>
</head>
<body>

  <div id="header">
    <h1>Welcome to my Profile!</h1>
    <a href="https://x.com/aatiqreyas" target="_blank">
      <img id="profile-img" src="https://img.shields.io/badge/aatiqreyas-black?style=for-the-badge&logo=x" alt="Profile">
    </a>
  </div>

  <div id="about-me">
    <h2>About Me</h2>
    <p>I am passionate about software development and always eager to learn new technologies. My primary areas of expertise include:</p>
    <ul>
      <li>Web Development</li>
      <li>Mobile Development</li>
      <li>Database Management</li>
    </ul>
  </div>

  <div id="skills">
    <h2>Skills</h2>
    <p>
      <img class="skill-badge" src="https://img.shields.io/badge/C-black?style=for-the-badge&logo=c" alt="C">
      <img class="skill-badge" src="https://img.shields.io/badge/Python-black?style=for-the-badge&logo=python" alt="Python">
      <img class="skill-badge" src="https://img.shields.io/badge/C++-black?style=for-the-badge&logo=c%2B%2B" alt="C++">
      <img class="skill-badge" src="https://img.shields.io/badge/MySQL-black?style=for-the-badge&logo=mysql" alt="MySQL">
      <img class="skill-badge" src="https://img.shields.io/badge/Java-black?style=for-the-badge&logo=java" alt="Java">
      <img class="skill-badge" src="https://img.shields.io/badge/PHP-black?style=for-the-badge&logo=php" alt="PHP">
      <img class="skill-badge" src="https://img.shields.io/badge/Android-black?style=for-the-badge&logo=android" alt="Android">
    </p>
  </div>

  <div id="contact">
    <h2>Contact Me</h2>
    <ul>
      <li>Email: <a href="mailto:aatiq@mail.com">aatiq@mail.com</a></li>
      <li>Website: <a href="https://aatiq.in">aatiq.in</a></li>
      <li>LinkedIn: <a href="https://linkedin.com/in/aatiqreyas">linkedin.com/in/aatiqreyas</a></li>
      <li>GitHub: <a href="https://github.com/aatiqreyas">github.com/aatiqreyas</a></li>
    </ul>
  </div>

</body>
</html>
