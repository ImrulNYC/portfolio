<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        :root {
            --primary-color: #333;
            --secondary-color: #f4f4f4;
            --text-color: #fff;
            --accent-color: #007acc;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: var(--primary-color);
            color: var(--text-color);
            padding: 1.5em 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: var(--text-color);
            margin: 0 1em;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: var(--accent-color);
        }
        main {
            padding: 2em;
        }
        section {
            margin-bottom: 4em;
        }
        section h2 {
            margin-top: 0;
            text-align: center;
            color: var(--primary-color);
        }
        .project {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-bottom: 2em;
        }
        .project div {
            flex: 1 1 calc(50% - 1em);
            background-color: var(--secondary-color);
            padding: 1em;
            margin: 0.5em;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: var(--primary-color);
            color: var(--text-color);
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        @media (max-width: 600px) {
            .project div {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hi, I'm [Your Name], a passionate developer with experience in [mention your skills or specialties]. I love creating applications that are both functional and visually appealing.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <div>
                    <h3>Project 1</h3>
                    <p>Brief description of Project 1.</p>
                </div>
                <div>
                    <h3>Project 2</h3>
                    <p>Brief description of Project 2.</p>
                </div>
                <div>
                    <h3>Project 3</h3>
                    <p>Brief description of Project 3.</p>
                </div>
                <div>
                    <h3>Project 4</h3>
                    <p>Brief description of Project 4.</p>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>You can reach me at <a href="mailto:your.email@example.com">your.email@example.com</a> or follow me on <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>
