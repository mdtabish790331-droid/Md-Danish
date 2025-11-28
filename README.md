<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohammad Danish - Frontend Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            text-align: center;
            padding: 60px 0 40px;
            border-bottom: 1px solid #21262d;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #f0f6fc;
            font-weight: 700;
        }

        h3 {
            font-size: 1.5rem;
            color: #7ee787;
            font-weight: 400;
            margin-bottom: 30px;
        }

        .profile-stats {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 30px 0;
            flex-wrap: wrap;
        }

        .stat-item {
            background-color: #161b22;
            padding: 15px 25px;
            border-radius: 6px;
            border: 1px solid #30363d;
            text-align: center;
            min-width: 150px;
        }

        .stat-number {
            font-size: 1.8rem;
            font-weight: 700;
            color: #7ee787;
        }

        .stat-label {
            font-size: 0.9rem;
            color: #8b949e;
        }

        .trophy-section {
            margin: 30px 0;
        }

        .trophy-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }

        .trophy {
            background-color: #161b22;
            border-radius: 50%;
            width: 70px;
            height: 70px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 1px solid #30363d;
            font-size: 1.8rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }

        .social-link {
            color: #c9d1d9;
            font-size: 1.8rem;
            transition: color 0.3s;
        }

        .social-link:hover {
            color: #7ee787;
        }

        .content-section {
            margin: 50px 0;
        }

        .section-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #f0f6fc;
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .project-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 20px;
            transition: transform 0.3s, border-color 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
            border-color: #7ee787;
        }

        .project-title {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: #7ee787;
        }

        .project-description {
            color: #8b949e;
            margin-bottom: 15px;
        }

        .project-link {
            color: #7ee787;
            text-decoration: none;
            font-weight: 500;
            display: inline-flex;
            align-items: center;
            gap: 5px;
        }

        .project-link:hover {
            text-decoration: underline;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .skill-item {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 15px;
            text-align: center;
            transition: transform 0.3s, border-color 0.3s;
        }

        .skill-item:hover {
            transform: translateY(-3px);
            border-color: #7ee787;
        }

        .skill-icon {
            font-size: 2rem;
            margin-bottom: 10px;
            color: #7ee787;
        }

        .skill-name {
            font-size: 0.9rem;
        }

        .stats-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-top: 20px;
        }

        .stats-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 20px;
        }

        .stats-title {
            font-size: 1.2rem;
            margin-bottom: 15px;
            color: #7ee787;
            text-align: center;
        }

        .contact-info {
            text-align: center;
            margin-top: 30px;
        }

        .contact-email {
            color: #7ee787;
            font-size: 1.2rem;
            text-decoration: none;
        }

        .contact-email:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            .stats-container {
                grid-template-columns: 1fr;
            }
            
            .profile-stats {
                gap: 15px;
            }
            
            .stat-item {
                min-width: 120px;
                padding: 10px 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi 👋, I'm Mohammad Danish</h1>
            <h3>A passionate frontend developer from India</h3>
            
            <div class="profile-stats">
                <div class="stat-item">
                    <div class="stat-number">1.2K</div>
                    <div class="stat-label">Profile Views</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">24</div>
                    <div class="stat-label">Repositories</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">18</div>
                    <div class="stat-label">Followers</div>
                </div>
            </div>
            
            <div class="trophy-section">
                <h3 class="section-title">Achievements</h3>
                <div class="trophy-container">
                    <div class="trophy">🏆</div>
                    <div class="trophy">⭐</div>
                    <div class="trophy">🚀</div>
                    <div class="trophy">💻</div>
                    <div class="trophy">🔥</div>
                </div>
            </div>
            
            <div class="social-links">
                <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                <a href="#" class="social-link"><i class="fab fa-linkedin"></i></a>
                <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                <a href="#" class="social-link"><i class="fab fa-hackerrank"></i></a>
            </div>
        </header>
        
        <section class="content-section">
            <h2 class="section-title">About Me</h2>
            <p>I'm a passionate frontend developer with experience in creating dynamic and responsive web applications. I'm currently expanding my skills in deep learning and machine learning to build more intelligent applications.</p>
            
            <div class="profile-stats" style="margin: 30px 0;">
                <div class="stat-item">
                    <div class="stat-number">3+</div>
                    <div class="stat-label">Years Coding</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">15+</div>
                    <div class="stat-label">Projects</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">5</div>
                    <div class="stat-label">Technologies</div>
                </div>
            </div>
        </section>
        
        <section class="content-section">
            <h2 class="section-title">Current Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3 class="project-title">Agro-Analytica</h3>
                    <p class="project-description">An agricultural analytics platform that helps farmers optimize crop yield using data analysis.</p>
                    <a href="#" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="project-card">
                    <h3 class="project-title">AI-Based Body Measurement</h3>
                    <p class="project-description">A system for accurate body measurement and movement recognition for online clothing size prediction.</p>
                    <a href="#" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="project-card">
                    <h3 class="project-title">E-Commerce Platform</h3>
                    <p class="project-description">A responsive e-commerce website with modern UI/UX and seamless shopping experience.</p>
                    <a href="#" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
                </div>
            </div>
        </section>
        
        <section class="content-section">
            <h2 class="section-title">Skills & Technologies</h2>
            <div class="skills-grid">
                <div class="skill-item">
                    <div class="skill-icon"><i class="fab fa-html5"></i></div>
                    <div class="skill-name">HTML5</div>
                </div>
                <div class="skill-item">
                    <div class="skill-icon"><i class="fab fa-css3-alt"></i></div>
                    <div class="skill-name">CSS3</div>
                </div>
                <div class="skill-item">
                    <div class="skill-icon"><i class="fab fa-js"></i></div>
                    <div class="skill-name">JavaScript</div>
                </div>
                <div class="skill-item">
                    <div class="skill-icon"><i class="fab fa-python"></i></div>
                    <div class="skill-name">Python</div>
                </div>
                <div class="skill-item">
                    <div class="skill-icon"><i class="fab fa-java"></i></div>
                    <div class="skill-name">Java</div>
                </div>
                <div class="skill-item">
                    <div class="skill-icon"><i class="fab fa-git-alt"></i></div>
                    <div class="skill-name">Git</div>
                </div>
                <div class="skill-item">
                    <div class="skill-icon"><i class="fab fa-linux"></i></div>
                    <div class="skill-name">Linux</div>
                </div>
                <div class="skill-item">
                    <div class="skill-icon"><i class="fas fa-code"></i></div>
                    <div class="skill-name">C/C++</div>
                </div>
            </div>
        </section>
        
        <section class="content-section">
            <h2 class="section-title">GitHub Statistics</h2>
            <div class="stats-container">
                <div class="stats-card">
                    <h3 class="stats-title">Most Used Languages</h3>
                    <div style="height: 200px; background: linear-gradient(135deg, #0d4220 0%, #0d4220 40%, #096a2e 40%, #096a2e 60%, #7ee787 60%, #7ee787 100%); border-radius: 6px; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold;">
                        Python: 40%<br>
                        JavaScript: 20%<br>
                        Java: 15%<br>
                        HTML/CSS: 25%
                    </div>
                </div>
                <div class="stats-card">
                    <h3 class="stats-title">Contributions</h3>
                    <div style="height: 200px; background: linear-gradient(to right, #0d4220, #7ee787); border-radius: 6px; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold;">
                        Current Streak: 15 days<br>
                        Longest Streak: 42 days<br>
                        Total Contributions: 687
                    </div>
                </div>
            </div>
        </section>
        
        <section class="content-section">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-info">
                <p>Feel free to reach out to me for collaborations or just to say hello!</p>
                <a href="mailto:mdtabish790331@gmail.com" class="contact-email">mdtabish790331@gmail.com</a>
            </div>
        </section>
    </div>
</body>
</html>
