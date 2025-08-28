<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Simple animation for the banner */
        .banner-gradient {
            background: linear-gradient(-45deg, #dc2626, #7c3aed, #0d1117, #161b22);
            background-size: 400% 400%;
            animation: gradient 15s ease infinite;
        }
        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
    </style>
</head>
<body class="bg-slate-900 text-gray-300">
    <div class="container mx-auto p-4 md:p-8 max-w-4xl">

        <!-- Header Banner -->
        <header class="banner-gradient p-10 rounded-xl text-center mb-8 shadow-2xl">
            <h1 class="text-4xl md:text-5xl font-bold text-white">Hey there, I'm [Your Name]</h1>
            <p class="text-xl text-white/80 mt-2">🦇 Developer | 🔴 Tech Enthusiast | 🎮 Retro Gaming Fan</p>
        </header>

        <!-- Main Content -->
        <main class="space-y-8">

            <!-- About Me Section -->
            <section class="bg-gray-800/50 p-6 rounded-xl border border-gray-700">
                <h2 class="text-2xl font-bold text-white mb-4">🚀 About Me</h2>
                <p class="text-gray-400">
                    Full Stack Developer based in Nagpur, Maharashtra, India. Passionate about Web Development, Gaming, and Comic Books. Currently learning advanced React, Node.js, and Python. Fun fact: I love creating 8-bit style pixel art in my free time! 🎨
                </p>
            </section>

            <!-- Tech Stack Section -->
            <section class="bg-gray-800/50 p-6 rounded-xl border border-gray-700">
                <h2 class="text-2xl font-bold text-white mb-4">⚡ Tech Stack</h2>
                <div class="flex flex-wrap gap-3">
                    <!-- Replace with your actual tech stack from shields.io -->
                    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
                    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
                    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
                    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
                    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
                    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
                    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
                </div>
            </section>

            <!-- Featured Projects Section -->
            <section class="bg-gray-800/50 p-6 rounded-xl border border-gray-700">
                <h2 class="text-2xl font-bold text-white mb-4">🏆 Featured Projects</h2>
                <div class="overflow-x-auto">
                    <table class="w-full text-left">
                        <thead class="border-b border-gray-600 text-white">
                            <tr>
                                <th class="p-2">Project</th>
                                <th class="p-2">Summary</th>
                                <th class="p-2">Tech</th>
                            </tr>
                        </thead>
                        <tbody class="text-gray-400">
                            <tr class="border-b border-gray-700">
                                <td class="p-2 font-semibold">🎮 Retro Game Hub</td>
                                <td class="p-2">Classic games recreated in modern web tech.</td>
                                <td class="p-2">HTML5, CSS3, JavaScript</td>
                            </tr>
                            <tr class="border-b border-gray-700">
                                <td class="p-2 font-semibold">🦸‍♂️ Hero Database</td>
                                <td class="p-2">A comprehensive comic character info app.</td>
                                <td class="p-2">React, Node.js, MongoDB</td>
                            </tr>
                            <tr>
                                <td class="p-2 font-semibold">🎨 Pixel Art Creator</td>
                                <td class="p-2">Online tool for creating retro-style pixel art.</td>
                                <td class="p-2">Canvas API, JavaScript</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>

            <!-- GitHub Insights Section -->
            <section class="bg-gray-800/50 p-6 rounded-xl border border-gray-700">
                <h2 class="text-2xl font-bold text-white mb-4">📈 GitHub Insights</h2>
                <!-- IMPORTANT: Replace 'YOUR_USERNAME' with your actual GitHub username -->
                <div class="flex flex-wrap justify-center gap-4">
                    <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical&icon_color=7c3aed" alt="GitHub Stats" class="max-w-full">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=radical" alt="Top Languages" class="max-w-full">
                </div>
            </section>

            <!-- Connect With Me Section -->
            <section class="bg-gray-800/50 p-6 rounded-xl border border-gray-700">
                <h2 class="text-2xl font-bold text-white mb-4 text-center">🌐 Connect with me</h2>
                <div class="flex justify-center flex-wrap gap-4">
                    <!-- Replace with your actual links -->
                    <a href="https://linkedin.com/in/YOUR_LINKEDIN">
                        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                    </a>
                    <a href="https://twitter.com/YOUR_TWITTER">
                        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
                    </a>
                    <a href="mailto:your.email@gmail.com">
                        <img src="https://img.shields.io/badge/Email-DC2626?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                    </a>
                </div>
            </section>

        </main>

        <!-- Footer -->
        <footer class="text-center mt-8 p-6">
            <!-- IMPORTANT: Replace 'YOUR_USERNAME' with your actual GitHub username -->
            <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=dc2626" alt="profile views">
        </footer>

    </div>
</body>
</html>
