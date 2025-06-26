<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile - ALX Front-End Dev</title>
    <!-- Tailwind CSS CDN for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://rsms.me/inter/inter.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* GitHub Dark Mode Background */
            color: #c9d1d9; /* GitHub Dark Mode Text */
        }
        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 2rem;
        }
        h1, h2, h3 {
            color: #58a6ff; /* GitHub Blue for headings */
            font-weight: 700;
        }
        .section-card {
            background-color: #161b22; /* GitHub Dark Mode Card Background */
            border-radius: 0.75rem; /* Rounded corners */
            padding: 1.5rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border: 1px solid #30363d; /* Subtle border */
        }
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .icon {
            display: inline-block;
            vertical-align: middle;
            margin-right: 0.5rem;
        }
    </style>
</head>
<body class="p-4 sm:p-6 lg:p-8">

    <div class="container">

        <!-- Header Section -->
        <header class="text-center mb-10">
            <img src="https://media.licdn.com/dms/image/v2/D4D03AQEVUiOJ4J9UZw/profile-displayphoto-shrink_800_800/B4DZeH5f06GkAg-/0/1750331687367?e=1756339200&v=beta&t=zF4JfOfuA4cOYSWUVTh7kc8_YQx6DFZGYkUa7onSsYM" alt="Your Profile Photo" class="w-36 h-36 rounded-full mx-auto mb-4 border-4 border-[#58a6ff]">
            <h1 class="text-4xl sm:text-5xl font-extrabold mb-2 leading-tight">Hello, I'm Bernard Baako!</h1>
            <p class="text-xl sm:text-2xl text-gray-400">ALX Front-End Developer & Solution Creator</p>
            <div class="mt-4 flex justify-center space-x-4">
                <!-- Add your badges/social links here, e.g., GitHub, LinkedIn -->
                <a href="https://github.com/[YourGitHubUsername]" target="_blank" class="text-gray-400 hover:text-[#58a6ff] transition duration-300">
                    <svg class="icon w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.499.09.679-.217.679-.481 0-.237-.008-.865-.013-1.707-2.782.602-3.369-1.34-3.369-1.34-.454-1.156-1.11-1.464-1.11-1.464-.908-.618.069-.606.069-.606 1.003.07 1.531 1.032 1.531 1.032.892 1.529 2.341 1.087 2.91.828.092-.647.35-1.087.636-1.334-2.22-.253-4.555-1.113-4.555-4.953 0-1.096.393-1.995 1.03-2.692-.104-.253-.448-1.274.098-2.65 0 0 .84-.27 2.75 1.025A9.434 9.434 0 0112 6.814c.85.006 1.7.103 2.494.306 1.909-1.296 2.747-1.025 2.747-1.025.546 1.376.202 2.398.098 2.65.637.697 1.028 1.596 1.028 2.692 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.335-.012 2.41-.012 2.727 0 .266.18.577.688.48C21.137 20.19 24 16.425 24 12.017 24 6.484 19.522 2 14 2h-2z" clip-rule="evenodd" /></svg>
                </a>
                <a href="https://linkedin.com/in/[YourLinkedInUsername]" target="_blank" class="text-gray-400 hover:text-[#58a6ff] transition duration-300">
                    <svg class="icon w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M0 0h24v24H0z" fill="none"/><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                </a>
                 <a href="mailto:[YourEmail@example.com]" class="text-gray-400 hover:text-[#58a6ff] transition duration-300">
                    <svg class="icon w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
                </a>
            </div>
        </header>

        <!-- About Me Section -->
        <section class="section-card">
            <h2 class="text-3xl font-bold mb-4 flex items-center">
                <svg class="icon w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                About Me
            </h2>
            <p class="text-gray-300 leading-relaxed mb-3">
                As an aspiring Front-End Developer from the <strong class="text-[#58a6ff]">ALX Software Engineering program</strong>, I am deeply passionate about turning innovative ideas into tangible, user-friendly digital experiences. My journey into software engineering was fueled by a fundamental desire: <strong class="text-white">to create solutions that genuinely make life easier for people.</strong>
            </p>
            <p class="text-gray-300 leading-relaxed">
                I believe that well-crafted code has the power to solve complex problems and streamline everyday processes. This drive to build, to optimize, and to innovate is what excites me most about development, pushing me to constantly learn and grow in this dynamic field.
            </p>
        </section>

        <!-- My Vision Section -->
        <section class="section-card">
            <h2 class="text-3xl font-bold mb-4 flex items-center">
                <svg class="icon w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.01 12.01 0 002.944 12c0 2.879.617 5.645 1.76 8.114a12.008 12.008 0 0011.026 0 12.008 12.008 0 001.76-8.114 12.01 12.01 0 00-.593-5.044z"></path></svg>
                My Vision: Solutions for a Better World
            </h2>
            <p class="text-gray-300 leading-relaxed mb-3">
                My overarching aim is to leverage my skills to <strong class="text-white">design and implement solutions that simplify complex challenges and enhance daily living.</strong> I am particularly inspired by applications that bridge gaps and create accessibility, and this inspiration has led me to a specific area of focus: <strong class="text-[#58a6ff]">telehealth applications.</strong>
            </p>
            <p class="text-gray-300 leading-relaxed">
                The potential of telehealth to revolutionize healthcare access, especially in underserved communities, deeply resonates with my drive to create impactful solutions. I am eager to contribute to projects that bring healthcare closer to those who need it, making it more convenient, efficient, and equitable for everyone.
            </p>
        </section>

        <!-- Skills Section -->
        <section class="section-card">
            <h2 class="text-3xl font-bold mb-4 flex items-center">
                <svg class="icon w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.001 2.001M16 16l2.001 2.001M6 6l-.001-.001M18 6l-.001-.001M6 18l-.001-.001M18 18l-.001-.001M10 12h.01M14 12h.01M10 16h.01M14 16h.01M10 8h.01M14 8h.01M17.293 8.707l-2.586-2.586A2 2 0 0013.293 5.707L11 8H8.586a2 2 0 00-1.414.586L4.707 11.293A2 2 0 004.707 14.707L7.414 17.414A2 2 0 008.828 17H11l2.293 2.293A2 2 0 0014.707 19.293L17.414 16.586A2 2 0 0017.414 14.707L14.707 12A2 2 0 0014.707 8.707L17.293 6.121z"></path></svg>
                Skills & Technologies
            </h2>
            <div class="flex flex-wrap gap-3">
                <span class="skill-badge">HTML5</span>
                <span class="skill-badge">CSS3</span>
                <span class="skill-badge">JavaScript (ES6+)</span>
                <span class="skill-badge">React.js</span>
                <span class="skill-badge">Tailwind CSS</span>
                <span class="skill-badge">Git & GitHub</span>
                <span class="skill-badge">Responsive Design</span>
                <span class="skill-badge">Problem Solving</span>
                <span class="skill-badge">API Integration</span>
                <span class="skill-badge">User Interface (UI) Design</span>
                <span class="skill-badge">User Experience (UX) Principles</span>
            </div>
             <style>
                .skill-badge {
                    background-color: #30363d;
                    color: #c9d1d9;
                    padding: 0.5rem 1rem;
                    border-radius: 9999px; /* Fully rounded */
                    font-size: 0.875rem;
                    font-weight: 600;
                    border: 1px solid #8b949e;
                    transition: all 0.2s ease-in-out;
                }
                .skill-badge:hover {
                    background-color: #58a6ff;
                    color: #0d1117;
                    border-color: #58a6ff;
                    transform: translateY(-2px);
                }
            </style>
        </section>

        <!-- Projects Section -->
        <section class="section-card">
            <h2 class="text-3xl font-bold mb-4 flex items-center">
                <svg class="icon w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 21h7a2 2 0 002-2V9a2 2 0 00-2-2h-7a2 2 0 00-2 2v10a2 2 0 002 2zM9 3L4 8m5-5v4m5-4L9 8h4m-4 4v4m5-5H9m-4 0v4m5-5v4m5-5v4m-5-5H9m-4 0v4m5-5v4m-5-5H9"></path></svg>
                My Projects
            </h2>
            <p class="text-gray-300 leading-relaxed mb-4">
                Here are some projects I've worked on, showcasing my skills and passion for creating impactful solutions.
            </p>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-6">
                <!-- Project Card 1: Placeholder for a telehealth app -->
                <div class="bg-[#0d1117] rounded-lg p-5 border border-[#30363d] hover:border-[#58a6ff] transition duration-300">
                    <h3 class="text-xl font-semibold mb-2 text-[#58a6ff]">Telehealth Platform (Concept)</h3>
                    <p class="text-gray-400 mb-3 text-sm">
                        <em>Future Project/Concept</em> - A conceptual front-end for a telehealth application, focusing on intuitive user interfaces for appointment scheduling, virtual consultations, and secure health record access. Built with React.js and Tailwind CSS.
                    </p>
                    <div class="flex flex-wrap gap-2 text-xs">
                        <span class="px-2 py-1 bg-gray-700 rounded-md">#React</span>
                        <span class="px-2 py-1 bg-gray-700 rounded-md">#Telehealth</span>
                        <span class="px-2 py-1 bg-gray-700 rounded-md">#UI/UX</span>
                    </div>
                    <div class="mt-4 flex space-x-3">
                        <a href="[LinkToProjectRepo]" target="_blank" class="text-sm px-4 py-2 rounded-md bg-[#58a6ff] text-white hover:bg-[#438ad4] transition duration-300">
                            View Code
                        </a>
                        <!-- Optional: <a href="[LinkToLiveDemo]" target="_blank" class="text-sm px-4 py-2 rounded-md border border-[#58a6ff] text-[#58a6ff] hover:bg-[#58a6ff] hover:text-white transition duration-300">Live Demo</a> -->
                    </div>
                </div>

                <!-- Project Card 2: Placeholder for another relevant project -->
                <div class="bg-[#0d1117] rounded-lg p-5 border border-[#30363d] hover:border-[#58a6ff] transition duration-300">
                    <h3 class="text-xl font-semibold mb-2 text-[#58a6ff]">[Your ALX Project Name]</h3>
                    <p class="text-gray-400 mb-3 text-sm">
                        A project developed during my ALX studies, demonstrating proficiency in [specific technologies like HTML, CSS, JS]. It focuses on [brief description of problem solved/feature].
                    </p>
                    <div class="flex flex-wrap gap-2 text-xs">
                        <span class="px-2 py-1 bg-gray-700 rounded-md">#HTML</span>
                        <span class="px-2 py-1 bg-gray-700 rounded-md">#CSS</span>
                        <span class="px-2 py-1 bg-gray-700 rounded-md">#JavaScript</span>
                    </div>
                    <div class="mt-4 flex space-x-3">
                        <a href="[LinkToProjectRepo]" target="_blank" class="text-sm px-4 py-2 rounded-md bg-[#58a6ff] text-white hover:bg-[#438ad4] transition duration-300">
                            View Code
                        </a>
                    </div>
                </div>

                <!-- Add more project cards as needed -->

            </div>
        </section>

        <!-- GitHub Stats & Contributions (Optional but recommended) -->
        <section class="section-card text-center">
            <h2 class="text-3xl font-bold mb-4 flex items-center justify-center">
                 <svg class="icon w-8 h-8 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path></svg>
                My GitHub Contributions
            </h2>
            <p class="text-gray-300 mb-4">
                You can add dynamic GitHub stats here using tools like <a href="https://github.com/anuraghazra/github-readme-stats" target="_blank" class="text-[#58a6ff]">GitHub Readme Stats</a> or <a href="https://github.com/ryo-ma/github-profile-trophy" target="_blank" class="text-[#58a6ff]">GitHub Profile Trophy</a>.
            </p>
            <!-- Example (replace [YourGitHubUsername] with your actual username) -->
            <img src="https://github-readme-stats.vercel.app/api?username=[YourGitHubUsername]&show_icons=true&theme=dark&include_all_commits=true&count_private=true" alt="GitHub Stats" class="mx-auto my-4 w-full max-w-md">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[YourGitHubUsername]&layout=compact&theme=dark" alt="Top Languages" class="mx-auto my-4 w-full max-w-md">
            <!-- <img src="https://github-profile-trophy.vercel.app/?username=[YourGitHubUsername]&theme=dark" alt="GitHub Trophies" class="mx-auto my-4 w-full max-w-md"> -->
        </section>

        <!-- Connect Section -->
        <section class="section-card text-center">
            <h2 class="text-3xl font-bold mb-4 flex items-center justify-center">
                <svg class="icon w-8 h-8 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path></svg>
                Let's Connect!
            </h2>
            <p class="text-gray-300 leading-relaxed mb-4">
                I'm always open to collaborating on exciting projects, discussing innovative solutions, or simply connecting with fellow developers. Feel free to reach out!
            </p>
            <div class="flex justify-center space-x-6 text-xl">
                <a href="https://linkedin.com/in/[BernardBaako]" target="_blank" class="text-[#58a6ff] hover:text-white transition duration-300">LinkedIn</a>
                <a href="mailto:[bernardishaque@gmaiil.com]" class="text-[#58a6ff] hover:text-white transition duration-300">Email</a>
                <a href="https://twitter.com/[@bbish97]" target="_blank" class="text-[#58a6ff] hover:text-white transition duration-300">Twitter</a>
                <!-- Add other social links if desired -->
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center text-gray-500 text-sm mt-10">
            <p>&copy; 2025 Bernard Baako. All Rights Reserved. Built with passion and code.</p>
        </footer>

    </div>

</body>
</html>

