
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhargava G K | Cybersecurity Expert</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>tailwind.config={theme:{extend:{colors:{primary:'#00FF41',secondary:'#0066FF'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css" rel="stylesheet">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        
        :root {
            --bg-color: #0C0C0C;
            --text-color: #e2e2e2;
            --primary: #00FF41;
            --secondary: #0066FF;
            --accent: #FF00AA;
            --terminal-font: 'Fira Code', monospace;
        }
        
        body {
            font-family: var(--terminal-font);
            background-color: var(--bg-color);
            color: var(--text-color);
            overflow-x: hidden;
        }
        
        .terminal-text {
            font-family: var(--terminal-font);
        }
        
        .glow {
            text-shadow: 0 0 5px var(--primary), 0 0 10px var(--primary);
        }
        
        .glow-blue {
            text-shadow: 0 0 5px var(--secondary), 0 0 10px var(--secondary);
        }
        
        .glow-box {
            box-shadow: 0 0 5px var(--primary), 0 0 10px rgba(0, 255, 65, 0.3);
        }
        
        .glow-box-blue {
            box-shadow: 0 0 5px var(--secondary), 0 0 10px rgba(0, 102, 255, 0.3);
        }
        
        .matrix-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.1;
        }
        
        .typed-cursor {
            color: var(--primary);
            animation: blink 1s infinite;
        }
        
        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }
        
        .terminal-window {
            border: 1px solid rgba(0, 255, 65, 0.3);
            border-radius: 8px;
            background-color: rgba(12, 12, 12, 0.8);
            backdrop-filter: blur(5px);
        }
        
        .terminal-header {
            border-bottom: 1px solid rgba(0, 255, 65, 0.3);
            padding: 8px 16px;
            display: flex;
            align-items: center;
        }
        
        .terminal-circle {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            margin-right: 8px;
        }
        
        .progress-bar {
            height: 6px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 3px;
            overflow: hidden;
            position: relative;
        }
        
        .progress-fill {
            height: 100%;
            position: absolute;
            left: 0;
            top: 0;
            background-color: var(--primary);
            transition: width 1s ease;
        }
        
        .hexagon {
            position: relative;
            width: 100px;
            height: 57.74px;
            margin: 28.87px 0;
            background-color: rgba(0, 255, 65, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }
        
        .hexagon:before,
        .hexagon:after {
            content: "";
            position: absolute;
            width: 0;
            border-left: 50px solid transparent;
            border-right: 50px solid transparent;
        }
        
        .hexagon:before {
            bottom: 100%;
            border-bottom: 28.87px solid rgba(0, 255, 65, 0.1);
        }
        
        .hexagon:after {
            top: 100%;
            border-top: 28.87px solid rgba(0, 255, 65, 0.1);
        }
        
        .hexagon:hover {
            background-color: rgba(0, 255, 65, 0.2);
        }
        
        .hexagon:hover:before {
            border-bottom-color: rgba(0, 255, 65, 0.2);
        }
        
        .hexagon:hover:after {
            border-top-color: rgba(0, 255, 65, 0.2);
        }
        
        .timeline-item {
            position: relative;
            padding-left: 30px;
        }
        
        .timeline-item:before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            height: 100%;
            width: 1px;
            background-color: rgba(0, 255, 65, 0.3);
        }
        
        .timeline-item:after {
            content: '';
            position: absolute;
            left: -5px;
            top: 10px;
            height: 12px;
            width: 12px;
            border-radius: 50%;
            background-color: var(--primary);
            box-shadow: 0 0 5px var(--primary), 0 0 10px var(--primary);
        }
        
        .glass-card {
            background: rgba(20, 20, 20, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(0, 255, 65, 0.1);
            transition: all 0.3s ease;
        }
        
        .glass-card:hover {
            border-color: var(--primary);
            box-shadow: 0 0 15px rgba(0, 255, 65, 0.3);
            transform: translateY(-5px);
        }
        
        input, textarea, button {
            background-color: rgba(30, 30, 30, 0.7);
            border: 1px solid rgba(0, 255, 65, 0.3);
            color: var(--text-color);
            font-family: var(--terminal-font);
            transition: all 0.3s ease;
            outline: none;
        }
        
        input:focus, textarea:focus {
            border-color: var(--primary);
            box-shadow: 0 0 5px rgba(0, 255, 65, 0.5);
        }
        
        .custom-checkbox {
            appearance: none;
            width: 20px;
            height: 20px;
            border: 1px solid rgba(0, 255, 65, 0.5);
            background-color: transparent;
            border-radius: 4px;
            cursor: pointer;
            position: relative;
        }
        
        .custom-checkbox:checked {
            background-color: var(--primary);
            border-color: var(--primary);
        }
        
        .custom-checkbox:checked::after {
            content: '✓';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: var(--bg-color);
            font-size: 14px;
        }
        
        .custom-range {
            -webkit-appearance: none;
            width: 100%;
            height: 6px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 3px;
            outline: none;
        }
        
        .custom-range::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 16px;
            height: 16px;
            border-radius: 50%;
            background: var(--primary);
            cursor: pointer;
            box-shadow: 0 0 5px var(--primary);
        }
        
        .custom-range::-moz-range-thumb {
            width: 16px;
            height: 16px;
            border-radius: 50%;
            background: var(--primary);
            cursor: pointer;
            box-shadow: 0 0 5px var(--primary);
            border: none;
        }
        
        .custom-switch {
            position: relative;
            display: inline-block;
            width: 50px;
            height: 24px;
        }
        
        .custom-switch input {
            opacity: 0;
            width: 0;
            height: 0;
        }
        
        .switch-slider {
            position: absolute;
            cursor: pointer;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(30, 30, 30, 0.7);
            transition: .4s;
            border-radius: 34px;
            border: 1px solid rgba(0, 255, 65, 0.3);
        }
        
        .switch-slider:before {
            position: absolute;
            content: "";
            height: 16px;
            width: 16px;
            left: 4px;
            bottom: 3px;
            background-color: var(--text-color);
            transition: .4s;
            border-radius: 50%;
        }
        
        input:checked + .switch-slider {
            background-color: var(--primary);
        }
        
        input:checked + .switch-slider:before {
            transform: translateX(26px);
        }
        
        .radio-container {
            display: flex;
            align-items: center;
        }
        
        .custom-radio {
            appearance: none;
            width: 20px;
            height: 20px;
            border: 1px solid rgba(0, 255, 65, 0.5);
            border-radius: 50%;
            background-color: transparent;
            cursor: pointer;
            position: relative;
        }
        
        .custom-radio:checked {
            border-color: var(--primary);
        }
        
        .custom-radio:checked::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 10px;
            height: 10px;
            border-radius: 50%;
            background-color: var(--primary);
            box-shadow: 0 0 5px var(--primary);
        }
        
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: rgba(30, 30, 30, 0.7);
        }
        
        ::-webkit-scrollbar-thumb {
            background: rgba(0, 255, 65, 0.5);
            border-radius: 4px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
            background: var(--primary);
        }
        
        @keyframes scanline {
            0% {
                transform: translateY(-100%);
            }
            100% {
                transform: translateY(100%);
            }
        }
        
        .scanline {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 10px;
            background: linear-gradient(to bottom, 
                rgba(0, 255, 65, 0) 0%,
                rgba(0, 255, 65, 0.1) 50%,
                rgba(0, 255, 65, 0) 100%);
            opacity: 0.1;
            animation: scanline 8s linear infinite;
            pointer-events: none;
        }
    </style>
</head>
<body>
    <div class="scanline"></div>
    
    <!-- Matrix Background Canvas -->
    <canvas id="matrixCanvas" class="matrix-bg"></canvas>
    
    <!-- Navigation -->
    <nav class="fixed top-0 left-0 w-full z-50 bg-[rgba(12,12,12,0.9)] backdrop-blur-md border-b border-[rgba(0,255,65,0.3)]">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#home" class="text-primary font-['Pacifico'] text-2xl">logo</a>
            
            <div class="hidden md:flex items-center space-x-6">
                <div class="flex items-center space-x-2 text-xs text-gray-400">
                    <span>CPU:</span>
                    <div class="w-20 h-2 bg-[rgba(255,255,255,0.1)] rounded-full overflow-hidden">
                        <div class="h-full bg-primary" style="width: 42%"></div>
                    </div>
                    <span>42%</span>
                </div>
                
                <div class="flex items-center space-x-2 text-xs text-gray-400">
                    <span>MEM:</span>
                    <div class="w-20 h-2 bg-[rgba(255,255,255,0.1)] rounded-full overflow-hidden">
                        <div class="h-full bg-primary" style="width: 68%"></div>
                    </div>
                    <span>68%</span>
                </div>
                
                <div class="flex items-center space-x-2 text-xs text-gray-400">
                    <span>NET:</span>
                    <div class="w-20 h-2 bg-[rgba(255,255,255,0.1)] rounded-full overflow-hidden">
                        <div class="h-full bg-primary" style="width: 87%"></div>
                    </div>
                    <span>87%</span>
                </div>
            </div>
            
            <div class="hidden md:flex items-center space-x-8">
                <a href="#home" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center">
                    <span class="text-primary mr-1">~$</span> home
                </a>
                <a href="#about" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center">
                    <span class="text-primary mr-1">~$</span> about
                </a>
                <a href="#skills" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center">
                    <span class="text-primary mr-1">~$</span> skills
                </a>
                <a href="#projects" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center">
                    <span class="text-primary mr-1">~$</span> projects
                </a>
                <a href="#experience" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center">
                    <span class="text-primary mr-1">~$</span> experience
                </a>
                <a href="#blog" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center">
                    <span class="text-primary mr-1">~$</span> blog
                </a>
                <a href="#contact" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center">
                    <span class="text-primary mr-1">~$</span> contact
                </a>
            </div>
            
            <button id="mobileMenuButton" class="md:hidden w-10 h-10 flex items-center justify-center text-gray-300">
                <i class="ri-menu-line ri-lg"></i>
            </button>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-[rgba(12,12,12,0.95)] border-t border-[rgba(0,255,65,0.3)]">
            <div class="container mx-auto px-4 py-3 flex flex-col space-y-4">
                <a href="#home" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center py-2">
                    <span class="text-primary mr-1">~$</span> home
                </a>
                <a href="#about" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center py-2">
                    <span class="text-primary mr-1">~$</span> about
                </a>
                <a href="#skills" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center py-2">
                    <span class="text-primary mr-1">~$</span> skills
                </a>
                <a href="#projects" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center py-2">
                    <span class="text-primary mr-1">~$</span> projects
                </a>
                <a href="#experience" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center py-2">
                    <span class="text-primary mr-1">~$</span> experience
                </a>
                <a href="#blog" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center py-2">
                    <span class="text-primary mr-1">~$</span> blog
                </a>
                <a href="#contact" class="text-gray-300 hover:text-primary transition-colors duration-300 flex items-center py-2">
                    <span class="text-primary mr-1">~$</span> contact
                </a>
                
                <div class="flex justify-between items-center pt-4 border-t border-[rgba(255,255,255,0.1)]">
                    <div class="flex items-center space-x-2 text-xs text-gray-400">
                        <span>CPU: 42%</span>
                        <span>MEM: 68%</span>
                        <span>NET: 87%</span>
                    </div>
                </div>
            </div>
        </div>
    </nav>
    
    <!-- Home Section -->
    <section id="home" class="min-h-screen pt-20 flex items-center relative overflow-hidden">
        <div class="container mx-auto px-4 py-16 relative z-10">
            <div class="flex flex-col md:flex-row items-center">
                <div class="w-full md:w-1/2 mb-10 md:mb-0">
                    <div class="terminal-window p-6 md:p-8">
                        <div class="terminal-header mb-4">
                            <div class="terminal-circle bg-red-500"></div>
                            <div class="terminal-circle bg-yellow-500 mx-2"></div>
                            <div class="terminal-circle bg-green-500"></div>
                            <span class="ml-4 text-gray-400 text-sm">bhargava@secure-terminal:~</span>
                        </div>
                        
                        <div class="space-y-4">
                            <div class="flex items-center">
                                <span class="text-primary mr-2">~$</span>
                                <span class="typing-text text-xl md:text-2xl font-semibold" id="typingText">ACCESS GRANTED</span>
                                <span class="typed-cursor">|</span>
                            </div>
                            
                            <div class="text-gray-300 text-sm md:text-base mt-4">
                                <p class="mb-3">Welcome to my secure terminal. I'm <span class="text-primary font-semibold">Bhargava G K</span>, a cybersecurity specialist focused on protecting digital assets and hunting vulnerabilities.</p>
                                <p>Specializing in penetration testing, network security, and ethical hacking with a mission to make the digital world safer one vulnerability at a time.</p>
                            </div>
                            
                            <div class="flex flex-wrap gap-4 mt-6">
                                <div class="bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] p-3 rounded">
                                    <div class="text-xs text-gray-400">THREATS NEUTRALIZED</div>
                                    <div class="text-primary text-2xl font-bold">1,458</div>
                                </div>
                                
                                <div class="bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] p-3 rounded">
                                    <div class="text-xs text-gray-400">SYSTEMS SECURED</div>
                                    <div class="text-primary text-2xl font-bold">237</div>
                                </div>
                                
                                <div class="bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] p-3 rounded">
                                    <div class="text-xs text-gray-400">CTF POINTS</div>
                                    <div class="text-primary text-2xl font-bold">12,845</div>
                                </div>
                            </div>
                            
                            <div class="flex space-x-4 mt-8">
                                <a href="#contact" class="bg-primary text-black px-6 py-3 rounded-button font-medium hover:bg-opacity-80 transition-all duration-300 whitespace-nowrap flex items-center">
                                    <i class="ri-terminal-line mr-2"></i> Connect with me
                                </a>
                                <a href="#projects" class="bg-transparent border border-primary text-primary px-6 py-3 rounded-button font-medium hover:bg-primary hover:bg-opacity-10 transition-all duration-300 whitespace-nowrap flex items-center">
                                    <i class="ri-code-box-line mr-2"></i> View Projects
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="w-full md:w-1/2 flex justify-center">
                    <div class="relative">
                        <div class="w-[320px] h-[320px] md:w-[400px] md:h-[400px] rounded-full bg-[rgba(0,255,65,0.03)] border border-[rgba(0,255,65,0.1)] flex items-center justify-center">
                            <div class="w-[240px] h-[240px] md:w-[300px] md:h-[300px] rounded-full bg-[rgba(0,255,65,0.05)] border border-[rgba(0,255,65,0.15)] flex items-center justify-center">
                                <div class="w-[160px] h-[160px] md:w-[200px] md:h-[200px] rounded-full bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.2)] flex items-center justify-center">
                                    <div class="w-[80px] h-[80px] md:w-[100px] md:h-[100px] rounded-full bg-[rgba(0,255,65,0.2)] border border-[rgba(0,255,65,0.3)] flex items-center justify-center">
                                        <i class="ri-shield-keyhole-line ri-3x text-primary"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        
                        <div class="absolute top-0 left-0 w-full h-full animate-spin-slow" style="animation: spin 20s linear infinite;">
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(0deg) translateY(-160px);"></div>
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(45deg) translateY(-160px);"></div>
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(90deg) translateY(-160px);"></div>
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(135deg) translateY(-160px);"></div>
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(180deg) translateY(-160px);"></div>
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(225deg) translateY(-160px);"></div>
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(270deg) translateY(-160px);"></div>
                            <div class="absolute top-[50%] left-[50%] w-2 h-2 bg-primary rounded-full shadow-[0_0_10px_#00FF41]" style="transform: translate(-50%, -50%) rotate(315deg) translateY(-160px);"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- About Section -->
    <section id="about" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="mb-12 text-center">
                <h2 class="text-3xl font-bold mb-2">
                    <span class="text-primary">&lt;</span> About Me <span class="text-primary">/&gt;</span>
                </h2>
                <p class="text-gray-400">The human behind the terminal</p>
            </div>
            
            <div class="flex flex-col md:flex-row gap-8">
                <div class="w-full md:w-1/2">
                    <div class="terminal-window p-6 h-full">
                        <div class="terminal-header mb-4">
                            <div class="terminal-circle bg-red-500"></div>
                            <div class="terminal-circle bg-yellow-500 mx-2"></div>
                            <div class="terminal-circle bg-green-500"></div>
                            <span class="ml-4 text-gray-400 text-sm">user_profile.sh</span>
                        </div>
                        
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <span class="text-primary mr-2">~$</span>
                                <span class="text-gray-300">cat profile.json</span>
                            </div>
                            
                            <div class="bg-[rgba(0,0,0,0.3)] p-4 rounded text-gray-300 text-sm font-mono">
                                <pre class="whitespace-pre-wrap">{
  "name": "Bhargava G K",
  "title": "Cybersecurity Specialist",
  "location": "Bangalore, India",
  "education": [
    {
      "degree": "M.Tech in Cyber Security",
      "institution": "National Institute of Technology",
      "year": "2023"
    },
    {
      "degree": "B.Tech in Computer Science",
      "institution": "Visvesvaraya Technological University",
      "year": "2021"
    }
  ],
  "interests": [
    "Penetration Testing",
    "Vulnerability Research",
    "Network Security",
    "Digital Forensics",
    "CTF Competitions",
    "Open Source Security Tools"
  ],
  "languages": ["English", "Hindi", "Kannada"]
}</pre>
                            </div>
                            
                            <div class="flex items-start">
                                <span class="text-primary mr-2">~$</span>
                                <span class="text-gray-300">./get_personal_statement.sh</span>
                            </div>
                            
                            <div class="text-gray-300 text-sm">
                                <p class="mb-3">I'm a cybersecurity enthusiast with a passion for identifying and mitigating security vulnerabilities. My journey began during my undergraduate studies when I discovered the fascinating world of ethical hacking.</p>
                                <p class="mb-3">Since then, I've dedicated my career to helping organizations strengthen their security posture through penetration testing, security assessments, and developing defensive strategies against emerging threats.</p>
                                <p>When I'm not hunting bugs or securing networks, you'll find me participating in CTF competitions, contributing to open-source security tools, or mentoring aspiring cybersecurity professionals.</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="w-full md:w-1/2">
                    <div class="terminal-window p-6 h-full">
                        <div class="terminal-header mb-4">
                            <div class="terminal-circle bg-red-500"></div>
                            <div class="terminal-circle bg-yellow-500 mx-2"></div>
                            <div class="terminal-circle bg-green-500"></div>
                            <span class="ml-4 text-gray-400 text-sm">timeline.sh</span>
                        </div>
                        
                        <div class="space-y-6 mt-4">
                            <div class="timeline-item pl-8 pb-6">
                                <div class="text-primary font-semibold">2023 - Present</div>
                                <div class="text-white font-medium">Senior Security Analyst</div>
                                <div class="text-gray-400">CyberDefend Solutions</div>
                                <p class="text-gray-300 text-sm mt-2">Leading penetration testing engagements and security assessments for enterprise clients. Specializing in web application security and network infrastructure testing.</p>
                            </div>
                            
                            <div class="timeline-item pl-8 pb-6">
                                <div class="text-primary font-semibold">2021 - 2023</div>
                                <div class="text-white font-medium">Security Researcher</div>
                                <div class="text-gray-400">SecureNet Technologies</div>
                                <p class="text-gray-300 text-sm mt-2">Conducted vulnerability research and developed exploit proof-of-concepts. Contributed to the company's threat intelligence platform.</p>
                            </div>
                            
                            <div class="timeline-item pl-8 pb-6">
                                <div class="text-primary font-semibold">2020 - 2021</div>
                                <div class="text-white font-medium">Cybersecurity Intern</div>
                                <div class="text-gray-400">ShadowFox Security</div>
                                <p class="text-gray-300 text-sm mt-2">Assisted in security assessments and developed automated tools for vulnerability scanning. Participated in incident response drills.</p>
                            </div>
                            
                            <div class="timeline-item pl-8">
                                <div class="text-primary font-semibold">2019</div>
                                <div class="text-white font-medium">CTF Team Lead</div>
                                <div class="text-gray-400">University Cybersecurity Club</div>
                                <p class="text-gray-300 text-sm mt-2">Led a team of 5 members to secure 2nd place in the National Collegiate Cyber Defense Competition.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Skills Section -->
    <section id="skills" class="py-20 relative bg-[rgba(0,0,0,0.3)]">
        <div class="container mx-auto px-4">
            <div class="mb-12 text-center">
                <h2 class="text-3xl font-bold mb-2">
                    <span class="text-primary">&lt;</span> Technical Arsenal <span class="text-primary">/&gt;</span>
                </h2>
                <p class="text-gray-400">Tools and skills in my security toolkit</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Security Domains -->
                <div class="terminal-window p-6">
                    <div class="terminal-header mb-4">
                        <div class="terminal-circle bg-red-500"></div>
                        <div class="terminal-circle bg-yellow-500 mx-2"></div>
                        <div class="terminal-circle bg-green-500"></div>
                        <span class="ml-4 text-gray-400 text-sm">security_domains.sh</span>
                    </div>
                    
                    <h3 class="text-xl font-semibold text-white mb-4">Security Domains</h3>
                    
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Penetration Testing</span>
                                <span class="text-primary">95%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 95%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Network Security</span>
                                <span class="text-primary">90%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 90%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Web Application Security</span>
                                <span class="text-primary">92%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 92%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Malware Analysis</span>
                                <span class="text-primary">85%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 85%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Digital Forensics</span>
                                <span class="text-primary">80%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 80%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Cloud Security</span>
                                <span class="text-primary">78%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 78%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Security Tools -->
                <div class="terminal-window p-6">
                    <div class="terminal-header mb-4">
                        <div class="terminal-circle bg-red-500"></div>
                        <div class="terminal-circle bg-yellow-500 mx-2"></div>
                        <div class="terminal-circle bg-green-500"></div>
                        <span class="ml-4 text-gray-400 text-sm">security_tools.sh</span>
                    </div>
                    
                    <h3 class="text-xl font-semibold text-white mb-4">Security Tools</h3>
                    
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-radar-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">Nmap</div>
                                <div class="text-xs text-gray-400">Network Scanner</div>
                            </div>
                        </div>
                        
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-bug-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">Metasploit</div>
                                <div class="text-xs text-gray-400">Exploitation</div>
                            </div>
                        </div>
                        
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-wifi-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">Wireshark</div>
                                <div class="text-xs text-gray-400">Packet Analysis</div>
                            </div>
                        </div>
                        
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-shield-keyhole-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">Burp Suite</div>
                                <div class="text-xs text-gray-400">Web App Testing</div>
                            </div>
                        </div>
                        
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-lock-password-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">Hashcat</div>
                                <div class="text-xs text-gray-400">Password Cracking</div>
                            </div>
                        </div>
                        
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-spy-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">OWASP ZAP</div>
                                <div class="text-xs text-gray-400">Vulnerability Scanner</div>
                            </div>
                        </div>
                        
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-file-search-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">Volatility</div>
                                <div class="text-xs text-gray-400">Memory Forensics</div>
                            </div>
                        </div>
                        
                        <div class="bg-[rgba(0,0,0,0.3)] p-3 rounded flex items-center">
                            <div class="w-10 h-10 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-3">
                                <i class="ri-terminal-box-line text-primary"></i>
                            </div>
                            <div>
                                <div class="text-white font-medium">Kali Linux</div>
                                <div class="text-xs text-gray-400">Security OS</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Programming & Scripting -->
                <div class="terminal-window p-6">
                    <div class="terminal-header mb-4">
                        <div class="terminal-circle bg-red-500"></div>
                        <div class="terminal-circle bg-yellow-500 mx-2"></div>
                        <div class="terminal-circle bg-green-500"></div>
                        <span class="ml-4 text-gray-400 text-sm">programming.sh</span>
                    </div>
                    
                    <h3 class="text-xl font-semibold text-white mb-4">Programming & Scripting</h3>
                    
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Python</span>
                                <span class="text-primary">95%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 95%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">Bash Scripting</span>
                                <span class="text-primary">90%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 90%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">SQL</span>
                                <span class="text-primary">85%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 85%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">JavaScript</span>
                                <span class="text-primary">80%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 80%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">C/C++</span>
                                <span class="text-primary">75%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 75%"></div>
                            </div>
                        </div>
                        
                        <div>
                            <div class="flex justify-between mb-1">
                                <span class="text-gray-300">PowerShell</span>
                                <span class="text-primary">70%</span>
                            </div>
                            <div class="progress-bar">
                                <div class="progress-fill" style="width: 70%"></div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="mt-6">
                        <h4 class="text-white font-medium mb-3">Certifications</h4>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">CEH v11</span>
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">OSCP</span>
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">CompTIA Security+</span>
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">AWS Security Specialist</span>
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">GIAC GPEN</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Projects Section -->
    <section id="projects" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="mb-12 text-center">
                <h2 class="text-3xl font-bold mb-2">
                    <span class="text-primary">&lt;</span> Security Projects <span class="text-primary">/&gt;</span>
                </h2>
                <p class="text-gray-400">A showcase of my cybersecurity work</p>
            </div>
            
            <div class="flex justify-center mb-8">
                <div class="inline-flex bg-[rgba(0,0,0,0.3)] p-1 rounded-full">
                    <button class="project-filter-btn active px-4 py-2 rounded-full text-primary bg-[rgba(0,255,65,0.1)]" data-filter="all">All Projects</button>
                    <button class="project-filter-btn px-4 py-2 rounded-full text-gray-300 hover:text-primary" data-filter="tools">Security Tools</button>
                    <button class="project-filter-btn px-4 py-2 rounded-full text-gray-300 hover:text-primary" data-filter="ctf">CTF Writeups</button>
                    <button class="project-filter-btn px-4 py-2 rounded-full text-gray-300 hover:text-primary" data-filter="research">Research</button>
                </div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="glass-card rounded-lg overflow-hidden project-item" data-category="tools">
                    <div class="h-48 bg-[rgba(0,0,0,0.5)] relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <i class="ri-shield-keyhole-line ri-3x text-primary"></i>
                        </div>
                        <div class="absolute top-3 right-3 bg-[rgba(0,0,0,0.7)] text-primary text-xs px-2 py-1 rounded">Security Tool</div>
                    </div>
                    
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-white mb-2">VulnHunter Scanner</h3>
                        <p class="text-gray-300 text-sm mb-4">An automated vulnerability scanner with custom exploit modules for web applications. Built with Python and leveraging multiple security APIs.</p>
                        
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Python</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Flask</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">OWASP</span>
                        </div>
                        
                        <div class="flex justify-between">
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-github-fill mr-1"></i> View Code
                            </a>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-external-link-line mr-1"></i> Live Demo
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="glass-card rounded-lg overflow-hidden project-item" data-category="research">
                    <div class="h-48 bg-[rgba(0,0,0,0.5)] relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <i class="ri-file-search-line ri-3x text-primary"></i>
                        </div>
                        <div class="absolute top-3 right-3 bg-[rgba(0,0,0,0.7)] text-primary text-xs px-2 py-1 rounded">Research</div>
                    </div>
                    
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-white mb-2">Zero-Day Vulnerability Research</h3>
                        <p class="text-gray-300 text-sm mb-4">Discovered and responsibly disclosed a critical authentication bypass vulnerability in a popular open-source CMS platform.</p>
                        
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">CVE-2024-1234</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Authentication</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">PHP</span>
                        </div>
                        
                        <div class="flex justify-between">
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-file-paper-2-line mr-1"></i> Read Paper
                            </a>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-github-fill mr-1"></i> PoC Code
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="glass-card rounded-lg overflow-hidden project-item" data-category="ctf">
                    <div class="h-48 bg-[rgba(0,0,0,0.5)] relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <i class="ri-flag-line ri-3x text-primary"></i>
                        </div>
                        <div class="absolute top-3 right-3 bg-[rgba(0,0,0,0.7)] text-primary text-xs px-2 py-1 rounded">CTF Writeup</div>
                    </div>
                    
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-white mb-2">HackTheBox: Obscurity</h3>
                        <p class="text-gray-300 text-sm mb-4">Detailed walkthrough of solving the "Obscurity" challenge on HackTheBox, focusing on Python code injection and privilege escalation techniques.</p>
                        
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Code Injection</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Privilege Escalation</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Linux</span>
                        </div>
                        
                        <div class="flex justify-between">
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-file-text-line mr-1"></i> Read Writeup
                            </a>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-video-line mr-1"></i> Video Walkthrough
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Project 4 -->
                <div class="glass-card rounded-lg overflow-hidden project-item" data-category="tools">
                    <div class="h-48 bg-[rgba(0,0,0,0.5)] relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <i class="ri-wifi-line ri-3x text-primary"></i>
                        </div>
                        <div class="absolute top-3 right-3 bg-[rgba(0,0,0,0.7)] text-primary text-xs px-2 py-1 rounded">Security Tool</div>
                    </div>
                    
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-white mb-2">NetSentry IDS</h3>
                        <p class="text-gray-300 text-sm mb-4">A lightweight intrusion detection system that uses machine learning to identify anomalous network traffic patterns in real-time.</p>
                        
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Python</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">TensorFlow</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Network Security</span>
                        </div>
                        
                        <div class="flex justify-between">
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-github-fill mr-1"></i> View Code
                            </a>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-file-paper-2-line mr-1"></i> Documentation
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Project 5 -->
                <div class="glass-card rounded-lg overflow-hidden project-item" data-category="research">
                    <div class="h-48 bg-[rgba(0,0,0,0.5)] relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <i class="ri-lock-line ri-3x text-primary"></i>
                        </div>
                        <div class="absolute top-3 right-3 bg-[rgba(0,0,0,0.7)] text-primary text-xs px-2 py-1 rounded">Research</div>
                    </div>
                    
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-white mb-2">Secure Authentication Framework</h3>
                        <p class="text-gray-300 text-sm mb-4">Developed a multi-factor authentication framework with biometric integration for high-security environments.</p>
                        
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Authentication</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Biometrics</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Java</span>
                        </div>
                        
                        <div class="flex justify-between">
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-github-fill mr-1"></i> View Code
                            </a>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-presentation-line mr-1"></i> Presentation
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Project 6 -->
                <div class="glass-card rounded-lg overflow-hidden project-item" data-category="ctf">
                    <div class="h-48 bg-[rgba(0,0,0,0.5)] relative overflow-hidden">
                        <div class="absolute inset-0 flex items-center justify-center">
                            <i class="ri-bug-line ri-3x text-primary"></i>
                        </div>
                        <div class="absolute top-3 right-3 bg-[rgba(0,0,0,0.7)] text-primary text-xs px-2 py-1 rounded">CTF Writeup</div>
                    </div>
                    
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-white mb-2">DEFCON CTF: Binary Exploitation</h3>
                        <p class="text-gray-300 text-sm mb-4">Detailed solution for a complex binary exploitation challenge from DEFCON CTF, involving ROP chains and format string vulnerabilities.</p>
                        
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">Binary Exploitation</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">ROP</span>
                            <span class="bg-[rgba(0,0,0,0.3)] text-gray-400 text-xs px-2 py-1 rounded">C/C++</span>
                        </div>
                        
                        <div class="flex justify-between">
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-file-text-line mr-1"></i> Read Writeup
                            </a>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                <i class="ri-github-fill mr-1"></i> Exploit Code
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="bg-transparent border border-primary text-primary px-6 py-3 rounded-button font-medium hover:bg-primary hover:bg-opacity-10 transition-all duration-300 whitespace-nowrap inline-flex items-center">
                    <i class="ri-github-fill mr-2"></i> View More on GitHub
                </a>
            </div>
        </div>
    </section>
    
    <!-- Experience Section -->
    <section id="experience" class="py-20 relative bg-[rgba(0,0,0,0.3)]">
        <div class="container mx-auto px-4">
            <div class="mb-12 text-center">
                <h2 class="text-3xl font-bold mb-2">
                    <span class="text-primary">&lt;</span> Experience & Certifications <span class="text-primary">/&gt;</span>
                </h2>
                <p class="text-gray-400">Professional journey and credentials</p>
            </div>
            
            <div class="flex flex-col md:flex-row gap-8">
                <div class="w-full md:w-1/2">
                    <div class="terminal-window p-6">
                        <div class="terminal-header mb-4">
                            <div class="terminal-circle bg-red-500"></div>
                            <div class="terminal-circle bg-yellow-500 mx-2"></div>
                            <div class="terminal-circle bg-green-500"></div>
                            <span class="ml-4 text-gray-400 text-sm">work_experience.sh</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-6">Professional Experience</h3>
                        
                        <div class="space-y-8">
                            <div class="glass-card p-4 rounded-lg">
                                <div class="flex justify-between items-start">
                                    <div>
                                        <h4 class="text-white font-medium">Senior Security Analyst</h4>
                                        <p class="text-primary text-sm">CyberDefend Solutions</p>
                                    </div>
                                    <div class="text-gray-400 text-sm">2023 - Present</div>
                                </div>
                                <ul class="mt-3 space-y-2 text-sm text-gray-300">
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Led 15+ penetration testing engagements for Fortune 500 clients</span>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Developed custom security assessment methodologies for cloud environments</span>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Mentored junior security analysts and conducted internal training</span>
                                    </li>
                                </ul>
                            </div>
                            
                            <div class="glass-card p-4 rounded-lg">
                                <div class="flex justify-between items-start">
                                    <div>
                                        <h4 class="text-white font-medium">Security Researcher</h4>
                                        <p class="text-primary text-sm">SecureNet Technologies</p>
                                    </div>
                                    <div class="text-gray-400 text-sm">2021 - 2023</div>
                                </div>
                                <ul class="mt-3 space-y-2 text-sm text-gray-300">
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Discovered and reported 20+ zero-day vulnerabilities in enterprise applications</span>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Developed automated tools for vulnerability detection and exploitation</span>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Contributed to the company's threat intelligence platform</span>
                                    </li>
                                </ul>
                            </div>
                            
                            <div class="glass-card p-4 rounded-lg">
                                <div class="flex justify-between items-start">
                                    <div>
                                        <h4 class="text-white font-medium">Cybersecurity Intern</h4>
                                        <p class="text-primary text-sm">ShadowFox Security</p>
                                    </div>
                                    <div class="text-gray-400 text-sm">2020 - 2021</div>
                                </div>
                                <ul class="mt-3 space-y-2 text-sm text-gray-300">
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Assisted senior security analysts in penetration testing engagements</span>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Developed a Python-based tool for automating security scans</span>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="ri-checkbox-circle-line text-primary mt-1 mr-2"></i>
                                        <span>Participated in incident response drills and security awareness training</span>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="w-full md:w-1/2">
                    <div class="terminal-window p-6">
                        <div class="terminal-header mb-4">
                            <div class="terminal-circle bg-red-500"></div>
                            <div class="terminal-circle bg-yellow-500 mx-2"></div>
                            <div class="terminal-circle bg-green-500"></div>
                            <span class="ml-4 text-gray-400 text-sm">certifications.sh</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-6">Certifications & Achievements</h3>
                        
                        <div class="space-y-6">
                            <div class="glass-card p-4 rounded-lg flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                    <i class="ri-verified-badge-line text-primary ri-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-medium">Offensive Security Certified Professional (OSCP)</h4>
                                    <p class="text-gray-400 text-sm">Offensive Security | 2022</p>
                                </div>
                            </div>
                            
                            <div class="glass-card p-4 rounded-lg flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                    <i class="ri-verified-badge-line text-primary ri-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-medium">Certified Ethical Hacker (CEH)</h4>
                                    <p class="text-gray-400 text-sm">EC-Council | 2021</p>
                                </div>
                            </div>
                            
                            <div class="glass-card p-4 rounded-lg flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                    <i class="ri-verified-badge-line text-primary ri-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-medium">CompTIA Security+</h4>
                                    <p class="text-gray-400 text-sm">CompTIA | 2020</p>
                                </div>
                            </div>
                            
                            <div class="glass-card p-4 rounded-lg flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                    <i class="ri-verified-badge-line text-primary ri-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-medium">AWS Certified Security Specialist</h4>
                                    <p class="text-gray-400 text-sm">Amazon Web Services | 2022</p>
                                </div>
                            </div>
                            
                            <div class="glass-card p-4 rounded-lg flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                    <i class="ri-trophy-line text-primary ri-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-medium">2nd Place - National Cyber Defense Competition</h4>
                                    <p class="text-gray-400 text-sm">CyberSec Alliance | 2021</p>
                                </div>
                            </div>
                            
                            <div class="glass-card p-4 rounded-lg flex items-center">
                                <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                    <i class="ri-bug-line text-primary ri-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-medium">Bug Bounty Hall of Fame</h4>
                                    <p class="text-gray-400 text-sm">HackerOne & Bugcrowd | 2022-2023</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Blog Section -->
    <section id="blog" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="mb-12 text-center">
                <h2 class="text-3xl font-bold mb-2">
                    <span class="text-primary">&lt;</span> Security Logs <span class="text-primary">/&gt;</span>
                </h2>
                <p class="text-gray-400">Insights, tutorials, and threat reports</p>
            </div>
            
            <div class="terminal-window p-6 mb-8">
                <div class="terminal-header mb-4">
                    <div class="terminal-circle bg-red-500"></div>
                    <div class="terminal-circle bg-yellow-500 mx-2"></div>
                    <div class="terminal-circle bg-green-500"></div>
                    <span class="ml-4 text-gray-400 text-sm">search_logs.sh</span>
                </div>
                
                <div class="flex flex-col md:flex-row gap-4">
                    <div class="relative flex-grow">
                        <input type="text" placeholder="Search security logs..." class="w-full bg-[rgba(0,0,0,0.3)] border border-[rgba(0,255,65,0.3)] text-gray-300 px-4 py-3 rounded-lg pl-10">
                        <div class="absolute left-3 top-1/2 transform -translate-y-1/2 text-gray-400">
                            <i class="ri-search-line"></i>
                        </div>
                    </div>
                    
                    <div class="flex gap-2">
                        <div class="relative">
                            <button class="flex items-center justify-between bg-[rgba(0,0,0,0.3)] border border-[rgba(0,255,65,0.3)] text-gray-300 px-4 py-3 rounded-lg w-40 whitespace-nowrap">
                                <span>All Categories</span>
                                <i class="ri-arrow-down-s-line"></i>
                            </button>
                        </div>
                        
                        <div class="relative">
                            <button class="flex items-center justify-between bg-[rgba(0,0,0,0.3)] border border-[rgba(0,255,65,0.3)] text-gray-300 px-4 py-3 rounded-lg w-40 whitespace-nowrap">
                                <span>Latest First</span>
                                <i class="ri-arrow-down-s-line"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Blog Post 1 -->
                <div class="glass-card rounded-lg overflow-hidden">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">Tutorial</span>
                            <span class="text-gray-400 text-sm">2025-04-02</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-3">Bypassing Modern WAF Implementations</h3>
                        <p class="text-gray-300 text-sm mb-4">A deep dive into techniques for bypassing modern Web Application Firewalls, with practical examples and countermeasures.</p>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-gray-400 text-xs flex items-center">
                                <i class="ri-time-line mr-1"></i> 12 min read
                            </span>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                Read More <i class="ri-arrow-right-line ml-1"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 2 -->
                <div class="glass-card rounded-lg overflow-hidden">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">Threat Report</span>
                            <span class="text-gray-400 text-sm">2025-03-18</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-3">Analysis of the ShadowBlade Ransomware</h3>
                        <p class="text-gray-300 text-sm mb-4">Technical breakdown of the emerging ShadowBlade ransomware strain, including IOCs, infection vectors, and mitigation strategies.</p>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-gray-400 text-xs flex items-center">
                                <i class="ri-time-line mr-1"></i> 15 min read
                            </span>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                Read More <i class="ri-arrow-right-line ml-1"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 3 -->
                <div class="glass-card rounded-lg overflow-hidden">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">Guide</span>
                            <span class="text-gray-400 text-sm">2025-02-25</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-3">Building a Home Security Lab</h3>
                        <p class="text-gray-300 text-sm mb-4">Step-by-step guide to setting up a comprehensive cybersecurity lab environment at home using open-source tools and virtualization.</p>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-gray-400 text-xs flex items-center">
                                <i class="ri-time-line mr-1"></i> 18 min read
                            </span>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                Read More <i class="ri-arrow-right-line ml-1"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 4 -->
                <div class="glass-card rounded-lg overflow-hidden">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">Research</span>
                            <span class="text-gray-400 text-sm">2025-02-10</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-3">Exploiting JWT Authentication Flaws</h3>
                        <p class="text-gray-300 text-sm mb-4">In-depth analysis of common JWT implementation vulnerabilities and how to exploit them, with recommendations for secure implementation.</p>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-gray-400 text-xs flex items-center">
                                <i class="ri-time-line mr-1"></i> 14 min read
                            </span>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                Read More <i class="ri-arrow-right-line ml-1"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 5 -->
                <div class="glass-card rounded-lg overflow-hidden">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">Tutorial</span>
                            <span class="text-gray-400 text-sm">2025-01-28</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-3">Advanced OSINT Techniques for Security Professionals</h3>
                        <p class="text-gray-300 text-sm mb-4">Exploring advanced open-source intelligence gathering techniques for security assessments and threat hunting.</p>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-gray-400 text-xs flex items-center">
                                <i class="ri-time-line mr-1"></i> 16 min read
                            </span>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                Read More <i class="ri-arrow-right-line ml-1"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 6 -->
                <div class="glass-card rounded-lg overflow-hidden">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-4">
                            <span class="bg-[rgba(0,255,65,0.1)] text-primary text-xs px-3 py-1 rounded-full border border-[rgba(0,255,65,0.3)]">Opinion</span>
                            <span class="text-gray-400 text-sm">2025-01-15</span>
                        </div>
                        
                        <h3 class="text-xl font-semibold text-white mb-3">The Future of AI in Cybersecurity: Friend or Foe?</h3>
                        <p class="text-gray-300 text-sm mb-4">Examining the dual-edged nature of AI in cybersecurity, from automated defense systems to AI-powered attacks.</p>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-gray-400 text-xs flex items-center">
                                <i class="ri-time-line mr-1"></i> 10 min read
                            </span>
                            <a href="#" class="text-primary hover:text-opacity-80 flex items-center text-sm">
                                Read More <i class="ri-arrow-right-line ml-1"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="bg-transparent border border-primary text-primary px-6 py-3 rounded-button font-medium hover:bg-primary hover:bg-opacity-10 transition-all duration-300 whitespace-nowrap inline-flex items-center">
                    <i class="ri-article-line mr-2"></i> View All Posts
                </a>
            </div>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section id="contact" class="py-20 relative bg-[rgba(0,0,0,0.3)]">
        <div class="container mx-auto px-4">
            <div class="mb-12 text-center">
                <h2 class="text-3xl font-bold mb-2">
                    <span class="text-primary">&lt;</span> Establish Connection <span class="text-primary">/&gt;</span>
                </h2>
                <p class="text-gray-400">Reach out for collaborations or inquiries</p>
            </div>
            
            <div class="flex flex-col md:flex-row gap-8">
                <div class="w-full md:w-1/2">
                    <div class="terminal-window p-6 h-full">
                        <div class="terminal-header mb-4">
                            <div class="terminal-circle bg-red-500"></div>
                            <div class="terminal-circle bg-yellow-500 mx-2"></div>
                            <div class="terminal-circle bg-green-500"></div>
                            <span class="ml-4 text-gray-400 text-sm">contact_form.sh</span>
                        </div>
                        
                        <form class="space-y-6">
                            <div class="flex items-start">
                                <span class="text-primary mr-2 mt-3">~$</span>
                                <div class="flex-grow">
                                    <label for="name" class="block text-gray-300 text-sm mb-2">Name:</label>
                                    <input type="text" id="name" class="w-full bg-[rgba(0,0,0,0.3)] border border-[rgba(0,255,65,0.3)] text-gray-300 px-4 py-3 rounded-lg focus:border-primary">
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <span class="text-primary mr-2 mt-3">~$</span>
                                <div class="flex-grow">
                                    <label for="email" class="block text-gray-300 text-sm mb-2">Email:</label>
                                    <input type="email" id="email" class="w-full bg-[rgba(0,0,0,0.3)] border border-[rgba(0,255,65,0.3)] text-gray-300 px-4 py-3 rounded-lg focus:border-primary">
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <span class="text-primary mr-2 mt-3">~$</span>
                                <div class="flex-grow">
                                    <label for="subject" class="block text-gray-300 text-sm mb-2">Subject:</label>
                                    <input type="text" id="subject" class="w-full bg-[rgba(0,0,0,0.3)] border border-[rgba(0,255,65,0.3)] text-gray-300 px-4 py-3 rounded-lg focus:border-primary">
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <span class="text-primary mr-2 mt-3">~$</span>
                                <div class="flex-grow">
                                    <label for="message" class="block text-gray-300 text-sm mb-2">Message:</label>
                                    <textarea id="message" rows="5" class="w-full bg-[rgba(0,0,0,0.3)] border border-[rgba(0,255,65,0.3)] text-gray-300 px-4 py-3 rounded-lg focus:border-primary"></textarea>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <span class="text-primary mr-2">~$</span>
                                <div class="flex-grow">
                                    <div class="flex items-center">
                                        <input type="checkbox" id="security" class="custom-checkbox mr-3">
                                        <label for="security" class="text-gray-300 text-sm">I'm not a malicious script trying to exploit this form</label>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <span class="text-primary mr-2">~$</span>
                                <button type="submit" class="bg-primary text-black px-6 py-3 rounded-button font-medium hover:bg-opacity-80 transition-all duration-300 whitespace-nowrap flex items-center">
                                    <i class="ri-send-plane-line mr-2"></i> Send Message
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
                
                <div class="w-full md:w-1/2">
                    <div class="terminal-window p-6 h-full">
                        <div class="terminal-header mb-4">
                            <div class="terminal-circle bg-red-500"></div>
                            <div class="terminal-circle bg-yellow-500 mx-2"></div>
                            <div class="terminal-circle bg-green-500"></div>
                            <span class="ml-4 text-gray-400 text-sm">contact_info.sh</span>
                        </div>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <span class="text-primary mr-2">~$</span>
                                <span class="text-gray-300">cat contact_details.txt</span>
                            </div>
                            
                            <div class="space-y-6 pl-6">
                                <div class="flex items-center">
                                    <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                        <i class="ri-mail-line text-primary ri-lg"></i>
                                    </div>
                                    <div>
                                        <h4 class="text-white font-medium">Email</h4>
                                        <a href="mailto:bhargava@securityexpert.com" class="text-primary hover:text-opacity-80">bhargava@securityexpert.com</a>
                                    </div>
                                </div>
                                
                                <div class="flex items-center">
                                    <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                        <i class="ri-map-pin-line text-primary ri-lg"></i>
                                    </div>
                                    <div>
                                        <h4 class="text-white font-medium">Location</h4>
                                        <p class="text-gray-300">Bangalore, India</p>
                                    </div>
                                </div>
                                
                                <div class="flex items-center">
                                    <div class="w-12 h-12 flex items-center justify-center bg-[rgba(0,255,65,0.1)] rounded-full mr-4">
                                        <i class="ri-time-line text-primary ri-lg"></i>
                                    </div>
                                    <div>
                                        <h4 class="text-white font-medium">Response Time</h4>
                                        <p class="text-gray-300">Usually within 24 hours</p>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="flex items-start mt-8">
                                <span class="text-primary mr-2">~$</span>
                                <span class="text-gray-300">ls -la social_profiles/</span>
                            </div>
                            
                            <div class="flex flex-wrap gap-4 pl-6">
                                <a href="#" class="flex items-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] px-4 py-3 rounded-lg transition-all duration-300">
                                    <div class="w-8 h-8 flex items-center justify-center mr-3">
                                        <i class="ri-github-fill text-white ri-lg"></i>
                                    </div>
                                    <span class="text-white"> <a href="https://github.com/barghava/gk-16" class="button" target="_blank">Go to GitHub GitHub</a></span>
                                </a>
                                
                                <a href="#" class="flex items-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] px-4 py-3 rounded-lg transition-all duration-300">
                                    <div class="w-8 h-8 flex items-center justify-center mr-3">
                                        <i class="ri-linkedin-fill text-white ri-lg"></i>
                                    </div>
                                    <span class="text-white">LinkedIn</span>
                                </a>
                                
                                <a href="#" class="flex items-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] px-4 py-3 rounded-lg transition-all duration-300">
                                    <div class="w-8 h-8 flex items-center justify-center mr-3">
                                        <i class="ri-twitter-x-fill text-white ri-lg"></i>
                                    </div>
                                    <span class="text-white">Twitter</span>
                                </a>
                                
                                <a href="#" class="flex items-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] px-4 py-3 rounded-lg transition-all duration-300">
                                    <div class="w-8 h-8 flex items-center justify-center mr-3">
                                        <i class="ri-medium-fill text-white ri-lg"></i>
                                    </div>
                                    <span class="text-white">Medium</span>
                                </a>
                            </div>
                            
                            <div class="mt-8 bg-[rgba(0,0,0,0.3)] p-4 rounded-lg border border-[rgba(255,0,0,0.3)] text-gray-300">
                                <div class="flex items-center mb-2">
                                    <i class="ri-shield-flash-line text-red-500 mr-2"></i>
                                    <span class="text-red-500 font-medium">Security Notice</span>
                                </div>
                                <p class="text-sm">All communications are encrypted using PGP. For sensitive information, please use my public key available on my GitHub profile.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="py-8 bg-[rgba(0,0,0,0.5)] border-t border-[rgba(0,255,65,0.1)]">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <a href="#home" class="text-primary font-['Pacifico'] text-2xl">logo</a>
                    <p class="text-gray-400 text-sm mt-2">CYBER SECURITY</p>
                </div>
                
                <div class="flex flex-wrap justify-center gap-6 mb-4 md:mb-0">
                    <a href="#home" class="text-gray-300 hover:text-primary transition-colors duration-300">Home</a>
                    <a href="#about" class="text-gray-300 hover:text-primary transition-colors duration-300">About</a>
                    <a href="#skills" class="text-gray-300 hover:text-primary transition-colors duration-300">Skills</a>
                    <a href="#projects" class="text-gray-300 hover:text-primary transition-colors duration-300">Projects</a>
                    <a href="#experience" class="text-gray-300 hover:text-primary transition-colors duration-300">Experience</a>
                    <a href="#blog" class="text-gray-300 hover:text-primary transition-colors duration-300">Blog</a>
                    <a href="#contact" class="text-gray-300 hover:text-primary transition-colors duration-300">Contact</a>
                </div>
                
                <div class="flex gap-4">
                    <a href="#" class="w-10 h-10 flex items-center justify-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] rounded-full transition-all duration-300">
                        <i class="ri-github-fill text-white"></i>
                    </a>
                    <a href="#" class="w-10 h-10 flex items-center justify-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] rounded-full transition-all duration-300">
                        <i class="ri-linkedin-fill text-white"></i>
                    </a>
                    <a href="#" class="w-10 h-10 flex items-center justify-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] rounded-full transition-all duration-300">
                        <i class="ri-twitter-x-fill text-white"></i>
                    </a>
                    <a href="#" class="w-10 h-10 flex items-center justify-center bg-[rgba(0,0,0,0.3)] hover:bg-[rgba(0,255,65,0.1)] border border-[rgba(0,255,65,0.3)] rounded-full transition-all duration-300">
                        <i class="ri-medium-fill text-white"></i>
                    </a>
                </div>
            </div>
            
            <div class="mt-8 pt-6 border-t border-[rgba(255,255,255,0.1)] flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm mb-4 md:mb-0">© 2025 Bhargava G K. All rights reserved.</p>
                
                <div class="flex gap-4 text-gray-400 text-sm">
                    <a href="#" class="hover:text-primary transition-colors duration-300">Privacy Policy</a>
                    <span>|</span>
                    <a href="#" class="hover:text-primary transition-colors duration-300">Terms of Service</a>
                </div>
            </div>
        </div>
    </footer>
    
    <!-- Hidden Terminal (Easter Egg) -->
    <div id="hiddenTerminal" class="fixed bottom-0 right-0 w-full md:w-1/2 h-0 overflow-hidden bg-[rgba(0,0,0,0.95)] z-50 transition-all duration-500">
        <div class="terminal-header p-3 flex justify-between items-center border-b border-[rgba(0,255,65,0.3)]">
            <div class="flex items-center">
                <div class="terminal-circle bg-red-500"></div>
                <div class="terminal-circle bg-yellow-500 mx-2"></div>
                <div class="terminal-circle bg-green-500"></div>
                <span class="ml-4 text-gray-400 text-sm">secret_terminal.sh</span>
            </div>
            <button id="closeTerminal" class="text-gray-400 hover:text-white">
                <i class="ri-close-line"></i>
            </button>
        </div>
        
        <div class="p-4 h-full overflow-y-auto terminal-content">
            <div class="mb-4">
                <span class="text-primary">root@secure-system:~#</span> <span class="text-white">Access granted to hidden terminal</span>
            </div>
            <div class="mb-4">
                <span class="text-primary">root@secure-system:~#</span> <span class="text-white">Type 'help' for available commands</span>
            </div>
            <div id="terminalOutput"></div>
            <div class="flex items-center">
                <span class="text-primary mr-2">root@secure-system:~#</span>
                <input type="text" id="terminalInput" class="bg-transparent border-none text-white focus:outline-none flex-grow" autofocus>
            </div>
        </div>
    </div>
    
    <script>
        // Matrix Background Effect
        const canvas = document.getElementById('matrixCanvas');
        const ctx = canvas.getContext('2d');
        
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;
        
        const characters = 'アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホマミムメモヤユヨラリルレロワヲン0123456789';
        const columns = canvas.width / 20;
        const drops = [];
        
        for (let i = 0; i < columns; i++) {
            drops[i] = 1;
        }
        
        function drawMatrix() {
            ctx.fillStyle = 'rgba(12, 12, 12, 0.05)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            ctx.fillStyle = '#00FF41';
            ctx.font = '15px monospace';
            
            for (let i = 0; i < drops.length; i++) {
                const text = characters.charAt(Math.floor(Math.random() * characters.length));
                ctx.fillText(text, i * 20, drops[i] * 20);
                
                if (drops[i] * 20 > canvas.height && Math.random() > 0.975) {
                    drops[i] = 0;
                }
                
                drops[i]++;
            }
        }
        
        setInterval(drawMatrix, 50);
        
        // Typing Animation
        const typingText = document.getElementById('typingText');
        const text = "ACCESS GRANTED";
        let index = 0;
        
        function typeText() {
            if (index < text.length) {
                typingText.textContent += text.charAt(index);
                index++;
                setTimeout(typeText, 100);
            } else {
                setTimeout(() => {
                    typingText.textContent = "";
                    index = 0;
                    typeText();
                }, 3000);
            }
        }
        
        typeText();
        
        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobileMenuButton');
        const mobileMenu = document.getElementById('mobileMenu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Project Filtering
        const filterButtons = document.querySelectorAll('.project-filter-btn');
        const projectItems = document.querySelectorAll('.project-item');
        
        filterButtons.forEach(button => {
            button.addEventListener('click', () => {
                // Remove active class from all buttons
                filterButtons.forEach(btn => {
                    btn.classList.remove('active', 'bg-[rgba(0,255,65,0.1)]', 'text-primary');
                    btn.classList.add('text-gray-300');
                });
                
                // Add active class to clicked button
                button.classList.add('active', 'bg-[rgba(0,255,65,0.1)]', 'text-primary');
                button.classList.remove('text-gray-300');
                
                const filter = button.getAttribute('data-filter');
                
                projectItems.forEach(item => {
                    if (filter === 'all' || item.getAttribute('data-category') === filter) {
                        item.style.display = 'block';
                    } else {
                        item.style.display = 'none';
                    }
                });
            });
        });
        
        // Hidden Terminal Functionality
        const konami = ['ArrowUp', 'ArrowUp', 'ArrowDown', 'ArrowDown', 'ArrowLeft', 'ArrowRight', 'ArrowLeft', 'ArrowRight', 'b', 'a'];
        let konamiIndex = 0;
        
        document.addEventListener('keydown', (e) => {
            if (e.key === konami[konamiIndex]) {
                konamiIndex++;
                
                if (konamiIndex === konami.length) {
                    openTerminal();
                    konamiIndex = 0;
                }
            } else {
                konamiIndex = 0;
            }
        });
        
        const hiddenTerminal = document.getElementById('hiddenTerminal');
        const closeTerminal = document.getElementById('closeTerminal');
        const terminalInput = document.getElementById('terminalInput');
        const terminalOutput = document.getElementById('terminalOutput');
        
        function openTerminal() {
            hiddenTerminal.style.height = '400px';
            setTimeout(() => {
                terminalInput.focus();
            }, 500);
        }
        
        closeTerminal.addEventListener('click', () => {
            hiddenTerminal.style.height = '0';
        });
        
        terminalInput.addEventListener('keydown', (e) => {
            if (e.key === 'Enter') {
                const command = terminalInput.value.trim();
                
                const commandLine = document.createElement('div');
                commandLine.innerHTML = `<span class="text-primary">root@secure-system:~#</span> <span class="text-white">${command}</span>`;
                terminalOutput.appendChild(commandLine);
                
                let response = '';
                
                switch (command.toLowerCase()) {
                    case 'help':
                        response = `
                            <div class="pl-4 mt-2 mb-4">
                                <div class="text-gray-300">Available commands:</div>
                                <div class="text-gray-300 pl-4">- <span class="text-primary">help</span>: Show this help message</div>
                                <div class="text-gray-300 pl-4">- <span class="text-primary">about</span>: Display information about me</div>
                                <div class="text-gray-300 pl-4">- <span class="text-primary">skills</span>: List my technical skills</div>
                                <div class="text-gray-300 pl-4">- <span class="text-primary">contact</span>: Show contact information</div>
                                <div class="text-gray-300 pl-4">- <span class="text-primary">clear</span>: Clear the terminal</div>
                                <div class="text-gray-300 pl-4">- <span class="text-primary">exit</span>: Close the terminal</div>
                            </div>
                        `;
                        break;
                    case 'about':
                        response = `
                            <div class="pl-4 mt-2 mb-4">
                                <div class="text-gray-300">Bhargava G K - Cybersecurity Specialist</div>
                                <div class="text-gray-300 mt-2">Passionate about identifying and mitigating security vulnerabilities. Specialized in penetration testing, network security, and ethical hacking.</div>
                            </div>
                        `;
                        break;
                    case 'skills':
                        response = `
                            <div class="pl-4 mt-2 mb-4">
                                <div class="text-gray-300">Technical Skills:</div>
                                <div class="text-gray-300 pl-4">- Penetration Testing</div>
                                <div class="text-gray-300 pl-4">- Network Security</div>
                                <div class="text-gray-300 pl-4">- Web Application Security</div>
                                <div class="text-gray-300 pl-4">- Malware Analysis</div>
                                <div class="text-gray-300 pl-4">- Digital Forensics</div>
                                <div class="text-gray-300 pl-4">- Python, Bash, C/C++</div>
                            </div>
                        `;
                        break;
                    case 'contact':
                        response = `
                            <div class="pl-4 mt-2 mb-4">
                                <div class="text-gray-300">Contact Information:</div>
                                <div class="text-gray-300 pl-4">- Email: bhargava@securityexpert.com</div>
                                <div class="text-gray-300 pl-4">- Location: Bangalore, India</div>
                                <div class="text-gray-300 pl-4">- GitHub: github.com/bhargavagk</div>
                                <div class="text-gray-300 pl-4">- LinkedIn: linkedin.com/in/bhargavagk</div>
                            </div>
                        `;
                        break;
                    case 'clear':
                        terminalOutput.innerHTML = '';
                        break;
                    case 'exit':
                        hiddenTerminal.style.height = '0';
                        break;
                    default:
                        response = `<div class="pl-4 mt-2 mb-4 text-red-500">Command not found: ${command}. Type 'help' for available commands.</div>`;
                }
                
                if (command.toLowerCase() !== 'clear') {
                    const responseElement = document.createElement('div');
                    responseElement.innerHTML = response;
                    terminalOutput.appendChild(responseElement);
                }
                
                terminalInput.value = '';
                
                // Scroll to bottom
                terminalOutput.scrollTop = terminalOutput.scrollHeight;
            }
        });
        
        // Animate progress bars on scroll
        const progressBars = document.querySelectorAll('.progress-fill');
        
        function animateProgressBars() {
            progressBars.forEach(bar => {
                const rect = bar.getBoundingClientRect();
                const isVisible = (rect.top <= window.innerHeight * 0.8);
                
                if (isVisible) {
                    const width = bar.parentElement.previousElementSibling.querySelector('.text-primary').textContent;
                    bar.style.width = width;
                } else {
                    bar.style.width = '0';
                }
            });
        }
        
        window.addEventListener('scroll', animateProgressBars);
        window.addEventListener('load', animateProgressBars);
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });
        
        // Resize canvas on window resize
        window.addEventListener('resize', () => {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });
    </script>
</body>
</html>
