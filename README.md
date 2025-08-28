<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0d1117, #161b22);
            color: #c9d1d9;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        .header {
            text-align: center;
            margin-bottom: 40px;
            padding: 30px;
            background: #21262d;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }
        .header img {
            margin: 0 15px;
        }
        .header h1 {
            color: #f0f6fc;
            margin: 20px 0 10px 0;
        }
        .header h3 {
            color: #7c3aed;
            margin: 0;
        }
        .section {
            background: #21262d;
            margin: 20px 0;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }
        .section h2 {
            color: #f0f6fc;
            border-bottom: 2px solid #dc2626;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin: 20px 0;
        }
        .tech-badge {
            background: #dc2626;
            color: white;
            padding: 8px 16px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s;
        }
        .tech-badge:hover {
            transform: scale(1.05);
        }
        .stats-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }
        .stat-card {
            background: #161b22;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            flex: 1;
            min-width: 200px;
        }
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        .project-card {
            background: #161b22;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #dc2626;
        }
        .project-card h3 {
            color: #f0f6fc;
            margin-top: 0;
        }
        .social-links {
            text-align: center;
            margin: 30px 0;
        }
        .social-links a {
            display: inline-block;
            margin: 0 10px;
            padding: 10px 20px;
            background: #dc2626;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .social-links a:hover {
            background: #b91c1c;
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            background: #21262d;
            border-radius: 10px;
        }
        code {
            background: #161b22;
            padding: 15px;
            border-radius: 5px;
            display: block;
            margin: 15px 0;
            font-family: 'Courier New', monospace;
            color: #79c0ff;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <img src="7972f109-9eec-4a16-9c4a-048426972da4.png" alt="8-bit Red Hood" height="120">
            <img src="b4c7c63d-f1be-448b-820c-0eaced58ff81.png" alt="8-bit Batman Symbol" height="80">
            <h1>👋 Welcome to my GitHub Profile!</h1>
            <h3>🦇 Developer | 🔴 Tech Enthusiast | 🎮 Retro Gaming Fan</h3>
        </div>

        <!-- About Me Section -->
        <div class="section">
            <h2>🚀 About Me</h2>
            <code>
const developer = {
    name: "Your Name",
    role: "Full Stack Developer", 
    location: "Nagpur, Maharashtra, India",
    interests: ["Web Development", "Gaming", "Comic Books", "Open Source"],
    currentlyLearning: ["React", "Node.js", "Python"],
    funFact: "I create pixel art in my free time! 🎨"
};
            </code>
        </div>

        <!-- Tech Stack Section -->
        <div class="section">
            <h2>🛠️ Tech Stack & Tools</h2>
            <div class="tech-stack">
                <span class="tech-badge">JavaScript</span>
                <span class="tech-badge">Python</span>
                <span class="tech-badge">React</span>
                <span class="tech-badge">Node.js</span>
                <span class="tech-badge">HTML5</span>
                <span class="tech-badge">CSS3</span>
                <span class="tech-badge">Git</span>
                <span class="tech-badge">VS Code</span>
            </div>
        </div>

        <!-- Stats Section -->
        <div class="section">
            <h2>📊 GitHub Stats</h2>
            <div class="stats-container">
                <div class="stat-card">
                    <h3>🔥 Repositories</h3>
                    <p style="font-size: 2em; color: #dc2626;">25+</p>
                </div>
                <div class="stat-card">
                    <h3>⭐ Stars Earned</h3>
                    <p style="font-size: 2em; color: #dc2626;">100+</p>
                </div>
                <div class="stat-card">
                    <h3>🤝 Followers</h3>
                    <p style="font-size: 2em; color: #dc2626;">50+</p>
                </div>
            </div>
        </div>

        <!-- Current Focus Section -->
        <div class="section">
            <h2>🎯 Current Focus</h2>
            <ul>
                <li>🔭 Working on: <strong>Web Development Projects</strong></li>
                <li>🌱 Learning: <strong>Advanced React & Backend Technologies</strong></li>
                <li>👯 Looking to collaborate on: <strong>Open Source Projects</strong></li>
                <li>💬 Ask me about: <strong>JavaScript, Python, Pixel Art</strong></li>
                <li>⚡ Fun fact: <strong>I recreate comic book characters in 8-bit style!</strong></li>
            </ul>
        </div>

        <!-- Featured Projects Section -->
        <div class="section">
            <h2>🏆 Featured Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>🎮 Retro Game Hub</h3>
                    <p>Collection of classic games recreated in modern web technologies</p>
                    <p><strong>Tech:</strong> HTML5, CSS3, JavaScript</p>
                </div>
                <div class="project-card">
                    <h3>🦸‍♂️ Hero Database</h3>
                    <p>Comprehensive comic character information application</p>
                    <p><strong>Tech:</strong> React, Node.js, MongoDB</p>
                </div>
                <div class="project-card">
                    <h3>🎨 Pixel Art Creator</h3>
                    <p>Online tool for creating retro-style pixel art</p>
                    <p><strong>Tech:</strong> Canvas API, JavaScript</p>
                </div>
            </div>
        </div>

        <!-- Gaming & Interests Section -->
        <div class="section">
            <h2>🎮 Gaming & Interests</h2>
            <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
                <span style="background: #161b22; padding: 10px 15px; border-radius: 20px;">🕹️ Retro Gaming</span>
                <span style="background: #161b22; padding: 10px 15px; border-radius: 20px;">🦇 DC Comics Fan</span>
                <span style="background: #161b22; padding: 10px 15px; border-radius: 20px;">🎨 Pixel Art Creator</span>
                <span style="background: #161b22; padding: 10px 15px; border-radius: 20px;">📚 Continuous Learning</span>
                <span style="background: #161b22; padding: 10px 15px; border-radius: 20px;">🌟 Open Source</span>
            </div>
        </div>

        <!-- Social Links -->
        <div class="section">
            <h2>🤝 Connect With Me</h2>
            <div class="social-links">
                <a href="https://linkedin.com/in/YOUR_LINKEDIN">LinkedIn</a>
                <a href="https://twitter.com/YOUR_TWITTER">Twitter</a>
                <a href="mailto:your.email@gmail.com">Email</a>
                <a href="https://instagram.com/YOUR_INSTAGRAM">Instagram</a>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p><strong>Thanks for visiting! ⭐ Star some repositories if you find them interesting!</strong></p>
            <img src="7972f109-9eec-4a16-9c4a-048426972da4.png" alt="Red Hood Pixel Art" height="60">
            <p>Profile Views: <span style="background: #dc2626; padding: 2px 8px; border-radius: 3px;">1,234</span></p>
        </div>
    </div>
</body>
</html>
