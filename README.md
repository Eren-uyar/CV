<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Curriculum Vitae</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f1f1f1;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: #333;
        }

        h2 {
            color: #555;
        }

        .section {
            margin-bottom: 20px;
        }

        .section h3 {
            margin-bottom: 10px;
        }

        .section p {
            margin: 0;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            margin-bottom: 5px;
        }

        .contact-info {
            display: flex;
            align-items: center;
        }

        .contact-icon {
            margin-right: 10px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
        }

        .skill {
            background-color: #007bff;
            color: #fff;
            padding: 5px 10px;
            border-radius: 5px;
            margin-right: 10px;
            margin-bottom: 10px;
        }

        .education, .experience {
            margin-bottom: 20px;
        }

        .date {
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Your Name</h1>
            <p>Web Developer</p>
        </header>

        <section class="section contact-info">
            <img src="phone-icon.png" alt="Phone Icon" class="contact-icon">
            <p>+1 (123) 456-7890</p>
        </section>

        <section class="section contact-info">
            <img src="email-icon.png" alt="Email Icon" class="contact-icon">
            <p>youremail@example.com</p>
        </section>

        <section class="section">
            <h2>Summary</h2>
            <p>A passionate web developer with experience in HTML, CSS, and JavaScript. Proven track record of creating responsive and stylish websites.</p>
        </section>

        <section class="section">
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill">HTML5</div>
                <div class="skill">CSS3</div>
                <div class="skill">JavaScript</div>
                <div class="skill">Responsive Design</div>
                <div class="skill">UI/UX Design</div>
            </div>
        </section>

        <section class="section education">
            <h2>Education</h2>
            <ul>
                <li>
                    <h3>BS in Computer Science</h3>
                    <p>University of Example, 20XX-20XX</p>
                </li>
            </ul>
        </section>

        <section class="section experience">
            <h2>Experience</h2>
            <ul>
                <li>
                    <h3>Web Developer</h3>
                    <p>ABC Web Solutions, 20XX-20XX</p>
                </li>
                <li>
                    <h3>Front-end Developer</h3>
                    <p>XYZ Design Studio, 20XX-20XX</p>
                </li>
            </ul>
        </section>
    </div>
</body>
</html>
