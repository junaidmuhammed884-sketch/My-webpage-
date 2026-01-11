<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium Resume Optimization Service - Land Your Dream Job</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/daisyui@4.4.19/dist/full.min.css" rel="stylesheet" type="text/css" />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap');
        
        * {
            font-family: 'Inter', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 25%, #16213e 50%, #0f3460 75%, #533483 100%);
        }
        
        .glass-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .glass-card-dark {
            background: rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .animate-float {
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        
        .animate-pulse-slow {
            animation: pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        
        .hover-lift {
            transition: all 0.3s ease;
        }
        
        .hover-lift:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
        }
        
        .scroll-reveal {
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.8s ease;
        }
        
        .scroll-reveal.revealed {
            opacity: 1;
            transform: translateY(0);
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .btn-glow {
            box-shadow: 0 0 20px rgba(102, 126, 234, 0.5);
            transition: all 0.3s ease;
        }
        
        .btn-glow:hover {
            box-shadow: 0 0 30px rgba(102, 126, 234, 0.8);
            transform: translateY(-2px);
        }
        
        .particles {
            position: absolute;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: 0;
        }
        
        .particle {
            position: absolute;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            animation: particle-float 15s infinite linear;
        }
        
        @keyframes particle-float {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) rotate(360deg);
                opacity: 0;
            }
        }
        
        .copy-btn {
            transition: all 0.2s ease;
        }
        
        .copy-btn:hover {
            background: rgba(102, 126, 234, 0.2);
        }
        
        .copy-success {
            background: rgba(34, 197, 94, 0.2) !important;
            color: #22c55e !important;
        }
    </style>
</head>
<body class="gradient-bg text-white overflow-x-hidden">
    <!-- Animated Background Particles -->
    <div class="particles fixed inset-0 pointer-events-none">
        <div class="particle" style="left: 10%; width: 4px; height: 4px; animation-delay: 0s;"></div>
        <div class="particle" style="left: 20%; width: 6px; height: 6px; animation-delay: 2s;"></div>
        <div class="particle" style="left: 30%; width: 3px; height: 3px; animation-delay: 4s;"></div>
        <div class="particle" style="left: 40%; width: 5px; height: 5px; animation-delay: 6s;"></div>
        <div class="particle" style="left: 50%; width: 4px; height: 4px; animation-delay: 8s;"></div>
        <div class="particle" style="left: 60%; width: 6px; height: 6px; animation-delay: 10s;"></div>
        <div class="particle" style="left: 70%; width: 3px; height: 3px; animation-delay: 12s;"></div>
        <div class="particle" style="left: 80%; width: 5px; height: 5px; animation-delay: 14s;"></div>
        <div class="particle" style="left: 90%; width: 4px; height: 4px; animation-delay: 16s;"></div>
    </div>

    <!-- Scarcity Alert Bar -->
    <div class="bg-red-600 text-white text-center py-3 px-4 relative z-50">
        <div class="flex items-center justify-center space-x-2">
            <i class="fas fa-exclamation-triangle animate-pulse"></i>
            <span class="font-semibold">Limited availability — Only 5 clients accepted this week</span>
            <i class="fas fa-exclamation-triangle animate-pulse"></i>
        </div>
    </div>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center relative px-4 py-20">
        <div class="container mx-auto text-center relative z-10">
            <div class="scroll-reveal">
                <h1 class="text-5xl md:text-7xl font-black mb-6 leading-tight">
                    Land Your Dream Job in 
                    <span class="gradient-text">7 Days</span>
                    <br>— Or Your Money Back
                </h1>
                <p class="text-xl md:text-2xl mb-8 text-gray-300 max-w-3xl mx-auto leading-relaxed">
                    ATS-optimized resumes that beat hiring bots and grab recruiters' attention in seconds.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
                    <button onclick="scrollToSection('booking')" class="btn btn-primary btn-lg px-8 py-4 text-lg font-bold btn-glow">
                        <i class="fas fa-calendar-check mr-2"></i>
                        Book Free Resume Review
                    </button>
                    <button onclick="scrollToSection('packages')" class="btn btn-outline btn-lg px-8 py-4 text-lg font-bold text-white border-white hover:bg-white hover:text-gray-900">
                        <i class="fas fa-eye mr-2"></i>
                        View Packages
                    </button>
                </div>
            </div>
            <div class="mt-16 animate-float">
                <div class="glass-card rounded-2xl p-8 max-w-2xl mx-auto">
                    <div class="flex items-center justify-center space-x-8">
                        <div class="text-center">
                            <div class="text-3xl font-bold text-green-400">97%</div>
                            <div class="text-sm text-gray-300">Success Rate</div>
                        </div>
                        <div class="text-center">
                            <div class="text-3xl font-bold text-blue-400">3-7</div>
                            <div class="text-sm text-gray-300">Days to Interviews</div>
                        </div>
                        <div class="text-center">
                            <div class="text-3xl font-bold text-purple-400">500+</div>
                            <div class="text-sm text-gray-300">Happy Clients</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Problem Section -->
    <section class="py-20 px-4 relative">
        <div class="container mx-auto">
            <div class="text-center mb-16 scroll-reveal">
                <h2 class="text-4xl md:text-5xl font-bold mb-6">Why Qualified Candidates Get <span class="text-red-400">Ignored</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    The modern hiring process is broken. Here's what's standing between you and your dream job.
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <div class="glass-card-dark rounded-2xl p-8 text-center hover-lift scroll-reveal">
                    <div class="text-5xl mb-6 text-red-400">
                        <i class="fas fa-robot"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">ATS Systems Reject You</h3>
                    <p class="text-gray-300">
                        75% of resumes never reach human eyes. Applicant Tracking Systems filter out qualified candidates due to poor formatting and missing keywords.
                    </p>
                </div>
                
                <div class="glass-card-dark rounded-2xl p-8 text-center hover-lift scroll-reveal">
                    <div class="text-5xl mb-6 text-yellow-400">
                        <i class="fas fa-stopwatch"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">6-Second Scan Rule</h3>
                    <p class="text-gray-300">
                        Recruiters spend only 6 seconds scanning your resume. If your achievements and value aren't immediately clear, you're out.
                    </p>
                </div>
                
                <div class="glass-card-dark rounded-2xl p-8 text-center hover-lift scroll-reveal">
                    <div class="text-5xl mb-6 text-blue-400">
                        <i class="fas fa-search-minus"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">Missing Impact Metrics</h3>
                    <p class="text-gray-300">
                        Generic job descriptions don't sell your value. Without quantified achievements and industry keywords, you blend into the crowd.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Packages Section -->
    <section id="packages" class="py-20 px-4 relative">
        <div class="container mx-auto">
            <div class="text-center mb-16 scroll-reveal">
                <h2 class="text-4xl md:text-5xl font-bold mb-6">Choose Your <span class="gradient-text">Success Package</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Professional resume optimization packages designed to get you noticed and hired faster.
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <!-- Basic Package -->
                <div class="glass-card rounded-2xl p-8 hover-lift scroll-reveal">
                    <div class="text-center mb-8">
                        <h3 class="text-2xl font-bold mb-2">BASIC</h3>
                        <div class="text-4xl font-black mb-4">$97</div>
                        <p class="text-gray-300">Perfect for job seekers ready to optimize their resume</p>
                    </div>
                    
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>ATS-optimized resume rewrite</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>Achievement-focused bullet points with metrics</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>Keyword optimization for target role</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>24–48 hour delivery</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>1 revision</span>
                        </li>
                    </ul>
                    
                    <button onclick="scrollToSection('payment')" class="btn btn-outline w-full btn-lg font-bold text-white border-white hover:bg-white hover:text-gray-900">
                        Select Package
                    </button>
                </div>
                
                <!-- Pro Package -->
                <div class="glass-card rounded-2xl p-8 hover-lift scroll-reveal relative border-2 border-purple-500">
                    <div class="absolute -top-4 left-1/2 transform -translate-x-1/2">
                        <span class="bg-purple-500 text-white px-4 py-2 rounded-full text-sm font-bold">
                            ⭐ MOST POPULAR
                        </span>
                    </div>
                    
                    <div class="text-center mb-8 mt-4">
                        <h3 class="text-2xl font-bold mb-2">PRO</h3>
                        <div class="text-4xl font-black mb-4 text-purple-400">$197</div>
                        <p class="text-gray-300">Complete career package for serious job seekers</p>
                    </div>
                    
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>Everything in Basic</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>Custom cover letter template</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>LinkedIn profile optimization</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>2 revisions</span>
                        </li>
                    </ul>
                    
                    <button onclick="scrollToSection('payment')" class="btn btn-primary w-full btn-lg font-bold btn-glow">
                        Select Package
                    </button>
                </div>
                
                <!-- Premium Package -->
                <div class="glass-card rounded-2xl p-8 hover-lift scroll-reveal">
                    <div class="text-center mb-8">
                        <h3 class="text-2xl font-bold mb-2">PREMIUM</h3>
                        <div class="text-4xl font-black mb-4 text-yellow-400">$297</div>
                        <p class="text-gray-300">Ultimate career transformation package</p>
                    </div>
                    
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>Everything in Pro</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>Interview preparation guide</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>30-day unlimited revisions</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-400 mr-3"></i>
                            <span>Priority 24-hour delivery</span>
                        </li>
                    </ul>
                    
                    <button onclick="scrollToSection('payment')" class="btn btn-outline w-full btn-lg font-bold text-white border-white hover:bg-white hover:text-gray-900">
                        Select Package
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Results Section -->
    <section class="py-20 px-4 relative">
        <div class="container mx-auto">
            <div class="text-center mb-16 scroll-reveal">
                <h2 class="text-4xl md:text-5xl font-bold mb-6">Real Results, Real <span class="text-green-400">Interviews</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    See how our clients transformed their job search and landed their dream positions.
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <div class="glass-card-dark rounded-2xl p-8 hover-lift scroll-reveal">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-user text-white"></i>
                        </div>
                        <div>
                            <h4 class="font-bold">Marketing Manager</h4>
                            <p class="text-sm text-gray-400">Tech Industry</p>
                        </div>
                    </div>
                    <div class="mb-4">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-red-400 font-bold">Before:</span>
                            <span>0 responses</span>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-green-400 font-bold">After:</span>
                            <span>4 interviews in 8 days</span>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">
                        "I was applying for months with no luck. After the resume rewrite, I got 4 interview requests in just 8 days!"
                    </p>
                </div>
                
                <div class="glass-card-dark rounded-2xl p-8 hover-lift scroll-reveal">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-gradient-to-r from-green-500 to-blue-600 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-code text-white"></i>
                        </div>
                        <div>
                            <h4 class="font-bold">Software Engineer</h4>
                            <p class="text-sm text-gray-400">Fintech</p>
                        </div>
                    </div>
                    <div class="mb-4">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-red-400 font-bold">Before:</span>
                            <span>2 months searching</span>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-green-400 font-bold">After:</span>
                            <span>3 offers in 3 weeks</span>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">
                        "The ATS optimization was a game-changer. I went from being ignored to having multiple companies compete for me."
                    </p>
                </div>
                
                <div class="glass-card-dark rounded-2xl p-8 hover-lift scroll-reveal">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-gradient-to-r from-purple-500 to-pink-600 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-chart-line text-white"></i>
                        </div>
                        <div>
                            <h4 class="font-bold">Sales Professional</h4>
                            <p class="text-sm text-gray-400">SaaS</p>
                        </div>
                    </div>
                    <div class="mb-4">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-red-400 font-bold">Before:</span>
                            <span>50 applications, no callbacks</span>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-green-400 font-bold">After:</span>
                            <span>Callbacks in 5 days</span>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">
                        "The metrics-focused approach made all the difference. Recruiters finally saw my value and impact."
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Guarantee Section -->
    <section class="py-20 px-4 relative">
        <div class="container mx-auto">
            <div class="glass-card rounded-2xl p-12 text-center max-w-4xl mx-auto scroll-reveal border-2 border-green-500">
                <div class="text-6xl mb-6 text-green-400">
                    <i class="fas fa-shield-alt"></i>
                </div>
                <h2 class="text-3xl md:text-4xl font-bold mb-6">Our Iron-Clad Guarantee</h2>
                <p class="text-xl md:text-2xl mb-8 text-gray-300 leading-relaxed">
                    Get <span class="text-green-400 font-bold">3+ interview requests in 14 days</span> or I'll revise your resume for free until you do.
                </p>
                <div class="bg-green-500/20 rounded-xl p-6 border border-green-500/30">
                    <p class="text-lg text-green-300">
                        <i class="fas fa-check-circle mr-2"></i>
                        No questions asked. No fine print. Just results.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="py-20 px-4 relative">
        <div class="container mx-auto">
            <div class="text-center mb-16 scroll-reveal">
                <h2 class="text-4xl md:text-5xl font-bold mb-6">How It <span class="gradient-text">Works</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Simple, streamlined process to transform your career prospects in days, not months.
                </p>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <div class="relative">
                    <!-- Timeline Line -->
                    <div class="absolute left-1/2 transform -translate-x-1/2 w-1 h-full bg-gradient-to-b from-blue-500 to-purple-600 rounded-full"></div>
                    
                    <!-- Step 1 -->
                    <div class="flex items-center mb-16 scroll-reveal">
                        <div class="w-1/2 pr-8 text-right">
                            <div class="glass-card-dark rounded-2xl p-6">
                                <h3 class="text-2xl font-bold mb-4">1. Fill Out Intake Form</h3>
                                <p class="text-gray-300">Quick 5-minute form about your target role, experience, and career goals.</p>
                            </div>
                        </div>
                        <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full flex items-center justify-center relative z-10 flex-shrink-0">
                            <i class="fas fa-edit text-white text-xl"></i>
                        </div>
                        <div class="w-1/2 pl-8"></div>
                    </div>
                    
                    <!-- Step 2 -->
                    <div class="flex items-center mb-16 scroll-reveal">
                        <div class="w-1/2 pr-8"></div>
                        <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-pink-600 rounded-full flex items-center justify-center relative z-10 flex-shrink-0">
                            <i class="fas fa-search text-white text-xl"></i>
                        </div>
                        <div class="w-1/2 pl-8">
                            <div class="glass-card-dark rounded-2xl p-6">
                                <h3 class="text-2xl font-bold mb-4">2. Expert Analysis</h3>
                                <p class="text-gray-300">Professional resume and job market analysis within 24 hours.</p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Step 3 -->
                    <div class="flex items-center mb-16 scroll-reveal">
                        <div class="w-1/2 pr-8 text-right">
                            <div class="glass-card-dark rounded-2xl p-6">
                                <h3 class="text-2xl font-bold mb-4">3. Receive Optimized Documents</h3>
                                <p class="text-gray-300">Get your ATS-optimized resume, cover letter, and LinkedIn profile.</p>
                            </div>
                        </div>
                        <div class="w-16 h-16 bg-gradient-to-r from-green-500 to-blue-600 rounded-full flex items-center justify-center relative z-10 flex-shrink-0">
                            <i class="fas fa-file-alt text-white text-xl"></i>
                        </div>
                        <div class="w-1/2 pl-8"></div>
                    </div>
                    
                    <!-- Step 4 -->
                    <div class="flex items-center scroll-reveal">
                        <div class="w-1/2 pr-8"></div>
                        <div class="w-16 h-16 bg-gradient-to-r from-yellow-500 to-red-600 rounded-full flex items-center justify-center relative z-10 flex-shrink-0">
                            <i class="fas fa-rocket text-white text-xl"></i>
                        </div>
                        <div class="w-1/2 pl-8">
                            <div class="glass-card-dark rounded-2xl p-6">
                                <h3 class="text-2xl font-bold mb-4">4. Start Getting Interviews</h3>
                                <p class="text-gray-300">Watch the interview requests roll in as recruiters notice your optimized profile.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Payment Section -->
    <section id="payment" class="py-20 px-4 relative">
        <div class="container mx-auto">
            <div class="text-center mb-16 scroll-reveal">
                <h2 class="text-4xl md:text-5xl font-bold mb-6">Secure Payment via <span class="text-green-400">Bank Transfer</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Choose your preferred currency and complete your payment securely.
                </p>
            </div>
            
            <div class="max-w-4xl mx-auto scroll-reveal">
                <!-- Currency Tabs -->
                <div class="tabs tabs-boxed justify-center mb-8 bg-transparent">
                    <a class="tab tab-active" onclick="showCurrency('usd')" id="usd-tab">USD</a>
                    <a class="tab" onclick="showCurrency('eur')" id="eur-tab">EUR</a>
                    <a class="tab" onclick="showCurrency('gbp')" id="gbp-tab">GBP</a>
                </div>
                
                <!-- USD Payment Details -->
                <div id="usd-details" class="currency-details glass-card rounded-2xl p-8">
                    <h3 class="text-2xl font-bold mb-6 text-center">USD Payment Details</h3>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div class="space-y-4">
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Account Name:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="usd-name">junaid muhammad</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('usd-name', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Account Number:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="usd-account">219949223563</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('usd-account', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Routing:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="usd-routing">101019644</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('usd-routing', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="space-y-4">
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Account Type:</span>
                                <span>Checking</span>
                            </div>
                            <div class="p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Bank Address:</span>
                                <p class="mt-2 text-sm">1801 Main St., Kansas City, MO 64108</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- EUR Payment Details -->
                <div id="eur-details" class="currency-details glass-card rounded-2xl p-8 hidden">
                    <h3 class="text-2xl font-bold mb-6 text-center">EUR Payment Details</h3>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div class="space-y-4">
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Account Name:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="eur-name">junaid muhammad</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('eur-name', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Account Number:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="eur-account">40719605</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('eur-account', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Sort Code:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="eur-sort">041307</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('eur-sort', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Swift Code:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="eur-swift">CLJUGB21XXX</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('eur-swift', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="space-y-4">
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">IBAN:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="eur-iban">GB77CLJU04130740719605</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('eur-iban', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Bank:</span>
                                <p class="mt-2 text-sm">Clear Junction Limited</p>
                            </div>
                            <div class="p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Bank Address:</span>
                                <p class="mt-2 text-sm">4th Floor Imperial House, 15 Kingsway, London, WC2B 6UN</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- GBP Payment Details -->
                <div id="gbp-details" class="currency-details glass-card rounded-2xl p-8 hidden">
                    <h3 class="text-2xl font-bold mb-6 text-center">GBP Payment Details</h3>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div class="space-y-4">
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Account Name:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="gbp-name">junaid muhammad</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('gbp-name', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Account Number:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="gbp-account">40719605</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('gbp-account', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Sort Code:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="gbp-sort">041307</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('gbp-sort', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Swift Code:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="gbp-swift">CLJUGB21XXX</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('gbp-swift', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="space-y-4">
                            <div class="flex justify-between items-center p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">IBAN:</span>
                                <div class="flex items-center space-x-2">
                                    <span id="gbp-iban">GB77CLJU04130740719605</span>
                                    <button class="copy-btn p-2 rounded" onclick="copyToClipboard('gbp-iban', this)">
                                        <i class="fas fa-copy"></i>
                                    </button>
                                </div>
                            </div>
                            <div class="p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Bank:</span>
                                <p class="mt-2 text-sm">Clear Junction Limited</p>
                            </div>
                            <div class="p-4 bg-gray-800/50 rounded-lg">
                                <span class="font-semibold">Bank Address:</span>
                                <p class="mt-2 text-sm">4th Floor Imperial House, 15 Kingsway, London, WC2B 6UN</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Payment Note -->
                <div class="mt-8 p-6 bg-blue-500/20 rounded-xl border border-blue-500/30 text-center">
                    <p class="text-lg">
                        <i class="fas fa-info-circle mr-2"></i>
                        After payment, send proof via Calendly or Reddit DM.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Booking Section -->
    <section id="booking" class="py-20 px-4 relative">
        <div class="container mx-auto">
            <div class="text-center mb-16 scroll-reveal">
                <h2 class="text-4xl md:text-5xl font-bold mb-6">Ready to <span class="gradient-text">Start?</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Book your free consultation or get in touch to begin your career transformation.
                </p>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <div class="grid md:grid-cols-2 gap-8">
                    <div class="glass-card rounded-2xl p-8 text-center hover-lift scroll-reveal">
                        <div class="text-5xl mb-6 text-blue-400">
                            <i class="fas fa-calendar-alt"></i>
                        </div>
                        <h3 class="text-2xl font-bold mb-4">Schedule Free Consultation</h3>
                        <p class="text-gray-300 mb-6">
                            Book a 30-minute call to discuss your career goals and how we can help you land your dream job.
                        </p>
                        <a href="https://calendly.com/junaidmuhammed884/30min" target="_blank" class="btn btn-primary btn-lg w-full font-bold btn-glow">
                            <i class="fas fa-calendar-check mr-2"></i>
                            Book on Calendly
                        </a>
                    </div>
                    
                    <div class="glass-card rounded-2xl p-8 text-center hover-lift scroll-reveal">
                        <div class="text-5xl mb-6 text-orange-400">
                            <i class="fab fa-reddit"></i>
                        </div>
                        <h3 class="text-2xl font-bold mb-4">Contact via Reddit</h3>
                        <p class="text-gray-300 mb-6">
                            Prefer to chat first? Send me a direct message on Reddit to discuss your needs and get started.
                        </p>
                        <a href="https://www.reddit.com/u/ArmadilloAble8805/s/JLhU3xBU32" target="_blank" class="btn btn-outline btn-lg w-full font-bold text-white border-white hover:bg-white hover:text-gray-900">
                            <i class="fab fa-reddit mr-2"></i>
                            Message on Reddit
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 px-4 border-t border-gray-800">
        <div class="container mx-auto text-center">
            <div class="mb-8">
                <h3 class="text-2xl font-bold mb-4">Transform Your Career Today</h3>
                <p class="text-gray-400 max-w-2xl mx-auto">
                    Professional resume optimization services designed to get you noticed, interviewed, and hired faster. Your dream job is just one optimized resume away.
                </p>
            </div>
            
            <div class="flex flex-col md:flex-row justify-center items-center space-y-4 md:space-y-0 md:space-x-8 mb-8">
                <a href="https://calendly.com/junaidmuhammed884/30min" target="_blank" class="text-blue-400 hover:text-blue-300 transition-colors">
                    <i class="fas fa-calendar mr-2"></i>
                    Schedule Consultation
                </a>
                <a href="https://www.reddit.com/u/ArmadilloAble8805/s/JLhU3xBU32" target="_blank" class="text-orange-400 hover:text-orange-300 transition-colors">
                    <i class="fab fa-reddit mr-2"></i>
                    Reddit Contact
                </a>
            </div>
            
            <div class="text-gray-500 text-sm">
                <p>&copy; 2024 Professional Resume Optimization Service. All rights reserved.</p>
                <p class="mt-2">Helping professionals land their dream jobs since 2020.</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({
                behavior: 'smooth'
            });
        }

        // Currency tab switching
        function showCurrency(currency) {
            // Hide all currency details
            document.querySelectorAll('.currency-details').forEach(el => {
                el.classList.add('hidden');
            });
            
            // Remove active class from all tabs
            document.querySelectorAll('.tab').forEach(el => {
                el.classList.remove('tab-active');
            });
            
            // Show selected currency details
            document.getElementById(currency + '-details').classList.remove('hidden');
            
            // Add active class to selected tab
            document.getElementById(currency + '-tab').classList.add('tab-active');
        }

        // Copy to clipboard functionality
        function copyToClipboard(elementId, button) {
            const text = document.getElementById(elementId).textContent;
            navigator.clipboard.writeText(text).then(function() {
                // Change button appearance to show success
                const icon = button.querySelector('i');
                const originalClass = icon.className;
                
                button.classList.add('copy-success');
                icon.className = 'fas fa-check';
                
                setTimeout(() => {
                    button.classList.remove('copy-success');
                    icon.className = originalClass;
                }, 2000);
            });
        }

        // Scroll reveal animation
        function revealOnScroll() {
            const reveals = document.querySelectorAll('.scroll-reveal');
            
            reveals.forEach(element => {
                const windowHeight = window.innerHeight;
                const elementTop = element.getBoundingClientRect().top;
                const elementVisible = 150;
                
                if (elementTop < windowHeight - elementVisible) {
                    element.classList.add('revealed');
                }
            });
        }

        // Initialize scroll reveal
        window.addEventListener('scroll', revealOnScroll);
        window.addEventListener('load', revealOnScroll);

        // Smooth scroll for all internal links
        document.addEventListener('DOMContentLoaded', function() {
            // Initial reveal check
            revealOnScroll();
            
            // Add smooth scrolling to all buttons that scroll to sections
            document.querySelectorAll('button[onclick*="scrollToSection"]').forEach(button => {
                button.addEventListener('click', function(e) {
                    e.preventDefault();
                    const sectionId = this.getAttribute('onclick').match(/'([^']+)'/)[1];
                    scrollToSection(sectionId);
                });
            });
        });

        // Add some interactive hover effects
        document.addEventListener('DOMContentLoaded', function() {
            // Add hover effects to cards
            const cards = document.querySelectorAll('.hover-lift');
            cards.forEach(card => {
                card.addEventListener('mouseenter', function() {
                    this.style.transform = 'translateY(-10px)';
                });
                
                card.addEventListener('mouseleave', function() {
                    this.style.transform = 'translateY(0)';
                });
            });
        });
    </script>
</body>
</html>
