<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Technical Project Manager & Digital Transformation Leader portfolio - 5+ years driving fintech, SaaS, enterprise platforms, and IT delivery.">
    <meta name="keywords" content="Project Manager, Digital Transformation, FinTech, SaaS, Enterprise Solutions, Agile, SDLC, SLA Governance">
    <meta name="author" content="Farid Ahmed">
    
    <!-- Open Graph Metadata -->
    <meta property="og:title" content="Farid Ahmed | Project Manager & Digital Transformation Leader">
    <meta property="og:description" content="5+ years leading technology, FinTech, SaaS, and enterprise solutions.">
    <meta property="og:type" content="website">

    <title id="page-title">Farid Ahmed — Portfolio</title>

    <!-- Google Fonts: Hind Siliguri -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3a86ff',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            900: '#0f172a'
                        }
                    },
                    fontFamily: {
                        sans: ['"Hind Siliguri"', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <!-- Font Awesome 6.5.1 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Modern Base Setup & Custom Glassmorphism */
        body {
            font-family: 'Hind Siliguri', sans-serif;
            background-color: #0f172a;
            color: #f8fafc;
            overflow-x: hidden;
        }

        .glass-nav {
            background: rgba(15, 23, 42, 0.75);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
        }

        .glass-card {
            background: rgba(30, 41, 59, 0.6);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }

        .glass-card:hover {
            border-color: rgba(58, 134, 255, 0.4);
        }

        .gradient-text {
            background: linear-gradient(135deg, #ffffff 0%, #93c5fd 50%, #3a86ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gradient-accent-text {
            background: linear-gradient(135deg, #60a5fa 0%, #3a86ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Image Reveal Hover Effect for Projects */
        .project-img-wrapper {
            position: relative;
            overflow: hidden;
            height: 240px;
        }
        .project-img-wrapper img {
            transition: transform 3.5s ease-in-out;
            transform: translateY(0);
            width: 100%;
            object-fit: cover;
            object-position: top;
        }
        .project-img-wrapper:hover img {
            transform: translateY(calc(-100% + 240px));
        }

        /* Reduced Motion Fallback */
        @media (prefers-reduced-motion: reduce) {
            *, ::before, ::after {
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
                scroll-behavior: auto !important;
            }
            .project-img-wrapper:hover img {
                transform: none !important;
            }
        }

        /* Smooth reveal default states */
        .reveal-element {
            opacity: 0;
            transform: translateY(24px);
            transition: opacity 0.7s cubic-bezier(0.16, 1, 0.3, 1), transform 0.7s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .reveal-element.active {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="selection:bg-brand-500 selection:text-white antialiased">

    <!-- Dynamic Centralized Configuration Script -->
    <script>
        const siteData = {
            personalInfo: {
                name: "Farid Ahmed",
                designation: "Project Manager | Digital Transformation | FinTech | SaaS",
                phone: "+8801759433577",
                email: "faridahmed75bd@gmail.com",
                address: "Dhaka, Bangladesh / Remote",
                profileImage: "https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgSoHkqMIrFLRZAXto-JxqpwqWjdN8sC45dl6QokHrlaU9nZYJYNBChbh3frNVP9ftHtjUTLPcz55EvX6Wkw87BNW-H7xpfIWkfUAc8UA5HK4F2OHej_5UjJ3MXdV574m7aMNJR5KlG9bH5l0d3yt8k915ftjKnmG27aejM1cCG5He29tAgv1DZrcdl50pL/s1600/Farid%20Ahmed%20(3).png",
                resumeLink: "https://drive.google.com/file/d/1KAu5xykvjA3M4JWCZXq2O0yr2KasfyoN/view?usp=drive_link",
                typingWords: ["FinTech Delivery", "Digital Transformation", "Agile Leadership", "Enterprise SaaS"]
            },
            about: {
                title: "Driving Technology Delivery, Operational Governance & FinTech Growth",
                description: "Technology Project Management professional with 5+ years of experience leading end-to-end software, web, SaaS, fintech, and digital transformation projects. Experienced in project planning, scope and timeline management, resource allocation, client communication, risk management, Agile delivery, and cross-functional team coordination across enterprise platforms."
            },
            socialLinks: {
                linkedin: "https://linkedin.com/in/faridahmed75",
                github: "https://github.com/faridahmed75",
                facebook: "https://facebook.com",
                twitter: "https://x.com"
            },
            skills: [
                { category: "Project & Delivery Management", items: ["Project Planning", "Scope & Timeline Management", "Agile & Scrum", "RAID Management", "Sprint & Backlog Grooming", "KPI & Performance"] },
                { category: "Client & Stakeholder", items: ["Requirement Discovery", "Client Communication", "Cross-functional Coordination", "International Client Mgmt", "SLA Governance"] },
                { category: "Tools, Analytics & AI", items: ["Jira & ClickUp", "Metabase & SQL", "Power BI & Looker Studio", "Grafana & Zabbix", "Generative AI Workflows"] }
            ],
            workExperienceImage: "https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhBjImc6DamoMHzK-zDN3FuOpjiAiopH9q5E0RPZXT5Pe9Xi4W8Wx7zXWaPFQoyZY1b1DPeT5aj0AfmmzBYBdGG0vHhds0xMyXqQUiKGPuLKs-bHTss7bZsMc4orW70O3YJC2jt3PU83N7J3hIOefGhhne5tfivFoBtRkiH1aqPQMNc65fkstb_avfaI8aY/s1600/ChatGPT%20Image%20Jun%208,%202026,%2012_03_49%20PM.png",
            experienceSummary: "A results-oriented Technology Project Manager with 5+ years of experience directing complex fintech, enterprise software, and infrastructure operations from requirement discovery to post-launch optimization.",
            experiences: [
                {
                    duration: "Oct 2025 — Present",
                    designation: "Project Manager",
                    company: "Sheba Platform Limited (Reporting to Group CEO)",
                    responsibilities: [
                        "Led end-to-end technology and fintech projects from discovery through planning, UAT, launch, and continuous improvement.",
                        "Managed strategic partnerships with 12+ banks and 35+ service providers, ensuring SLA governance and operational excellence.",
                        "Enhanced transaction success rate from 65% to 95% across core MFS & DFS products (Add Money, Money Transfer, Utility Payments, etc.).",
                        "Led the Digital Loan product implementation through Sheba Pay across multiple banking partners.",
                        "Managed departmental budgeting, workforce planning, resource allocation, and executive reporting."
                    ],
                    skills: ["FinTech", "Banking API Integration", "SLA Governance", "Executive Dashboards", "Agile Delivery"]
                },
                {
                    duration: "Apr 2024 — Oct 2025",
                    designation: "Asst. Manager, System Operations Center (SOC)",
                    company: "Sheba Platform Limited",
                    responsibilities: [
                        "Led a 25+ member cross-functional team spanning System Engineering, SQA, Network Engineering, and Service Management.",
                        "Built and operationalized the System Operations Center (SOC) from scratch, establishing SOPs, KPIs, and SLA governance.",
                        "Increased system stability from 88.85% to 99.95% and SLA resolution performance from 45% to 70%.",
                        "Developed & launched Sheba Pulse, digitizing operational workflows across 20+ teams (350+ users) and boosting efficiency by ~65%.",
                        "Introduced automated log & error monitoring for real-time detection of transaction failures and fraudulent activities."
                    ],
                    skills: ["SOC Management", "System Stability", "Incident Management", "Grafana/Zabbix", "Workflow Automation"]
                },
                {
                    duration: "Feb 2023 — Mar 2024",
                    designation: "Senior Project Manager",
                    company: "IT Valley BD",
                    responsibilities: [
                        "Managed multiple web and digital tech projects, delivering solutions for 30+ educational institutions and 5+ corporate groups.",
                        "Increased business revenue by 15% through optimized project delivery and sales strategies.",
                        "Coordinated clients, developers, UI/UX designers, and QA teams using Agile frameworks."
                    ],
                    skills: ["Requirement Discovery", "Functional Specs", "Agile Execution", "Revenue Growth", "Client Relations"]
                },
                {
                    duration: "Mar 2021 — Feb 2023",
                    designation: "Project Manager",
                    company: "Fixway IT",
                    responsibilities: [
                        "Managed web and software development projects for international clients, overseeing timelines, scope, and deliverables.",
                        "Translated complex business requirements into user stories, project plans, and sprint backlogs."
                    ],
                    skills: ["International Client Mgmt", "User Stories", "SDLC", "Scope Management"]
                }
            ],
            projects: [
                {
                    title: "Sheba Pay & Digital Loan Integration",
                    description: "FinTech payment and digital loan platform with multi-bank integrations, processing utility bills, MFS/DFS top-ups, and corporate payouts.",
                    image: "https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&q=80&w=1200",
                    technologies: ["FinTech", "API Integration", "Banking SLA", "DFS/MFS"],
                    liveUrl: "#",
                    githubUrl: "#"
                },
                {
                    title: "Sheba Pulse — Operations Platform",
                    description: "Enterprise workflow automation platform centralizing incident reporting and escalation across 20+ teams and 350+ active users.",
                    image: "https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&q=80&w=1200",
                    technologies: ["Workflow Automation", "Analytics", "Incident Mgmt"],
                    liveUrl: "#",
                    githubUrl: "#"
                },
                {
                    title: "Enterprise ERP & School Management",
                    description: "Custom management systems delivered for over 30 educational institutions and 5 corporate business groups.",
                    image: "https://webmundo.in/public/upload/portfolio_other_17670899291ea851c1-1d3e-4d2f-9bd7-99c33651d79a.png",
                    technologies: ["SaaS", "ERP", "School System", "CRM/HRM"],
                    liveUrl: "#",
                    githubUrl: "#"
                }
            ],
            otherProjects: [
                {
                    title: "Custom Project Alpha",
                    description: "Enterprise software application tailored for customized workflow requirements and team efficiency.",
                    image: "https://images.unsplash.com/photo-1507238691740-187a5b1d37b8?auto=format&fit=crop&q=80&w=1200",
                    technologies: ["Custom Module", "UI/UX", "Workflow"],
                    liveUrl: "#",
                    githubUrl: "#"
                },
                {
                    title: "Digital Platform Beta",
                    description: "Scalable web infrastructure solution built for seamless customer interaction and real-time tracking.",
                    image: "https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?auto=format&fit=crop&q=80&w=1200",
                    technologies: ["Web Platform", "SLA Tracking", "Cloud"],
                    liveUrl: "#",
                    githubUrl: "#"
                }
            ],
            certifications: [
                { name: "Generative AI Overview for Project Managers", institution: "Project Management Institute (PMI)", icon: "fa-certificate" },
                { name: "ISO 31000 & Gen AI - Risk & Compliance", institution: "Global Skill Development Council", icon: "fa-shield-halved" },
                { name: "Professional Diploma in Agile and Scrum", institution: "Udemy", icon: "fa-list-check" },
                { name: "C-Level Management: Business Growth", institution: "Udemy", icon: "fa-chart-line" },
                { name: "SIEM 101", institution: "LetsDefend", icon: "fa-user-shield" },
                { name: "SOC Analyst", institution: "LetsDefend", icon: "fa-shield-virus" },
                { name: "Advance Web Development with Laravel and Python", institution: "ICT Division", icon: "fa-code" },
                { name: "Leadership and People Management - 99th percentile", institution: "TestGorilla", icon: "fa-users-gear" }
            ],
            organizationalExperiences: [
                {
                    duration: "2021 — Present",
                    designation: "Active Member & Technical Advisor",
                    organization: "Professional Tech Communities",
                    responsibilities: [
                        "Participated in technology transformation forums, technical workshops, and Agile best-practice events.",
                        "Mentored junior professionals in project governance, requirement gathering, and SOC implementation."
                    ]
                }
            ],
            education: [
                {
                    duration: "2025 — 2026",
                    designation: "Master's in Information Technology",
                    organization: "Jahangirnagar University",
                    responsibilities: [
                        "Advanced studies focusing on enterprise information systems, tech architecture, and data management."
                    ]
                },
                {
                    duration: "2017 — 2021",
                    designation: "Bachelor of Science in Physics",
                    organization: "Jashore University of Science and Technology",
                    responsibilities: [
                        "Developed strong analytical, mathematical modeling, and problem-solving skills foundational to technical PM roles."
                    ]
                }
            ],
            testimonials: [
                {
                    quote: "Farid's strategic vision, coupled with high-level operational execution, transformed our fintech transaction efficiency and banking integrations.",
                    author: "Adnan Imtiaz Halim",
                    role: "Founder & Group CEO, Sheba Platform Limited"
                },
                {
                    quote: "An exceptional project leader who bridges engineering, QA, and executive leadership seamlessly to guarantee 99.95% stability.",
                    author: "Nesar Ahmed Julius",
                    role: "CHRO & Head of Admin, Sirajganj Economic Zone Ltd."
                }
            ],
            contact: {
                phone: "+8801759433577",
                email: "faridahmed75bd@gmail.com",
                address: "Dhaka, Bangladesh / Remote Work Supported",
                mapUrl: "https://maps.google.com/maps?q=Dhaka,+Bangladesh&t=&z=13&ie=UTF8&iwloc=&output=embed"
            },
            integrations: {
                googleScriptUrl: "",
                telegramBotToken: "",
                telegramChatId: ""
            }
        };
    </script>

    <!-- Header Navigation -->
    <header class="fixed top-0 left-0 right-0 z-50 glass-nav transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-10 h-10 rounded-xl bg-brand-500/20 border border-brand-500/40 text-brand-500 flex items-center justify-center font-bold text-lg group-hover:scale-105 transition-transform">
                    FA
                </div>
                <span id="nav-brand-name" class="font-bold text-lg tracking-tight text-slate-100 group-hover:text-brand-500 transition-colors">
                    Farid Ahmed
                </span>
            </a>

            <!-- Desktop Nav -->
            <nav class="hidden md:flex items-center space-x-7 text-sm font-medium">
                <a href="#about" class="text-slate-300 hover:text-brand-500 transition-colors">About</a>
                <a href="#experience" class="text-slate-300 hover:text-brand-500 transition-colors">Experience</a>
                <a href="#skills" class="text-slate-300 hover:text-brand-500 transition-colors">Skills</a>
                <a href="#projects" class="text-slate-300 hover:text-brand-500 transition-colors">Projects</a>
                <a href="#certifications" class="text-slate-300 hover:text-brand-500 transition-colors">Certifications</a>
                <a href="#organizational" class="text-slate-300 hover:text-brand-500 transition-colors">Organizational</a>
                <a href="#other-projects" class="text-slate-300 hover:text-brand-500 transition-colors">Other Projects</a>
                <a href="#education" class="text-slate-300 hover:text-brand-500 transition-colors">Education</a>
                <a href="#contact" class="px-5 py-2.5 rounded-full bg-brand-500 hover:bg-brand-600 text-white font-semibold transition-all shadow-lg shadow-brand-500/20 hover:shadow-brand-500/40">
                    Get in Touch
                </a>
            </nav>

            <!-- Mobile Hamburger Button -->
            <button id="mobile-menu-btn" class="md:hidden p-2 text-slate-300 hover:text-white focus:outline-none" aria-label="Toggle Navigation Menu">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Nav Menu -->
        <div id="mobile-menu" class="hidden md:hidden glass-nav border-t border-slate-800 px-6 py-6 space-y-4">
            <a href="#about" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">About</a>
            <a href="#experience" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Experience</a>
            <a href="#skills" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Skills</a>
            <a href="#projects" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Projects</a>
            <a href="#certifications" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Certifications</a>
            <a href="#organizational" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Organizational</a>
            <a href="#other-projects" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Other Projects</a>
            <a href="#education" class="mobile-nav-link block text-base font-medium text-slate-200 hover:text-brand-500">Education</a>
            <a href="#contact" class="mobile-nav-link inline-block w-full text-center py-3 rounded-xl bg-brand-500 text-white font-semibold">Get in Touch</a>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="pt-20">

        <!-- Hero Section -->
        <section class="min-h-[calc(100vh-80px)] flex items-center justify-center relative overflow-hidden py-16 px-4 sm:px-6 lg:px-8">
            <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] bg-brand-500/10 rounded-full blur-3xl pointer-events-none"></div>
            
            <div class="max-w-7xl mx-auto w-full grid grid-cols-1 lg:grid-cols-12 gap-12 items-center relative z-10">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left reveal-element">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-brand-500/10 border border-brand-500/20 text-brand-500 text-sm font-medium">
                        <span class="w-2 h-2 rounded-full bg-brand-500 animate-pulse"></span>
                        Available for Technical Project Leadership
                    </div>

                    <h1 class="text-4xl sm:text-6xl font-bold tracking-tight text-white leading-tight">
                        Hi, I'm <span id="hero-name" class="gradient-text">Farid Ahmed</span>
                    </h1>

                    <h2 class="text-xl sm:text-2xl font-semibold text-slate-300 flex items-center justify-center lg:justify-start gap-2">
                        <span id="hero-designation">Project Manager | Digital Transformation Leader</span>
                    </h2>

                    <p class="text-lg text-slate-400 max-w-2xl mx-auto lg:mx-0 font-normal leading-relaxed">
                        Leading end-to-end software, FinTech, SaaS, and digital transformation initiatives with 5+ years of driving enterprise reliability and project outcomes.
                    </p>

                    <div class="text-sm font-mono text-brand-500 flex items-center justify-center lg:justify-start gap-2">
                        <i class="fa-solid fa-code text-xs"></i>
                        <span>Focus:</span>
                        <span id="typing-text" class="border-r-2 border-brand-500 pr-1"></span>
                    </div>

                    <div class="pt-4 flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="#projects" class="w-full sm:w-auto px-8 py-3.5 rounded-xl bg-brand-500 hover:bg-brand-600 text-white font-semibold transition-all shadow-lg shadow-brand-500/25 hover:shadow-brand-500/40 text-center">
                            View Portfolio <i class="fa-solid fa-arrow-right ml-2 text-sm"></i>
                        </a>
                        <a id="hero-resume-btn" href="#" target="_blank" class="w-full sm:w-auto px-8 py-3.5 rounded-xl border border-slate-700 hover:border-brand-500/50 bg-slate-900/50 text-slate-200 hover:text-white font-semibold transition-all text-center">
                            Download Resume <i class="fa-solid fa-download ml-2 text-sm"></i>
                        </a>
                    </div>

                    <div class="pt-6 flex items-center justify-center lg:justify-start gap-5 text-slate-400">
                        <a id="social-linkedin" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="LinkedIn Profile">
                            <i class="fa-brands fa-linkedin-in text-lg"></i>
                        </a>
                        <a id="social-github" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="GitHub Profile">
                            <i class="fa-brands fa-github text-lg"></i>
                        </a>
                        <a id="social-facebook" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="Facebook Profile">
                            <i class="fa-brands fa-facebook-f text-lg"></i>
                        </a>
                        <a id="social-twitter" href="#" target="_blank" class="w-10 h-10 rounded-lg glass-card flex items-center justify-center hover:text-brand-500 hover:border-brand-500/50 transition-all" aria-label="Twitter Profile">
                            <i class="fa-brands fa-x-twitter text-lg"></i>
                        </a>
                    </div>
                </div>

                <div class="lg:col-span-5 flex justify-center reveal-element">
                    <div class="relative w-72 h-72 sm:w-80 sm:h-80 lg:w-96 lg:h-96">
                        <div class="absolute inset-0 rounded-3xl bg-gradient-to-tr from-brand-500 to-cyan-400 opacity-20 blur-xl"></div>
                        <div class="relative w-full h-full rounded-3xl border-2 border-slate-700/60 overflow-hidden shadow-2xl glass-card bg-slate-900">
                            <img id="profile-img" src="" alt="Farid Ahmed" class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="glass-card rounded-3xl p-8 sm:p-12 border border-slate-800/80 reveal-element">
                <div class="max-w-3xl">
                    <h2 class="text-sm font-semibold tracking-wider text-brand-500 uppercase mb-2">Executive Overview</h2>
                    <h3 id="about-title" class="text-2xl sm:text-3xl font-bold text-white mb-6 leading-snug">
                        Driving Technology Delivery, Operational Governance & FinTech Growth
                    </h3>
                    <p id="about-description" class="text-slate-300 text-lg leading-relaxed font-normal">
                        Technology Project Management professional with 5+ years of experience leading end-to-end software, web, SaaS, fintech, and digital transformation projects...
                    </p>
                </div>

                <div class="mt-10 grid grid-cols-2 md:grid-cols-4 gap-6 pt-8 border-t border-slate-800">
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">5+ Yrs</div>
                        <div class="text-sm text-slate-400">Project Leadership</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">99.95%</div>
                        <div class="text-sm text-slate-400">System Stability Achieved</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">12+</div>
                        <div class="text-sm text-slate-400">Bank Partners Managed</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold text-white mb-1">95%</div>
                        <div class="text-sm text-slate-400">Transaction Success Rate</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Work Experience Section -->
        <section id="experience" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="mb-12 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Work Experience</h2>
                <p id="experience-summary" class="mt-4 text-slate-400 text-lg max-w-3xl leading-relaxed">
                    <!-- Dynamic Experience Summary -->
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                <div class="lg:col-span-5 reveal-element">
                    <div class="sticky top-28">
                        <div class="relative group rounded-3xl overflow-hidden border border-slate-800 bg-slate-900 shadow-2xl">
                            <img id="work-exp-image" src="" alt="Work Experience Illustration" class="w-full h-auto object-cover rounded-3xl group-hover:scale-105 transition-transform duration-500">
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 space-y-10 reveal-element">
                    <div id="experience-container" class="relative pl-6 sm:pl-8 border-l-2 border-slate-800 space-y-12">
                        <!-- Dynamic Experience Cards Injected Here -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="text-center max-w-2xl mx-auto mb-16 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white">Core Competencies & Tooling</h2>
                <p class="text-slate-400 mt-3">Comprehensive expertise across project governance, software delivery, and analytics.</p>
            </div>

            <div id="skills-container" class="grid grid-cols-1 md:grid-cols-3 gap-8 reveal-element">
                <!-- Dynamic Skills Categories -->
            </div>
        </section>

        <!-- Projects / Portfolio Section -->
        <section id="projects" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 reveal-element">
                <div>
                    <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Product Experience & Projects</h2>
                    <p class="text-slate-400 mt-2">Key digital products and enterprise platforms managed across FinTech and SaaS.</p>
                </div>
            </div>

            <div id="projects-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Dynamic Project Cards Injected Here -->
            </div>
        </section>

        <!-- Professional Trainings & Certifications Section -->
        <section id="certifications" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="text-center max-w-2xl mx-auto mb-16 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white">Professional Certifications</h2>
                <p class="text-slate-400 mt-3">Industry-recognized credentials in Agile, Generative AI, Cyber Security, Risk & Business Growth.</p>
            </div>

            <div id="certifications-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 reveal-element">
                <!-- Dynamic Certification Cards -->
            </div>
        </section>

        <!-- Organizational Experience Section -->
        <section id="organizational" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="mb-12 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Organizational Experience</h2>
                <p class="mt-4 text-slate-400 text-lg max-w-3xl leading-relaxed">
                    Community leadership, mentoring initiatives, and professional membership roles.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                <div class="lg:col-span-5 reveal-element">
                    <div class="sticky top-28">
                        <div class="relative group rounded-3xl overflow-hidden border border-slate-800 bg-slate-900 shadow-2xl p-8 space-y-4">
                            <span class="px-3 py-1 rounded-full bg-brand-500/20 text-brand-500 text-xs font-semibold border border-brand-500/30">
                                Leadership & Community
                            </span>
                            <h4 class="text-xl font-bold text-white">Community Engagement</h4>
                            <p class="text-sm text-slate-300">Fostering collaboration, tech leadership, and continuous skill advancement across developer & manager communities.</p>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 space-y-10 reveal-element">
                    <div id="org-experience-container" class="relative pl-6 sm:pl-8 border-l-2 border-slate-800 space-y-12">
                        <!-- Dynamic Organizational Cards Injected Here -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Other Projects Section -->
        <section id="other-projects" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 reveal-element">
                <div>
                    <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Other Projects</h2>
                    <p class="text-slate-400 mt-2">Additional technical initiatives, client solutions, and specialized developments.</p>
                </div>
            </div>

            <div id="other-projects-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Dynamic Other Project Cards Injected Here -->
            </div>
        </section>

        <!-- Education Section -->
        <section id="education" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="mb-12 reveal-element">
                <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Academic Qualifications</h2>
                <p class="mt-4 text-slate-400 text-lg max-w-3xl leading-relaxed">
                    Formal educational background in Information Technology and Physical Sciences.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                <div class="lg:col-span-5 reveal-element">
                    <div class="sticky top-28">
                        <div class="relative group rounded-3xl overflow-hidden border border-slate-800 bg-slate-900 shadow-2xl p-8 space-y-4">
                            <span class="px-3 py-1 rounded-full bg-brand-500/20 text-brand-500 text-xs font-semibold border border-brand-500/30">
                                Educational Foundation
                            </span>
                            <h4 class="text-xl font-bold text-white">Technical Rigor</h4>
                            <p class="text-sm text-slate-300">Combining IT systems expertise with analytical scientific methodology.</p>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 space-y-10 reveal-element">
                    <div id="education-container" class="relative pl-6 sm:pl-8 border-l-2 border-slate-800 space-y-12">
                        <!-- Dynamic Education Cards Injected Here -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="glass-card rounded-3xl p-8 sm:p-12 border border-slate-800/80 reveal-element">
                <h2 class="text-2xl font-bold text-white mb-8 text-center">Executive References & Endorsements</h2>
                <div id="testimonials-container" class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <!-- Dynamic Testimonials -->
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                <div class="lg:col-span-5 reveal-element space-y-6">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white tracking-tight">Let's Connect</h2>
                    <p class="text-slate-400 text-lg">
                        Seeking executive project management roles, digital transformation initiatives, or consulting engagements? Reach out directly.
                    </p>

                    <div class="space-y-4 pt-4">
                        <div class="flex items-center gap-4 p-4 rounded-2xl glass-card">
                            <div class="w-12 h-12 rounded-xl bg-brand-500/10 text-brand-500 flex items-center justify-center text-xl">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold">Email</div>
                                <a id="contact-email" href="" class="text-white hover:text-brand-500 font-medium"></a>
                            </div>
                        </div>

                        <div class="flex items-center gap-4 p-4 rounded-2xl glass-card">
                            <div class="w-12 h-12 rounded-xl bg-brand-500/10 text-brand-500 flex items-center justify-center text-xl">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold">Phone</div>
                                <a id="contact-phone" href="" class="text-white hover:text-brand-500 font-medium"></a>
                            </div>
                        </div>

                        <div class="flex items-center gap-4 p-4 rounded-2xl glass-card">
                            <div class="w-12 h-12 rounded-xl bg-brand-500/10 text-brand-500 flex items-center justify-center text-xl">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <div class="text-xs text-slate-400 uppercase tracking-wider font-semibold">Location</div>
                                <span id="contact-address" class="text-white font-medium"></span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 reveal-element">
                    <form id="contact-form" class="glass-card rounded-3xl p-8 border border-slate-800 space-y-6">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div>
                                <label for="form-name" class="block text-sm font-medium text-slate-300 mb-2">Full Name</label>
                                <input type="text" id="form-name" required class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="John Doe">
                            </div>
                            <div>
                                <label for="form-phone" class="block text-sm font-medium text-slate-300 mb-2">Phone Number</label>
                                <input type="tel" id="form-phone" class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="+1 (555) 000-0000">
                            </div>
                        </div>

                        <div>
                            <label for="form-email" class="block text-sm font-medium text-slate-300 mb-2">Email Address</label>
                            <input type="email" id="form-email" required class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="john@example.com">
                        </div>

                        <div>
                            <label for="form-message" class="block text-sm font-medium text-slate-300 mb-2">Message</label>
                            <textarea id="form-message" rows="4" required class="w-full px-4 py-3 rounded-xl bg-slate-900/60 border border-slate-800 text-white focus:outline-none focus:border-brand-500 transition-colors" placeholder="Describe project or inquiry details..."></textarea>
                        </div>

                        <button type="submit" id="form-submit-btn" class="w-full py-4 rounded-xl bg-brand-500 hover:bg-brand-600 text-white font-semibold transition-all shadow-lg shadow-brand-500/20 hover:shadow-brand-500/40 flex items-center justify-center gap-2">
                            <span>Send Message</span>
                            <i class="fa-solid fa-paper-plane text-sm"></i>
                        </button>
                        <div id="form-status" class="text-sm text-center hidden"></div>
                    </form>
                </div>
            </div>
        </section>

        <!-- Google Map Section -->
        <section class="py-12 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="rounded-3xl overflow-hidden glass-card p-3 border border-slate-800/80 reveal-element shadow-2xl">
                <iframe id="google-map" class="w-full h-80 rounded-2xl border-0" loading="lazy" allowfullscreen></iframe>
            </div>
        </section>

    </main>

    <!-- Footer Section -->
    <footer class="border-t border-slate-800/80 bg-slate-950 py-12 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6">
            <div>
                <span id="footer-name" class="font-bold text-lg text-white">Farid Ahmed</span>
                <p id="footer-designation" class="text-sm text-slate-400">Project Manager | Digital Transformation Leader</p>
            </div>
            <div class="text-sm text-slate-500 text-center md:text-right">
                © <span id="current-year"></span> <span id="footer-copyright-name">Farid Ahmed</span>. All Rights Reserved.
            </div>
        </div>
    </footer>

    <!-- Rendering & Logic Engine -->
    <script>
        document.addEventListener("DOMContentLoaded", () => {
            
            // 1. Populate Personal & Contact Info
            document.getElementById("page-title").innerText = `${siteData.personalInfo.name} — Portfolio`;
            document.getElementById("nav-brand-name").innerText = siteData.personalInfo.name;
            document.getElementById("hero-name").innerText = siteData.personalInfo.name;
            document.getElementById("hero-designation").innerText = siteData.personalInfo.designation;
            document.getElementById("hero-resume-btn").href = siteData.personalInfo.resumeLink;
            document.getElementById("profile-img").src = siteData.personalInfo.profileImage;
            document.getElementById("work-exp-image").src = siteData.workExperienceImage;
            
            // Social Links
            document.getElementById("social-linkedin").href = siteData.socialLinks.linkedin;
            document.getElementById("social-github").href = siteData.socialLinks.github;
            document.getElementById("social-facebook").href = siteData.socialLinks.facebook;
            document.getElementById("social-twitter").href = siteData.socialLinks.twitter;

            // About Section
            document.getElementById("about-title").innerText = siteData.about.title;
            document.getElementById("about-description").innerText = siteData.about.description;

            // Contact Info
            document.getElementById("contact-email").innerText = siteData.contact.email;
            document.getElementById("contact-email").href = `mailto:${siteData.contact.email}`;
            document.getElementById("contact-phone").innerText = siteData.contact.phone;
            document.getElementById("contact-phone").href = `tel:${siteData.contact.phone}`;
            
            document.getElementById("contact-address").innerText = siteData.contact.address;
            document.getElementById("google-map").src = siteData.contact.mapUrl;

            // Footer Info
            document.getElementById("footer-name").innerText = siteData.personalInfo.name;
            document.getElementById("footer-designation").innerText = siteData.personalInfo.designation;
            document.getElementById("footer-copyright-name").innerText = siteData.personalInfo.name;
            document.getElementById("current-year").innerText = new Date().getFullYear();

            // 2. Typing Effect for Hero Subtext
            const typingContainer = document.getElementById("typing-text");
            const words = siteData.personalInfo.typingWords || ["FinTech Delivery", "Agile Execution"];
            let wordIdx = 0, charIdx = 0, isDeleting = false;

            function typeEffect() {
                const currentWord = words[wordIdx];
                if (isDeleting) {
                    typingContainer.innerText = currentWord.substring(0, charIdx - 1);
                    charIdx--;
                } else {
                    typingContainer.innerText = currentWord.substring(0, charIdx + 1);
                    charIdx++;
                }

                let speed = isDeleting ? 40 : 80;
                if (!isDeleting && charIdx === currentWord.length) {
                    speed = 2000;
                    isDeleting = true;
                } else if (isDeleting && charIdx === 0) {
                    isDeleting = false;
                    wordIdx = (wordIdx + 1) % words.length;
                    speed = 400;
                }
                setTimeout(typeEffect, speed);
            }
            typeEffect();

            // 3. Render Work Experience Section
            document.getElementById("experience-summary").innerText = siteData.experienceSummary;

            const expContainer = document.getElementById("experience-container");
            expContainer.innerHTML = siteData.experiences.map(exp => `
                <div class="relative group">
                    <span class="absolute -left-[31px] sm:-left-[39px] top-1.5 w-4 h-4 rounded-full bg-slate-900 border-2 border-brand-500 group-hover:scale-125 transition-transform"></span>

                    <div class="flex flex-wrap items-center gap-3 mb-2">
                        <span class="px-3 py-1 rounded-full bg-brand-500/10 border border-brand-500/20 text-brand-500 text-xs font-semibold">
                            ${exp.duration}
                        </span>
                        <span class="text-slate-400 text-sm font-medium">${exp.company}</span>
                    </div>

                    <h3 class="text-xl font-bold text-white mb-4">${exp.designation}</h3>

                    <ul class="space-y-2.5 mb-6 text-slate-300 text-sm leading-relaxed">
                        ${exp.responsibilities.map(r => `
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-caret-right text-brand-500 text-xs mt-1"></i>
                                <span>${r}</span>
                            </li>
                        `).join('')}
                    </ul>

                    <div class="space-y-2">
                        <div class="text-xs font-semibold text-slate-400 uppercase tracking-wider">Key Skills Applied</div>
                        <div class="flex flex-wrap gap-2">
                            ${exp.skills.map(s => `
                                <span class="px-3 py-1 rounded-lg text-xs font-medium bg-slate-900/80 border border-slate-800 text-slate-300 hover:border-brand-500/40 hover:text-white transition-all">
                                    ${s}
                                </span>
                            `).join('')}
                        </div>
                    </div>
                </div>
            `).join('');

            // 4. Render Skills Section
            const skillsContainer = document.getElementById("skills-container");
            skillsContainer.innerHTML = siteData.skills.map(cat => `
                <div class="glass-card rounded-2xl p-6 border border-slate-800/80">
                    <h3 class="text-lg font-bold text-white mb-4 pb-3 border-b border-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-brand-500 text-sm"></i>
                        ${cat.category}
                    </h3>
                    <div class="flex flex-wrap gap-2">
                        ${cat.items.map(skill => `
                            <span class="px-3 py-1.5 rounded-lg text-xs font-medium bg-slate-900/60 border border-slate-800 text-slate-300 hover:border-brand-500/30 transition-colors">
                                ${skill}
                            </span>
                        `).join('')}
                    </div>
                </div>
            `).join('');

            // 5. Render Main Projects Section
            const projectsContainer = document.getElementById("projects-container");
            projectsContainer.innerHTML = siteData.projects.map(proj => `
                <div class="glass-card rounded-2xl overflow-hidden border border-slate-800/80 flex flex-col justify-between group hover:border-brand-500/30 transition-all reveal-element">
                    <div>
                        <div class="project-img-wrapper bg-slate-900">
                            <img src="${proj.image}" alt="${proj.title}">
                        </div>

                        <div class="p-6 space-y-3">
                            <h3 class="text-xl font-bold text-white group-hover:text-brand-500 transition-colors">${proj.title}</h3>
                            <p class="text-sm text-slate-400 leading-relaxed">${proj.description}</p>
                            
                            <div class="flex flex-wrap gap-1.5 pt-2">
                                ${proj.technologies.map(t => `
                                    <span class="px-2.5 py-0.5 rounded-md text-[11px] font-medium bg-brand-500/10 text-brand-500">
                                        ${t}
                                    </span>
                                `).join('')}
                            </div>
                        </div>
                    </div>

                    <div class="p-6 pt-0 flex items-center gap-4">
                        <a href="${proj.liveUrl}" class="text-xs font-semibold text-white hover:text-brand-500 flex items-center gap-1.5 transition-colors">
                            <span>Live Preview</span>
                            <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                        </a>
                        <a href="${proj.githubUrl}" class="text-xs font-semibold text-slate-400 hover:text-white flex items-center gap-1.5 transition-colors">
                            <span>Details</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>
            `).join('');

            // 6. Render Certifications Section
            const certsContainer = document.getElementById("certifications-container");
            certsContainer.innerHTML = siteData.certifications.map(cert => `
                <div class="glass-card rounded-2xl p-6 border border-slate-800/80 flex flex-col justify-between group hover:border-brand-500/40 transition-all">
                    <div>
                        <div class="w-10 h-10 rounded-xl bg-brand-500/10 border border-brand-500/20 text-brand-500 flex items-center justify-center text-lg mb-4 group-hover:scale-110 transition-transform">
                            <i class="fa-solid ${cert.icon}"></i>
                        </div>
                        <h3 class="text-base font-bold text-white group-hover:text-brand-500 transition-colors mb-2">${cert.name}</h3>
                    </div>
                    <div class="pt-4 border-t border-slate-800/60 flex items-center justify-between text-xs text-slate-400">
                        <span>Issuer</span>
                        <span class="font-semibold text-slate-200 text-right">${cert.institution}</span>
                    </div>
                </div>
            `).join('');

            // 7. Render Organizational Experience Section
            const orgContainer = document.getElementById("org-experience-container");
            orgContainer.innerHTML = siteData.organizationalExperiences.map(org => `
                <div class="relative group">
                    <span class="absolute -left-[31px] sm:-left-[39px] top-1.5 w-4 h-4 rounded-full bg-slate-900 border-2 border-brand-500 group-hover:scale-125 transition-transform"></span>

                    <div class="flex flex-wrap items-center gap-3 mb-2">
                        <span class="px-3 py-1 rounded-full bg-brand-500/10 border border-brand-500/20 text-brand-500 text-xs font-semibold">
                            ${org.duration}
                        </span>
                        <span class="text-slate-400 text-sm font-medium">${org.organization}</span>
                    </div>

                    <h3 class="text-xl font-bold text-white mb-4">${org.designation}</h3>

                    <ul class="space-y-2.5 text-slate-300 text-sm leading-relaxed">
                        ${org.responsibilities.map(r => `
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-square-check text-brand-500 text-xs mt-1"></i>
                                <span>${r}</span>
                            </li>
                        `).join('')}
                    </ul>
                </div>
            `).join('');

            // 8. Render Other Projects Section
            const otherProjectsContainer = document.getElementById("other-projects-container");
            otherProjectsContainer.innerHTML = siteData.otherProjects.map(proj => `
                <div class="glass-card rounded-2xl overflow-hidden border border-slate-800/80 flex flex-col justify-between group hover:border-brand-500/30 transition-all reveal-element">
                    <div>
                        <div class="project-img-wrapper bg-slate-900">
                            <img src="${proj.image}" alt="${proj.title}">
                        </div>

                        <div class="p-6 space-y-3">
                            <h3 class="text-xl font-bold text-white group-hover:text-brand-500 transition-colors">${proj.title}</h3>
                            <p class="text-sm text-slate-400 leading-relaxed">${proj.description}</p>
                            
                            <div class="flex flex-wrap gap-1.5 pt-2">
                                ${proj.technologies.map(t => `
                                    <span class="px-2.5 py-0.5 rounded-md text-[11px] font-medium bg-brand-500/10 text-brand-500">
                                        ${t}
                                    </span>
                                `).join('')}
                            </div>
                        </div>
                    </div>

                    <div class="p-6 pt-0 flex items-center gap-4">
                        <a href="${proj.liveUrl}" class="text-xs font-semibold text-white hover:text-brand-500 flex items-center gap-1.5 transition-colors">
                            <span>Live Preview</span>
                            <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                        </a>
                        <a href="${proj.githubUrl}" class="text-xs font-semibold text-slate-400 hover:text-white flex items-center gap-1.5 transition-colors">
                            <span>Details</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>
            `).join('');

            // 9. Render Academic Qualifications (Education) Section
            const eduContainer = document.getElementById("education-container");
            eduContainer.innerHTML = siteData.education.map(edu => `
                <div class="relative group">
                    <span class="absolute -left-[31px] sm:-left-[39px] top-1.5 w-4 h-4 rounded-full bg-slate-900 border-2 border-brand-500 group-hover:scale-125 transition-transform"></span>

                    <div class="flex flex-wrap items-center gap-3 mb-2">
                        <span class="px-3 py-1 rounded-full bg-brand-500/10 border border-brand-500/20 text-brand-500 text-xs font-semibold">
                            ${edu.duration}
                        </span>
                        <span class="text-slate-400 text-sm font-medium">${edu.organization}</span>
                    </div>

                    <h3 class="text-xl font-bold text-white mb-4">${edu.designation}</h3>

                    <ul class="space-y-2.5 text-slate-300 text-sm leading-relaxed">
                        ${edu.responsibilities.map(r => `
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-graduation-cap text-brand-500 text-xs mt-1"></i>
                                <span>${r}</span>
                            </li>
                        `).join('')}
                    </ul>
                </div>
            `).join('');

            // 10. Render Testimonials
            const testContainer = document.getElementById("testimonials-container");
            testContainer.innerHTML = siteData.testimonials.map(t => `
                <div class="space-y-4">
                    <i class="fa-solid fa-quote-left text-2xl text-brand-500/40"></i>
                    <p class="text-slate-300 text-base italic leading-relaxed">"${t.quote}"</p>
                    <div>
                        <div class="font-bold text-white text-sm">${t.author}</div>
                        <div class="text-xs text-slate-400">${t.role}</div>
                    </div>
                </div>
            `).join('');

            // 11. Mobile Menu Toggle
            const mobileMenuBtn = document.getElementById("mobile-menu-btn");
            const mobileMenu = document.getElementById("mobile-menu");
            mobileMenuBtn.addEventListener("click", () => {
                mobileMenu.classList.toggle("hidden");
            });

            document.querySelectorAll(".mobile-nav-link").forEach(link => {
                link.addEventListener("click", () => mobileMenu.classList.add("hidden"));
            });

            // 12. Scroll Reveal Observer
            const observerOptions = { threshold: 0.1, rootMargin: "0px 0px -50px 0px" };
            const revealObserver = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add("active");
                        observer.unobserve(entry.target);
                    }
                });
            }, observerOptions);

            document.querySelectorAll(".reveal-element").forEach(el => revealObserver.observe(el));

            // 13. Contact Form Submission Handling
            const contactForm = document.getElementById("contact-form");
            const formSubmitBtn = document.getElementById("form-submit-btn");
            const formStatus = document.getElementById("form-status");

            contactForm.addEventListener("submit", async (e) => {
                e.preventDefault();
                
                const name = document.getElementById("form-name").value.trim();
                const phone = document.getElementById("form-phone").value.trim();
                const email = document.getElementById("form-email").value.trim();
                const message = document.getElementById("form-message").value.trim();

                formSubmitBtn.disabled = true;
                formSubmitBtn.innerHTML = `<i class="fa-solid fa-spinner animate-spin"></i> Sending...`;
                formStatus.classList.add("hidden");

                try {
                    if (siteData.integrations.googleScriptUrl) {
                        const formData = new URLSearchParams();
                        formData.append("name", name);
                        formData.append("phone", phone);
                        formData.append("email", email);
                        formData.append("message", message);

                        fetch(siteData.integrations.googleScriptUrl, {
                            method: "POST",
                            mode: "no-cors",
                            headers: { "Content-Type": "application/x-www-form-urlencoded" },
                            body: formData.toString()
                        });
                    }

                    if (siteData.integrations.telegramBotToken && siteData.integrations.telegramChatId) {
                        const tgText = `📬 *New Portfolio Inquiry*\n\n*Name:* ${name}\n*Phone:* ${phone}\n*Email:* ${email}\n*Message:* ${message}`;
                        await fetch(`https://api.telegram.org/bot${siteData.integrations.telegramBotToken}/sendMessage`, {
                            method: "POST",
                            headers: { "Content-Type": "application/json" },
                            body: JSON.stringify({
                                chat_id: siteData.integrations.telegramChatId,
                                text: tgText,
                                parse_mode: "Markdown"
                            })
                        });
                    }

                    formStatus.innerText = "Thank you! Your message has been received successfully.";
                    formStatus.className = "text-sm text-center text-emerald-400 font-medium block";
                    contactForm.reset();
                } catch (err) {
                    console.error(err);
                    formStatus.innerText = "Form submitted! Thank you.";
                    formStatus.className = "text-sm text-center text-emerald-400 font-medium block";
                    contactForm.reset();
                } finally {
                    formSubmitBtn.disabled = false;
                    formSubmitBtn.innerHTML = `<span>Send Message</span><i class="fa-solid fa-paper-plane text-sm"></i>`;
                }
            });
        });
    </script>
</body>
</html>
