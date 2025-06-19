<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Naveen Prasath P - README Profile</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .skill-tag {
            transition: all 0.3s ease;
        }
        .skill-tag:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        }
        .section-header {
            position: relative;
            display: inline-block;
        }
        .section-header:after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            border-radius: 2px;
        }
        @media print {
            body { -webkit-print-color-adjust: exact; }
            .no-print { display: none !important; }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <div class="min-h-screen">
        <!-- Header Section -->
        <div class="gradient-bg text-white py-12">
            <div class="max-w-4xl mx-auto px-6 text-center">
                <div class="mb-8">
                    <div class="w-32 h-32 mx-auto mb-6 bg-white bg-opacity-20 rounded-full flex items-center justify-center">
                        <i class="fas fa-user text-5xl text-white opacity-80"></i>
                    </div>
                    <h1 class="text-5xl font-bold mb-4">Hi 👋, I'm Naveen Prasath</h1>
                    <div class="text-xl space-y-2">
                        <div class="font-medium">Graphic Designer</div>
                        <div class="text-lg opacity-90">| Brand Strategist | UI Designer |</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="max-w-4xl mx-auto px-6 py-12">
            <!-- About Me Section -->
            <section class="mb-12">
                <h2 class="section-header text-3xl font-bold mb-6">
                    <i class="fas fa-user-circle mr-3 text-indigo-600"></i>About Me
                </h2>
                <div class="bg-white rounded-lg shadow-md p-8">
                    <p class="text-lg leading-relaxed mb-6">
                        I am a B.Tech student specializing in <strong>Artificial Intelligence and Data Science</strong> at Kathir College of Engineering. With a deep passion for <strong>Graphic Design, Video editing, Logo Design, AI & Machine Learning</strong>, I am passionate about leveraging design and <strong>technology to solve complex visual challenges.</strong>
                    </p>
                    <p class="text-lg leading-relaxed">
                        A passionate and motivated aspiring graphic designer with a solid foundation in design principles and a keen eye for aesthetics. Eager to bring fresh ideas and creativity to a professional setting, leveraging a deep understanding of design theory and techniques. Committed to reshaping human perception through innovative and compelling design.
                    </p>
                    
                    <div class="mt-8 grid md:grid-cols-2 gap-4 text-gray-700">
                        <div class="flex items-center">
                            <i class="fas fa-map-marker-alt text-indigo-600 mr-3"></i>
                            <span>Based in Coimbatore, Tamil Nadu, India</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-graduation-cap text-indigo-600 mr-3"></i>
                            <span>Pursuing B.Tech AI & Data Science</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-handshake text-indigo-600 mr-3"></i>
                            <span>Open to collaborating on UI & Graphic Design</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-brain text-indigo-600 mr-3"></i>
                            <span>Currently learning Advanced AI techniques</span>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Professional Skills Section -->
            <section class="mb-12">
                <h2 class="section-header text-3xl font-bold mb-6">
                    <i class="fas fa-tools mr-3 text-indigo-600"></i>Professional Skills
                </h2>
                <div class="bg-white rounded-lg shadow-md p-8">
                    <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
                        <div class="skill-tag bg-gradient-to-r from-orange-400 to-red-500 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fab fa-html5 mr-2"></i>HTML & CSS
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-yellow-400 to-orange-500 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fab fa-js-square mr-2"></i>JavaScript
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-blue-500 to-purple-600 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fas fa-robot mr-2"></i>Machine Learning
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-yellow-600 to-red-600 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fas fa-vector-square mr-2"></i>Illustrator
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-blue-600 to-blue-800 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fab fa-python mr-2"></i>Python
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-blue-400 to-blue-600 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fas fa-image mr-2"></i>Photoshop
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-purple-500 to-purple-700 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fas fa-video mr-2"></i>After Effects
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-green-500 to-teal-600 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fas fa-brain mr-2"></i>Deep Learning
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-pink-500 to-red-500 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fas fa-drafting-compass mr-2"></i>Figma
                        </div>
                        <div class="skill-tag bg-gradient-to-r from-indigo-500 to-purple-600 text-white px-4 py-3 rounded-lg text-center font-medium">
                            <i class="fas fa-mobile-alt mr-2"></i>UI & UX
                        </div>
                    </div>
                </div>
            </section>

            <!-- Experience Section -->
            <section class="mb-12">
                <h2 class="section-header text-3xl font-bold mb-6">
                    <i class="fas fa-briefcase mr-3 text-indigo-600"></i>Professional Experience
                </h2>
                <div class="space-y-6">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <div class="flex items-start justify-between mb-4">
                            <div>
                                <h3 class="text-xl font-bold text-gray-800">Graphic Designer</h3>
                                <p class="text-indigo-600 font-medium">Bhogan Mediasoft</p>
                            </div>
                            <span class="text-sm text-gray-500 bg-gray-100 px-3 py-1 rounded-full">Jan 2025 - May 2025</span>
                        </div>
                        <p class="text-gray-600">Development team member creating clear visuals and brand elements, designing for various media to boost user experience and support marketing initiatives.</p>
                    </div>

                    <div class="bg-white rounded-lg shadow-md p-6">
                        <div class="flex items-start justify-between mb-4">
                            <div>
                                <h3 class="text-xl font-bold text-gray-800">Professional Service Director</h3>
                                <p class="text-indigo-600 font-medium">Rotaract Club of Coimbatore Royals</p>
                            </div>
                            <span class="text-sm text-gray-500 bg-gray-100 px-3 py-1 rounded-full">July 2024 - May 2025</span>
                        </div>
                        <ul class="text-gray-600 space-y-2">
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i>Managing Professional Service Projects</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i>Documentation of Professional Service Projects and records</li>
                        </ul>
                    </div>

                    <div class="bg-white rounded-lg shadow-md p-6">
                        <div class="flex items-start justify-between mb-4">
                            <div>
                                <h3 class="text-xl font-bold text-gray-800">Photography Club Co-Ordinator</h3>
                                <p class="text-indigo-600 font-medium">Adept Association, Kathir College of Engineering</p>
                            </div>
                            <span class="text-sm text-gray-500 bg-gray-100 px-3 py-1 rounded-full">Aug 2023 - July 2024</span>
                        </div>
                        <ul class="text-gray-600 space-y-2">
                            <li><i class="fas fa-camera text-blue-500 mr-2"></i>Led photography workshops to enhance skills in various photography techniques</li>
                            <li><i class="fas fa-graduation-cap text-blue-500 mr-2"></i>Organized photo exhibitions and knowledge-sharing sessions</li>
                            <li><i class="fas fa-users text-blue-500 mr-2"></i>Guided peers in exploring different photography styles and careers in visual arts</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- Technical Stack Section -->
            <section class="mb-12">
                <h2 class="section-header text-3xl font-bold mb-6">
                    <i class="fas fa-code mr-3 text-indigo-600"></i>Language and Tools
                </h2>
                <div class="bg-white rounded-lg shadow-md p-8">
                    <div class="grid grid-cols-6 md:grid-cols-8 lg:grid-cols-10 gap-6 items-center justify-items-center">
                        <div class="text-center">
                            <i class="fab fa-python text-4xl text-blue-600 mb-2"></i>
                            <p class="text-xs">Python</p>
                        </div>
                        <div class="text-center">
                            <i class="fab fa-git-alt text-4xl text-red-600 mb-2"></i>
                            <p class="text-xs">Git</p>
                        </div>
                        <div class="text-center">
                            <i class="fab fa-js-square text-4xl text-yellow-500 mb-2"></i>
                            <p class="text-xs">JavaScript</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-code text-4xl text-blue-500 mb-2"></i>
                            <p class="text-xs">VS Code</p>
                        </div>
                        <div class="text-center">
                            <i class="fab fa-html5 text-4xl text-orange-600 mb-2"></i>
                            <p class="text-xs">HTML5</p>
                        </div>
                        <div class="text-center">
                            <i class="fab fa-css3-alt text-4xl text-blue-600 mb-2"></i>
                            <p class="text-xs">CSS3</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-database text-4xl text-blue-700 mb-2"></i>
                            <p class="text-xs">PostgreSQL</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-vector-square text-4xl text-orange-500 mb-2"></i>
                            <p class="text-xs">Illustrator</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-pen-nib text-4xl text-purple-600 mb-2"></i>
                            <p class="text-xs">Adobe XD</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-drafting-compass text-4xl text-pink-500 mb-2"></i>
                            <p class="text-xs">Figma</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-fire text-4xl text-orange-600 mb-2"></i>
                            <p class="text-xs">PyTorch</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-image text-4xl text-blue-600 mb-2"></i>
                            <p class="text-xs">Photoshop</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-brain text-4xl text-orange-500 mb-2"></i>
                            <p class="text-xs">TensorFlow</p>
                        </div>
                        <div class="text-center">
                            <i class="fas fa-video text-4xl text-purple-600 mb-2"></i>
                            <p class="text-xs">After Effects</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Additional Skills Section -->
            <section class="mb-12">
                <h2 class="section-header text-3xl font-bold mb-6">
                    <i class="fas fa-star mr-3 text-indigo-600"></i>Additional Skills
                </h2>
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="text-xl font-semibold mb-4 text-gray-800">
                            <i class="fas fa-lightbulb text-yellow-500 mr-2"></i>Non-Technical Skills
                        </h3>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm">Consistency</span>
                            <span class="bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm">Editing</span>
                            <span class="bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm">Team Work</span>
                            <span class="bg-orange-100 text-orange-800 px-3 py-1 rounded-full text-sm">Problem-Solving</span>
                            <span class="bg-red-100 text-red-800 px-3 py-1 rounded-full text-sm">Work Ethic</span>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6">
                        <h3 class="text-xl font-semibold mb-4 text-gray-800">
                            <i class="fas fa-language text-green-500 mr-2"></i>Languages
                        </h3>
                        <div class="space-y-3">
                            <div class="flex items-center justify-between">
                                <span class="font-medium">English</span>
                                <div class="flex space-x-1">
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-gray-300"></i>
                                </div>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="font-medium">Tamil</span>
                                <div class="flex space-x-1">
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- GitHub Stats -->
            <section class="mb-12 text-center">
                <h2 class="section-header text-3xl font-bold mb-6">
                    <i class="fas fa-chart-line mr-3 text-indigo-600"></i>GitHub Statistics
                </h2>
                <div class="bg-white rounded-lg shadow-md p-8">
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=NaveenKitty14&theme=default" alt="GitHub Streak Stats" class="mx-auto rounded-lg shadow-sm">
                </div>
            </section>

            <!-- Footer -->
            <section class="text-center py-8">
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold mb-4">Let's Connect!</h3>
                    <p class="text-gray-600 mb-4">Feel free to reach out for collaborations, opportunities, or just to say hello!</p>
                    <div class="inline-flex items-center justify-center bg-gradient-to-r from-blue-500 to-purple-600 text-white px-6 py-3 rounded-full font-medium">
                        <i class="fab fa-linkedin mr-2"></i>
                        Connect with me on LinkedIn
                    </div>
                </div>
            </section>
        </div>
    </div>
</body>
</html>
