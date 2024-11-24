<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rajasekaran's Portfolio</title>
    <style>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(120deg, #f4f4f4, #e0e0e0);
}
header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}
nav ul {
    list-style: none;
}
nav ul li {
    display: inline;
    margin: 0 15px;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
}
main {
    padding-top: 70px;
}
section {
    padding: 2rem;
    text-align: center;
}
.profile img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid #333;
}
.profile h1 {
    margin-top: 1rem;
    font-size: 2.5rem;
    color: #333;
}
.profile p {
    margin-top: 1rem;
    font-size: 1.2rem;
    color: #666;
}
#about {
    background: #f9f9f9;
}
#projects {
    background: #fff;
}
.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 1rem;
    margin-top: 1rem;
}
.project {
    background: #f4f4f4;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}
.project:hover {
    transform: scale(1.05);
}
form {
    max-width: 500px;
    margin: 0 auto;
    padding: 1rem;
    background: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}
form input, form textarea, form button {
    width: 100%;
    margin: 0.5rem 0;
    padding: 0.75rem;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 1rem;
}
form input, form textarea {
    background: #f4f4f4;
}
form input:focus, form textarea:focus {
    border-color: #333;
    outline: none;
    background: #e9e9e9;
}
form button {
    background: #333;
    color: #fff;
    cursor: pointer;
    transition: background 0.3s;
    border: none;
}
form button:hover {
    background: #555;
}
</style>
</head>
<body>
    <header class="animate__animated animate__fadeInDown">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <div class="profile animate__animated animate__zoomIn">
                <img src="https://github.com/account" alt="Rajasekaran">
                <h1>Hello, I'm Rajasekaran</h1>
                <p>Welcome to my professional portfolio website! I'm a passionate PC hardware enthusiast and AI aficionado.</p>
            </div>
        </section>
        <section id="about" class="animate__animated animate__fadeIn">
            <h2>About Me</h2>
            <p>I am an enthusiastic learner passionate about PC hardware, cutting-edge technologies, and the fascinating world of Artificial Intelligence. My curiosity drives me to explore the inner workings of computers, from assembling hardware to understanding the latest advancements in processors and GPUs.</p>
        </section>
        <section id="projects" class="animate__animated animate__fadeInUp">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project">
                    <h3>Project One</h3>
                    <p>Description of project one</p>
                    <a href="https://example.com/project1" target="_blank">View Project</a>
                </div>
                <div class="project">
                    <h3>Project Two</h3>
                    <p>Description of project two</p>
                    <a href="https://example.com/project2" target="_blank">View Project</a>
                </div>
                <div class="project">
                    <h3>Project Three</h3>
                    <p>Description of project three</p>
                    <a href="https://example.com/project3" target="_blank">View Project</a>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </section>
        <section id="contact" class="animate__animated animate__fadeIn">
            <h2>Contact Me</h2>
            <form action="your-server-endpoint" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
  
</body>
</html>
