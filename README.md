<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karabo's Website</title>
</head>
<body>
    <header>
        <h1>Welcome to Karabo's Website</h1>
        <nav>
            <a href="#about">About Me</a> | 
            <a href="#projects">Projects</a> | 
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I'm Karabo! Welcome to my simple website where you can learn more about my projects and how to reach me.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>Project 1: Interactive Webpage</li>
            <li>Project 2: Simple Calculator</li>
            <li>Project 3: Color Changer</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can contact me via <a href="mailto:karabo@example.com">email</a>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Karabo's Website</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
    text-align: center;
    margin: 0;
    padding: 0;
}

header {
    background-color: #007bff;
    color: white;
    padding: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
}

nav a:hover {
    text-decoration: underline;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
}

footer {
    background-color: #333;
    color: white;
    padding: 10px;
    margin-top: 20px;
}
