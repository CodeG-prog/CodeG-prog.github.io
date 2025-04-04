<!DOCTYPE html>
<html lang ="eng">
    <head>
        <meta charset ="UTF-8">
        <meta name ="viewport" content="width=device-width, initial-scale=1.0">
        <meta name ="description" content="My Portfolio Page">
        <meta name ="keywords" content="Portfolio, Web Development, Projects">
        <meta name ="author" content ="Wekesa Augustine">
        <title>My Portfolio</title>
        <link rel="stylesheet" href="mystyle.css"/>
        
        <favicon>
            <a href="unnamed.jpg" rel="icon" type="image/x-icon" alt="My Portfolio Favicon" width="16" height="16">
            </a>
    
        </favicon>
    
    </head>
    
    <body>  
        <header class="header" style="background-color:rgb(13, 148, 13); color: rgb(234, 191, 191); padding: 20px;">


                <h1 class ="name" style="text-align: center;font-size: 40px;color: rgb(192, 202, 210);">Wekesa Augustine</h1>
                <p class ="tagline" style="text-align: center; color: rgb(247, 247, 247);">Aspiring Web Developer/Data Analyst</p>
                <hr>
                <nav class = "navbar">
                    <ul class ="nav-list" style="text-align:center;color: rgb(255, 252, 252);background-color: azure;">
                        <li><a href ="Home">Home</a></li>
                        <li><a href ="About">About Me</a></li>
                        <li><a href = "Skills">Skills</a></li>
                        <li><a href ="Projects">Projects</a></li>
                        <li><a href ="Contact">Contact</a></li>

                    </ul>


                </nav>

         </header>
         <section id ="about-me">
            
            <h2>About Me</h2>
            <div class ="about-me-content">
                <p style="font-size:large; color: black;">I'm Wekesa Augustine!!! Welcome to my portfolio! I'm a passionate web developer with a strong foundation in HTML, CSS, and JavaScript. 
                    I love creating dynamic and user-friendly websites that provide an excellent user experience.</p>
                <img src ="profile.jpg.jpg" style="display:inline-flex" height="600px" width="500px" class="profile-image">
                <br>
            </div>
            <br>
            <p style="font-size:large; color: black;">  An aspiring web developer with a passion for creating dynamic and user-friendly websites. 
                I have a strong foundation in HTML, CSS, and JavaScript, and I'm constantly learning new technologies such as Python,Github and MYSQL to enhance my skills.</p>
            <p style="font-size:large;color: black;"> In my free time, I enjoy exploring new programming languages, working on personal projects, and contributing to open-source initiatives.
                 I'm excited to connect with like-minded individuals and collaborate on innovative web development projects.</p>
            <p style="font-size:large; color: black;"> With a background in design and development bring a unique perspective to every project. 
                I'm constantly learning new technologies and techniques to stay at the forefront of web development</p>
                <hr
         
            </section
         <hr>

         <section id ="skills">
            <h2 style="color: black;">My Skills</h2>
            <ul class ="skills-list" style="list-style-type: circle; padding: 20px; color: black; font-weight: 200; text-align: justify; font-size:large;">
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>Python</li>
                    <li>GitHub</li>
                    <li>MySQL</li>
                    <li>React</li>
                    <li>Node.js</li>
                    <li>Responsive Design</li>         
            </ul>

            <div class="skills-list-content" style="display:table-cell;position: relative; align-items:stretch; flex-wrap: wrap;align-content: normal;">
                <br>
                <img src="pexels-luis-gomes-166706-546819.jpg" width="400px" height="300px" alt="Skills Image" class="skills-image">
                <img src="pexels-tima-miroshnichenko-6549342.jpg". width="400px" height="300px" alt="Skills Image" class="skills-image">
                <img src="pexels-goumbik-574071.jpg" width="400px" height="300px" alt="Skills Image" class="skills-image">
                <img src="pexels-divinetechygirl-1181671.jpg" width="400px" height="300px" alt="Skills Image" class="skills-image">
            </div>
            <hr>
        </section>
            <section id ="projects">
                <h2>My Projects</h2>
                <div class="projects-grid">
                    <div class="project-card">
    
                        <div class="project-info">
                            <h3>Portfolio Websites</h3>
                            <p style="font-size:large;color:black;">A fully responsive portfolio website.</pre>
                            <p style="display: block; color: rgb(1, 0, 0);">Check out for new projects soon😊😊😊😊</p>
                            <div class="project-links">
                                <a href="https://github.com/CodeG-prog/Portfolio-Website.git">My Portfolio sample codes</a>
                                <a href="Resume latest (1).pdf" download="Resume latest(1).pdf">Download My Resume</a>"
                            </div>
                        </div>
                    </div>
                    </div>
            </section>
            <br>
            <hr>
            <section id ="contact"style="padding: 20px; color: black; font-weight: 200; text-align: justify; font-size:large;border: 1px solid black; background-color: rgb(255, 255, 255);">
                <h2>Contact Me</h2>
                <form action="post" method="post" class="contact-form">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" placeholder="Wekesa John" required>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" minlength="20" maxlength="40" placeholder="wekesaaugustine28@gmail.com" required>
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                    <button style="color: rgb(223, 54, 54); padding: auto; " type="submit">Send Message</button>
                
                </form>
            
            </section>

<hr>
            <section>
            
    <footer>
                <p style="text-align: center; ";>Thank you for visiting my portfolio! 2025 Wekesa Augustine. All rights reserved.</p>
                <ul class="social-media" style="font-size: 15px;background-color: rgb(173, 42, 42);color:white;">
                    <li><a href="https://www.linkedin.com/in/juma-augustine-3bb977100/">LinkedIn</a></li>
                    <li><a href="https://github.com/CodeG-prog">GitHub</a></li>
                    <li><a href="https://x.com/sir_wake">Twitter</a></li>
                    <li><a href= "https://web.facebook.com/wekesa.masibo">Facebook</a></li>
                </ul>
    </footer>
        </section>
        </body>
</html>



* {text-align:calc(100% - 1rem);
    margin: 4;
    padding: 4;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    line-height: 1.6;
    color: #dbd5e7;
    background-color: rgb(199, 186, 186);
background-position: center;
background-size: cover;
text-align: justify;
}

/* Header Styles */
header {width: 100%;
    color:#3498db;
    background-attachment: fixed;
    background-color: white;
    color: rgb(215, 25, 25);
    padding:20px;
    text-align: center;
}

.profile-img {
    padding: 20px;
    text-align: center;
    border-radius: 20px;
    width: 100px;
    height: 100px;
    border-radius: 25%;
    object-fit: cover;
    border: 5px solid #a2a0a0;
    margin-bottom: 1rem;
}

h1 {
    font-size: 60px;
    margin-bottom: 0.5rem;
    color: rgb(133, 109, 114);
}

.tagline {
    font-size: 20px;
    opacity: 0.9;
    margin-bottom: 1rem;
    color: #d9c5c5;
}

/* Navigation */
nav {
    background-color: rgb(254, 255, 254);
    padding: 20px;
    position: sticky;
    top: 0;
    z-index: 100;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style:armenian;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: rgb(190, 31, 31);
    font-weight: bold;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    transition: background-color 0.3s;
    position: relative;
}

nav ul li a:hover {
    background-color: #db7434;
}

/* Section Styles */
section {
    padding:0%;
    max-width: 700px;
    margin: 0 auto;
}

section h2 {
    font-size: 2rem;
    margin-bottom: 2rem;
    color: #d6470e;
    text-align: center;
    position: relative;
    font-weight: bold;
}

section h2::after {
    display:contents;
    width: 80px;
    height: 4px;
    background: #e1e6ea;
    margin: 0.5rem auto;
}

/* About Section */
.about-content {
    display: flex;
    align-items: center;
    gap: 2rem;
    margin-bottom: 2rem;
    padding: 2rem;
    background: rgb(200, 137, 137);
    border-radius: 8px;
    ;
}

.about-text {
    flex: 2;
}

.about-img {
    flex: 1;
    text-align: center;
}

.about-img img {
    max-width: 150%;
    border-radius: 8px;
    box-shadow: 0 5px 15px rgba(206, 18, 18, 0.762);
}

/* Skills Section */
.skills-container {
    display:flow-root;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
}

.skill {
    display:-moz-stack;
    background: rgb(221, 28, 28);
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(207, 124, 52, 0.1);
    width: calc(33% - 1.5rem);
    text-align: center;
    transition: transform 0.3s}

.skill i {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #3498db;
}

/* Projects Section */
.projects-grid {
    display:flow-root;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 2rem;
}

.project-card {
    background: rgb(199, 186, 186);
    border-radius: 8px;
    overflow:visible;
    box-shadow: 0 3px 10px rgba(226, 41, 41, 0.1);
    transition: transform 0.3s;
}

.project-card:hover {
    transform: translateY(-5px);
}

.project-img {
    width: 100%;
    height: 300px;
    object-fit:fill;
}

.project-info {
    padding:0vmax
}

.project-info h3 {
    margin-bottom: 0.5rem;
}

.project-links {
    margin-top: 1rem;
}

.project-links a {
    display: grid;
    margin-right: 1rem;
    background: #163549;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    font-size: 0.9rem;
}

.project-links a:hover {
    background: #2980b9;
}

/* Contact Section */
.contact-form {
    max-width: 600px;
    max-height: fit-content;
    margin: 0 auto;
    box-shadow: 0 3px 10px rgb(82, 25, 4);
    border-radius: 8px;
    padding: 2rem;
    padding: 20px;
    border-radius: 10px;
    display: contents;
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: cover;
    margin-bottom: 0.5rem;
    font-weight: bold;
}

.form-group input,
.form-group textarea {
    width: 200%;
    padding: 0.8rem;
    border: 1px solid #c63838;
    border-radius: 4px;
    font-size: 1rem;
}

.form-group textarea {
    height: 150px;
    resize: vertical;
}

.submit-btn {
    background: #db343f;
    color: rgb(211, 10, 10);
    border: none;
    padding: 1rem 2rem;
    font-size: 1rem;
    border-radius: 4px;
    cursor: pointer;
    transition: background 0.3s;
}

.submit-btn:hover {
    background: #b9293c;
}

/* Footer */
footer {
    display: calc();
        height: 30px;
        color: rgb(234, 14, 14);
        text-align: center;
        line-height: 30px;
        position: relative;
        margin-top: -30px;
    }


.social-links {
    margin: 1rem 0;
    display: -ms-grid;
    justify-content: center;
    gap: 1rem;
    font-size: 1.5rem;
    color: white;
}

.social-links a {
    padding: 20px;
    color: rgb(199, 186, 186);
    margin: 0 0.5rem;
    font-size: 1.5rem;
    transition: color 0.3s;
}

.social-links a:hover {
    color: white;
    transform: scale(1.2);
}


/* Responsive Design */
@media (max-width: 1000px) {
    .about-content {
        flex-direction: column;
        display: grid;
    }

    .skill {
        width: calc(50% - 1.5rem);
    }

    nav ul {
        flex-direction: row;
        align-items: center;
    }

    nav ul li {
        margin: 0.5rem 0;
    }
}

@media (max-width: 480px) {
    .skill {
        width: 100%;
    }

    section {
        padding: 20px;
    }
}

