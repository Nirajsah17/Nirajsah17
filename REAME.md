<!DOCTYPE html>
<html lang="en" class="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Niraj Kumar Sah - GitHub Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        background: 'var(--background)',
                        foreground: 'var(--foreground)',
                        primary: 'var(--primary)',
                        muted: 'var(--muted)',
                    },
                    keyframes: {
                        fadeIn: {
                            '0%': { opacity: '0', transform: 'translateY(10px)' },
                            '100%': { opacity: '1', transform: 'translateY(0)' },
                        },
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-5px)' },
                        },
                    },
                    animation: {
                        fadeIn: 'fadeIn 0.5s ease-out forwards',
                        float: 'float 3s ease-in-out infinite',
                    },
                },
            },
        }
    </script>
    <style>
        :root {
            --background: #ffffff;
            --foreground: #000000;
            --primary: #0070f3;
            --muted: #6b7280;
        }
        .dark {
            --background: #1a202c;
            --foreground: #ffffff;
            --primary: #3b82f6;
            --muted: #9ca3af;
        }
        .animate-delay-100 { animation-delay: 100ms; }
        .animate-delay-200 { animation-delay: 200ms; }
        .animate-delay-300 { animation-delay: 300ms; }
        .animate-delay-400 { animation-delay: 400ms; }
        .animate-delay-500 { animation-delay: 500ms; }
    </style>
</head>
<body class="bg-background text-foreground min-h-screen transition-colors duration-300">
    <div class="container mx-auto p-4 space-y-6">
        <!-- Theme Toggle Button -->
        <button id="themeToggle" class="fixed top-4 right-4 p-2 rounded-full bg-primary text-background transition-transform hover:scale-110 focus:outline-none focus:ring-2 focus:ring-primary focus:ring-opacity-50 cursor-pointer">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" />
            </svg>
        </button>

        <!-- Header -->
        <header class="flex flex-col md:flex-row items-center gap-4 animate-fadeIn">
            <img alt="javascript" src="images/niraj.png" alt="Profile picture" class="w-24 h-24 md:w-32 md:h-32 rounded-full animate-float">
            <div class="text-center md:text-left">
                <h1 class="text-2xl font-bold">Niraj Kumar Sah</h1>
                <p class="text-muted">Software engineer @Mapmyindia</p>
                <p class="text-muted">nirajnsp5@gmail.com</p>
            </div>
        </header>

        <!-- About Me -->
        <section class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg animate-fadeIn animate-delay-100">
            <h2 class="text-xl font-bold mb-2">About Me</h2>
            <p>
                Passionate and dedicated Front-End Developer with 3+ years of experience in building optimized and user-friendly web interfaces.
                Proficient with HTML, CSS, JavaScript, TypeScript, and ReactJs. Seeking to bring technical expertise and problem-solving skills to a
                dynamic product development team.
            </p>
        </section>

        <!-- Connect -->
        <section class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg animate-fadeIn animate-delay-200">
            <h2 class="text-xl font-bold mb-2">Connect</h2>
            <div class="flex flex-wrap gap-2">
                <a href="mailto:nirajsnp5@gmail.com" target="_blank" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">
                    <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    Email
                </a>
                <a href="https://linkedin.com/in/niraj-kumar-21142817b" target="_blank" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">
                    <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
                    LinkedIn
                </a>
                <a href="https://twitter.com/niraj71177480" target="_blank" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">
                    <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/></svg>
                    Twitter
                </a>
            </div>
        </section>

        <!-- Projects -->
        <section class="animate-fadeIn animate-delay-300">
            <h2 class="text-2xl font-bold mb-4">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg transform hover:-translate-y-1">
                    <h3 class="font-bold mb-2">Edito (code editor)</h3>
                    <p class="text-muted mb-4">A simple in browser code editor with storage support in browser IndexDb</p>
                    <div class="flex justify-between">
                        <a href="https://np-helix-editor.netlify.app/" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Launch</a>
                        <a href="https://github.com/Nirajsah17/edito" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Code</a>
                        <a href="https://github.com/Nirajsah17/edito/pulls" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Contribute</a>
                    </div>
                </div>
                <div class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg transform hover:-translate-y-1">
                    <h3 class="font-bold mb-2">Snake Game</h3>
                    <p class="text-muted mb-4">A classic snake game powered by angular and apk build through capacitor</p>
                    <div class="flex justify-between">
                        <a href="https://nirajsah-snake.netlify.app/" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Launch</a>
                        <a href="https://github.com/Nirajsah17/snake" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Code</a>
                        <a href="https://github.com/Nirajsah17/snake/pulls" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Contribute</a>
                    </div>
                </div>
                <div class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg transform hover:-translate-y-1">
                    <h3 class="font-bold mb-2">Image Editor</h3>
                    <p class="text-muted mb-4">Edit Image in browser basic image editor functionality like zoom pan filter and more...</p>
                    <div class="flex justify-between">
                        <a href="https://chhavie-ditor.netlify.app/" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Launch</a>
                        <a href="https://github.com/Nirajsah17/chhavi" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Code</a>
                        <a href="https://github.com/Nirajsah17/chhavi/pulls" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Contribute</a>
                    </div>
                </div>
                <div class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg transform hover:-translate-y-1">
                  <h3 class="font-bold mb-2">My Learning</h3>
                  <p class="text-muted mb-4">To keep track of my learning and references will be available here as a static site</p>
                  <div class="flex justify-between">
                      <a href="https://nirajsah17.github.io/practice/" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Launch</a>
                      <a href="https://github.com/Nirajsah17/practice" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Code</a>
                      <a href="https://github.com/Nirajsah17/practice" target="_blank" class="px-3 py-2 text-sm font-medium text-center text-foreground bg-background border rounded-lg transition-colors duration-300 hover:bg-primary hover:text-background">Contribute</a>
                  </div>
              </div>
            </div>
        </section>

        <!-- Technologies -->
        <section class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg animate-fadeIn animate-delay-400">
            <h2 class="text-xl font-bold mb-2">Technologies</h2>
            <div class="flex flex-wrap gap-2">
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="javascript" src="https://img.shields.io/badge/-JavaScript-gray?style=flat-square&logo=javascript"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="Angular" src="https://img.shields.io/badge/-Angular-gray?style=flat-square&logo=Angular"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="React" src="https://img.shields.io/badge/-React-gray?style=flat-square&logo=React"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="html5" src="https://img.shields.io/badge/-HTML-gray?style=flat-square&logo=html5"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="css3" src="https://img.shields.io/badge/-css-gray?style=flat-square&logo=css3"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="git" src="https://img.shields.io/badge/-GIT-gray?style=flat-square&logo=git"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="gitlab" src="https://img.shields.io/badge/-GitLab-gray?style=flat-square&logo=gitlab"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="node.js" src="https://img.shields.io/badge/-node.js-gray?style=flat-square&logo=node.js"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="express" src="https://img.shields.io/badge/-Express-gray?style=flat-square&logo=express"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="mongodb" src="https://img.shields.io/badge/-MongoDB-gray?style=flat-square&logo=Mongodb"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="postgresql" src="https://img.shields.io/badge/-PostgresSQL-gray?style=flat-square&logo=postgresql"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="bash scripting" src="https://img.shields.io/badge/-Shell Scripting-gray?style=flat-square&logo=gnu-bash"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="docker" src="https://img.shields.io/badge/-Docker-gray?style=flat-square&logo=docker"/></span>
                <span class="px-2 py-1 text-sm font-medium bg-muted text-background rounded transition-transform hover:scale-105"><img alt="linux" src="https://img.shields.io/badge/-Linux-gray?style=flat-square&logo=linux"/></span>
            </div>
        </section>

        <!-- Experience -->
        <section class="bg-background border rounded-lg p-4 shadow transition-all duration-300 hover:shadow-lg animate-fadeIn animate-delay-500">
            <h2 class="text-xl font-bold mb-2">Experience</h2>
            <p class="text-muted">Design and Developed web applications using webcomponent technologies(custom elements, html template, shadow DOM, custom events), Javascript and React.
              Managing Backend services using docker, docker compose for smooth deliverable of micro-services. Implemented high availability proxy for postgresql database that reduces the load from database</p>
        </section>
    </div>

    <script>
        const themeToggle = document.getElementById('themeToggle');
        const html = document.documentElement;

        themeToggle.addEventListener('click', () => {
            html.classList.toggle('dark');
            updateThemeToggleIcon();
        });

        function updateThemeToggleIcon() {
            const isDark = html.classList.contains('dark');
            themeToggle.innerHTML = isDark
                ? '<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z" /></svg>'
                : '<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" /></svg>';
        }

        // Initialize the icon based on the initial theme
        updateThemeToggleIcon();
    </script>
</body>
</html>