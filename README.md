<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farid Ahmed | Technical Project Manager & Digital Transformation Leader</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            background-color: #0b0f19;
            color: #f3f4f6;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
        }
        .glass-card {
            background: rgba(17, 24, 39, 0.7);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glass-nav {
            background: rgba(11, 15, 25, 0.8);
            backdrop-filter: blur(16px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
        }
        .accent-gradient {
            background: linear-gradient(135deg, #3b82f6 0%, #06b6d4 100%);
        }
        .text-gradient {
            background: linear-gradient(135deg, #60a5fa 0%, #38bdf8 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <header class="fixed top-0 left-0 right-0 z-50 glass-nav">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="text-xl font-bold tracking-tight text-white">FARID<span class="text-blue-500">.AHMED</span></a>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-gray-300">
                <a href="#about" class="hover:text-blue-400 transition-colors">About</a>
                <a href="#projects" class="hover:text-blue-400 transition-colors">Products</a>
                <a href="#experience" class="hover:text-blue-400 transition-colors">Experience</a>
                <a href="#skills" class="hover:text-blue-400 transition-colors">Skills & Tools</a>
                <a href="#certifications" class="hover:text-blue-400 transition-colors">Certifications</a>
            </nav>
            <a href="#contact" class="hidden md:inline-flex items-center justify-center px-5 py-2.5 text-sm font-semibold text-white accent-gradient rounded-lg shadow-lg hover:opacity-90 transition-all">
                Let's Connect
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="pt-36 pb-20 md:pt-44 md:pb-32 max-w-7xl mx-auto px-6">
        <div class="grid md:grid-cols-12 gap-12 items-center">
            <div class="md:col-span-8 space-y-6">
                <div class="inline-flex items-center space-x-2 px-3.5 py-1.5 rounded-full glass-card text-blue-400 text-xs font-semibold">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                    <span>Available for Executive Project Leadership</span>
                </div>
                <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white leading-tight">
                    Driving Digital Transformation & <span class="text-gradient">FinTech Delivery</span>
                </h1>
                <p class="text-lg text-gray-400 max-w-2xl leading-relaxed">
                    Technical Project Manager with 5+ years of experience steering enterprise SaaS, FinTech platforms, and high-scale operations. Specialized in SLA governance, API integrations, and Agile delivery.
                </p>
                <div class="flex flex-wrap gap-4 pt-4">
                    <a href="#contact" class="px-6 py-3.5 text-sm font-semibold text-white accent-gradient rounded-xl shadow-lg hover:opacity-90 transition-all flex items-center space-x-2">
                        <span>Get in Touch</span>
                        <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </a>
                    <a href="https://github.com/faridahmed75" target="_blank" class="px-6 py-3.5 text-sm font-semibold text-gray-300 glass-card rounded-xl hover:bg-gray-800 transition-all flex items-center space-x-2">
                        <i data-lucide="github" class="w-4 h-4"></i>
                        <span>GitHub Profile</span>
                    </a>
                </div>
            </div>
            
            <div class="md:col-span-4">
                <div class="glass-card p-6 rounded-2xl border border-gray-800 space-y-4">
                    <h3 class="text-xs font-bold uppercase tracking-wider text-gray-400">Direct Contact</h3>
                    <div class="space-y-3">
                        <a href="mailto:faridahmed75bd@gmail.com" class="flex items-center space-x-3 text-sm text-gray-300 hover:text-blue-400 transition-colors">
                            <i data-lucide="mail" class="w-4 h-4 text-blue-500"></i>
                            <span>faridahmed75bd@gmail.com</span>
                        </a>
                        <a href="tel:+8801759433577" class="flex items-center space-x-3 text-sm text-gray-300 hover:text-blue-400 transition-colors">
                            <i data-lucide="phone" class="w-4 h-4 text-blue-500"></i>
                            <span>+880 1759-433577</span>
                        </a>
                        <div class="flex items-center space-x-3 text-sm text-gray-300">
                            <i data-lucide="map-pin" class="w-4 h-4 text-blue-500"></i>
                            <span>Dhaka, Bangladesh</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Metrics Bar -->
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-16 pt-12 border-t border-gray-800">
            <div class="glass-card p-6 rounded-xl">
                <div class="text-3xl font-extrabold text-white">99.95%</div>
                <div class="text-sm text-gray-400 mt-1">System Stability Maintained</div>
            </div>
            <div class="glass-card p-6 rounded-xl">
                <div class="text-3xl font-extrabold text-white">95%</div>
                <div class="text-sm text-gray-400 mt-1">Transaction Success Rate[cite: 1]</div>
            </div>
            <div class="glass-card p-6 rounded-xl">
                <div class="text-3xl font-extrabold text-white">12+</div>
                <div class="text-sm text-gray-400 mt-1">Banking Partnerships Managed[cite: 1]</div>
            </div>
            <div class="glass-card p-6 rounded-xl">
                <div class="text-3xl font-extrabold text-white">35+</div>
                <div class="text-sm text-gray-400 mt-1">Enterprise Service Integrations[cite: 1]</div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-950/50">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-sm font-bold uppercase tracking-widest text-blue-500 mb-2">Executive Summary</h2>
            <h3 class="text-3xl font-bold text-white mb-8">Bridging Strategy, Technology & Execution</h3>
            <div class="grid md:grid-cols-2 gap-8 text-gray-300 leading-relaxed">
                <p>
                    Accomplished Project Management Professional with 5+ years of hands-on experience driving end-to-end software delivery, SaaS products, FinTech implementations, and large-scale digital transformation initiatives[cite: 1]. Proven expertise in translating complex executive visions into structured project plans, risk-mitigated strategies, and high-velocity engineering outcomes[cite: 1].
                </p>
                <p>
                    Experienced in building operational centers from the ground up, executing banking integration platforms, and leading cross-functional teams spanning SQA, Systems Engineering, and UX Design[cite: 1]. Adept at applying Agile/Scrum methodologies, SLA governance, and AI-assisted workflows to maximize business value[cite: 1].
                </p>
            </div>
        </div>
    </section>

    <!-- Flagship Products / Projects Section -->
    <section id="projects" class="py-20 max-w-7xl mx-auto px-6">
        <h2 class="text-sm font-bold uppercase tracking-widest text-blue-500 mb-2">Portfolio Showcase</h2>
        <h3 class="text-3xl font-bold text-white mb-12">Featured Products & Enterprise Solutions</h3>

        <div class="grid md:grid-cols-2 gap-8">
            <!-- Project 1 -->
            <div class="glass-card p-8 rounded-2xl hover:border-blue-500/50 transition-all">
                <div class="flex justify-between items-start mb-4">
                    <span class="px-3 py-1 text-xs font-semibold text-blue-400 bg-blue-500/10 rounded-full">FinTech Platform</span>
                    <i data-lucide="shield-check" class="w-6 h-6 text-blue-400"></i>
                </div>
                <h4 class="text-2xl font-bold text-white mb-3">Sheba Pay & Digital Loan Integration</h4>
                <p class="text-gray-400 text-sm mb-6 leading-relaxed">
                    Spearheaded digital payment infrastructure and loan product deployments integrated with multiple banking platforms[cite: 1]. Scaled core DFS/MFS success rates from 65% to 95% across bill payments, top-ups, and distributor settlements[cite: 1].
                </p>
                <div class="flex flex-wrap gap-2">
                    <span class="px-2.5 py-1 text-xs bg-gray-800 text-gray-300 rounded">Banking APIs</span>
                    <span class="px-2.5 py-1 text-xs bg-gray-800 text-gray-300 rounded">DFS / MFS</span>
                    <span class="px-2.5 py-1 text-xs bg-gray-800 text-gray-300 rounded">SLA Governance</span>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="glass-card p-8 rounded-2xl hover:border-blue-500/50 transition-all">
                <div class="flex justify-between items-start mb-4">
                    <span class="px-3 py-1 text-xs font-semibold text-cyan-400 bg-cyan-500/10 rounded-full">Enterprise Operations</span>
                    <i data-lucide="cpu" class="w-6 h-6 text-cyan-400"></i>
                </div>
                <h4 class="text-2xl font-bold text-white mb-3">Sheba Pulse</h4>
                <p class="text-gray-400 text-sm mb-6 leading-relaxed">
                    Designed and launched an enterprise workflow automation and incident escalation platform serving 350+ active users across 20+ internal teams[cite: 1]. Boosted operational ticket handling efficiency by ~65%[cite: 1].
                </p>
                <div class="flex flex-wrap gap-2">
                    <span class="px-2.5 py-1 text-xs bg-gray-800 text-gray-300 rounded">Workflow Automation</span>
                    <span class="px-2.5 py-1 text-xs bg-gray-800 text-gray-300 rounded">Centralized Analytics</span>
                    <span class="px-2.5 py-1 text-xs bg-gray-800 text-gray-300 rounded">Incidents</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Professional Experience Timeline -->
    <section id="experience" class="py-20 bg-gray-950/50">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-sm font-bold uppercase tracking-widest text-blue-500 mb-2">Career Trajectory</h2>
            <h3 class="text-3xl font-bold text-white mb-12">Work Experience</h3>

            <div class="space-y-8 relative before:absolute before:inset-0 before:left-3 md:before:left-1/2 before:-ml-px before:w-0.5 before:bg-gray-800">
                
                <!-- Role 1 -->
                <div class="relative flex items-start md:justify-between group">
                    <div class="flex items-center w-full">
                        <div class="w-full md:w-1/2 md:pr-8">
                            <div class="glass-card p-6 rounded-xl border border-gray-800">
                                <span class="text-xs text-blue-400 font-semibold">Oct 2025 - Present</span>
                                <h4 class="text-xl font-bold text-white mt-1">Project Manager</h4>
                                <p class="text-sm text-gray-400 mb-4">Sheba Platform Limited (Reported to Group CEO)[cite: 1]</p>
                                <ul class="text-sm text-gray-400 space-y-2 list-disc list-inside">
                                    <li>Manage strategic partnerships with 12+ banks and 35+ enterprise service providers[cite: 1].</li>
                                    <li>Supervise product priorities, departmental budgets, SLA governance, and executive KPI reporting[cite: 1].</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Role 2 -->
                <div class="relative flex items-start md:justify-between group">
                    <div class="flex items-center w-full">
                        <div class="w-full md:w-1/2 md:ml-auto md:pl-8">
                            <div class="glass-card p-6 rounded-xl border border-gray-800">
                                <span class="text-xs text-blue-400 font-semibold">Apr 2024 - Oct 2025</span>
                                <h4 class="text-xl font-bold text-white mt-1">Asst. Manager, System Operations Center (SOC)</h4>
                                <p class="text-sm text-gray-400 mb-4">Sheba Platform Limited[cite: 1]</p>
                                <ul class="text-sm text-gray-400 space-y-2 list-disc list-inside">
                                    <li>Led a 25+ cross-functional organization covering System Engineering, SQA, and SRE[cite: 1].</li>
                                    <li>Increased overall system stability from 88.85% to 99.95%[cite: 1].</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Role 3 -->
                <div class="relative flex items-start md:justify-between group">
                    <div class="flex items-center w-full">
                        <div class="w-full md:w-1/2 md:pr-8">
                            <div class="glass-card p-6 rounded-xl border border-gray-800">
                                <span class="text-xs text-blue-400 font-semibold">Feb 2023 - Mar 2024</span>
                                <h4 class="text-xl font-bold text-white mt-1">Senior Project Manager</h4>
                                <p class="text-sm text-gray-400 mb-4">IT Valley BD[cite: 1]</p>
                                <ul class="text-sm text-gray-400 space-y-2 list-disc list-inside">
                                    <li>Delivered tech solutions across 30+ educational institutions & 5+ corporate groups[cite: 1].</li>
                                    <li>Increased sales revenue by 15% through optimized project delivery[cite: 1].</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Tooling & Certifications -->
    <section id="skills" class="py-20 max-w-7xl mx-auto px-6">
        <h2 class="text-sm font-bold uppercase tracking-widest text-blue-500 mb-2">Competencies & Tools</h2>
        <h3 class="text-3xl font-bold text-white mb-12">Technical Toolkit</h3>

        <div class="grid md:grid-cols-3 gap-6">
            <div class="glass-card p-6 rounded-xl">
                <h4 class="text-lg font-bold text-white mb-4 flex items-center space-x-2">
                    <i data-lucide="layout-grid" class="w-5 h-5 text-blue-400"></i>
                    <span>Delivery & Agile</span>
                </h4>
                <div class="flex flex-wrap gap-2 text-xs">
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Jira</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">ClickUp</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Scrum</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Kanban</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">ITIL Framework</span>
                </div>
            </div>

            <div class="glass-card p-6 rounded-xl">
                <h4 class="text-lg font-bold text-white mb-4 flex items-center space-x-2">
                    <i data-lucide="bar-chart-2" class="w-5 h-5 text-cyan-400"></i>
                    <span>Analytics & Governance</span>
                </h4>
                <div class="flex flex-wrap gap-2 text-xs">
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Metabase</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Power BI</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Grafana</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">SQL</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">GRC Framework</span>
                </div>
            </div>

            <div class="glass-card p-6 rounded-xl">
                <h4 class="text-lg font-bold text-white mb-4 flex items-center space-x-2">
                    <i data-lucide="sparkles" class="w-5 h-5 text-indigo-400"></i>
                    <span>AI & Innovation</span>
                </h4>
                <div class="flex flex-wrap gap-2 text-xs">
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Generative AI</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">ChatGPT</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Claude</span>
                    <span class="px-3 py-1.5 bg-gray-800 text-gray-300 rounded-lg">Workflow Automation</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Certifications & Education -->
    <section id="certifications" class="py-20 bg-gray-950/50">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-sm font-bold uppercase tracking-widest text-blue-500 mb-2">Qualifications</h2>
            <h3 class="text-3xl font-bold text-white mb-12">Education & Professional Certifications</h3>

            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <h4 class="text-lg font-bold text-white mb-4">Certifications</h4>
                    <div class="space-y-4">
                        <div class="glass-card p-4 rounded-xl">
                            <div class="font-bold text-white">Generative AI Overview for Project Managers</div>
                            <div class="text-xs text-blue-400">Project Management Institute (PMI)</div>
                        </div>
                        <div class="glass-card p-4 rounded-xl">
                            <div class="font-bold text-white">ISO 31000 & Gen AI - Risk & Compliance</div>
                            <div class="text-xs text-blue-400">Global Skill Development Council (GSDC)</div>
                        </div>
                        <div class="glass-card p-4 rounded-xl">
                            <div class="font-bold text-white">Professional Diploma in Agile and Scrum</div>
                            <div class="text-xs text-blue-400">Udemy</div>
                        </div>
                    </div>
                </div>

                <div>
                    <h4 class="text-lg font-bold text-white mb-4">Education</h4>
                    <div class="space-y-4">
                        <div class="glass-card p-4 rounded-xl">
                            <div class="font-bold text-white">Master's in Information Technology</div>
                            <div class="text-sm text-gray-400">Jahangirnagar University (2025–2026)</div>
                        </div>
                        <div class="glass-card p-4 rounded-xl">
                            <div class="font-bold text-white">Bachelor of Science in Physics</div>
                            <div class="text-sm text-gray-400">Jashore University of Science and Technology (2017–2021)</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer id="contact" class="py-16 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-6 text-center space-y-6">
            <h3 class="text-2xl font-bold text-white">Ready to scale your next digital solution?</h3>
            <p class="text-gray-400 max-w-md mx-auto text-sm">Open for strategic enterprise opportunities, technical project management roles, and high-impact digital consulting.</p>
            <div class="pt-4">
                <a href="mailto:faridahmed75bd@gmail.com" class="px-8 py-3.5 text-sm font-semibold text-white accent-gradient rounded-xl shadow-lg hover:opacity-90 transition-all inline-block">
                    Send an Email
                </a>
            </div>
            <div class="text-xs text-gray-500 pt-8">
                &copy; 2026 Farid Ahmed. All rights reserved.
            </div>
        </div>
    </footer>

    <!-- Initialize Lucide Icons -->
    <script>
        lucide.createIcons();
    </script>
</body>
</html>
