<!DOCTYPE html>
<html lang="id" x-data="site()" :class="darkMode ? 'dark' : ''" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Calvin Misiro — Developer & Mahasiswa</title>

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,400&display=swap" rel="stylesheet"/>

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Alpine JS -->
  <script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"/>

  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            jakarta: ['"Plus Jakarta Sans"', 'sans-serif'],
          },
          colors: {
            navy: {
              50:  '#eef2ff',
              100: '#e0e7ff',
              200: '#c7d2fe',
              300: '#a5b4fc',
              400: '#818cf8',
              500: '#6366f1',
              600: '#1e3a5f',
              700: '#162d4a',
              800: '#0f2238',
              900: '#091829',
              950: '#050e1a',
            },
            accent: '#3b82f6',
          },
          animation: {
            'fade-in-up': 'fadeInUp 0.7s ease both',
            'fade-in':    'fadeIn 0.6s ease both',
            'float':      'float 4s ease-in-out infinite',
            'pulse-slow': 'pulse 3s ease-in-out infinite',
          },
          keyframes: {
            fadeInUp: {
              '0%':   { opacity: '0', transform: 'translateY(30px)' },
              '100%': { opacity: '1', transform: 'translateY(0)' },
            },
            fadeIn: {
              '0%':   { opacity: '0' },
              '100%': { opacity: '1' },
            },
            float: {
              '0%, 100%': { transform: 'translateY(0px)' },
              '50%':      { transform: 'translateY(-12px)' },
            },
          },
        },
      },
    }
  </script>

  <style>
    * { font-family: 'Plus Jakarta Sans', sans-serif; }

    /* Scrollbar */
    ::-webkit-scrollbar { width: 6px; }
    ::-webkit-scrollbar-track { background: transparent; }
    ::-webkit-scrollbar-thumb { background: #1e3a5f; border-radius: 99px; }
    .dark ::-webkit-scrollbar-thumb { background: #3b82f6; }

    /* Mesh gradient bg */
    .mesh-light {
      background: radial-gradient(ellipse at 20% 20%, #c7d2fe 0%, transparent 55%),
                  radial-gradient(ellipse at 80% 80%, #bfdbfe 0%, transparent 55%),
                  radial-gradient(ellipse at 60% 10%, #dbeafe 0%, transparent 45%),
                  #f0f4ff;
    }
    .mesh-dark {
      background: radial-gradient(ellipse at 20% 20%, #0f2238 0%, transparent 55%),
                  radial-gradient(ellipse at 80% 80%, #091829 0%, transparent 55%),
                  radial-gradient(ellipse at 60% 10%, #162d4a 0%, transparent 45%),
                  #050e1a;
    }

    /* Noise overlay */
    .noise::after {
      content: '';
      position: absolute;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none;
      opacity: 0.4;
    }

    /* Glow blob */
    .glow-blob {
      position: absolute;
      border-radius: 9999px;
      filter: blur(80px);
      opacity: 0.18;
      pointer-events: none;
    }

    /* Card hover */
    .port-card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .port-card:hover {
      transform: translateY(-6px);
    }

    /* Nav active underline */
    .nav-link {
      position: relative;
    }
    .nav-link::after {
      content: '';
      position: absolute;
      bottom: -3px; left: 0;
      width: 0; height: 2px;
      background: #3b82f6;
      transition: width 0.3s ease;
      border-radius: 99px;
    }
    .nav-link:hover::after { width: 100%; }

    /* Typing cursor */
    .cursor-blink {
      display: inline-block;
      width: 3px;
      height: 1.1em;
      background: #3b82f6;
      margin-left: 4px;
      vertical-align: text-bottom;
      animation: blink 0.9s step-end infinite;
    }
    @keyframes blink { 50% { opacity: 0; } }

    /* Skill bar */
    .skill-bar-fill {
      transition: width 1.2s cubic-bezier(0.4, 0, 0.2, 1);
    }

    /* Section reveal */
    .reveal {
      opacity: 0;
      transform: translateY(28px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: none;
    }

    /* Stagger children */
    .stagger > *:nth-child(1) { transition-delay: 0.05s; }
    .stagger > *:nth-child(2) { transition-delay: 0.12s; }
    .stagger > *:nth-child(3) { transition-delay: 0.19s; }
    .stagger > *:nth-child(4) { transition-delay: 0.26s; }
    .stagger > *:nth-child(5) { transition-delay: 0.33s; }
    .stagger > *:nth-child(6) { transition-delay: 0.40s; }

    /* Glass card */
    .glass {
      background: rgba(255,255,255,0.55);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
    }
    .dark .glass {
      background: rgba(9,24,41,0.55);
    }
  </style>
</head>

<body
  class="transition-colors duration-500 font-jakarta overflow-x-hidden"
  :class="darkMode ? 'bg-navy-950 text-slate-100' : 'bg-slate-50 text-navy-800'"
  x-init="init()"
>

<!-- ═══════════════════════════ TOP BAR ═══════════════════════════ -->
<div
  class="w-full text-xs py-2 px-6 flex items-center justify-between transition-colors duration-500"
  :class="darkMode ? 'bg-navy-900 text-navy-300' : 'bg-navy-700 text-blue-100'"
>
  <span class="flex items-center gap-2">
    <i class="fa-solid fa-circle-dot text-green-400 animate-pulse-slow"></i>
    Available for freelance &amp; collaboration
  </span>
  <span class="flex items-center gap-4">
    <a href="mailto:calvin@example.com" class="hover:text-white transition-colors flex items-center gap-1">
      <i class="fa-solid fa-envelope"></i>
      <span class="hidden sm:inline">calvin@example.com</span>
    </a>
    <a href="tel:+6281234567890" class="hover:text-white transition-colors flex items-center gap-1">
      <i class="fa-solid fa-phone"></i>
      <span class="hidden sm:inline">+62 812-3456-7890</span>
    </a>
  </span>
</div>

<!-- ═══════════════════════════ NAVBAR ═══════════════════════════ -->
<nav
  id="navbar"
  class="sticky top-0 z-50 w-full transition-all duration-300 border-b"
  :class="[
    scrolled
      ? (darkMode ? 'bg-navy-950/90 border-navy-800 shadow-xl shadow-navy-950/40' : 'bg-white/90 border-slate-200 shadow-lg')
      : (darkMode ? 'bg-navy-950/60 border-transparent' : 'bg-white/60 border-transparent'),
    'backdrop-blur-xl'
  ]"
>
  <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
    <!-- Logo -->
    <a href="#home" class="flex items-center gap-2 group">
      <div class="w-9 h-9 rounded-xl bg-accent flex items-center justify-center text-white font-bold text-base shadow-lg shadow-accent/30 group-hover:scale-110 transition-transform">
        CM
      </div>
      <span class="font-extrabold text-lg tracking-tight" :class="darkMode ? 'text-white' : 'text-navy-800'">
        Calvin<span class="text-accent">.</span>
      </span>
    </a>

    <!-- Desktop Nav -->
    <ul class="hidden md:flex items-center gap-8 text-sm font-semibold">
      <template x-for="item in navItems" :key="item.href">
        <li>
          <a
            :href="item.href"
            class="nav-link transition-colors"
            :class="darkMode ? 'text-slate-300 hover:text-white' : 'text-navy-600 hover:text-navy-900'"
            x-text="item.label"
          ></a>
        </li>
      </template>
    </ul>

    <!-- Right Controls -->
    <div class="flex items-center gap-3">
      <!-- Theme Toggle -->
      <button
        @click="darkMode = !darkMode"
        class="w-10 h-10 rounded-xl flex items-center justify-center transition-all duration-300 hover:scale-110"
        :class="darkMode ? 'bg-navy-700 text-yellow-300 hover:bg-navy-600' : 'bg-navy-100 text-navy-700 hover:bg-navy-200'"
        :title="darkMode ? 'Switch to Light' : 'Switch to Dark'"
      >
        <i :class="darkMode ? 'fa-solid fa-sun' : 'fa-solid fa-moon'"></i>
      </button>

      <!-- Hire Me -->
      <a
        href="#kontak"
        class="hidden sm:flex items-center gap-2 px-4 py-2 rounded-xl text-sm font-bold text-white bg-accent hover:bg-blue-500 transition-all shadow-lg shadow-accent/30 hover:shadow-accent/50 hover:scale-105"
      >
        <i class="fa-solid fa-paper-plane"></i>
        Hire Me
      </a>

      <!-- Mobile hamburger -->
      <button
        @click="mobileMenu = !mobileMenu"
        class="md:hidden w-10 h-10 rounded-xl flex items-center justify-center"
        :class="darkMode ? 'bg-navy-700 text-white' : 'bg-navy-100 text-navy-700'"
      >
        <i :class="mobileMenu ? 'fa-solid fa-xmark' : 'fa-solid fa-bars'"></i>
      </button>
    </div>
  </div>

  <!-- Mobile Menu -->
  <div
    x-show="mobileMenu"
    x-transition:enter="transition ease-out duration-200"
    x-transition:enter-start="opacity-0 -translate-y-4"
    x-transition:enter-end="opacity-100 translate-y-0"
    x-transition:leave="transition ease-in duration-150"
    x-transition:leave-start="opacity-100 translate-y-0"
    x-transition:leave-end="opacity-0 -translate-y-4"
    class="md:hidden border-t px-6 py-4 space-y-3"
    :class="darkMode ? 'border-navy-800 bg-navy-950' : 'border-slate-100 bg-white'"
  >
    <template x-for="item in navItems" :key="item.href">
      <a
        :href="item.href"
        @click="mobileMenu = false"
        class="flex items-center gap-3 py-2 text-sm font-semibold transition-colors"
        :class="darkMode ? 'text-slate-300 hover:text-white' : 'text-navy-700 hover:text-navy-900'"
      >
        <i :class="item.icon + ' text-accent w-4'"></i>
        <span x-text="item.label"></span>
      </a>
    </template>
    <a
      href="#kontak"
      @click="mobileMenu = false"
      class="flex items-center justify-center gap-2 w-full py-2.5 rounded-xl text-sm font-bold text-white bg-accent mt-2"
    >
      <i class="fa-solid fa-paper-plane"></i> Hire Me
    </a>
  </div>
</nav>

<!-- ═══════════════════════════ HERO / BANNER ═══════════════════════════ -->
<section
  id="home"
  class="relative min-h-screen flex items-center overflow-hidden noise"
  :class="darkMode ? 'mesh-dark' : 'mesh-light'"
>
  <!-- Blobs -->
  <div class="glow-blob w-96 h-96 bg-accent top-10 -left-20" :class="darkMode ? 'opacity-20' : 'opacity-10'"></div>
  <div class="glow-blob w-80 h-80 bg-blue-400 bottom-0 right-0" :class="darkMode ? 'opacity-15' : 'opacity-10'"></div>

  <div class="max-w-6xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-16 items-center relative z-10">

    <!-- Text -->
    <div class="space-y-6">
      <div
        class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full text-xs font-bold tracking-widest uppercase border"
        :class="darkMode ? 'border-navy-600 text-accent bg-navy-800/60' : 'border-blue-200 text-accent bg-blue-50'"
        style="animation: fadeInUp 0.6s ease both;"
      >
        <i class="fa-solid fa-graduation-cap"></i>
        Mahasiswa &amp; Web Developer
      </div>

      <h1
        class="text-5xl sm:text-6xl font-extrabold leading-tight tracking-tight"
        :class="darkMode ? 'text-white' : 'text-navy-900'"
        style="animation: fadeInUp 0.7s 0.1s ease both; opacity:0; animation-fill-mode:both;"
      >
        Hi, I'm<br>
        <span class="text-accent">Calvin</span> Misiro<span class="text-accent">.</span>
      </h1>

      <p
        class="text-lg leading-relaxed max-w-md"
        :class="darkMode ? 'text-slate-400' : 'text-navy-500'"
        style="animation: fadeInUp 0.7s 0.2s ease both; opacity:0; animation-fill-mode:both;"
      >
        Saya membangun pengalaman web yang indah, fungsional, dan cepat — dari landing page hingga aplikasi full-stack.
      </p>

      <!-- Typing line -->
      <div
        class="flex items-center gap-2 text-sm font-mono"
        :class="darkMode ? 'text-blue-300' : 'text-navy-600'"
        style="animation: fadeInUp 0.7s 0.3s ease both; opacity:0; animation-fill-mode:both;"
      >
        <span>&gt; Currently:</span>
        <span x-text="typingText" class="font-semibold text-accent"></span>
        <span class="cursor-blink"></span>
      </div>

      <!-- CTA Buttons -->
      <div
        class="flex flex-wrap gap-3 pt-2"
        style="animation: fadeInUp 0.7s 0.4s ease both; opacity:0; animation-fill-mode:both;"
      >
        <a
          href="#portfolio"
          class="flex items-center gap-2 px-6 py-3 rounded-xl font-bold text-white bg-accent hover:bg-blue-500 transition-all shadow-lg shadow-accent/40 hover:shadow-accent/60 hover:scale-105 text-sm"
        >
          <i class="fa-solid fa-briefcase"></i>
          Lihat Portfolio
        </a>
        <a
          href="#kontak"
          class="flex items-center gap-2 px-6 py-3 rounded-xl font-bold border-2 transition-all hover:scale-105 text-sm"
          :class="darkMode ? 'border-navy-600 text-slate-200 hover:bg-navy-800' : 'border-navy-200 text-navy-700 hover:bg-navy-50'"
        >
          <i class="fa-solid fa-envelope"></i>
          Hubungi Saya
        </a>
      </div>

      <!-- Stats -->
      <div
        class="flex gap-8 pt-4 border-t"
        :class="darkMode ? 'border-navy-800' : 'border-blue-100'"
        style="animation: fadeInUp 0.7s 0.5s ease both; opacity:0; animation-fill-mode:both;"
      >
        <template x-for="stat in stats" :key="stat.label">
          <div>
            <div class="text-2xl font-extrabold text-accent" x-text="stat.value"></div>
            <div class="text-xs font-medium" :class="darkMode ? 'text-slate-500' : 'text-navy-400'" x-text="stat.label"></div>
          </div>
        </template>
      </div>
    </div>

    <!-- Avatar / Graphic -->
    <div class="flex justify-center relative" style="animation: fadeIn 0.9s 0.3s ease both; opacity:0; animation-fill-mode:both;">
      <div class="relative animate-float">
        <!-- Ring -->
        <div class="absolute inset-0 rounded-full border-2 border-accent/30 scale-110"></div>
        <div class="absolute inset-0 rounded-full border border-accent/15 scale-125"></div>

        <!-- Avatar -->
        <div
          class="w-64 h-64 sm:w-72 sm:h-72 rounded-full flex items-center justify-center text-8xl font-black shadow-2xl relative overflow-hidden"
          :class="darkMode ? 'bg-navy-800 text-white' : 'bg-white text-navy-900'"
          style="box-shadow: 0 0 0 6px rgba(59,130,246,0.2), 0 24px 64px rgba(30,58,95,0.35);"
        >
          <!-- Decorative ring gradient -->
          <div class="absolute inset-0 bg-gradient-to-br from-accent/10 to-transparent rounded-full"></div>
          <span class="relative z-10 select-none">👨‍💻</span>
        </div>

        <!-- Floating badges -->
        <div
          class="absolute -top-2 -right-4 px-3 py-1.5 rounded-full text-xs font-bold text-white bg-accent shadow-lg shadow-accent/40 flex items-center gap-1.5"
          style="animation: float 3.5s ease-in-out infinite 0.5s;"
        >
          <i class="fa-brands fa-react"></i> React
        </div>
        <div
          class="absolute -bottom-3 -left-4 px-3 py-1.5 rounded-full text-xs font-bold text-white shadow-lg flex items-center gap-1.5"
          :class="darkMode ? 'bg-navy-700' : 'bg-navy-700'"
          style="animation: float 4s ease-in-out infinite 1s;"
        >
          <i class="fa-brands fa-node-js text-green-400"></i> Node.js
        </div>
        <div
          class="absolute top-1/2 -right-8 px-3 py-1.5 rounded-full text-xs font-bold shadow-lg flex items-center gap-1.5"
          :class="darkMode ? 'bg-navy-700 text-slate-200' : 'bg-white text-navy-700'"
          style="animation: float 3s ease-in-out infinite 1.5s;"
        >
          <i class="fa-brands fa-laravel text-red-400"></i> Laravel
        </div>
      </div>
    </div>
  </div>

  <!-- Scroll indicator -->
  <div class="absolute bottom-8 left-1/2 -translate-x-1/2 flex flex-col items-center gap-2 text-xs opacity-50" :class="darkMode ? 'text-slate-400' : 'text-navy-400'">
    <span>Scroll</span>
    <i class="fa-solid fa-chevron-down animate-bounce"></i>
  </div>
</section>

<!-- ═══════════════════════════ ABOUT / SKILLS ═══════════════════════════ -->
<section
  id="tentang"
  class="py-24 relative"
  :class="darkMode ? 'bg-navy-900' : 'bg-white'"
>
  <div class="max-w-6xl mx-auto px-6">
    <div class="reveal grid md:grid-cols-2 gap-16 items-center">

      <!-- Skills -->
      <div class="space-y-8">
        <div>
          <span class="text-xs font-bold tracking-widest uppercase text-accent flex items-center gap-2 mb-3">
            <i class="fa-solid fa-code"></i> Tech Stack
          </span>
          <h2 class="text-3xl font-extrabold" :class="darkMode ? 'text-white' : 'text-navy-900'">
            Keahlian yang Saya Miliki
          </h2>
        </div>

        <div class="space-y-4">
          <template x-for="skill in skills" :key="skill.name">
            <div>
              <div class="flex justify-between text-sm font-semibold mb-1.5">
                <span class="flex items-center gap-2" :class="darkMode ? 'text-slate-300' : 'text-navy-700'">
                  <i :class="skill.icon + ' text-accent'"></i>
                  <span x-text="skill.name"></span>
                </span>
                <span class="text-accent" x-text="skill.level + '%'"></span>
              </div>
              <div class="w-full h-2 rounded-full overflow-hidden" :class="darkMode ? 'bg-navy-700' : 'bg-slate-100'">
                <div
                  class="h-full rounded-full bg-gradient-to-r from-accent to-blue-400 skill-bar-fill"
                  :style="'width: ' + (skillsVisible ? skill.level : 0) + '%'"
                ></div>
              </div>
            </div>
          </template>
        </div>
      </div>

      <!-- About text -->
      <div class="space-y-6">
        <div>
          <span class="text-xs font-bold tracking-widest uppercase text-accent flex items-center gap-2 mb-3">
            <i class="fa-solid fa-user"></i> Tentang Saya
          </span>
          <h2 class="text-3xl font-extrabold" :class="darkMode ? 'text-white' : 'text-navy-900'">
            Siapa Calvin Misiro?
          </h2>
        </div>
        <p class="leading-relaxed" :class="darkMode ? 'text-slate-400' : 'text-navy-500'">
          Saya adalah mahasiswa Teknik Informatika yang antusias di dunia pengembangan web. Dengan lebih dari 2 tahun pengalaman membangun proyek nyata, saya menggabungkan teori akademik dan keahlian praktis untuk menciptakan solusi digital yang berdampak.
        </p>
        <p class="leading-relaxed" :class="darkMode ? 'text-slate-400' : 'text-navy-500'">
          Saya percaya bahwa kode yang baik bukan hanya soal fungsi, tetapi juga keindahan, kecepatan, dan pengalaman pengguna. Setiap proyek adalah kesempatan untuk belajar dan berinovasi.
        </p>

        <!-- Education -->
        <div
          class="flex items-start gap-4 p-4 rounded-2xl border"
          :class="darkMode ? 'border-navy-700 bg-navy-800/50' : 'border-blue-100 bg-blue-50/60'"
        >
          <div class="w-10 h-10 rounded-xl bg-accent flex items-center justify-center text-white shrink-0">
            <i class="fa-solid fa-graduation-cap"></i>
          </div>
          <div>
            <div class="font-bold text-sm" :class="darkMode ? 'text-white' : 'text-navy-800'">S1 Teknik Informatika</div>
            <div class="text-xs" :class="darkMode ? 'text-slate-400' : 'text-navy-500'">Universitas Hasanuddin · 2022 — Sekarang</div>
          </div>
        </div>

        <a
          href="#"
          class="inline-flex items-center gap-2 px-5 py-2.5 rounded-xl font-bold text-sm text-white bg-accent hover:bg-blue-500 transition-all shadow-lg shadow-accent/30 hover:scale-105"
        >
          <i class="fa-solid fa-file-arrow-down"></i>
          Download CV
        </a>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════════ PORTFOLIO ═══════════════════════════ -->
<section
  id="portfolio"
  class="py-24 relative"
  :class="darkMode ? 'bg-navy-950' : 'bg-slate-50'"
>
  <div class="glow-blob w-72 h-72 bg-accent top-0 right-0 opacity-5"></div>

  <div class="max-w-6xl mx-auto px-6">
    <!-- Header -->
    <div class="reveal text-center mb-16 space-y-3">
      <span class="text-xs font-bold tracking-widest uppercase text-accent flex items-center justify-center gap-2">
        <i class="fa-solid fa-briefcase"></i> Portfolio
      </span>
      <h2 class="text-4xl font-extrabold" :class="darkMode ? 'text-white' : 'text-navy-900'">Hasil Karya Saya</h2>
      <p class="max-w-xl mx-auto" :class="darkMode ? 'text-slate-400' : 'text-navy-500'">
        Proyek-proyek pilihan yang mencerminkan keahlian dan passion saya dalam membangun produk digital.
      </p>

      <!-- Filter -->
      <div class="flex flex-wrap justify-center gap-2 pt-4">
        <template x-for="f in filters" :key="f">
          <button
            @click="activeFilter = f"
            class="px-4 py-1.5 rounded-full text-xs font-bold transition-all"
            :class="activeFilter === f
              ? 'bg-accent text-white shadow-lg shadow-accent/30'
              : (darkMode ? 'bg-navy-800 text-slate-400 hover:bg-navy-700' : 'bg-white text-navy-500 border border-slate-200 hover:bg-navy-50')"
          >
            <span x-text="f"></span>
          </button>
        </template>
      </div>
    </div>

    <!-- Cards -->
    <div class="reveal stagger grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <template x-for="project in filteredProjects" :key="project.id">
        <div
          class="port-card rounded-2xl overflow-hidden border"
          :class="darkMode ? 'bg-navy-800 border-navy-700' : 'bg-white border-slate-100 shadow-sm'"
        >
          <!-- Thumbnail -->
          <div
            class="h-44 flex items-center justify-center text-5xl relative overflow-hidden"
            :class="darkMode ? 'bg-navy-900' : 'bg-slate-100'"
          >
            <div class="absolute inset-0 opacity-30" :style="'background: linear-gradient(135deg, ' + project.color + '33, transparent)'"></div>
            <span x-text="project.emoji" class="relative z-10 animate-float"></span>
            <!-- Tag -->
            <span
              class="absolute top-3 right-3 px-2 py-0.5 rounded-full text-xs font-bold text-white"
              :style="'background: ' + project.color"
              x-text="project.tag"
            ></span>
          </div>

          <!-- Body -->
          <div class="p-5 space-y-3">
            <h3 class="font-extrabold text-base" :class="darkMode ? 'text-white' : 'text-navy-900'" x-text="project.title"></h3>
            <p class="text-sm leading-relaxed" :class="darkMode ? 'text-slate-400' : 'text-navy-500'" x-text="project.desc"></p>

            <!-- Tech badges -->
            <div class="flex flex-wrap gap-1.5">
              <template x-for="tech in project.techs" :key="tech">
                <span
                  class="px-2 py-0.5 rounded-md text-xs font-semibold"
                  :class="darkMode ? 'bg-navy-700 text-blue-300' : 'bg-blue-50 text-accent'"
                  x-text="tech"
                ></span>
              </template>
            </div>

            <!-- Actions -->
            <div class="flex gap-2 pt-1">
              <a
                href="#"
                class="flex-1 flex items-center justify-center gap-1.5 py-2 rounded-xl text-xs font-bold text-white bg-accent hover:bg-blue-500 transition-all"
              >
                <i class="fa-solid fa-eye"></i> Demo
              </a>
              <a
                href="#"
                class="flex items-center justify-center gap-1.5 px-3 py-2 rounded-xl text-xs font-bold border transition-all"
                :class="darkMode ? 'border-navy-600 text-slate-300 hover:bg-navy-700' : 'border-slate-200 text-navy-600 hover:bg-slate-50'"
              >
                <i class="fa-brands fa-github"></i>
              </a>
            </div>
          </div>
        </div>
      </template>
    </div>

    <!-- Show more -->
    <div class="text-center mt-10">
      <a
        href="https://github.com"
        target="_blank"
        class="inline-flex items-center gap-2 px-6 py-3 rounded-xl font-bold text-sm border-2 transition-all hover:scale-105"
        :class="darkMode ? 'border-navy-700 text-slate-300 hover:bg-navy-800' : 'border-slate-200 text-navy-700 hover:bg-white'"
      >
        <i class="fa-brands fa-github"></i>
        Lihat Semua di GitHub
      </a>
    </div>
  </div>
</section>

<!-- ═══════════════════════════ SERVICES ═══════════════════════════ -->
<section
  id="layanan"
  class="py-24"
  :class="darkMode ? 'bg-navy-900' : 'bg-white'"
>
  <div class="max-w-6xl mx-auto px-6">
    <div class="reveal text-center mb-14 space-y-3">
      <span class="text-xs font-bold tracking-widest uppercase text-accent flex items-center justify-center gap-2">
        <i class="fa-solid fa-wand-magic-sparkles"></i> Layanan
      </span>
      <h2 class="text-4xl font-extrabold" :class="darkMode ? 'text-white' : 'text-navy-900'">Apa yang Saya Tawarkan</h2>
    </div>

    <div class="reveal stagger grid sm:grid-cols-2 lg:grid-cols-3 gap-5">
      <template x-for="svc in services" :key="svc.title">
        <div
          class="group p-6 rounded-2xl border transition-all hover:border-accent/50"
          :class="darkMode ? 'bg-navy-800/60 border-navy-700 hover:bg-navy-800' : 'bg-slate-50 border-slate-100 hover:bg-white hover:shadow-lg'"
        >
          <div
            class="w-12 h-12 rounded-2xl flex items-center justify-center text-xl text-white mb-4 shadow-lg"
            :style="'background:' + svc.color + '; box-shadow: 0 8px 20px ' + svc.color + '44'"
          >
            <i :class="svc.icon"></i>
          </div>
          <h3 class="font-extrabold mb-2" :class="darkMode ? 'text-white' : 'text-navy-900'" x-text="svc.title"></h3>
          <p class="text-sm leading-relaxed" :class="darkMode ? 'text-slate-400' : 'text-navy-500'" x-text="svc.desc"></p>
        </div>
      </template>
    </div>
  </div>
</section>

<!-- ═══════════════════════════ KONTAK ═══════════════════════════ -->
<section
  id="kontak"
  class="py-24 relative overflow-hidden"
  :class="darkMode ? 'bg-navy-950' : 'bg-slate-50'"
>
  <div class="glow-blob w-96 h-96 bg-accent bottom-0 left-0 opacity-5"></div>

  <div class="max-w-4xl mx-auto px-6">
    <div class="reveal text-center mb-14 space-y-3">
      <span class="text-xs font-bold tracking-widest uppercase text-accent flex items-center justify-center gap-2">
        <i class="fa-solid fa-paper-plane"></i> Kontak
      </span>
      <h2 class="text-4xl font-extrabold" :class="darkMode ? 'text-white' : 'text-navy-900'">Ayo Berkolaborasi!</h2>
      <p :class="darkMode ? 'text-slate-400' : 'text-navy-500'">Punya proyek menarik? Hubungi saya dan kita mulai dari sini.</p>
    </div>

    <div class="reveal grid md:grid-cols-2 gap-8">

      <!-- Contact Info -->
      <div class="space-y-5">
        <template x-for="ci in contactInfo" :key="ci.label">
          <div
            class="flex items-center gap-4 p-4 rounded-2xl border transition-all"
            :class="darkMode ? 'bg-navy-800 border-navy-700 hover:border-accent/40' : 'bg-white border-slate-100 hover:border-accent/40 shadow-sm'"
          >
            <div class="w-11 h-11 rounded-xl bg-accent flex items-center justify-center text-white shadow-md shadow-accent/30">
              <i :class="ci.icon"></i>
            </div>
            <div>
              <div class="text-xs font-semibold uppercase tracking-wide" :class="darkMode ? 'text-slate-500' : 'text-navy-400'" x-text="ci.label"></div>
              <div class="font-bold text-sm" :class="darkMode ? 'text-white' : 'text-navy-800'" x-text="ci.value"></div>
            </div>
          </div>
        </template>

        <!-- Sosial -->
        <div class="flex gap-3 pt-2">
          <template x-for="social in socials" :key="social.icon">
            <a
              :href="social.url"
              target="_blank"
              class="w-11 h-11 rounded-xl flex items-center justify-center text-white transition-all hover:scale-110"
              :style="'background:' + social.color + '; box-shadow: 0 6px 16px ' + social.color + '44'"
            >
              <i :class="social.icon"></i>
            </a>
          </template>
        </div>
      </div>

      <!-- Form -->
      <div
        class="p-6 rounded-2xl border space-y-4"
        :class="darkMode ? 'bg-navy-800 border-navy-700' : 'bg-white border-slate-100 shadow-sm'"
      >
        <div>
          <label class="text-xs font-bold uppercase tracking-wide mb-1.5 block" :class="darkMode ? 'text-slate-400' : 'text-navy-500'">
            <i class="fa-solid fa-user mr-1"></i> Nama
          </label>
          <input
            type="text"
            placeholder="Nama lengkap Anda"
            class="w-full px-4 py-2.5 rounded-xl text-sm border outline-none focus:ring-2 focus:ring-accent transition"
            :class="darkMode ? 'bg-navy-700 border-navy-600 text-white placeholder-navy-400' : 'bg-slate-50 border-slate-200 text-navy-800 placeholder-slate-400'"
          />
        </div>
        <div>
          <label class="text-xs font-bold uppercase tracking-wide mb-1.5 block" :class="darkMode ? 'text-slate-400' : 'text-navy-500'">
            <i class="fa-solid fa-envelope mr-1"></i> Email
          </label>
          <input
            type="email"
            placeholder="email@example.com"
            class="w-full px-4 py-2.5 rounded-xl text-sm border outline-none focus:ring-2 focus:ring-accent transition"
            :class="darkMode ? 'bg-navy-700 border-navy-600 text-white placeholder-navy-400' : 'bg-slate-50 border-slate-200 text-navy-800 placeholder-slate-400'"
          />
        </div>
        <div>
          <label class="text-xs font-bold uppercase tracking-wide mb-1.5 block" :class="darkMode ? 'text-slate-400' : 'text-navy-500'">
            <i class="fa-solid fa-comment mr-1"></i> Pesan
          </label>
          <textarea
            rows="4"
            placeholder="Ceritakan proyek Anda..."
            class="w-full px-4 py-2.5 rounded-xl text-sm border outline-none focus:ring-2 focus:ring-accent transition resize-none"
            :class="darkMode ? 'bg-navy-700 border-navy-600 text-white placeholder-navy-400' : 'bg-slate-50 border-slate-200 text-navy-800 placeholder-slate-400'"
          ></textarea>
        </div>
        <button
          class="w-full flex items-center justify-center gap-2 py-3 rounded-xl font-bold text-sm text-white bg-accent hover:bg-blue-500 transition-all shadow-lg shadow-accent/40 hover:scale-[1.02]"
        >
          <i class="fa-solid fa-paper-plane"></i>
          Kirim Pesan
        </button>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════════ FOOTER ═══════════════════════════ -->
<footer
  class="py-8 border-t text-center text-sm"
  :class="darkMode ? 'bg-navy-950 border-navy-800 text-slate-500' : 'bg-white border-slate-100 text-navy-400'"
>
  <div class="max-w-6xl mx-auto px-6 flex flex-col sm:flex-row items-center justify-between gap-3">
    <span>© 2025 <strong class="text-accent">Calvin Misiro</strong>. All rights reserved.</span>
    <span class="flex items-center gap-1">
      Made with <i class="fa-solid fa-heart text-red-400 mx-1"></i> &amp; lots of coffee
      <i class="fa-solid fa-mug-hot text-amber-400 ml-1"></i>
    </span>
  </div>
</footer>

<!-- ═══════════════════════════ FLOATING BUTTONS ═══════════════════════════ -->
<div class="fixed bottom-6 right-6 flex flex-col gap-3 z-50">
  <!-- GitHub -->
  <a
    href="https://github.com/calvinmisiro"
    target="_blank"
    class="w-12 h-12 rounded-full flex items-center justify-center text-white shadow-xl transition-all hover:scale-110"
    :class="darkMode ? 'bg-slate-700 hover:bg-slate-600' : 'bg-navy-800 hover:bg-navy-700'"
    title="GitHub"
    x-show="showFab"
    x-transition:enter="transition ease-out duration-300"
    x-transition:enter-start="opacity-0 scale-75"
    x-transition:enter-end="opacity-100 scale-100"
  >
    <i class="fa-brands fa-github text-lg"></i>
  </a>

  <!-- WhatsApp -->
  <a
    href="https://wa.me/6281234567890"
    target="_blank"
    class="w-12 h-12 rounded-full flex items-center justify-center text-white bg-green-500 hover:bg-green-400 shadow-xl shadow-green-500/40 transition-all hover:scale-110"
    title="WhatsApp"
    x-show="showFab"
    x-transition:enter="transition ease-out duration-300 delay-75"
    x-transition:enter-start="opacity-0 scale-75"
    x-transition:enter-end="opacity-100 scale-100"
  >
    <i class="fa-brands fa-whatsapp text-xl"></i>
  </a>

  <!-- Back to Top -->
  <button
    @click="window.scrollTo({top:0,behavior:'smooth'})"
    class="w-12 h-12 rounded-full flex items-center justify-center text-white bg-accent hover:bg-blue-500 shadow-xl shadow-accent/40 transition-all hover:scale-110"
    title="Back to Top"
    x-show="scrolled"
    x-transition:enter="transition ease-out duration-300"
    x-transition:enter-start="opacity-0 scale-75 translate-y-4"
    x-transition:enter-end="opacity-100 scale-100 translate-y-0"
    x-transition:leave="transition ease-in duration-200"
    x-transition:leave-start="opacity-100 scale-100"
    x-transition:leave-end="opacity-0 scale-75"
  >
    <i class="fa-solid fa-chevron-up"></i>
  </button>
</div>

<!-- ═══════════════════════════ ALPINE DATA ═══════════════════════════ -->
<script>
function site() {
  return {
    darkMode: false,
    scrolled: false,
    showFab: true,
    mobileMenu: false,
    activeFilter: 'Semua',
    skillsVisible: false,
    typingText: '',
    typingPhrases: [
      'Belajar Machine Learning 🧠',
      'Membangun REST API 🚀',
      'Ngoding Laravel 🎨',
      'Ngopi sambil debug ☕',
    ],
    typingIndex: 0,
    charIndex: 0,
    deleting: false,

    navItems: [
      { label: 'Home',      href: '#home',      icon: 'fa-solid fa-house' },
      { label: 'Tentang',   href: '#tentang',   icon: 'fa-solid fa-user' },
      { label: 'Portfolio', href: '#portfolio', icon: 'fa-solid fa-briefcase' },
      { label: 'Layanan',   href: '#layanan',   icon: 'fa-solid fa-wand-magic-sparkles' },
      { label: 'Kontak',    href: '#kontak',    icon: 'fa-solid fa-envelope' },
    ],

    stats: [
      { value: '20+', label: 'Proyek Selesai' },
      { value: '2+',  label: 'Tahun Coding' },
      { value: '15+', label: 'Klien Puas' },
    ],

    skills: [
      { name: 'HTML & CSS',   level: 92, icon: 'fa-brands fa-html5' },
      { name: 'JavaScript',   level: 85, icon: 'fa-brands fa-js' },
      { name: 'React.js',     level: 78, icon: 'fa-brands fa-react' },
      { name: 'Laravel/PHP',  level: 80, icon: 'fa-brands fa-laravel' },
      { name: 'MySQL',        level: 75, icon: 'fa-solid fa-database' },
      { name: 'Git & GitHub', level: 88, icon: 'fa-brands fa-git-alt' },
    ],

    filters: ['Semua', 'Web App', 'Mobile', 'UI/UX'],

    projects: [
      {
        id: 1, title: 'EduTrack LMS',
        desc: 'Platform manajemen pembelajaran berbasis web untuk kampus dengan fitur kuis dan laporan.',
        emoji: '📚', color: '#3b82f6', tag: 'Web App',
        techs: ['Laravel', 'Vue.js', 'MySQL', 'Tailwind'],
      },
      {
        id: 2, title: 'Toko Onlen App',
        desc: 'Aplikasi e-commerce full-stack dengan fitur keranjang, pembayaran, dan admin panel.',
        emoji: '🛒', color: '#10b981', tag: 'Web App',
        techs: ['React', 'Node.js', 'MongoDB', 'Stripe'],
      },
      {
        id: 3, title: 'WeatherNow',
        desc: 'Aplikasi cuaca real-time dengan tampilan responsif dan geolocation.',
        emoji: '🌤️', color: '#f59e0b', tag: 'Web App',
        techs: ['Vue.js', 'OpenWeather API', 'CSS3'],
      },
      {
        id: 4, title: 'Portfolio UI Kit',
        desc: 'Template dan komponen UI yang bisa digunakan ulang untuk portfolio developer.',
        emoji: '🎨', color: '#8b5cf6', tag: 'UI/UX',
        techs: ['Figma', 'HTML', 'Tailwind'],
      },
      {
        id: 5, title: 'Event Organizer App',
        desc: 'Sistem manajemen event kampus dengan QR-code check-in dan notifikasi realtime.',
        emoji: '📅', color: '#ec4899', tag: 'Web App',
        techs: ['Laravel', 'Alpine.js', 'Pusher'],
      },
      {
        id: 6, title: 'Finance Tracker',
        desc: 'Aplikasi pencatat keuangan pribadi dengan grafik analitik dan kategori pengeluaran.',
        emoji: '💰', color: '#14b8a6', tag: 'Mobile',
        techs: ['React Native', 'SQLite', 'Chart.js'],
      },
    ],

    services: [
      {
        title: 'Web Development',
        desc: 'Membangun website modern yang responsif, cepat, dan SEO-friendly menggunakan teknologi terkini.',
        icon: 'fa-solid fa-globe', color: '#3b82f6',
      },
      {
        title: 'UI/UX Design',
        desc: 'Merancang antarmuka yang intuitif dan estetis dengan pendekatan berpusat pada pengguna.',
        icon: 'fa-solid fa-pen-ruler', color: '#8b5cf6',
      },
      {
        title: 'Backend & API',
        desc: 'Mengembangkan REST API yang aman, skalabel, dan terdokumentasi dengan baik.',
        icon: 'fa-solid fa-server', color: '#10b981',
      },
      {
        title: 'Database Design',
        desc: 'Merancang skema database yang efisien dan mengoptimalkan query untuk performa maksimal.',
        icon: 'fa-solid fa-database', color: '#f59e0b',
      },
      {
        title: 'Code Review',
        desc: 'Memeriksa dan memperbaiki kode agar lebih bersih, aman, dan mudah di-maintain.',
        icon: 'fa-solid fa-code', color: '#ec4899',
      },
      {
        title: 'Konsultasi IT',
        desc: 'Memberikan saran teknologi dan solusi digital yang tepat untuk kebutuhan bisnis Anda.',
        icon: 'fa-solid fa-comments', color: '#14b8a6',
      },
    ],

    contactInfo: [
      { label: 'Email',     value: 'calvin@example.com',    icon: 'fa-solid fa-envelope' },
      { label: 'WhatsApp',  value: '+62 812-3456-7890',     icon: 'fa-brands fa-whatsapp' },
      { label: 'Lokasi',    value: 'Makassar, Indonesia',   icon: 'fa-solid fa-location-dot' },
    ],

    socials: [
      { icon: 'fa-brands fa-github',   url: 'https://github.com',    color: '#24292e' },
      { icon: 'fa-brands fa-linkedin', url: 'https://linkedin.com',  color: '#0077b5' },
      { icon: 'fa-brands fa-instagram',url: 'https://instagram.com', color: '#e1306c' },
      { icon: 'fa-brands fa-twitter',  url: 'https://twitter.com',   color: '#1da1f2' },
    ],

    get filteredProjects() {
      if (this.activeFilter === 'Semua') return this.projects;
      return this.projects.filter(p => p.tag === this.activeFilter);
    },

    init() {
      // Scroll listener
      window.addEventListener('scroll', () => {
        this.scrolled = window.scrollY > 80;
      });

      // Reveal on scroll
      const observer = new IntersectionObserver((entries) => {
        entries.forEach(e => {
          if (e.isIntersecting) {
            e.target.classList.add('visible');
            if (e.target.closest('#tentang')) {
              this.skillsVisible = true;
            }
          }
        });
      }, { threshold: 0.12 });

      document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

      // Typing effect
      this.typeLoop();
    },

    typeLoop() {
      const phrase = this.typingPhrases[this.typingIndex];
      if (!this.deleting) {
        this.typingText = phrase.substring(0, this.charIndex + 1);
        this.charIndex++;
        if (this.charIndex === phrase.length) {
          this.deleting = true;
          setTimeout(() => this.typeLoop(), 1800);
          return;
        }
      } else {
        this.typingText = phrase.substring(0, this.charIndex - 1);
        this.charIndex--;
        if (this.charIndex === 0) {
          this.deleting = false;
          this.typingIndex = (this.typingIndex + 1) % this.typingPhrases.length;
        }
      }
      setTimeout(() => this.typeLoop(), this.deleting ? 50 : 75);
    },
  }
}
</script>

</body>
</html>
