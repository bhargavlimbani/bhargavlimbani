<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhargav Limbani | Portfolio</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, sans-serif;
        }

        body{
            background:#f4f4f4;
            color:#333;
        }

        header{
            background:#0d6efd;
            color:white;
            text-align:center;
            padding:50px 20px;
        }

        nav{
            background:#222;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:0 15px;
        }

        section{
            max-width:1000px;
            margin:40px auto;
            padding:20px;
            background:white;
            border-radius:10px;
            box-shadow:0 2px 10px rgba(0,0,0,0.1);
        }

        h2{
            margin-bottom:15px;
            color:#0d6efd;
        }

        .project{
            margin-bottom:20px;
            padding:15px;
            border-left:4px solid #0d6efd;
            background:#f9f9f9;
        }

        footer{
            text-align:center;
            background:#222;
            color:white;
            padding:20px;
            margin-top:40px;
        }

        .btn{
            display:inline-block;
            padding:10px 20px;
            background:#0d6efd;
            color:white;
            text-decoration:none;
            border-radius:5px;
            margin-top:10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Bhargav Limbani</h1>
    <p>Software Developer | C# | ASP.NET Core | Flutter</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a Computer Engineering student passionate about software
        development. I have experience in C#, ASP.NET Core, SQL Server,
        Flutter, HTML, CSS, and JavaScript.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>C#</li>
        <li>ASP.NET Core MVC</li>
        <li>SQL Server</li>
        <li>Flutter</li>
        <li>HTML, CSS, JavaScript</li>
        <li>Git & GitHub</li>
    </ul>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="project">
        <h3>Jay Jalaram Packaging Management System</h3>
        <p>
            Web-based packaging management system developed using
            ASP.NET Core MVC and SQL Server.
        </p>
        <a href="https://github.com/bhargavlimbani/Jay-Jalaram-Packaging-webapp" class="btn">
            View Project
        </a>
    </div>

    <div class="project">
        <h3>Contact Book Application</h3>
        <p>
            Contact management application built using C# and database integration.
        </p>
        <a href="https://github.com/bhargavlimbani/Contact-Book" class="btn">
            View Project
        </a>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: bhargavlimbani3@gmail.com</p>
    <p>GitHub: github.com/bhargavlimbani</p>
    <p>LinkedIn: Add Your LinkedIn Profile</p>
</section>

<footer>
    <p>© 2026 Bhargav Limbani. All Rights Reserved.</p>
</footer>

</body>
</html>
