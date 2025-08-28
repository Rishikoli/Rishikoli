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
    </style>
</head>
<body class="bg-gradient-to-br from-gray-900 to-slate-800 text-gray-300">
    <div class="container mx-auto p-4 md:p-8 max-w-6xl">
        
        <!-- Header Section -->
        <header class="text-center mb-10 p-8 bg-gray-800/50 rounded-xl shadow-2xl backdrop-blur-sm border border-gray-700">
            <div class="flex justify-center items-center gap-4 mb-4">
                 <img src="https://placehold.co/120x120/dc2626/white?text=RH" alt="8-bit Red Hood" class="rounded-full border-4 border-red-600">
                 <img src="https://placehold.co/80x80/161b22/f0f6fc?text=Bat" alt="8-bit Batman Symbol" class="rounded-full">
            </div>
            <h1 class="text-4xl md:text-5xl font-bold text-white mb-2">👋 Welcome to my GitHub Profile!</h1>
            <h3 class="text-xl text-violet-400 font-medium">🦇 Developer | 🔴 Tech Enthusiast | 🎮 Retro Gaming Fan</h3>
        </header>

        <main class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Left Column -->
            <div class="md:col-span-2 space-y-8">
                
                <!-- About Me Section -->
                <section class="bg-gray-800/50 p-6 rounded-xl shadow-lg border border-gray-700">
                    <h2 class="text-2xl font-bold text-white border-b-2 border-red-600 pb-2 mb-4">🚀 About Me</h2>
                    <div class="bg-gray-900 p-4 rounded-lg font-mono text-sm text-cyan-400 overflow-x-auto">
<pre><code>const developer = {
  name: "Your Name",
  role: "Full Stack Developer",
  location: "Nagpur, Maharashtra, India",
  interests: ["Web Development", "Gaming", "Comic Books"],
  currentlyLearning: ["React", "Node.js", "Python"],
  funFact: "I create pixel art in my free time! 🎨"
};</code></pre>
                    </div>
                </section>

                <!-- Featured Projects Section -->
                <section class="bg-gray-800/50 p-6 rounded-xl shadow-lg border border-gray-700">
                    <h2 class="text-2xl font-bold text-white border-b-2 border-red-600 pb-2 mb-4">🏆 Featured Projects</h2>
                    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                        <!-- Project Card 1 -->
                        <div class="bg-gray-900 p-4 rounded-lg border-l-4 border-red-600 transform hover:scale-105 transition-transform duration-300">
                            <h3 class="text-lg font-bold text-white">🎮 Retro Game Hub</h3>
                            <p class="text-sm text-gray-400 mt-1">Classic games recreated in modern web tech.</p>
                            <p class="text-xs mt-2"><strong>Tech:</strong> HTML5, CSS3, JavaScript</p>
                        </div>
                        <!-- Project Card 2 -->
                        <div class="bg-gray-900 p-4 rounded-lg border-l-4 border-red-600 transform hover:scale-105 transition-transform duration-300">
                            <h3 class="text-lg font-bold text-white">🦸‍♂️ Hero Database</h3>
                            <p class="text-sm text-gray-400 mt-1">A comprehensive comic character info app.</p>
                            <p class="text-xs mt-2"><strong>Tech:</strong> React, Node.js, MongoDB</p>
                        </div>
                        <!-- Project Card 3 -->
                        <div class="bg-gray-900 p-4 rounded-lg border-l-4 border-red-600 transform hover:scale-105 transition-transform duration-300">
                            <h3 class="text-lg font-bold text-white">🎨 Pixel Art Creator</h3>
                            <p class="text-sm text-gray-400 mt-1">Online tool for creating retro-style pixel art.</p>
                            <p class="text-xs mt-2"><strong>Tech:</strong> Canvas API, JavaScript</p>
                        </div>
                    </div>
                </section>
            </div>

            <!-- Right Column -->
            <div class="space-y-8">
                <!-- Tech Stack Section -->
                <section class="bg-gray-800/50 p-6 rounded-xl shadow-lg border border-gray-700">
                    <h2 class="text-2xl font-bold text-white border-b-2 border-red-600 pb-2 mb-4">🛠️ Tech Stack</h2>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">JavaScript</span>
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">Python</span>
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">React</span>
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">Node.js</span>
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">HTML5</span>
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">CSS3</span>
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">Git</span>
                        <span class="bg-red-600 text-white text-xs font-bold px-3 py-1 rounded-full">VS Code</span>
                    </div>
                </section>

                <!-- GitHub Stats Section -->
                <section class="bg-gray-800/50 p-6 rounded-xl shadow-lg border border-gray-700">
                    <h2 class="text-2xl font-bold text-white border-b-2 border-red-600 pb-2 mb-4">📊 GitHub Stats</h2>
                    <div class="space-y-4">
                        <div class="bg-gray-900 p-3 rounded-lg text-center">
                            <h3 class="font-semibold text-white">🔥 Repositories</h3>
                            <p class="text-3xl font-bold text-red-500">25+</p>
                        </div>
                        <div class="bg-gray-900 p-3 rounded-lg text-center">
                            <h3 class="font-semibold text-white">⭐ Stars Earned</h3>
                            <p class="text-3xl font-bold text-red-500">100+</p>
                        </div>
                        <div class="bg-gray-900 p-3 rounded-lg text-center">
                            <h3 class="font-semibold text-white">🤝 Followers</h3>
                            <p class="text-3xl font-bold text-red-500">50+</p>
                        </div>
                    </div>
                </section>
                
                <!-- Connect With Me Section -->
                <section class="bg-gray-800/50 p-6 rounded-xl shadow-lg border border-gray-700">
                     <h2 class="text-2xl font-bold text-white border-b-2 border-red-600 pb-2 mb-4">🤝 Connect</h2>
                     <div class="flex justify-center flex-wrap gap-3">
                        <a href="https://linkedin.com/in/YOUR_LINKEDIN" class="bg-red-600 hover:bg-red-700 text-white font-bold py-2 px-4 rounded-lg transition-colors duration-300">LinkedIn</a>
                        <a href="https://twitter.com/YOUR_TWITTER" class="bg-red-600 hover:bg-red-700 text-white font-bold py-2 px-4 rounded-lg transition-colors duration-300">Twitter</a>
                        <a href="mailto:your.email@gmail.com" class="bg-red-600 hover:bg-red-700 text-white font-bold py-2 px-4 rounded-lg transition-colors duration-300">Email</a>
                     </div>
                </section>

            </div>
        </main>

        <!-- Footer -->
        <footer class="text-center mt-10 p-6 bg-gray-800/50 rounded-xl shadow-lg border border-gray-700">
            <p class="font-semibold mb-2">Thanks for visiting! ⭐ Star some repositories if you find them interesting!</p>
            <img src="https://placehold.co/60x60/dc2626/white?text=RH" alt="Red Hood Pixel Art" class="mx-auto my-2 rounded-full">
            <p class="text-sm">Profile Views: <span class="bg-red-600 text-white text-xs font-bold px-2 py-1 rounded-full">1,234</span></p>
        </footer>
    </div>
</body>
</html>
