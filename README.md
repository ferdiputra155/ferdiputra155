<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <a href="#about">About Me</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Mas Ferdi, an automotive enthusiast with a passion for technology and innovation.</p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Brief description of the project.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Brief description of the project.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: masferdi@example.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Mas Ferdi</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

nav a {
    color: #fff;
    margin: 0 1rem;
    text-decoration: none;
}

section {
    padding: 2rem;
}

.project {
    background: #f4f4f4;
    margin: 1rem 0;
    padding: 1rem;
    border: 1px solid #ddd;
}

footer {
    text-align: center;
    padding: 1rem;
    background: #333;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
}
document.addEventListener("DOMContentLoaded", () => {
    console.log("Welcome to my portfolio!");
});
# My Portfolio  
This is a simple portfolio webpage showcasing my projects and skills.

## Features  
- **Responsive Design**: Looks great on all devices.  
- **Easy Navigation**: Navigate between sections easily.  

## How to Use  
1. Clone this repository.  
2. Open `index.html` in your browser.  

## Future Updates  
- Add more projects.  
- Include animations and transitions.
