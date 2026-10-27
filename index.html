<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ฟังก์ชันตรีโกณมิติ ตอนที่ 2: สมการและอสมการ</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        pastel: {
                            pink: '#fce7f3',
                            pinkDark: '#f43f5e',
                            cyan: '#e0f2fe',
                            cyanDark: '#0284c7',
                            bg: '#fff5f7',
                            card: '#ffffff',
                            sidebar: '#fdf2f8',
                            text: '#1e293b'
                        }
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- MathJax 3 -->
    <script>
        window.MathJax = {
            tex: {
                inlineMath: [['$', '$'], ['\\(', '\\)']],
                displayMath: [['$$', '$$'], ['\\[', '\\]']]
            },
            startup: {
                ready: () => {
                    MathJax.startup.defaultReady();
                }
            }
        };
    </script>
    <script id="mathjax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Sarabun', sans-serif;
            background-color: #fff5f7;
            color: #1e293b;
        }
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #fce7f3;
        }
        ::-webkit-scrollbar-thumb {
            background: #f472b6;
            border-radius: 3px;
        }
        .active-nav {
            background-color: #fbcfe8 !important;
            color: #be123c !important;
            font-weight: 700;
            border-left: 4px solid #f43f5e;
        }
    </style>
</head>
<body class="h-screen overflow-hidden flex flex-col md:flex-row bg-[#fff5f7]">

    <!-- Mobile Header -->
    <div class="md:hidden flex items-center justify-between p-4 bg-white border-b border-pink-200 z-50 shadow-sm">
        <div class="flex items-center gap-3">
            <div class="w-9 h-9 rounded-xl bg-gradient-to-tr from-pink-400 to-sky-400 flex items-center justify-center font-bold text-white shadow-md">
                $\sin$
            </div>
            <div>
                <h1 class="font-bold text-sm text-slate-800 leading-tight">ตรีโกณมิติ</h1>
                <p class="text-xs text-sky-600">สมการและอสมการ</p>
            </div>
        </div>
        <button id="mobileMenuBtn" onclick="toggleSidebar()" class="p-2 text-pink-600 hover:text-pink-800 focus:outline-none">
            <i class="fa-solid fa-bars text-xl"></i>
        </button>
    </div>

    <!-- Sidebar Navigation -->
    <aside id="sidebar" class="fixed inset-y-0 left-0 z-40 w-80 bg-[#fdf2f8] border-r border-pink-200 transform -translate-x-full md:relative md:translate-x-0 transition-transform duration-300 ease-in-out flex flex-col h-full shadow-lg">
        <div class="p-5 border-b border-pink-200 hidden md:flex items-center gap-3 bg-white">
            <div class="w-10 h-10 rounded-2xl bg-gradient-to-tr from-pink-400 to-sky-400 flex items-center justify-center font-bold text-xl text-white shadow-md">
                $\tan$
            </div>
            <div>
                <h1 class="font-bold text-base text-slate-800">ตรีโกณมิติ</h1>
                <p class="text-xs text-sky-600 font-semibold">ฟังก์ชันตรีโกณมิติ ตอนที่ 2</p>
            </div>
        </div>

        <!-- Interactive Lab Button -->
        <div class="p-4 border-b border-pink-200 bg-pink-50/50">
            <button onclick="switchTab('interactive-lab')" class="w-full bg-gradient-to-r from-pink-400 to-sky-400 hover:from-pink-500 hover:to-sky-500 text-white p-3 rounded-xl shadow-md flex items-center justify-between transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fa-solid fa-compass-drafting text-lg group-hover:rotate-45 transition-transform"></i>
                    <div class="text-left">
                        <div class="text-xs text-pink-100">ห้องทดลองแบบปฏิสัมพันธ์</div>
                        <div class="font-bold text-sm">วงกลมหนึ่งหน่วย & สามเหลี่ยม</div>
                    </div>
                </div>
                <i class="fa-solid fa-chevron-right text-xs opacity-80"></i>
            </button>
        </div>

        <!-- Navigation Links -->
        <nav class="flex-1 overflow-y-auto p-4 space-y-6 text-sm">
            <!-- Part 1: Equations -->
            <div>
                <div class="text-xs font-bold uppercase tracking-wider text-pink-600 mb-2 px-3">1. สมการตรีโกณมิติ</div>
                <ul class="space-y-1">
                    <li><button onclick="switchTab('eq-intro')" class="nav-btn active-nav w-full text-left px-3 py-2 rounded-lg text-slate-700 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-mono font-bold">01</span><span>ทฤษฎีสมการตรีโกณมิติ</span></button></li>
                    <li><button onclick="switchTab('eq-ex1')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex1</span><span>ตัวอย่างสมการที่ 1</span></button></li>
                    <li><button onclick="switchTab('eq-ex2')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex2</span><span>ตัวอย่างสมการที่ 2</span></button></li>
                    <li><button onclick="switchTab('eq-ex3')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex3</span><span>ตัวอย่างสมการที่ 3</span></button></li>
                    <li><button onclick="switchTab('eq-ex4')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex4</span><span>ตัวอย่างสมการที่ 4</span></button></li>
                    <li><button onclick="switchTab('eq-ex5')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex5</span><span>ตัวอย่างสมการที่ 5</span></button></li>
                    <li><button onclick="switchTab('eq-ex6')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex6</span><span>ตัวอย่างสมการที่ 6</span></button></li>
                    <li><button onclick="switchTab('eq-ex7')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex7</span><span>ตัวอย่างสมการที่ 7</span></button></li>
                    <li><button onclick="switchTab('eq-ex8')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex8</span><span>ตัวอย่างสมการที่ 8</span></button></li>
                    <li><button onclick="switchTab('eq-ex9')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex9</span><span>ตัวอย่างสมการที่ 9</span></button></li>
                    <li><button onclick="switchTab('eq-ex10')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex10</span><span>ตัวอย่างสมการที่ 10</span></button></li>
                    <li><button onclick="switchTab('eq-ex11')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-sky-600 font-bold">Ex11</span><span>ตัวอย่างสมการที่ 11</span></button></li>
                </ul>
            </div>

            <!-- Part 2: Inequalities -->
            <div>
                <div class="text-xs font-bold uppercase tracking-wider text-sky-600 mb-2 px-3">2. อสมการตรีโกณมิติ</div>
                <ul class="space-y-1">
                    <li><button onclick="switchTab('ineq-intro')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-mono font-bold">02</span><span>หลักการแก้อสมการ & สามเหลี่ยม</span></button></li>
                    <li><button onclick="switchTab('ineq-ex1')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex1</span><span>ตัวอย่างอสมการที่ 1</span></button></li>
                    <li><button onclick="switchTab('ineq-ex2')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex2</span><span>ตัวอย่างอสมการที่ 2</span></button></li>
                    <li><button onclick="switchTab('ineq-ex3')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex3</span><span>ตัวอย่างอสมการที่ 3</span></button></li>
                    <li><button onclick="switchTab('ineq-ex4')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex4</span><span>ตัวอย่างอสมการที่ 4</span></button></li>
                    <li><button onclick="switchTab('ineq-ex5')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex5</span><span>ตัวอย่างอสมการที่ 5</span></button></li>
                    <li><button onclick="switchTab('ineq-ex6')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex6</span><span>ตัวอย่างอสมการที่ 6</span></button></li>
                    <li><button onclick="switchTab('ineq-ex7')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex7</span><span>ตัวอย่างอสมการที่ 7</span></button></li>
                    <li><button onclick="switchTab('ineq-ex8')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex8</span><span>ตัวอย่างอสมการที่ 8</span></button></li>
                    <li><button onclick="switchTab('ineq-ex9')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex9</span><span>ตัวอย่างอสมการที่ 9</span></button></li>
                    <li><button onclick="switchTab('ineq-ex10')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex10</span><span>ตัวอย่างอสมการที่ 10</span></button></li>
                    <li><button onclick="switchTab('ineq-ex11')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex11</span><span>ตัวอย่างอสมการที่ 11</span></button></li>
                    <li><button onclick="switchTab('ineq-ex12')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2"><span class="w-6 text-xs text-pink-500 font-bold">Ex12</span><span>ตัวอย่างอสมการที่ 12</span></button></li>
                </ul>
            </div>

            <!-- Part 3: Summary & Quiz -->
            <div>
                <div class="text-xs font-bold uppercase tracking-wider text-rose-500 mb-2 px-3">3. สรุปและแบบฝึกหัด</div>
                <ul class="space-y-1">
                    <li>
                        <button onclick="switchTab('summary-formulas')" class="nav-btn w-full text-left px-3 py-2 rounded-lg text-slate-600 hover:bg-pink-100 transition-colors flex items-center gap-2">
                            <span class="w-6 text-xs text-pink-600 font-mono font-bold">03</span>
                            <span>สรุปสูตรทั้งหมด</span>
                        </button>
                    </li>
                    <li>
                        <button onclick="switchTab('quiz-10')" class="nav-btn w-full text-left px-3 py-2.5 rounded-lg text-pink-700 bg-pink-100/80 hover:bg-pink-200 transition-colors flex items-center gap-2 font-bold">
                            <span class="w-6 text-xs text-pink-600 font-mono">04</span>
                            <span>โจทย์แบบฝึกหัด 10 ข้อ</span>
                        </button>
                    </li>
                </ul>
            </div>
        </nav>
    </aside>

    <!-- Main Content Area -->
    <main class="flex-1 h-full overflow-y-auto p-4 md:p-8 bg-[#fff5f7]">
        <div class="max-w-4xl mx-auto space-y-6">

            <!-- Banner Card -->
            <div class="bg-gradient-to-r from-pink-200 via-sky-100 to-pink-100 p-6 rounded-3xl border border-pink-300 shadow-md relative overflow-hidden">
                <div class="relative z-10">
                    <span class="inline-block px-3 py-1 bg-white/80 text-pink-600 border border-pink-300 rounded-full text-xs font-bold mb-2 shadow-sm">
                        สื่อการเรียนรู้แบบปฏิสัมพันธ์ (Interactive Learning)
                    </span>
                    <h1 class="text-2xl md:text-3xl font-bold text-slate-800 tracking-tight">
                        ฟังก์ชันตรีโกณมิติ ตอนที่ 2: สมการและอสมการ
                    </h1>
                    <p class="text-xs text-slate-600 mt-1">ระดับชั้นมัธยมศึกษาปีที่ 5 | รายวิชาภาษาอังกฤษเพื่อการจัดการเรียนรู้คณิตศาสตร์</p>
                </div>
            </div>

            <!-- 1. Equations Intro -->
            <section id="eq-intro" class="tab-content space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3 flex items-center gap-2">
                        <i class="fa-solid fa-book-open text-pink-500"></i>
                        ฟังก์ชันตรีโกณมิติและสมการตรีโกณมิติ
                    </h2>
                    <div class="space-y-3 text-slate-700 leading-relaxed text-sm md:text-base">
                        <p>1. <strong>สมการตรีโกณมิติ</strong> คือ สมการที่มีฟังก์ชันตรีโกณมิติเป็นส่วนประกอบ</p>
                        <p>2. <strong>การแก้สมการตรีโกณมิติ</strong> หมายถึง การหาค่ามุมของฟังก์ชันตรีโกณมิติที่กำหนด</p>
                        <p>3. หากสมการมีฟังก์ชันตรีโกณมิติหลายชนิด ควรแปลงให้เป็นฟังก์ชันชนิดเดียวกันก่อน โดยใช้เอกลักษณ์พื้นฐาน เช่น:</p>
                        <div class="grid grid-cols-1 sm:grid-cols-3 gap-3 my-4">
                            <div class="bg-pink-50 p-3 rounded-2xl border border-pink-200 text-center font-semibold text-pink-700">
                                $\sin^2\theta + \cos^2\theta = 1$
                            </div>
                            <div class="bg-sky-50 p-3 rounded-2xl border border-sky-200 text-center font-semibold text-sky-700">
                                $1 + \tan^2\theta = \sec^2\theta$ ($\cos\theta \neq 0$)
                            </div>
                            <div class="bg-pink-50 p-3 rounded-2xl border border-pink-200 text-center font-semibold text-pink-700">
                                $1 + \cot^2\theta = \csc^2\theta$ ($\sin\theta \neq 0$)
                            </div>
                        </div>
                        <p>4. ใช้วิธีแยกตัวประกอบเมื่อเหมาะสม</p>
                        <p>5. การหามุมต้องพิจารณาว่าเป็นฟังก์ชันตรีโกณมิติชนิดใด และใช้วิธีการหามุมตามกรณี เนื่องจากฟังก์ชันตรีโกณมิติไม่ใช่ฟังก์ชันหนึ่งต่อหนึ่ง ค่าของฟังก์ชันจึงอาจเกิดซ้ำได้ หากโจทย์ไม่ได้กำหนดช่วงคำตอบ ควรเขียนคำตอบเป็นคำตอบทั่วไป</p>
                    </div>
                </div>
            </section>

            <!-- Equations Examples 1 to 11 -->
            <section id="eq-ex1" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 1</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงหาคำตอบทั้งหมดของ $2\sin^2 x + \cos x - 2 = 0$ เมื่อ $0 \le x \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ใช้ $\sin^2 x = 1 - \cos^2 x$ แทนในสมการจะได้:</p>
                        <p>$2(1 - \cos^2 x) + \cos x - 2 = 0 \implies -2\cos^2 x + \cos x = 0 \Rightarrow \cos x(2\cos x - 1) = 0$</p>
                        <p>จึงได้ $\cos x = 0$ หรือ $\cos x = \frac{1}{2}$</p>
                        <p>• กรณีที่ 1: $\cos x = 0 \implies x = \frac{\pi}{2}, \frac{3\pi}{2}$</p>
                        <p>• กรณีที่ 2: $\cos x = \frac{1}{2} \implies x = \frac{\pi}{3}, \frac{5\pi}{3}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = \frac{\pi}{3}, \frac{\pi}{2}, \frac{3\pi}{2}, \frac{5\pi}{3}$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex2" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 2</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $\tan^2 x = 4\sin^2 x$ เมื่อ $0 \le x < 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>เขียน $\tan^2 x = \frac{\sin^2 x}{\cos^2 x}$ โดยมีเงื่อนไข $\cos x \neq 0$</p>
                        <p>$\frac{\sin^2 x}{\cos^2 x} - 4\sin^2 x = 0 \implies \sin^2 x\left(\frac{1}{\cos^2 x} - 4\right) = 0$</p>
                        <p>• กรณีที่ 1: $\sin^2 x = 0 \implies \sin x = 0 \implies x = 0, \pi$ ในช่วงที่กำหนด</p>
                        <p>• กรณีที่ 2: $\frac{1}{\cos^2 x} - 4 = 0 \implies \cos^2 x = \frac{1}{4} \implies \cos x = \pm\frac{1}{2}$</p>
                        <p>เมื่อ $\cos x = \frac{1}{2}$ ได้ $x = \frac{\pi}{3}, \frac{5\pi}{3}$ และเมื่อ $\cos x = -\frac{1}{2}$ ได้ $x = \frac{2\pi}{3}, \frac{4\pi}{3}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = 0, \frac{\pi}{3}, \frac{2\pi}{3}, \pi, \frac{4\pi}{3}, \frac{5\pi}{3}$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex3" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 3</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $2\sin^2 x + 3\cos x - 3 = 0$ เมื่อ $0 \le x \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ใช้ $\sin^2 x = 1 - \cos^2 x$ จะได้:</p>
                        <p>$2(1 - \cos^2 x) + 3\cos x - 3 = 0 \implies 2\cos^2 x - 3\cos x + 1 = 0$</p>
                        <p>แยกตัวประกอบ: $(2\cos x - 1)(\cos x - 1) = 0$</p>
                        <p>• กรณี $\cos x = \frac{1}{2} \implies x = \frac{\pi}{3}, \frac{5\pi}{3}$</p>
                        <p>• กรณี $\cos x = 1 \implies x = 0, 2\pi$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = 0, \frac{\pi}{3}, \frac{5\pi}{3}, 2\pi$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex4" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 4</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $2\cos^2 x + 3\cos x = -1$ เมื่อ $0 \le x < 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>จัดรูปเป็น $2\cos^2 x + 3\cos x + 1 = 0 \implies (2\cos x + 1)(\cos x + 1) = 0$</p>
                        <p>• กรณี $\cos x = -\frac{1}{2}$ ได้มุมอ้างอิง $\frac{\pi}{3}$ อยู่ในจตุภาคที่ 2 และ 3 จะได้ $x = \frac{2\pi}{3}, \frac{4\pi}{3}$</p>
                        <p>• กรณี $\cos x = -1$ ได้ $x = \pi$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = \frac{2\pi}{3}, \pi, \frac{4\pi}{3}$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex5" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 5</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $2\sin^2(2x) + 3\cot(2x) - 3\csc(2x) = 0$ เมื่อ $0 \le x \le \frac{\pi}{2}$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>เนื่องจาก $\cot(2x) = \frac{\cos(2x)}{\sin(2x)}$ และ $\csc(2x) = \frac{1}{\sin(2x)}$ ต้องมี $\sin(2x) \neq 0$ (นั่นคือ $x \neq 0$ และ $x \neq \frac{\pi}{2}$)</p>
                        <p>ใช้เอกลักษณ์ $\sin^2(2x) = 1 - \cos^2(2x)$ แล้วจัดรูป จะได้ $2\cos^2(2x) - 3\cos(2x) + 1 = 0$</p>
                        <p>$(2\cos(2x) - 1)(\cos(2x) - 1) = 0 \implies \cos(2x) = \frac{1}{2}$ หรือ $\cos(2x) = 1$</p>
                        <p>• กรณี $\cos(2x) = \frac{1}{2}$ ($0 \le 2x \le \pi$) ได้ $2x = \frac{\pi}{3} \implies x = \frac{\pi}{6}$</p>
                        <p>• กรณี $\cos(2x) = 1$ ได้ $x = 0$ แต่ทำให้ $\sin(2x) = 0$ จึงต้องตัดทิ้ง</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = \frac{\pi}{6}$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex6" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 6</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> กำหนดให้ $0 < \theta < \frac{\pi}{2}$ และ $\theta = \arctan\left(\frac{\sqrt{x}+1}{1-\sqrt{x}}\right) - \arctan\sqrt{x}$ เมื่อ $0 < x < 1$ จงหาค่า $\tan\theta + \cot\theta$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ใช้สูตร $\arctan A - \arctan B = \arctan\left(\frac{A-B}{1+AB}\right)$ โดย $A = \frac{\sqrt{x}+1}{1-\sqrt{x}}$ และ $B = \sqrt{x}$</p>
                        <p>คำนวณจะได้ $\frac{A-B}{1+AB} = 1$ ดังนั้น $\theta = \arctan(1) = \frac{\pi}{4}$</p>
                        <p>จะได้ $\tan\theta = 1$ และ $\cot\theta = 1$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\tan\theta + \cot\theta = 2$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex7" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 7</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> กำหนดให้ $-\frac{\pi}{2} < x < 0$ และ $\cos x + \sin x = \frac{1}{\sqrt{5}}$ จงหาค่า $\tan x - \cot x$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ยกกำลังสองทั้งสองข้าง: $(\cos x + \sin x)^2 = \frac{1}{5} \implies 1 + 2\sin x \cos x = \frac{1}{5} \implies \sin x \cos x = -\frac{2}{5}$</p>
                        <p>จาก $(\cos x - \sin x)^2 = 1 - 2\sin x \cos x = \frac{9}{5}$ เนื่องจากอยู่ในจตุภาคที่ 4 $\cos x > 0, \sin x < 0$ จะได้ $\cos x - \sin x = \frac{3}{\sqrt{5}}$</p>
                        <p>แทนค่าในสูตร $\tan x - \cot x = -\frac{(\cos x - \sin x)(\cos x + \sin x)}{\sin x \cos x} = \frac{3}{2}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\tan x - \cot x = \frac{3}{2}$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex8" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 8</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $\sec x \cos 5x + 1 = 0$ เมื่อ $0 < x \le \frac{\pi}{2}$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ใช้ $\sec x = \frac{1}{\cos x}$ จะได้ $\frac{\cos 5x}{\cos x} + 1 = 0 \implies \cos 5x + \cos x = 0$</p>
                        <p>ใช้สูตรแปลงผลบวกเป็นผลคูณ: $2\cos(3x)\cos(2x) = 0 \implies \cos 3x = 0$ หรือ $\cos 2x = 0$</p>
                        <p>จะได้ $3x = \frac{\pi}{2} \implies x = \frac{\pi}{6}$ และ $2x = \frac{\pi}{2} \implies x = \frac{\pi}{4}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = \frac{\pi}{6}, \frac{\pi}{4}$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex9" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 9</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $\sec^2 x - 2\tan x - 2 = 0$ เมื่อ $0 \le x \le \frac{\pi}{2}$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ใช้ $\sec^2 x = 1 + \tan^2 x$ จะได้ $1 + \tan^2 x - 2\tan x - 2 = 0 \implies \tan^2 x - 2\tan x - 1 = 0$</p>
                        <p>ใช้สูตรกำลังสองได้ $\tan x = 1 \pm \sqrt{2}$ ช่วง $0 \le x < \frac{\pi}{2}$ ค่า $\tan x$ ต้องไม่เป็นลบ จึงเหลือ $\tan x = 1 + \sqrt{2}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = \arctan(1 + \sqrt{2})$
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex10" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 10</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $2\sin^2(2\theta) + 3\cot(2\theta) - 3\csc(2\theta) = 0$ เมื่อ $0 \le \theta \le \frac{\pi}{2}$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>เงื่อนไข $\sin(2\theta) \neq 0 \implies \theta \neq 0, \frac{\pi}{2}$</p>
                        <p>แทน $\sin^2(2\theta) = 1 - \cos^2(2\theta)$ แล้วแยกตัวประกอบได้ $(2\cos(2\theta) - 1)(\cos(2\theta) - 1) = 0$</p>
                        <p>กรณี $\cos(2\theta) = \frac{1}{2} \implies 2\theta = \frac{\pi}{3} \implies \theta = \frac{\pi}{6}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta = \frac{\pi}{6}$ ($30^\circ$)
                        </div>
                    </div>
                </div>
            </section>

            <section id="eq-ex11" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างสมการที่ 11</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้สมการ $\sin x + \sqrt{3}\cos x = \sec\left(x + \frac{\pi}{3}\right)$ เมื่อ $0 \le x \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>หารด้วย 2 และใช้สูตรมุมผลบวกจะได้ $\sin\left(x + \frac{\pi}{3}\right) = \frac{1}{2}\sec\left(x + \frac{\pi}{3}\right) \implies 2\sin\left(x+\frac{\pi}{3}\right)\cos\left(x+\frac{\pi}{3}\right) = 1$</p>
                        <p>ใช้สูตรมุมสองเท่า: $\sin\left(2x + \frac{2\pi}{3}\right) = 1$ ช่วงมุม $2x+\frac{2\pi}{3}$ คือ $\frac{2\pi}{3}$ ถึง $\frac{14\pi}{3}$ มุมที่ทำให้ไซน์เป็น 1 คือ $\frac{5\pi}{2}$ และ $\frac{9\pi}{2}$</p>
                        <p>• กรณี $2x + \frac{2\pi}{3} = \frac{5\pi}{2} \implies x = \frac{11\pi}{12}$</p>
                        <p>• กรณี $2x + \frac{2\pi}{3} = \frac{9\pi}{2} \implies x = \frac{23\pi}{12}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x = \frac{11\pi}{12}, \frac{23\pi}{12}$
                        </div>
                    </div>
                </div>
            </section>

            <!-- 2. Inequalities Intro & Examples 1 to 12 -->
            <section id="ineq-intro" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3 flex items-center gap-2">
                        <i class="fa-solid fa-less-than-equal text-sky-500"></i>
                        หลักการแก้อสมการตรีโกณมิติและรูปสามเหลี่ยม
                    </h2>
                    <div class="space-y-3 text-slate-700 leading-relaxed text-sm md:text-base">
                        <p>1. <strong>อสมการตรีโกณมิติ</strong> คือ อสมการที่มีฟังก์ชันตรีโกณมิติเป็นส่วนประกอบ การแก้อสมการคือการหามุมที่ทำให้อสมการเป็นจริง โดยหาจุดวิกฤตแล้วใช้วงกลมหนึ่งหน่วยหรือกราฟ</p>
                        <p>2. <strong>กฎของสามเหลี่ยม:</strong></p>
                        <ul class="list-disc pl-6 space-y-1">
                            <li>กฎของไซน์: $\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C}$</li>
                            <li>กฎของโคไซน์: $a^2 = b^2 + c^2 - 2bc\cos A$, $b^2 = a^2 + c^2 - 2ac\cos B$, $c^2 = a^2 + b^2 - 2ab\cos C$</li>
                            <li>กฎการฉาย: $a = b\cos C + c\cos B$, $b = a\cos C + c\cos A$, $c = a\cos B + b\cos A$</li>
                        </ul>
                        <p>3. <strong>การหาพื้นที่สามเหลี่ยม:</strong> พื้นที่ = $\frac{1}{2}ab\sin C$ หรือสูตรเฮรอน $\sqrt{s(s-a)(s-b)(s-c)}$ เมื่อสัดส่วน $s = \frac{a+b+c}{2}$</p>
                    </div>
                </div>
            </section>

            <section id="ineq-ex1" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 1</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้ $\sin x + \cos x \ge 0$ เมื่อ $0 \le x < 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>หารทั้งสองข้างด้วย $\sqrt{2}$ จะได้ $\sin\left(x + \frac{\pi}{4}\right) \ge 0$ ช่วงของ $x+\frac{\pi}{4}$ คือ $\frac{\pi}{4} \le x+\frac{\pi}{4} < \frac{9\pi}{4}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x \in [0, \pi] \cup \left[\frac{3\pi}{2}, 2\pi\right)$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex2" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 2</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงหาเซตคำตอบของ $2\sin^4 x + \sin^2 x - 1 \ge 0$ เมื่อ $0 \le x \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ให้ $A = \sin^2 x$ จะได้ $2A^2 + A - 1 \ge 0 \implies (2A - 1)(A + 1) \ge 0$ เนื่องจาก $A+1 > 0$ เสมอ ได้ฐานคำตอบ $A \ge \frac{1}{2} \implies \sin^2 x \ge \frac{1}{2}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\left[\frac{\pi}{4}, \frac{3\pi}{4}\right] \cup \left[\frac{5\pi}{4}, \frac{7\pi}{4}\right]$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex3" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 3</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงหาค่า $\theta$ ที่ทำให้ $\sin\theta + \cos\theta \le 0$ เมื่อ $0 \le \theta \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>แปลงเป็น $\sin\left(\theta + \frac{\pi}{4}\right) \le 0$ ในช่วง $\frac{\pi}{4} \le \theta + \frac{\pi}{4} \le \frac{9\pi}{4}$ จะได้ $\pi \le \theta + \frac{\pi}{4} \le 2\pi$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta \in \left[\frac{3\pi}{4}, \frac{7\pi}{4}\right]$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex4" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 4</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้ $2\sin^4 x + 3\sin^2 x - 2 \ge 0$ เมื่อ $0 \le x \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ให้ $A = \sin^2 x$ จะได้ $(2A - 1)(A + 2) \ge 0 \implies A \ge \frac{1}{2} \implies \sin x \ge \frac{1}{\sqrt{2}}$ หรือ $\sin x \le -\frac{1}{\sqrt{2}}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x \in \left[\frac{\pi}{4}, \frac{3\pi}{4}\right] \cup \left[\frac{5\pi}{4}, \frac{7\pi}{4}\right]$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex5" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 5</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้ $\sqrt{3}\sin x + \cos x < 1$ เมื่อ $0 \le x \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>หารด้วย 2 จะได้ $\sin\left(x + \frac{\pi}{6}\right) < \frac{1}{2}$ แก้ช่วงมุมจะได้คำตอบ</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $x \in \left(\frac{2\pi}{3}, 2\pi\right)$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex6" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 6</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงหาช่วงคำตอบของ $\frac{1}{2} < \cos\theta < \frac{\sqrt{3}}{2}$ เมื่อ $\theta \in [0, 2\pi]$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>พิจารณาค่า Cosine อยู่ระหว่าง $\frac{1}{2}$ ถึง $\frac{\sqrt{3}}{2}$ ใน Quadrant 1 และ 4</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta \in \left(\frac{\pi}{6}, \frac{\pi}{3}\right) \cup \left(\frac{5\pi}{3}, \frac{11\pi}{6}\right)$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex7" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 7</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้อสมการ $(2\cos\theta - 1)(2\sin\theta - \sqrt{3}) < 0$ เมื่อ $0 \le \theta \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>พิจารณาเครื่องหมายตรงข้ามกันของสองวงเล็บ</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta \in \left[0, \frac{2\pi}{3}\right) \cup \left(\frac{5\pi}{3}, 2\pi\right]$ โดยตัด $\theta = \frac{\pi}{3}$ ออก
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex8" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 8</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้ $4\sin^2\theta - (2\sqrt{3}+2)\sin\theta + 1 > 0$ เมื่อ $0 \le \theta \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>แยกตัวประกอบ $(2\sin\theta - 1)(2\sin\theta - \sqrt{3}) > 0$ จะได้ $\sin\theta < \frac{1}{2}$ หรือ $\sin\theta > \frac{\sqrt{3}}{2}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta \in \left[0, \frac{\pi}{6}\right) \cup \left(\frac{\pi}{3}, \frac{2\pi}{3}\right) \cup \left(\frac{5\pi}{6}, 2\pi\right]$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex9" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 9</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้อสมการ $\sin x + \cos x \ge -\frac{\sqrt{2}}{2}$ เมื่อ $0 \le x < 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>แปลงอสมการโดยหารด้วย $\sqrt{2}$ ได้ $\sin\left(x + \frac{\pi}{4}\right) \ge -\frac{1}{2}$ หรือ $-\frac{\sqrt{2}}{2}$ ตามเงื่อนไข</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $[0, \pi] \cup \left[\frac{3\pi}{2}, 2\pi\right)$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex10" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 10</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-sky-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้ $(2\cos\theta - 1)(2\cos\theta - \sqrt{3}) < 0$ เมื่อ $0 \le \theta \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ค่าขอบเขตคือ $\cos\theta = \frac{1}{2}$ และ $\cos\theta = \frac{\sqrt{3}}{2}$ จะได้ $\frac{1}{2} < \cos\theta < \frac{\sqrt{3}}{2}$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta \in \left(\frac{\pi}{6}, \frac{\pi}{3}\right) \cup \left(\frac{5\pi}{3}, \frac{11\pi}{6}\right)$
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex11" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 11</h2>
                    <div class="bg-pink-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้ $(2\cos\theta - 1)(4\sin\theta - \sqrt{12}) < 0$ เมื่อ $0 \le \theta \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>จัดรูป $\sqrt{12} = 2\sqrt{3}$ แล้วหารด้วย 2 จะได้ $(2\cos\theta - 1)(2\sin\theta - \sqrt{3}) < 0$ พิจารณากรณีแยกย่อย</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta \in \left[0, \frac{2\pi}{3}\right) \cup \left(\frac{5\pi}{3}, 2\pi\right]$ (โดยไม่รวม $\frac{\pi}{3}$)
                        </div>
                    </div>
                </div>
            </section>

            <section id="ineq-ex12" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-4">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3">ตัวอย่างอสมการที่ 12</h2>
                    <div class="bg-sky-50 p-4 rounded-2xl border border-pink-200 font-medium text-slate-800">
                        <strong>โจทย์:</strong> จงแก้ $4\sin^2\theta - (2\sqrt{3}+2)\sin\theta > -1$ เมื่อ $0 \le \theta \le 2\pi$
                    </div>
                    <div class="space-y-3 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p class="font-bold text-sky-600">วิธีทำ:</p>
                        <p>ย้าย $-1$ มาทางซ้ายและให้ $A = \sin\theta$ แยกตัวประกอบ $(2A - 1)(2A - \sqrt{3}) > 0$</p>
                        <div class="p-4 bg-emerald-50 border border-emerald-200 rounded-2xl text-emerald-800 font-bold">
                            ตอบ: $\theta \in \left[0, \frac{\pi}{6}\right) \cup \left(\frac{\pi}{3}, \frac{2\pi}{3}\right) \cup \left(\frac{5\pi}{6}, 2\pi\right]$
                        </div>
                    </div>
                </div>
            </section>

            <!-- 3. Summary Formulas -->
            <section id="summary-formulas" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-6">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3 flex items-center gap-2">
                        <i class="fa-solid fa-bookmark text-rose-500"></i>
                        สรุปสูตรตรีโกณมิติที่สำคัญ
                    </h2>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm">
                        <div class="p-4 bg-pink-50 rounded-2xl border border-pink-200 space-y-2">
                            <h3 class="font-bold text-pink-700">1. เอกลักษณ์พื้นฐาน</h3>
                            <p>$\sin^2 x + \cos^2 x = 1$</p>
                            <p>$1 + \tan^2 x = \sec^2 x$</p>
                            <p>$1 + \cot^2 x = \csc^2 x$</p>
                            <p>$\tan x = \frac{\sin x}{\cos x}, \cot x = \frac{\cos x}{\sin x}$</p>
                        </div>
                        <div class="p-4 bg-sky-50 rounded-2xl border border-sky-200 space-y-2">
                            <h3 class="font-bold text-sky-700">2. สูตรมุมสองเท่า</h3>
                            <p>$\sin(2x) = 2\sin x \cos x$</p>
                            <p>$\cos(2x) = \cos^2 x - \sin^2 x = 2\cos^2 x - 1 = 1 - 2\sin^2 x$</p>
                            <p>$\tan(2x) = \frac{2\tan x}{1 - \tan^2 x}$</p>
                        </div>
                        <div class="p-4 bg-pink-50 rounded-2xl border border-pink-200 space-y-2">
                            <h3 class="font-bold text-pink-700">3. สูตรผลบวกและผลต่าง</h3>
                            <p>$\sin(A \pm B) = \sin A \cos B \pm \cos A \sin B$</p>
                            <p>$\cos(A \pm B) = \cos A \cos B \mp \sin A \sin B$</p>
                            <p>$\tan(A \pm B) = \frac{\tan A \pm \tan B}{1 \mp \tan A \tan B}$</p>
                        </div>
                        <div class="p-4 bg-sky-50 rounded-2xl border border-sky-200 space-y-2">
                            <h3 class="font-bold text-sky-700">4. สูตรแปลงผลบวกเป็นผลคูณ</h3>
                            <p>$\sin A + \sin B = 2\sin\left(\frac{A+B}{2}\right)\cos\left(\frac{A-B}{2}\right)$</p>
                            <p>$\cos A + \cos B = 2\cos\left(\frac{A+B}{2}\right)\cos\left(\frac{A-B}{2}\right)$</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- 4. Interactive Quiz (10 ข้อ แบบพิมพ์ตอบ มีตรวจคำตอบและเฉลย) -->
            <section id="quiz-10" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-6">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3 flex items-center gap-2">
                        <i class="fa-solid fa-pen-to-square text-pink-500"></i>
                        โจทย์แบบฝึกหัด 10 ข้อ
                    </h2>

                    <div class="space-y-6">
                        <!-- Q1 -->
                        <div class="p-4 bg-pink-50/50 rounded-2xl border border-pink-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 1:</p>
                            <p class="text-slate-700">จงหาค่า $x$ เมื่อ $\sin x = \frac{1}{2}$ สำหรับ $0 \le x \le \frac{\pi}{2}$</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans1" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-pink-300 text-sm focus:outline-none focus:ring-2 focus:ring-pink-400">
                                <button onclick="checkAnswer(1, ['pi/6', '30', '30 องศา', '30°'], 'x = \\frac{\\pi}{6} \\text{ หรือ } 30^\\circ', 'จากวงกลมหนึ่งหน่วย ค่า $\\sin x = \\frac{1}{2}$ ในจตุภาคที่ 1 คือมุม $30^\\circ$ หรือ $\\frac{\\pi}{6}$')" class="bg-pink-500 hover:bg-pink-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result1" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q2 -->
                        <div class="p-4 bg-sky-50/50 rounded-2xl border border-sky-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 2:</p>
                            <p class="text-slate-700">จงหาค่า $x$ ที่สอดคล้องกับสมการ $2\cos x - 1 = 0$ เมื่อ $0 \le x \le \pi$</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans2" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-sky-300 text-sm focus:outline-none focus:ring-2 focus:ring-sky-400">
                                <button onclick="checkAnswer(2, ['pi/3', '60', '60 องศา', '60°'], 'x = \\frac{\\pi}{3} \\text{ หรือ } 60^\\circ', 'จัดรูปสมการจะได้ $\\cos x = \\frac{1}{2}$ ในช่วง $[0, \\pi]$ จะได้มุม $x = 60^\\circ$ หรือ $\\frac{\\pi}{3}$')" class="bg-sky-500 hover:bg-sky-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result2" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q3 -->
                        <div class="p-4 bg-pink-50/50 rounded-2xl border border-pink-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 3:</p>
                            <p class="text-slate-700">จงหาค่า $\tan x$ เมื่อ $\sin x = \frac{3}{5}$ และ $x$ อยู่ในจตุภาคที่ 1</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans3" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-pink-300 text-sm focus:outline-none focus:ring-2 focus:ring-pink-400">
                                <button onclick="checkAnswer(3, ['3/4', '0.75'], '\\tan x = \\frac{3}{4}', 'จาก $\\sin x = \\frac{3}{5}$ จะได้ ด้านข้าม = 3, ฉาก = 5 หาด้านชิดด้วยพีทาโกรัส $\\sqrt{5^2 - 3^2} = 4$ ดังนั้น $\\tan x = \\frac{3}{4}$')" class="bg-pink-500 hover:bg-pink-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result3" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q4 -->
                        <div class="p-4 bg-sky-50/50 rounded-2xl border border-sky-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 4:</p>
                            <p class="text-slate-700">จงหาค่าของ $\sin^2(45^\circ) + \cos^2(45^\circ)$</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans4" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-sky-300 text-sm focus:outline-none focus:ring-2 focus:ring-sky-400">
                                <button onclick="checkAnswer(4, ['1'], '1', 'ใช้เอกลักษณ์ตรีโกณมิติพื้นฐาน $\\sin^2\\theta + \\cos^2\\theta = 1$ เสมอ')" class="bg-sky-500 hover:bg-sky-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result4" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q5 -->
                        <div class="p-4 bg-pink-50/50 rounded-2xl border border-pink-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 5:</p>
                            <p class="text-slate-700">ถ้า $\tan x = 1$ และ $0 \le x \le \pi$ จงหาค่ามุม $x$ (ในหน่วยองศา)</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans5" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-pink-300 text-sm focus:outline-none focus:ring-2 focus:ring-pink-400">
                                <button onclick="checkAnswer(5, ['45', '45 องศา', '45°', 'pi/4'], 'x = 45^\\circ', 'ค่า Tangent เป็น 1 ในช่วง $[0, \\pi]$ คือมุม $45^\\circ$ หรือ $\\frac{\\pi}{4}$')" class="bg-pink-500 hover:bg-pink-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result5" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q6 -->
                        <div class="p-4 bg-sky-50/50 rounded-2xl border border-sky-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 6:</p>
                            <p class="text-slate-700">จงแก้สมการ $\sin(2x) = 1$ เมื่อ $0 \le x \le \pi$ (ตอบเป็นเรเดียน)</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans6" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-sky-300 text-sm focus:outline-none focus:ring-2 focus:ring-sky-400">
                                <button onclick="checkAnswer(6, ['pi/4', '45', '45°'], 'x = \\frac{\\pi}{4}', 'จาก $\\sin(2x) = 1 \\implies 2x = \\frac{\\pi}{2} \\implies x = \\frac{\\pi}{4}$')" class="bg-sky-500 hover:bg-sky-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result6" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q7 -->
                        <div class="p-4 bg-pink-50/50 rounded-2xl border border-pink-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 7:</p>
                            <p class="text-slate-700">จงหาค่าของ $\cos(180^\circ)$</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans7" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-pink-300 text-sm focus:outline-none focus:ring-2 focus:ring-pink-400">
                                <button onclick="checkAnswer(7, ['-1'], '-1', 'พิกัดบนวงกลมหนึ่งหน่วยที่มุม $180^\\circ$ คือ $(-1, 0)$ ค่า $\\cos$ คือพิกัด X จึงได้ $-1$')" class="bg-pink-500 hover:bg-pink-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result7" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q8 -->
                        <div class="p-4 bg-sky-50/50 rounded-2xl border border-sky-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 8:</p>
                            <p class="text-slate-700">จงหาเซตคำตอบของอสมการ $\sin x > 0$ สำหรับ $x \in [0, 2\pi]$</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans8" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-sky-300 text-sm focus:outline-none focus:ring-2 focus:ring-sky-400">
                                <button onclick="checkAnswer(8, ['(0, pi)', '(0,pi)', '0 ถึง pi'], 'x \\in (0, \\pi)', 'ค่า Sine เป็นบวกในจตุภาคที่ 1 และ 2 ดังนั้น $x \\in (0, \\pi)$')" class="bg-sky-500 hover:bg-sky-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result8" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q9 -->
                        <div class="p-4 bg-pink-50/50 rounded-2xl border border-pink-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 9:</p>
                            <p class="text-slate-700">จงหาค่าของ $\sec(60^\circ)$</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans9" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-pink-300 text-sm focus:outline-none focus:ring-2 focus:ring-pink-400">
                                <button onclick="checkAnswer(9, ['2'], '2', 'ใช้สูตรส่วนกลับ $\\sec(60^\\circ) = \\frac{1}{\\cos(60^\\circ)} = \\frac{1}{1/2} = 2$')" class="bg-pink-500 hover:bg-pink-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result9" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>

                        <!-- Q10 -->
                        <div class="p-4 bg-sky-50/50 rounded-2xl border border-sky-200 space-y-3">
                            <p class="font-bold text-slate-800">ข้อที่ 10:</p>
                            <p class="text-slate-700">สามเหลี่ยม $ABC$ มีด้าน $a = 4$, $b = 6$ และมุม $C = 30^\circ$ จงหาพื้นที่สามเหลี่ยม $ABC$</p>
                            <div class="flex flex-col sm:flex-row gap-2">
                                <input type="text" id="ans10" placeholder="พิมพ์คำตอบของคุณที่นี่" class="flex-1 p-2.5 rounded-xl border border-sky-300 text-sm focus:outline-none focus:ring-2 focus:ring-sky-400">
                                <button onclick="checkAnswer(10, ['6', '6 ตารางหน่วย'], '\\text{พื้นที่ } 6 \\text{ ตารางหน่วย}', 'ใช้สูตรพื้นที่ = $\\frac{1}{2}ab\\sin C = \\frac{1}{2}(4)(6)\\sin 30^\\circ = 6$')" class="bg-sky-500 hover:bg-sky-600 text-white font-bold px-4 py-2.5 rounded-xl text-sm transition-colors">
                                    ตรวจคำตอบ
                                </button>
                            </div>
                            <div id="result10" class="hidden text-sm p-4 rounded-xl leading-relaxed"></div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Interactive Lab -->
            <section id="interactive-lab" class="tab-content hidden space-y-6">
                <div class="bg-white p-6 rounded-3xl border border-pink-200 shadow-sm space-y-6">
                    <h2 class="text-xl font-bold text-slate-800 border-b border-pink-100 pb-3 flex items-center gap-2">
                        <i class="fa-solid fa-flask text-sky-500"></i>
                        ห้องทดลองปฏิสัมพันธ์ (Interactive Lab) - วงกลมหนึ่งหน่วย
                    </h2>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center">
                        <div class="bg-pink-50/50 p-4 rounded-2xl border border-pink-200 flex flex-col items-center">
                            <h3 class="font-bold text-slate-700 mb-3">จำลองวงกลมหนึ่งหน่วย</h3>
                            <canvas id="unitCircleCanvas" width="220" height="220" class="bg-white rounded-2xl border border-pink-200 shadow-inner"></canvas>
                            <div class="w-full space-y-2 mt-4">
                                <label class="text-xs font-bold text-slate-600 flex justify-between">
                                    <span>ปรับค่ามุม ($\theta$):</span>
                                    <span id="angleValue" class="text-pink-600 font-bold">45°</span>
                                </label>
                                <input type="range" id="angleSlider" min="0" max="360" value="45" class="w-full accent-pink-500">
                            </div>
                        </div>
                        <div class="space-y-4 text-slate-700 text-sm">
                            <div class="p-4 bg-sky-50 rounded-2xl border border-sky-200 space-y-2">
                                <h4 class="font-bold text-sky-800">ค่าฟังก์ชันตรีโกณมิติ ณ มุมปัจจุบัน:</h4>
                                <p id="sinVal">$\sin(\theta) = 0.707$</p>
                                <p id="cosVal">$\cos(\theta) = 0.707$</p>
                                <p id="tanVal">$\tan(\theta) = 1.000$</p>
                            </div>
                            <p class="text-xs text-slate-500">คำแนะนำ: เลื่อนแถบสไลเดอร์เพื่อเปลี่ยนมุม แล้วสังเกตค่าพิกัดบนวงกลมหนึ่งหน่วยแบบเรียลไทม์</p>
                        </div>
                    </div>
                </div>
            </section>

        </div>
    </main>

    <!-- JavaScript Logic -->
    <script>
        function switchTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            document.querySelectorAll('.nav-btn').forEach(btn => btn.classList.remove('active-nav'));
            
            const activeContent = document.getElementById(tabId);
            if(activeContent) activeContent.classList.remove('hidden');

            const activeBtn = Array.from(document.querySelectorAll('.nav-btn')).find(b => b.getAttribute('onclick').includes(tabId));
            if(activeBtn) activeBtn.classList.add('active-nav');

            if(window.MathJax) MathJax.typesetPromise();
            if(tabId === 'interactive-lab') drawUnitCircle();
        }

        function toggleSidebar() {
            document.getElementById('sidebar').classList.toggle('-translate-x-full');
        }

        function checkAnswer(qNum, correctAnswers, solutionMathJax, stepsMathJax) {
            const userAns = document.getElementById('ans' + qNum).value.trim().toLowerCase();
            const resDiv = document.getElementById('result' + qNum);
            resDiv.classList.remove('hidden', 'bg-emerald-100', 'text-emerald-900', 'bg-rose-100', 'text-rose-900');
            
            const isCorrect = correctAnswers.some(ans => userAns === ans.toLowerCase());

            let statusHTML = isCorrect 
                ? '<div class="font-bold text-emerald-700 flex items-center gap-2 mb-2"><i class="fa-solid fa-circle-check"></i>ถูกต้องครับ! เก่งมากครับ</div>'
                : '<div class="font-bold text-rose-700 flex items-center gap-2 mb-2"><i class="fa-solid fa-circle-xmark"></i>ยังไม่ถูกต้อง ลองศึกษาแนวคิดและวิธีทำด้านล่างนี้นะครับ</div>';

            resDiv.classList.add(isCorrect ? 'bg-emerald-100' : 'bg-rose-100', 'border', 'p-4', 'rounded-xl');
            resDiv.innerHTML = `
                ${statusHTML}
                <div class="mt-2 pt-2 border-t border-slate-300 space-y-2">
                    <div><strong>คำตอบที่ถูกต้อง:</strong> $${solutionMathJax}$</div>
                    <div><strong>วิธีทำ:</strong></div>
                    <div class="bg-white/80 p-3 rounded-xl text-slate-800 text-xs md:text-sm leading-relaxed">
                        ${stepsMathJax}
                    </div>
                </div>
            `;
            if(window.MathJax) MathJax.typesetPromise([resDiv]);
        }

        const slider = document.getElementById('angleSlider');
        if(slider) {
            slider.addEventListener('input', (e) => {
                const deg = e.target.value;
                document.getElementById('angleValue').innerText = deg + '°';
                drawUnitCircle();
            });
        }

        function drawUnitCircle() {
            const canvas = document.getElementById('unitCircleCanvas');
            if(!canvas) return;
            const ctx = canvas.getContext('2d');
            const deg = parseFloat(slider.value);
            const rad = deg * Math.PI / 180;
            const cx = 110, cy = 110, r = 80;

            ctx.clearRect(0, 0, canvas.width, canvas.height);
            // Axes
            ctx.strokeStyle = '#cbd5e1';
            ctx.lineWidth = 1;
            ctx.beginPath(); ctx.moveTo(10, cy); ctx.lineTo(210, cy); ctx.moveTo(cx, 10); ctx.lineTo(cx, 210); ctx.stroke();
            
            // Circle
            ctx.strokeStyle = '#f472b6';
            ctx.lineWidth = 2;
            ctx.beginPath(); ctx.arc(cx, cy, r, 0, Math.PI * 2); ctx.stroke();
            
            // Point & Line
            const px = cx + r * Math.cos(rad);
            const py = cy - r * Math.sin(rad);
            ctx.strokeStyle = '#0284c7';
            ctx.beginPath(); ctx.moveTo(cx, cy); ctx.lineTo(px, py); ctx.stroke();
            ctx.fillStyle = '#f43f5e';
            ctx.beginPath(); ctx.arc(px, py, 6, 0, Math.PI * 2); ctx.fill();

            // Update text
            const sinVal = Math.sin(rad).toFixed(3);
            const cosVal = Math.cos(rad).toFixed(3);
            const tanVal = Math.abs(Math.cos(rad)) < 0.001 ? 'Undefined' : Math.tan(rad).toFixed(3);
            
            document.getElementById('sinVal').innerHTML = `$\\sin(${deg}^\\circ) = ${sinVal}$`;
            document.getElementById('cosVal').innerHTML = `$\\cos(${deg}^\\circ) = ${cosVal}$`;
            document.getElementById('tanVal').innerHTML = `$\\tan(${deg}^\\circ) = ${tanVal}$`;
            if(window.MathJax) MathJax.typesetPromise([document.getElementById('interactive-lab')]);
        }
    </script>
</body>
</html>
