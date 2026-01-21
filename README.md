<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Batuhan OĞUZ - Strategic Sales Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #f8fafc; }
        .gradient-bg { background: linear-gradient(135deg, #1e293b 0%, #334155 100%); }
        .card-hover:hover { transform: translateY(-5px); transition: all 0.3s ease; }
    </style>
</head>
<body class="text-slate-800">

    <!-- Hero Section -->
    <header class="gradient-bg text-white py-16 px-6 text-center shadow-2xl">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-5xl font-extrabold mb-4 tracking-tight">Batuhan OĞUZ</h1>
            <p class="text-xl text-blue-300 font-medium mb-8 uppercase tracking-widest">Strategic Sales Specialist | Market Expansion Architect</p>
            <div class="flex flex-wrap justify-center gap-6 text-sm">
                <span><i class="fas fa-envelope mr-2"></i>batuoguz031@gmail.com</span>
                <span><i class="fas fa-phone mr-2"></i>531-101-2077</span>
                <span><i class="fas fa-map-marker-alt mr-2"></i>Türkiye & Europe</span>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-6 py-12">
        
        <!-- Executive Summary & Growth Chart -->
        <section class="grid md:grid-cols-2 gap-12 mb-20 items-center">
            <div>
                <h2 class="text-3xl font-bold mb-6 text-slate-900 border-l-4 border-blue-600 pl-4">Visionary Sales Approach</h2>
                <p class="text-lg text-slate-600 leading-relaxed mb-6">
                    I possess the **entrepreneurial grit, data analytics (SQL/SAP),** and **international negotiation power** required to dominate the Turkish market in the industrial wood sector. Having doubled sales at Oakie.be through precision strategy, I am ready to scale your division to an industry-leading position.
                </p>
                <div class="bg-white p-6 rounded-xl shadow-lg border border-slate-100">
                    <h3 class="font-bold mb-4 text-blue-800"><i class="fas fa-chart-line mr-2"></i>Oakie.be Sales Growth Metric</h3>
                    <canvas id="growthChart" height="200"></canvas>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-4">
                <div class="bg-blue-600 text-white p-6 rounded-2xl shadow-lg card-hover">
                    <div class="text-4xl font-bold mb-2">200%</div>
                    <div class="text-sm opacity-80 font-medium">Sales Growth Achievement</div>
                </div>
                <div class="bg-slate-800 text-white p-6 rounded-2xl shadow-lg card-hover">
                    <div class="text-4xl font-bold mb-2">15+</div>
                    <div class="text-sm opacity-80 font-medium">International Alliances</div>
                </div>
                <div class="bg-slate-100 p-6 rounded-2xl border border-slate-200 card-hover">
                    <div class="text-3xl font-bold text-slate-800 mb-2">6 Countries</div>
                    <div class="text-sm text-slate-500 font-medium">Operational Management</div>
                </div>
                <div class="bg-slate-100 p-6 rounded-2xl border border-slate-200 card-hover">
                    <div class="text-3xl font-bold text-slate-800 mb-2">SAP/SQL</div>
                    <div class="text-sm text-slate-500 font-medium">Data-Driven Sales</div>
                </div>
            </div>
        </section>

        <!-- Skill Matrix -->
        <section class="mb-20">
            <h2 class="text-3xl font-bold mb-10 text-center">Competency Matrix</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Strategic -->
                <div class="bg-white p-8 rounded-2xl shadow-md border-t-4 border-blue-500">
                    <i class="fas fa-bullseye text-3xl text-blue-500 mb-4"></i>
                    <h3 class="text-xl font-bold mb-4">Strategic Growth</h3>
                    <ul class="space-y-2 text-slate-600">
                        <li><i class="fas fa-check text-green-500 mr-2"></i>Market Entry Strategy</li>
                        <li><i class="fas fa-check text-green-500 mr-2"></i>B2B Portfolio Management</li>
                        <li><i class="fas fa-check text-green-500 mr-2"></i>High-Stakes Negotiations</li>
                    </ul>
                </div>
                <!-- Technical -->
                <div class="bg-white p-8 rounded-2xl shadow-md border-t-4 border-slate-800">
                    <i class="fas fa-database text-3xl text-slate-800 mb-4"></i>
                    <h3 class="text-xl font-bold mb-4">Technical Analysis</h3>
                    <ul class="space-y-2 text-slate-600">
                        <li><i class="fas fa-check text-green-500 mr-2"></i>SAP S/4HANA & CRM</li>
                        <li><i class="fas fa-check text-green-500 mr-2"></i>SQL Data Mining</li>
                        <li><i class="fas fa-check text-green-500 mr-2"></i>Sales Forecasting</li>
                    </ul>
                </div>
                <!-- Operational -->
                <div class="bg-white p-8 rounded-2xl shadow-md border-t-4 border-blue-300">
                    <i class="fas fa-globe text-3xl text-blue-300 mb-4"></i>
                    <h3 class="text-xl font-bold mb-4">Operational Excellence</h3>
                    <ul class="space-y-2 text-slate-600">
                        <li><i class="fas fa-check text-green-500 mr-2"></i>Crisis & Logistics Mgmt</li>
                        <li><i class="fas fa-check text-green-500 mr-2"></i>EU Stakeholder Relations</li>
                        <li><i class="fas fa-check text-green-500 mr-2"></i>Cross-Cultural Agility</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Experience Timeline -->
        <section class="mb-20">
            <h2 class="text-3xl font-bold mb-10 text-center text-slate-900">Professional Milestones</h2>
            <div class="space-y-8">
                <div class="flex gap-6">
                    <div class="flex-none w-24 text-right font-bold text-blue-600 pt-2">Growth</div>
                    <div class="border-l-2 border-slate-200 pl-8 pb-8 relative">
                        <div class="absolute w-4 h-4 bg-blue-600 rounded-full -left-[9px] top-3"></div>
                        <h3 class="text-xl font-bold">Founder & Sales Director | Oakie.be</h3>
                        <p class="text-slate-600 mt-2 italic">Spearheaded luxury brand management and direct sales strategies, resulting in 200% revenue growth.</p>
                    </div>
                </div>
                <div class="flex gap-6">
                    <div class="flex-none w-24 text-right font-bold text-slate-400 pt-2">Global</div>
                    <div class="border-l-2 border-slate-200 pl-8 pb-8 relative">
                        <div class="absolute w-4 h-4 bg-slate-400 rounded-full -left-[9px] top-3"></div>
                        <h3 class="text-xl font-bold">Partnership Coordinator | European Union</h3>
                        <p class="text-slate-600 mt-2 italic">Orchestrated strategic alliances with 15+ international organizations across 6 countries.</p>
                    </div>
                </div>
                <div class="flex gap-6">
                    <div class="flex-none w-24 text-right font-bold text-slate-400 pt-2">Rigor</div>
                    <div class="border-l-2 border-slate-200 pl-8 pb-8 relative">
                        <div class="absolute w-4 h-4 bg-slate-400 rounded-full -left-[9px] top-3"></div>
                        <h3 class="text-xl font-bold">Operations Specialist | Istanbul Airport (IGA)</h3>
                        <p class="text-slate-600 mt-2 italic">Managed end-to-end resolution for mission-critical logistics and stakeholder issues under zero-failure constraints.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Türkiye Strategy -->
        <section class="bg-slate-900 text-white p-12 rounded-3xl mb-20">
            <h2 class="text-3xl font-bold mb-8 text-center text-blue-400">My Türkiye Market Expansion Roadmap</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="text-4xl font-bold mb-2 text-blue-300">01</div>
                    <h4 class="font-bold text-lg mb-2">Segmentation</h4>
                    <p class="text-sm text-slate-400">Leveraging SQL to identify high-potential furniture and construction manufacturers in the Turkish interior.</p>
                </div>
                <div class="text-center">
                    <div class="text-4xl font-bold mb-2 text-blue-300">02</div>
                    <h4 class="font-bold text-lg mb-2">Negotiation</h4>
                    <p class="text-sm text-slate-400">Blending European corporate standards with local market nuances for a high-conversion hybrid sales pitch.</p>
                </div>
                <div class="text-center">
                    <div class="text-4xl font-bold mb-2 text-blue-300">03</div>
                    <h4 class="font-bold text-lg mb-2">Retention</h4>
                    <p class="text-sm text-slate-400">Utilizing SAP S/4HANA to optimize supply chain delivery and ensure long-term client loyalty.</p>
                </div>
            </div>
        </section>

        <!-- Language Progress Bars -->
        <section class="mb-20">
            <h2 class="text-3xl font-bold mb-10 text-center">Language Proficiency</h2>
            <div class="max-w-md mx-auto space-y-6">
                <div>
                    <div class="flex justify-between mb-1">
                        <span class="font-bold">Turkish (Native)</span>
                        <span>100%</span>
                    </div>
                    <div class="w-full bg-slate-200 h-2 rounded-full overflow-hidden">
                        <div class="bg-blue-600 h-full w-[100%]"></div>
                    </div>
                </div>
                <div>
                    <div class="flex justify-between mb-1">
                        <span class="font-bold">English (Professional)</span>
                        <span>95%</span>
                    </div>
                    <div class="w-full bg-slate-200 h-2 rounded-full overflow-hidden">
                        <div class="bg-blue-600 h-full w-[95%]"></div>
                    </div>
                </div>
                <div>
                    <div class="flex justify-between mb-1">
                        <span class="font-bold">French (Improving)</span>
                        <span>65%</span>
                    </div>
                    <div class="w-full bg-slate-200 h-2 rounded-full overflow-hidden">
                        <div class="bg-blue-600 h-full w-[65%]"></div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-slate-100 py-12 text-center border-t border-slate-200">
        <p class="text-slate-500 font-medium italic mb-4">"I do not just represent a product; I represent a promise of growth and a partnership built on data."</p>
        <p class="text-slate-900 font-bold">Batuhan OĞUZ - 2024</p>
    </footer>

    <script>
        // Chart Initialization
        window.onload = function() {
            const ctx = document.getElementById('growthChart').getContext('2d');
            new Chart(ctx, {
                type: 'line',
                data: {
                    labels: ['Q1', 'Q2', 'Q3', 'Q4'],
                    datasets: [{
                        label: 'Oakie.be Sales Volume',
                        data: [100, 145, 180, 210],
                        borderColor: '#2563eb',
                        backgroundColor: 'rgba(37, 99, 235, 0.1)',
                        borderWidth: 3,
                        tension: 0.4,
                        fill: true
                    }]
                },
                options: {
                    responsive: true,
                    plugins: { legend: { display: false } },
                    scales: {
                        y: { display: false },
                        x: { grid: { display: false } }
                    }
                }
            });
        };
    </script>
</body>
</html>
