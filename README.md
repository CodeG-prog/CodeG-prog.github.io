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
