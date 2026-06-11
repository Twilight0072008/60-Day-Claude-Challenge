# 🌐 AI-Powered Portfolio Website Generator

A modern, responsive personal portfolio website generated using AI-powered prompt engineering and frontend development principles.

## 🚀 Project Overview

This project demonstrates how AI can be used as a full-stack development assistant to generate a complete portfolio website from a single structured prompt.

The generated website is designed to help students, developers, and professionals quickly create a modern online presence without building everything from scratch.

## ✨ Features

* Modern Hero Section
* About Me Section
* Skills Showcase
* Animated Skill Progress Bars
* Project Portfolio Cards
* Achievements & Certifications
* Contact Form
* Social Media Integration
* Dark/Light Mode Toggle
* Smooth Scrolling Animations
* Active Navigation Highlighting
* Mobile Responsive Design
* SEO Optimized Structure
* Single HTML File Deployment

## 🛠️ Tech Stack

### Frontend

* HTML5
* Tailwind CSS (CDN)
* Vanilla JavaScript

### Design

* Responsive UI
* Dark Mode
* Smooth Animations
* Modern Portfolio Layout

## 📂 Project Structure

```bash
portfolio-project/
│
├── portfolio.html
├── screenshots/
│   ├── hero-section.png
│   ├── skills-section.png
│   ├── projects-section.png
│   ├── dark-mode.png
│   └── contact-section.png
│
└── README.md
```

## 📸 Screenshots

### Hero Section

<img width="1349" height="913" alt="Screenshot 2026-06-11 225407" src="https://github.com/user-attachments/assets/2bfb0f92-fd2b-413d-981a-6a551fd3635a" />


### Skills Section

<img width="1337" height="909" alt="Screenshot 2026-06-11 225451" src="https://github.com/user-attachments/assets/39c96f17-aebd-493f-857d-83d381ffc16a" />


### Projects Section

<img width="1357" height="904" alt="Screenshot 2026-06-11 225530" src="https://github.com/user-attachments/assets/39329ab2-0264-43db-9bba-e7494207442a" />


### Dark Mode

<img width="1347" height="915" alt="Screenshot 2026-06-11 225602" src="https://github.com/user-attachments/assets/0ad5d311-55b2-4abf-b35c-1ba8fbe1c154" />


### Contact Section

<img width="1358" height="935" alt="Screenshot 2026-06-11 225639" src="https://github.com/user-attachments/assets/84cac6cc-4778-420b-8ca8-c645a69686a6" />


## 🎯 Project Goals

* Explore AI-assisted web development
* Generate a complete portfolio from a structured prompt
* Understand prompt engineering for frontend generation
* Create a recruiter-friendly personal portfolio
* Learn rapid prototyping using AI tools

## 📚 Key Learnings

### Prompt Engineering Matters

Detailed prompts lead to more accurate and feature-rich outputs.

### AI Accelerates Development

A complete portfolio structure can be generated within minutes.

### Responsive Design Is Essential

The generated website follows mobile-first design principles.

### Personal Branding Matters

A well-designed portfolio improves online presence and professional visibility.

### Human Refinement Remains Important

AI provides a strong foundation, but customization and polishing are necessary for production-ready results.

## 🔮 Future Improvements

* Blog Integration
* Project Filtering System
* Resume Download Feature
* Contact Form Backend
* Visitor Analytics
* Multi-language Support
* AI Chat Assistant Integration

## 🤝 Acknowledgements

Built as part of a learning journey exploring:

* AI-Assisted Development
* Prompt Engineering
* Frontend Development
* Personal Branding

## ⭐ Takeaway

This project demonstrates how AI can transform a simple text prompt into a fully functional, responsive, and recruiter-friendly portfolio website while significantly reducing development time.


# HTML Code

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Srishti Gupta — Mechanical Engineer & Web Developer</title>
  <meta name="description" content="Srishti Gupta — B.Tech Mechanical Engineering student at ABES EC Ghaziabad. Building at the intersection of software, automation, and engineering." />
  <meta name="keywords" content="Srishti Gupta, Mechanical Engineering, Web Developer, ABES EC, Ghaziabad, Portfolio" />
  <meta property="og:title" content="Srishti Gupta — Portfolio" />
  <meta property="og:description" content="Engineering meets code. Explore my projects, skills, and journey." />
  <meta property="og:type" content="website" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet" />
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            display: ['Space Grotesk', 'sans-serif'],
            body: ['Inter', 'sans-serif'],
          },
          colors: {
            amber: { 400: '#FBBF24', 500: '#F59E0B', 600: '#D97706' },
            navy: { 900: '#0A0F1E', 800: '#0D1528', 700: '#111C35', 600: '#162040' },
            slate: { 300: '#CBD5E1', 400: '#94A3B8' }
          }
        }
      }
    };
  </script>
  <style>
    :root {
      --accent: #F59E0B;
      --accent-light: #FCD34D;
    }

    * { box-sizing: border-box; }

    body {
      font-family: 'Inter', sans-serif;
      transition: background-color 0.3s, color 0.3s;
    }

    /* Blueprint grid — hero signature element */
    .blueprint-grid {
      background-image:
        linear-gradient(rgba(245,158,11,0.06) 1px, transparent 1px),
        linear-gradient(90deg, rgba(245,158,11,0.06) 1px, transparent 1px);
      background-size: 40px 40px;
    }

    .dark .blueprint-grid {
      background-image:
        linear-gradient(rgba(245,158,11,0.08) 1px, transparent 1px),
        linear-gradient(90deg, rgba(245,158,11,0.08) 1px, transparent 1px);
    }

    /* Typing cursor */
    .typing-cursor::after {
      content: '|';
      animation: blink 0.8s infinite;
      color: var(--accent);
      margin-left: 2px;
    }
    @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }

    /* Scroll reveal */
    .reveal {
      opacity: 0;
      transform: translateY(28px);
      transition: opacity 0.6s ease, transform 0.6s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .reveal-delay-1 { transition-delay: 0.1s; }
    .reveal-delay-2 { transition-delay: 0.2s; }
    .reveal-delay-3 { transition-delay: 0.3s; }
    .reveal-delay-4 { transition-delay: 0.4s; }

    /* Skill bar */
    .skill-bar-fill {
      width: 0;
      transition: width 1.2s cubic-bezier(.4,0,.2,1);
    }
    .skill-bar-fill.animate { width: var(--w); }

    /* Nav active */
    .nav-link.active {
      color: var(--accent);
    }
    .nav-link.active::after {
      width: 100%;
    }
    .nav-link::after {
      content: '';
      display: block;
      height: 2px;
      background: var(--accent);
      width: 0;
      transition: width 0.3s;
      margin-top: 2px;
    }
    .nav-link:hover::after { width: 100%; }

    /* Project card hover */
    .project-card {
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }

    /* Glow on accent elements */
    .glow {
      text-shadow: 0 0 30px rgba(245,158,11,0.4);
    }

    /* Mobile nav overlay */
    #mobile-nav {
      transition: transform 0.3s ease;
    }
    #mobile-nav.open { transform: translateX(0); }

    /* Light mode overrides */
    html:not(.dark) body { background-color: #F8F9FC; color: #1E293B; }
    html:not(.dark) .bg-navy { background-color: #1E293B; }

    /* Smooth scrollbar */
    ::-webkit-scrollbar { width: 6px; }
    ::-webkit-scrollbar-track { background: transparent; }
    ::-webkit-scrollbar-thumb { background: #F59E0B55; border-radius: 3px; }

    @media (prefers-reduced-motion: reduce) {
      .reveal, .skill-bar-fill { transition: none !important; }
      .typing-cursor::after { animation: none; }
    }
  </style>
</head>
<body class="dark bg-[#0A0F1E] text-slate-200 font-body">

  <!-- ═══════════════════ NAV ═══════════════════ -->
  <nav id="navbar" class="fixed top-0 left-0 right-0 z-50 transition-all duration-300">
    <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
      <!-- Logo -->
      <a href="#hero" class="font-display font-700 text-xl tracking-tight">
        <span class="text-amber-400">S</span>G
      </a>

      <!-- Desktop nav -->
      <ul class="hidden md:flex items-center gap-8 text-sm font-medium">
        <li><a href="#about" class="nav-link transition-colors hover:text-amber-400">About</a></li>
        <li><a href="#skills" class="nav-link transition-colors hover:text-amber-400">Skills</a></li>
        <li><a href="#projects" class="nav-link transition-colors hover:text-amber-400">Projects</a></li>
        <li><a href="#achievements" class="nav-link transition-colors hover:text-amber-400">Achievements</a></li>
        <li><a href="#contact" class="nav-link transition-colors hover:text-amber-400">Contact</a></li>
      </ul>

      <div class="flex items-center gap-3">
        <!-- Dark/Light toggle -->
        <button id="theme-toggle" aria-label="Toggle theme"
          class="w-10 h-10 rounded-full flex items-center justify-center border border-amber-400/30 hover:border-amber-400 hover:bg-amber-400/10 transition-all">
          <span id="theme-icon" class="text-base">☀️</span>
        </button>
        <!-- Mobile menu -->
        <button id="mob-menu-btn" class="md:hidden w-10 h-10 flex items-center justify-center" aria-label="Menu">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
        </button>
      </div>
    </div>
  </nav>

  <!-- Mobile nav drawer -->
  <div id="mobile-nav" class="fixed inset-0 z-40 translate-x-full">
    <div class="absolute inset-0 bg-black/60 backdrop-blur-sm" id="mob-overlay"></div>
    <div class="absolute right-0 top-0 h-full w-64 bg-[#0D1528] dark:bg-[#0D1528] bg-white border-l border-amber-400/20 p-8 flex flex-col gap-6">
      <button id="mob-close" class="self-end text-slate-400 hover:text-amber-400">✕</button>
      <ul class="flex flex-col gap-5 text-lg font-display">
        <li><a href="#about" class="mob-link hover:text-amber-400 transition-colors">About</a></li>
        <li><a href="#skills" class="mob-link hover:text-amber-400 transition-colors">Skills</a></li>
        <li><a href="#projects" class="mob-link hover:text-amber-400 transition-colors">Projects</a></li>
        <li><a href="#achievements" class="mob-link hover:text-amber-400 transition-colors">Achievements</a></li>
        <li><a href="#contact" class="mob-link hover:text-amber-400 transition-colors">Contact</a></li>
      </ul>
    </div>
  </div>

  <!-- ═══════════════════ HERO ═══════════════════ -->
  <section id="hero" class="relative min-h-screen flex items-center blueprint-grid overflow-hidden">
    <!-- Ambient glow orbs -->
    <div class="absolute top-1/4 left-1/4 w-72 h-72 bg-amber-500/10 rounded-full blur-3xl pointer-events-none"></div>
    <div class="absolute bottom-1/4 right-1/4 w-96 h-96 bg-amber-600/5 rounded-full blur-3xl pointer-events-none"></div>

    <div class="max-w-6xl mx-auto px-6 pt-24 pb-16 w-full">
      <div class="max-w-3xl">
        <!-- Eyebrow -->
        <div class="flex items-center gap-3 mb-6 reveal">
          <div class="h-px w-10 bg-amber-400"></div>
          <span class="text-amber-400 text-sm font-medium tracking-widest uppercase font-display">Portfolio</span>
        </div>

        <!-- Name -->
        <h1 class="font-display font-bold text-5xl sm:text-6xl md:text-7xl leading-tight mb-4 reveal reveal-delay-1">
          Srishti<br/><span class="text-amber-400 glow">Gupta.</span>
        </h1>

        <!-- Typing title -->
        <p class="font-display text-xl sm:text-2xl text-slate-300 mb-6 reveal reveal-delay-2">
          <span id="typed-text" class="typing-cursor"></span>
        </p>

        <!-- Bio snippet -->
        <p class="text-slate-400 text-base sm:text-lg leading-relaxed max-w-xl mb-10 reveal reveal-delay-3">
          B.Tech Mechanical Engineering student at ABES EC, Ghaziabad — bridging the gap between engineering precision and modern software. Building tools that make things work smarter.
        </p>

        <!-- CTAs -->
        <div class="flex flex-wrap items-center gap-4 mb-10 reveal reveal-delay-4">
          <a href="#projects"
            class="px-7 py-3 bg-amber-500 hover:bg-amber-400 text-[#0A0F1E] font-semibold font-display rounded-lg transition-all hover:shadow-lg hover:shadow-amber-500/30">
            View My Work
          </a>
          <a href="#contact"
            class="px-7 py-3 border border-amber-400/40 hover:border-amber-400 hover:bg-amber-400/10 rounded-lg font-display font-medium transition-all">
            Get In Touch
          </a>
        </div>

        <!-- Social links -->
        <div class="flex items-center gap-5 reveal reveal-delay-4">
          <a href="mailto:Shriiee702@gmail.com" aria-label="Email"
            class="text-slate-400 hover:text-amber-400 transition-colors">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/></svg>
          </a>
          <a href="https://www.linkedin.com/in/srishti-gupta-036636281/" target="_blank" rel="noopener" aria-label="LinkedIn"
            class="text-slate-400 hover:text-amber-400 transition-colors">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
          </a>
          <a href="https://github.com/Twilight0072008" target="_blank" rel="noopener" aria-label="GitHub"
            class="text-slate-400 hover:text-amber-400 transition-colors">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
          </a>
          <span class="text-slate-600 text-sm font-display ml-1">📍 Ghaziabad, India</span>
        </div>
      </div>
    </div>

    <!-- Scroll indicator -->
    <div class="absolute bottom-8 left-1/2 -translate-x-1/2 flex flex-col items-center gap-2 text-slate-500 text-xs font-display animate-bounce">
      <span>Scroll</span>
      <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
      </svg>
    </div>
  </section>

  <!-- ═══════════════════ ABOUT ═══════════════════ -->
  <section id="about" class="py-24 px-6">
    <div class="max-w-6xl mx-auto">
      <div class="grid md:grid-cols-2 gap-16 items-center">
        <!-- Visual -->
        <div class="reveal order-2 md:order-1">
          <div class="relative">
            <!-- Blueprint-style decorative box -->
            <div class="rounded-2xl overflow-hidden border border-amber-400/20 bg-[#0D1528] p-8">
              <div class="text-amber-400/60 font-display text-xs tracking-widest uppercase mb-6">// About</div>
              <div class="space-y-4">
                <div class="flex items-start gap-3">
                  <div class="mt-1 w-2 h-2 rounded-full bg-amber-400 flex-shrink-0"></div>
                  <p class="text-slate-300 text-sm leading-relaxed">
                    Pursuing <strong class="text-amber-400">B.Tech in Mechanical Engineering</strong> at Dr. A.P.J. Abdul Kalam Technical University (ABES EC, Ghaziabad) — graduating July 2029.
                  </p>
                </div>
                <div class="flex items-start gap-3">
                  <div class="mt-1 w-2 h-2 rounded-full bg-amber-400 flex-shrink-0"></div>
                  <p class="text-slate-300 text-sm leading-relaxed">
                    Passionate about <strong class="text-amber-400">combining software, automation, and engineering</strong> principles to bridge the gap between technology and mechanics.
                  </p>
                </div>
                <div class="flex items-start gap-3">
                  <div class="mt-1 w-2 h-2 rounded-full bg-amber-400 flex-shrink-0"></div>
                  <p class="text-slate-300 text-sm leading-relaxed">
                    Active in college clubs, sports tournaments, defence awareness activities, entrepreneurship events, and community leadership.
                  </p>
                </div>
              </div>
              <!-- Stats row -->
              <div class="mt-8 grid grid-cols-3 gap-4 pt-6 border-t border-amber-400/10">
                <div class="text-center">
                  <div class="font-display font-bold text-2xl text-amber-400">3+</div>
                  <div class="text-slate-500 text-xs mt-1">Projects</div>
                </div>
                <div class="text-center">
                  <div class="font-display font-bold text-2xl text-amber-400">4</div>
                  <div class="text-slate-500 text-xs mt-1">Certificates</div>
                </div>
                <div class="text-center">
                  <div class="font-display font-bold text-2xl text-amber-400">2029</div>
                  <div class="text-slate-500 text-xs mt-1">Graduating</div>
                </div>
              </div>
            </div>
            <!-- Decorative corner accents -->
            <div class="absolute -top-2 -left-2 w-6 h-6 border-t-2 border-l-2 border-amber-400/60 rounded-tl-sm"></div>
            <div class="absolute -bottom-2 -right-2 w-6 h-6 border-b-2 border-r-2 border-amber-400/60 rounded-br-sm"></div>
          </div>
        </div>

        <!-- Text -->
        <div class="reveal reveal-delay-2 order-1 md:order-2">
          <div class="flex items-center gap-3 mb-4">
            <div class="h-px w-8 bg-amber-400"></div>
            <span class="text-amber-400 text-sm font-medium tracking-widest uppercase font-display">Who I Am</span>
          </div>
          <h2 class="font-display font-bold text-3xl sm:text-4xl mb-6 leading-tight">
            Engineering student.<br/>Software builder.<br/><span class="text-amber-400">Problem solver.</span>
          </h2>
          <p class="text-slate-400 leading-relaxed mb-4">
            I'm Srishti — a first-year Mechanical Engineering student who discovered that the most interesting problems sit right at the intersection of physical systems and digital intelligence.
          </p>
          <p class="text-slate-400 leading-relaxed mb-8">
            I build web applications and tools that are practical, well-designed, and actually solve something. Whether it's an API for student data management or an AI-powered audio tagging system, I approach every project like an engineer: systematic, iterative, and detail-oriented.
          </p>
          <a href="mailto:Shriiee702@gmail.com"
            class="inline-flex items-center gap-2 text-amber-400 font-display font-medium hover:gap-4 transition-all">
            Let's connect
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
            </svg>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ═══════════════════ SKILLS ═══════════════════ -->
  <section id="skills" class="py-24 px-6 bg-[#0D1528]/60">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16 reveal">
        <div class="flex items-center justify-center gap-3 mb-4">
          <div class="h-px w-8 bg-amber-400"></div>
          <span class="text-amber-400 text-sm font-medium tracking-widest uppercase font-display">Capabilities</span>
          <div class="h-px w-8 bg-amber-400"></div>
        </div>
        <h2 class="font-display font-bold text-3xl sm:text-4xl">Skills & Tools</h2>
      </div>

      <div class="grid md:grid-cols-2 gap-16">
        <!-- Skill bars -->
        <div class="reveal reveal-delay-1">
          <h3 class="font-display font-semibold text-lg mb-6 text-amber-400">Technical Proficiency</h3>
          <div class="space-y-5" id="skill-bars">
            <div class="skill-item">
              <div class="flex justify-between text-sm mb-2">
                <span class="font-medium">HTML & CSS</span><span class="text-slate-400">85%</span>
              </div>
              <div class="h-1.5 bg-[#162040] rounded-full overflow-hidden">
                <div class="skill-bar-fill h-full bg-gradient-to-r from-amber-500 to-amber-300 rounded-full" style="--w:85%"></div>
              </div>
            </div>
            <div class="skill-item">
              <div class="flex justify-between text-sm mb-2">
                <span class="font-medium">JavaScript</span><span class="text-slate-400">75%</span>
              </div>
              <div class="h-1.5 bg-[#162040] rounded-full overflow-hidden">
                <div class="skill-bar-fill h-full bg-gradient-to-r from-amber-500 to-amber-300 rounded-full" style="--w:75%"></div>
              </div>
            </div>
            <div class="skill-item">
              <div class="flex justify-between text-sm mb-2">
                <span class="font-medium">Node.js / Express</span><span class="text-slate-400">65%</span>
              </div>
              <div class="h-1.5 bg-[#162040] rounded-full overflow-hidden">
                <div class="skill-bar-fill h-full bg-gradient-to-r from-amber-500 to-amber-300 rounded-full" style="--w:65%"></div>
              </div>
            </div>
            <div class="skill-item">
              <div class="flex justify-between text-sm mb-2">
                <span class="font-medium">SQL / MySQL</span><span class="text-slate-400">60%</span>
              </div>
              <div class="h-1.5 bg-[#162040] rounded-full overflow-hidden">
                <div class="skill-bar-fill h-full bg-gradient-to-r from-amber-500 to-amber-300 rounded-full" style="--w:60%"></div>
              </div>
            </div>
            <div class="skill-item">
              <div class="flex justify-between text-sm mb-2">
                <span class="font-medium">Figma / UI Design</span><span class="text-slate-400">70%</span>
              </div>
              <div class="h-1.5 bg-[#162040] rounded-full overflow-hidden">
                <div class="skill-bar-fill h-full bg-gradient-to-r from-amber-500 to-amber-300 rounded-full" style="--w:70%"></div>
              </div>
            </div>
            <div class="skill-item">
              <div class="flex justify-between text-sm mb-2">
                <span class="font-medium">C++ / Python</span><span class="text-slate-400">55%</span>
              </div>
              <div class="h-1.5 bg-[#162040] rounded-full overflow-hidden">
                <div class="skill-bar-fill h-full bg-gradient-to-r from-amber-500 to-amber-300 rounded-full" style="--w:55%"></div>
              </div>
            </div>
          </div>
        </div>

        <!-- Tag cloud -->
        <div class="reveal reveal-delay-2">
          <h3 class="font-display font-semibold text-lg mb-6 text-amber-400">Technologies & Tools</h3>
          <div class="mb-6">
            <p class="text-slate-500 text-xs uppercase tracking-widest font-display mb-3">Frontend</p>
            <div class="flex flex-wrap gap-2">
              <span class="tag">HTML5</span><span class="tag">CSS3</span><span class="tag">JavaScript</span>
              <span class="tag">Responsive Design</span><span class="tag">Chart.js</span>
            </div>
          </div>
          <div class="mb-6">
            <p class="text-slate-500 text-xs uppercase tracking-widest font-display mb-3">Backend & Data</p>
            <div class="flex flex-wrap gap-2">
              <span class="tag">Node.js</span><span class="tag">Express.js</span><span class="tag">MySQL</span><span class="tag">REST API</span>
            </div>
          </div>
          <div class="mb-6">
            <p class="text-slate-500 text-xs uppercase tracking-widest font-display mb-3">Design & Media</p>
            <div class="flex flex-wrap gap-2">
              <span class="tag">Figma</span><span class="tag">Canva</span><span class="tag">Adobe Premiere Pro</span>
            </div>
          </div>
          <div class="mb-6">
            <p class="text-slate-500 text-xs uppercase tracking-widest font-display mb-3">Dev Tools & AI</p>
            <div class="flex flex-wrap gap-2">
              <span class="tag">VS Code</span><span class="tag">GitHub</span><span class="tag">Claude AI</span><span class="tag">GitHub Copilot</span><span class="tag">AI/ML APIs</span>
            </div>
          </div>
          <div>
            <p class="text-slate-500 text-xs uppercase tracking-widest font-display mb-3">Soft Skills</p>
            <div class="flex flex-wrap gap-2">
              <span class="tag-soft">Leadership</span>
              <span class="tag-soft">Communication</span>
              <span class="tag-soft">Team Collaboration</span>
              <span class="tag-soft">Problem Solving</span>
              <span class="tag-soft">Adaptability</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Inline tag styles via a style block (can't use @apply without PostCSS) -->
  <style>
    .tag {
      display: inline-block;
      padding: 4px 12px;
      background: rgba(245,158,11,0.1);
      border: 1px solid rgba(245,158,11,0.25);
      border-radius: 6px;
      font-size: 0.75rem;
      font-family: 'Space Grotesk', sans-serif;
      font-weight: 500;
      color: #FCD34D;
      transition: all 0.2s;
      cursor: default;
    }
    .tag:hover { background: rgba(245,158,11,0.2); border-color: rgba(245,158,11,0.5); }
    .tag-soft {
      display: inline-block;
      padding: 4px 12px;
      background: rgba(100,116,139,0.1);
      border: 1px solid rgba(100,116,139,0.25);
      border-radius: 6px;
      font-size: 0.75rem;
      font-family: 'Space Grotesk', sans-serif;
      font-weight: 500;
      color: #94A3B8;
    }
    html:not(.dark) .tag { background: rgba(245,158,11,0.08); color: #92400E; border-color: rgba(245,158,11,0.3); }
    html:not(.dark) .tag-soft { color: #475569; }
  </style>

  <!-- ═══════════════════ PROJECTS ═══════════════════ -->
  <section id="projects" class="py-24 px-6">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16 reveal">
        <div class="flex items-center justify-center gap-3 mb-4">
          <div class="h-px w-8 bg-amber-400"></div>
          <span class="text-amber-400 text-sm font-medium tracking-widest uppercase font-display">Work</span>
          <div class="h-px w-8 bg-amber-400"></div>
        </div>
        <h2 class="font-display font-bold text-3xl sm:text-4xl">Featured Projects</h2>
        <p class="text-slate-400 mt-3 max-w-xl mx-auto">Practical builds that solve real problems — from backend APIs to AI-powered tools.</p>
      </div>

      <div class="grid md:grid-cols-3 gap-6">

        <!-- Project 1 -->
        <div class="project-card reveal reveal-delay-1 rounded-2xl border border-amber-400/15 bg-[#0D1528] overflow-hidden hover:border-amber-400/40 hover:shadow-xl hover:shadow-amber-500/10">
          <div class="h-2 bg-gradient-to-r from-amber-500 to-amber-300"></div>
          <div class="p-6">
            <div class="flex items-start justify-between mb-4">
              <div class="w-10 h-10 rounded-xl bg-amber-400/10 flex items-center justify-center text-amber-400">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h14M12 5l7 7-7 7"/>
                </svg>
              </div>
              <span class="text-amber-400/60 font-display text-xs">01</span>
            </div>
            <h3 class="font-display font-semibold text-lg mb-2">Student Management API</h3>
            <p class="text-slate-400 text-sm leading-relaxed mb-4">
              A RESTful backend API for managing complete student lifecycle operations — records, enrollment, grades, and queries. Built with clean architecture and MySQL relational data modeling.
            </p>
            <div class="flex flex-wrap gap-1.5 mb-6">
              <span class="tag">Node.js</span><span class="tag">Express.js</span><span class="tag">MySQL</span>
            </div>
            <div class="flex items-center gap-4 pt-4 border-t border-amber-400/10">
              <a href="https://github.com/Twilight0072008" target="_blank" rel="noopener"
                class="flex items-center gap-1.5 text-xs text-slate-400 hover:text-amber-400 transition-colors font-display">
                <svg class="w-3.5 h-3.5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
                Code
              </a>
            </div>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="project-card reveal reveal-delay-2 rounded-2xl border border-amber-400/15 bg-[#0D1528] overflow-hidden hover:border-amber-400/40 hover:shadow-xl hover:shadow-amber-500/10">
          <div class="h-2 bg-gradient-to-r from-teal-500 to-amber-400"></div>
          <div class="p-6">
            <div class="flex items-start justify-between mb-4">
              <div class="w-10 h-10 rounded-xl bg-teal-500/10 flex items-center justify-center text-teal-400">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.536 8.464a5 5 0 010 7.072M12 9.17l-2.121 2.122a3 3 0 000 4.243L12 17.657M9.879 6.343A8 8 0 0120.66 17.12"/>
                </svg>
              </div>
              <span class="text-amber-400/60 font-display text-xs">02</span>
            </div>
            <h3 class="font-display font-semibold text-lg mb-2">EchoTag</h3>
            <p class="text-slate-400 text-sm leading-relaxed mb-4">
              Smart audio organization platform that uses AI/ML APIs to automatically classify, label, and manage voice recordings. Transforms chaotic audio libraries into searchable, structured collections.
            </p>
            <div class="flex flex-wrap gap-1.5 mb-6">
              <span class="tag">HTML</span><span class="tag">CSS</span><span class="tag">JavaScript</span><span class="tag">AI/ML APIs</span>
            </div>
            <div class="flex items-center gap-4 pt-4 border-t border-amber-400/10">
              <a href="https://github.com/Twilight0072008" target="_blank" rel="noopener"
                class="flex items-center gap-1.5 text-xs text-slate-400 hover:text-amber-400 transition-colors font-display">
                <svg class="w-3.5 h-3.5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
                Code
              </a>
            </div>
          </div>
        </div>

        <!-- Project 3 -->
        <div class="project-card reveal reveal-delay-3 rounded-2xl border border-amber-400/15 bg-[#0D1528] overflow-hidden hover:border-amber-400/40 hover:shadow-xl hover:shadow-amber-500/10">
          <div class="h-2 bg-gradient-to-r from-emerald-500 to-teal-400"></div>
          <div class="p-6">
            <div class="flex items-start justify-between mb-4">
              <div class="w-10 h-10 rounded-xl bg-emerald-500/10 flex items-center justify-center text-emerald-400">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
                </svg>
              </div>
              <span class="text-amber-400/60 font-display text-xs">03</span>
            </div>
            <h3 class="font-display font-semibold text-lg mb-2">NutriScope Enhanced</h3>
            <p class="text-slate-400 text-sm leading-relaxed mb-4">
              Comprehensive nutrition intelligence platform featuring personalized meal planning, health risk analysis, CSV data uploads, and data-driven recommendations — all visualized through interactive charts.
            </p>
            <div class="flex flex-wrap gap-1.5 mb-6">
              <span class="tag">HTML5</span><span class="tag">CSS3</span><span class="tag">JavaScript</span><span class="tag">Chart.js</span>
            </div>
            <div class="flex items-center gap-4 pt-4 border-t border-amber-400/10">
              <a href="https://github.com/Twilight0072008" target="_blank" rel="noopener"
                class="flex items-center gap-1.5 text-xs text-slate-400 hover:text-amber-400 transition-colors font-display">
                <svg class="w-3.5 h-3.5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
                Code
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ═══════════════════ ACHIEVEMENTS ═══════════════════ -->
  <section id="achievements" class="py-24 px-6 bg-[#0D1528]/60">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16 reveal">
        <div class="flex items-center justify-center gap-3 mb-4">
          <div class="h-px w-8 bg-amber-400"></div>
          <span class="text-amber-400 text-sm font-medium tracking-widest uppercase font-display">Recognition</span>
          <div class="h-px w-8 bg-amber-400"></div>
        </div>
        <h2 class="font-display font-bold text-3xl sm:text-4xl">Achievements & Certifications</h2>
      </div>

      <div class="grid md:grid-cols-2 gap-6">

        <div class="reveal reveal-delay-1 group flex items-start gap-5 p-5 rounded-xl border border-amber-400/10 bg-[#0A0F1E] hover:border-amber-400/30 transition-all">
          <div class="w-10 h-10 rounded-full bg-amber-400/10 flex-shrink-0 flex items-center justify-center text-amber-400 group-hover:bg-amber-400/20 transition-all">🏆</div>
          <div>
            <div class="flex items-start justify-between gap-4">
              <h3 class="font-display font-semibold text-sm">E-Cell E-Summit</h3>
              <span class="text-amber-400/70 text-xs font-display flex-shrink-0">Dec 2025</span>
            </div>
            <p class="text-slate-400 text-sm mt-1">Certificate for participation in entrepreneurship and innovation events.</p>
          </div>
        </div>

        <div class="reveal reveal-delay-2 group flex items-start gap-5 p-5 rounded-xl border border-amber-400/10 bg-[#0A0F1E] hover:border-amber-400/30 transition-all">
          <div class="w-10 h-10 rounded-full bg-amber-400/10 flex-shrink-0 flex items-center justify-center text-amber-400 group-hover:bg-amber-400/20 transition-all">🎮</div>
          <div>
            <div class="flex items-start justify-between gap-4">
              <h3 class="font-display font-semibold text-sm">Squid Game</h3>
              <span class="text-amber-400/70 text-xs font-display flex-shrink-0">Nov 2025</span>
            </div>
            <p class="text-slate-400 text-sm mt-1">Certificate for participation in a competitive logic-based team event.</p>
          </div>
        </div>

        <div class="reveal reveal-delay-3 group flex items-start gap-5 p-5 rounded-xl border border-amber-400/10 bg-[#0A0F1E] hover:border-amber-400/30 transition-all">
          <div class="w-10 h-10 rounded-full bg-amber-400/10 flex-shrink-0 flex items-center justify-center text-amber-400 group-hover:bg-amber-400/20 transition-all">🛡️</div>
          <div>
            <div class="flex items-start justify-between gap-4">
              <h3 class="font-display font-semibold text-sm">Trishul Defence Club</h3>
              <span class="text-amber-400/70 text-xs font-display flex-shrink-0">Oct 2025</span>
            </div>
            <p class="text-slate-400 text-sm mt-1">Certificate for involvement in defence awareness and leadership activities.</p>
          </div>
        </div>

        <div class="reveal reveal-delay-4 group flex items-start gap-5 p-5 rounded-xl border border-amber-400/10 bg-[#0A0F1E] hover:border-amber-400/30 transition-all">
          <div class="w-10 h-10 rounded-full bg-amber-400/10 flex-shrink-0 flex items-center justify-center text-amber-400 group-hover:bg-amber-400/20 transition-all">🎨</div>
          <div>
            <div class="flex items-start justify-between gap-4">
              <h3 class="font-display font-semibold text-sm">GDG — Figma Workshop</h3>
              <span class="text-amber-400/70 text-xs font-display flex-shrink-0">Nov 2025</span>
            </div>
            <p class="text-slate-400 text-sm mt-1">Certificate for attending a hands-on Figma workshop and an insightful session on Web3 fundamentals.</p>
          </div>
        </div>

      </div>

      <!-- Education timeline -->
      <div class="mt-16 reveal">
        <h3 class="font-display font-semibold text-xl mb-8 text-center">Education</h3>
        <div class="relative max-w-2xl mx-auto">
          <div class="absolute left-4 top-0 bottom-0 w-px bg-amber-400/20"></div>
          <div class="space-y-8">
            <div class="flex items-start gap-6 pl-12 relative">
              <div class="absolute left-0 w-8 h-8 rounded-full bg-amber-400/10 border-2 border-amber-400/40 flex items-center justify-center text-amber-400 text-xs">1</div>
              <div>
                <div class="text-amber-400 text-xs font-display mb-1">Aug 2025 — July 2029</div>
                <h4 class="font-display font-semibold">B.Tech — Mechanical Engineering</h4>
                <p class="text-slate-400 text-sm">Dr. A.P.J. Abdul Kalam Technical University · ABES EC, Ghaziabad</p>
              </div>
            </div>
            <div class="flex items-start gap-6 pl-12 relative">
              <div class="absolute left-0 w-8 h-8 rounded-full bg-amber-400/10 border-2 border-amber-400/20 flex items-center justify-center text-amber-400 text-xs">2</div>
              <div>
                <div class="text-amber-400 text-xs font-display mb-1">March 2024</div>
                <h4 class="font-display font-semibold">Intermediate</h4>
                <p class="text-slate-400 text-sm">Oxford Public School, U.P.</p>
              </div>
            </div>
            <div class="flex items-start gap-6 pl-12 relative">
              <div class="absolute left-0 w-8 h-8 rounded-full bg-amber-400/10 border-2 border-amber-400/20 flex items-center justify-center text-amber-400 text-xs">3</div>
              <div>
                <div class="text-amber-400 text-xs font-display mb-1">March 2022</div>
                <h4 class="font-display font-semibold">Matriculate</h4>
                <p class="text-slate-400 text-sm">Siddharth Public School, U.P.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ═══════════════════ CONTACT ═══════════════════ -->
  <section id="contact" class="py-24 px-6">
    <div class="max-w-6xl mx-auto">
      <div class="text-center mb-16 reveal">
        <div class="flex items-center justify-center gap-3 mb-4">
          <div class="h-px w-8 bg-amber-400"></div>
          <span class="text-amber-400 text-sm font-medium tracking-widest uppercase font-display">Contact</span>
          <div class="h-px w-8 bg-amber-400"></div>
        </div>
        <h2 class="font-display font-bold text-3xl sm:text-4xl">Let's Build Something</h2>
        <p class="text-slate-400 mt-3 max-w-md mx-auto">Open to projects, collaborations, internships, and interesting conversations.</p>
      </div>

      <div class="grid md:grid-cols-2 gap-12 max-w-4xl mx-auto">

        <!-- Contact info -->
        <div class="reveal">
          <div class="space-y-6">
            <a href="mailto:Shriiee702@gmail.com"
              class="flex items-center gap-4 p-4 rounded-xl border border-amber-400/15 hover:border-amber-400/40 hover:bg-amber-400/5 transition-all group">
              <div class="w-10 h-10 bg-amber-400/10 rounded-xl flex items-center justify-center text-amber-400 group-hover:bg-amber-400/20 transition-all">
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"/><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"/></svg>
              </div>
              <div>
                <div class="text-xs text-slate-500 font-display mb-0.5">Email</div>
                <div class="text-sm font-medium">Shriiee702@gmail.com</div>
              </div>
            </a>

            <a href="https://www.linkedin.com/in/srishti-gupta-036636281/" target="_blank" rel="noopener"
              class="flex items-center gap-4 p-4 rounded-xl border border-amber-400/15 hover:border-amber-400/40 hover:bg-amber-400/5 transition-all group">
              <div class="w-10 h-10 bg-amber-400/10 rounded-xl flex items-center justify-center text-amber-400 group-hover:bg-amber-400/20 transition-all">
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
              </div>
              <div>
                <div class="text-xs text-slate-500 font-display mb-0.5">LinkedIn</div>
                <div class="text-sm font-medium">Srishti Gupta</div>
              </div>
            </a>

            <a href="https://github.com/Twilight0072008" target="_blank" rel="noopener"
              class="flex items-center gap-4 p-4 rounded-xl border border-amber-400/15 hover:border-amber-400/40 hover:bg-amber-400/5 transition-all group">
              <div class="w-10 h-10 bg-amber-400/10 rounded-xl flex items-center justify-center text-amber-400 group-hover:bg-amber-400/20 transition-all">
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
              </div>
              <div>
                <div class="text-xs text-slate-500 font-display mb-0.5">GitHub</div>
                <div class="text-sm font-medium">Twilight0072008</div>
              </div>
            </a>

            <div class="flex items-center gap-4 p-4 rounded-xl border border-amber-400/15">
              <div class="w-10 h-10 bg-amber-400/10 rounded-xl flex items-center justify-center text-amber-400">📍</div>
              <div>
                <div class="text-xs text-slate-500 font-display mb-0.5">Location</div>
                <div class="text-sm font-medium">Ghaziabad, Uttar Pradesh, India</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Contact form -->
        <div class="reveal reveal-delay-2">
          <div class="p-6 rounded-2xl border border-amber-400/15 bg-[#0D1528]">
            <h3 class="font-display font-semibold mb-5">Send a Message</h3>
            <div class="space-y-4">
              <div>
                <label class="block text-xs text-slate-500 font-display mb-1.5">Your Name</label>
                <input type="text" id="form-name" placeholder="Jane Smith"
                  class="w-full px-4 py-2.5 rounded-lg bg-[#0A0F1E] border border-amber-400/15 focus:border-amber-400/50 focus:outline-none text-sm transition-colors placeholder:text-slate-600" />
              </div>
              <div>
                <label class="block text-xs text-slate-500 font-display mb-1.5">Email</label>
                <input type="email" id="form-email" placeholder="jane@example.com"
                  class="w-full px-4 py-2.5 rounded-lg bg-[#0A0F1E] border border-amber-400/15 focus:border-amber-400/50 focus:outline-none text-sm transition-colors placeholder:text-slate-600" />
              </div>
              <div>
                <label class="block text-xs text-slate-500 font-display mb-1.5">Message</label>
                <textarea id="form-msg" rows="4" placeholder="Hi Srishti, I'd like to discuss..."
                  class="w-full px-4 py-2.5 rounded-lg bg-[#0A0F1E] border border-amber-400/15 focus:border-amber-400/50 focus:outline-none text-sm transition-colors placeholder:text-slate-600 resize-none"></textarea>
              </div>
              <button onclick="sendEmail()"
                class="w-full py-3 bg-amber-500 hover:bg-amber-400 text-[#0A0F1E] font-display font-semibold rounded-lg transition-all hover:shadow-lg hover:shadow-amber-500/30">
                Send Message
              </button>
              <div id="form-status" class="text-center text-sm text-slate-400 hidden"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ═══════════════════ FOOTER ═══════════════════ -->
  <footer class="py-8 px-6 border-t border-amber-400/10">
    <div class="max-w-6xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-4 text-slate-500 text-sm">
      <div class="font-display">
        <span class="text-amber-400">SG</span> · Srishti Gupta · Ghaziabad, India
      </div>
      <div class="font-display text-xs">
        Built with HTML · Tailwind CSS · Vanilla JS
      </div>
    </div>
  </footer>

  <!-- ═══════════════════ LIGHT MODE OVERRIDES ═══════════════════ -->
  <style>
    html:not(.dark) body { background-color: #F1F5F9; color: #0F172A; }
    html:not(.dark) section { }
    html:not(.dark) #navbar { }
    html:not(.dark) .bg-\[#0D1528\]\/60 { background-color: rgba(226,232,240,0.6); }
    html:not(.dark) .bg-\[#0D1528\] { background-color: #FFFFFF; }
    html:not(.dark) .bg-\[#0A0F1E\] { background-color: #F8FAFC; }
    html:not(.dark) .text-slate-400 { color: #475569; }
    html:not(.dark) .text-slate-300 { color: #334155; }
    html:not(.dark) .text-slate-200 { color: #1E293B; }
    html:not(.dark) .border-amber-400\/15 { border-color: rgba(245,158,11,0.2); }
    html:not(.dark) .border-amber-400\/10 { border-color: rgba(245,158,11,0.15); }
    html:not(.dark) nav { background: rgba(241,245,249,0.95); border-bottom: 1px solid rgba(245,158,11,0.1); }
    html:not(.dark) h1, html:not(.dark) h2, html:not(.dark) h3, html:not(.dark) h4 { color: #0F172A; }
    html:not(.dark) .blueprint-grid {
      background-image:
        linear-gradient(rgba(245,158,11,0.08) 1px, transparent 1px),
        linear-gradient(90deg, rgba(245,158,11,0.08) 1px, transparent 1px);
    }
  </style>

  <!-- ═══════════════════ JAVASCRIPT ═══════════════════ -->
  <script>
    // ── Dark/Light Toggle ──────────────────────────────
    const html = document.documentElement;
    const themeIcon = document.getElementById('theme-icon');
    let isDark = true;

    document.getElementById('theme-toggle').addEventListener('click', () => {
      isDark = !isDark;
      html.classList.toggle('dark', isDark);
      themeIcon.textContent = isDark ? '☀️' : '🌙';
    });

    // ── Typing Animation ──────────────────────────────
    const phrases = [
      'Mechanical Engineer',
      'Web Developer',
      'Frontend Builder',
      'GenAI Enthusiast',
      'Problem Solver'
    ];
    let phraseIdx = 0, charIdx = 0, isDeleting = false;
    const typedEl = document.getElementById('typed-text');

    function type() {
      const current = phrases[phraseIdx];
      if (isDeleting) {
        typedEl.textContent = current.substring(0, charIdx--);
        if (charIdx < 0) { isDeleting = false; phraseIdx = (phraseIdx + 1) % phrases.length; setTimeout(type, 500); return; }
      } else {
        typedEl.textContent = current.substring(0, charIdx++);
        if (charIdx > current.length) { isDeleting = true; setTimeout(type, 1800); return; }
      }
      setTimeout(type, isDeleting ? 60 : 100);
    }
    type();

    // ── Navbar scroll style ──────────────────────────
    const navbar = document.getElementById('navbar');
    window.addEventListener('scroll', () => {
      if (window.scrollY > 50) {
        navbar.style.background = isDark ? 'rgba(10,15,30,0.95)' : 'rgba(241,245,249,0.95)';
        navbar.style.backdropFilter = 'blur(12px)';
        navbar.style.borderBottom = '1px solid rgba(245,158,11,0.12)';
      } else {
        navbar.style.background = 'transparent';
        navbar.style.backdropFilter = 'none';
        navbar.style.borderBottom = 'none';
      }
    });

    // ── Active nav highlight ──────────────────────────
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('.nav-link');
    const io = new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          navLinks.forEach(l => l.classList.remove('active'));
          const active = document.querySelector(`.nav-link[href="#${e.target.id}"]`);
          if (active) active.classList.add('active');
        }
      });
    }, { threshold: 0.5 });
    sections.forEach(s => io.observe(s));

    // ── Scroll reveal ──────────────────────────────────
    const revealObs = new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) { e.target.classList.add('visible'); revealObs.unobserve(e.target); }
      });
    }, { threshold: 0.1 });
    document.querySelectorAll('.reveal').forEach(el => revealObs.observe(el));

    // ── Skill bars ──────────────────────────────────────
    const barObs = new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          e.target.querySelectorAll('.skill-bar-fill').forEach(b => b.classList.add('animate'));
          barObs.unobserve(e.target);
        }
      });
    }, { threshold: 0.3 });
    const skillBars = document.getElementById('skill-bars');
    if (skillBars) barObs.observe(skillBars);

    // ── Mobile nav ──────────────────────────────────────
    const mobileNav = document.getElementById('mobile-nav');
    document.getElementById('mob-menu-btn').addEventListener('click', () => mobileNav.classList.add('open'));
    document.getElementById('mob-close').addEventListener('click', () => mobileNav.classList.remove('open'));
    document.getElementById('mob-overlay').addEventListener('click', () => mobileNav.classList.remove('open'));
    document.querySelectorAll('.mob-link').forEach(l => l.addEventListener('click', () => mobileNav.classList.remove('open')));

    // ── Contact form ──────────────────────────────────
    function sendEmail() {
      const name = document.getElementById('form-name').value.trim();
      const email = document.getElementById('form-email').value.trim();
      const msg = document.getElementById('form-msg').value.trim();
      const status = document.getElementById('form-status');

      if (!name || !email || !msg) {
        status.textContent = 'Please fill in all fields.';
        status.classList.remove('hidden');
        return;
      }

      const subject = encodeURIComponent(`Portfolio Contact from ${name}`);
      const body = encodeURIComponent(`Hi Srishti,\n\nName: ${name}\nEmail: ${email}\n\nMessage:\n${msg}`);
      window.open(`mailto:Shriiee702@gmail.com?subject=${subject}&body=${body}`);

      status.textContent = '✓ Opening your email client…';
      status.classList.remove('hidden');
      setTimeout(() => status.classList.add('hidden'), 3000);
    }
  </script>

</body>
</html>
