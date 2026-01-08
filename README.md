<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md border-b border-gray-100">
        <div class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="text-xl font-bold tracking-tighter">YOUR NAME.</span>
            <div class="space-x-8 hidden md:block">
                <a href="#work" class="hover:text-blue-600 transition">Work</a>
                <a href="#about" class="hover:text-blue-600 transition">About</a>
                <a href="mailto:your@email.com" class="bg-black text-white px-5 py-2 rounded-full text-sm font-medium hover:bg-gray-800 transition">Contact</a>
            </div>
        </div>
    </nav>

    <section class="pt-32 pb-20 px-6">
        <div class="max-w-5xl mx-auto">
            <h1 class="text-5xl md:text-7xl font-bold leading-tight mb-6">
                Product Designer & <br><span class="text-blue-600">Problem Solver.</span>
            </h1>
            <p class="text-xl text-gray-600 max-w-2xl mb-8">
                I build digital experiences that are functional, accessible, and beautiful. Currently focusing on building scalable web applications.
            </p>
            <div class="flex gap-4">
                <a href="#work" class="bg-blue-600 text-white px-8 py-4 rounded-lg font-semibold hover:bg-blue-700 transition">View My Projects</a>
                <a href="#" class="border border-gray-300 px-8 py-4 rounded-lg font-semibold hover:bg-gray-100 transition">Download CV</a>
            </div>
        </div>
    </section>

    <section id="work" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-3xl font-bold mb-12">Selected Work</h2>
            
            <div class="grid md:grid-cols-2 gap-10">
                <div class="group cursor-pointer">
                    <div class="overflow-hidden rounded-2xl bg-gray-200 mb-4">
                        <img src="https://via.placeholder.com/600x400" alt="Project 1" class="group-hover:scale-105 transition duration-500">
                    </div>
                    <h3 class="text-xl font-bold">E-Commerce Redesign</h3>
                    <p class="text-gray-500">UI/UX · Development</p>
                </div>

                <div class="group cursor-pointer">
                    <div class="overflow-hidden rounded-2xl bg-gray-200 mb-4">
                        <img src="https://via.placeholder.com/600x400" alt="Project 2" class="group-hover:scale-105 transition duration-500">
                    </div>
                    <h3 class="text-xl font-bold">Fintech Dashboard</h3>
                    <p class="text-gray-500">React · Tailwind</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-20 px-6 bg-gray-50">
        <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-12 items-center">
            <div>
                <h2 class="text-3xl font-bold mb-6">Technical Toolkit</h2>
                <div class="flex flex-wrap gap-3">
                    <span class="px-4 py-2 bg-white border border-gray-200 rounded-full text-sm">JavaScript (ES6+)</span>
                    <span class="px-4 py-2 bg-white border border-gray-200 rounded-full text-sm">React.js</span>
                    <span class="px-4 py-2 bg-white border border-gray-200 rounded-full text-sm">Node.js</span>
                    <span class="px-4 py-2 bg-white border border-gray-200 rounded-full text-sm">Python</span>
                    <span class="px-4 py-2 bg-white border border-gray-200 rounded-full text-sm">Figma</span>
                </div>
            </div>
            <div class="bg-blue-600 p-8 rounded-3xl text-white">
                <h3 class="text-2xl font-bold mb-4">Let's build something together.</h3>
                <p class="mb-6 opacity-90">I'm currently looking for new opportunities. If you have a project in mind, let's chat.</p>
                <a href="mailto:your@email.com" class="inline-block bg-white text-blue-600 px-6 py-3 rounded-xl font-bold hover:bg-gray-100 transition">Get In Touch</a>
            </div>
        </div>
    </section>

    <footer class="py-10 border-t border-gray-200 text-center text-gray-500 text-sm">
        <p>&copy; 2026 Your Name. Built with precision.</p>
    </footer>

</body>
</html>
