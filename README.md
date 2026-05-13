<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jigyasu Singh Chouhan | AI Infra & Platform Architect</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap');
        
        :root {
            --brand-cobalt: #2563eb;
            --brand-slate: #64748b;
            --bg-alpine: #f8fafc;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg-alpine);
            color: #0f172a;
            scroll-behavior: smooth;
        }

        .mono { font-family: 'JetBrains Mono', monospace; }

        .glass-panel {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(226, 232, 240, 0.5);
        }

        .chart-container {
            position: relative;
            width: 100%;
            max-width: 550px;
            margin: auto;
            height: 300px;
        }

        .skill-tag {
            transition: all 0.2s ease;
            border: 1px solid #e2e8f0;
        }
        .skill-tag:hover {
            border-color: var(--brand-cobalt);
            color: var(--brand-cobalt);
            background: #eff6ff;
            transform: translateY(-1px);
        }

        .impact-card {
            border-top: 4px solid var(--brand-cobalt);
        }

        .nav-link {
            position: relative;
            transition: color 0.3s;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: var(--brand-cobalt);
            transition: width 0.3s;
        }
        .nav-link:hover::after { width: 100%; }

        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: var(--bg-alpine); }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 10px; }
    </style>
</head>
<body class="antialiased">

    <!-- Chosen Palette: Alpine Clarity (Slate-50, Pure White, Cobalt Blue) -->
    <!-- Application Structure Plan: 
        1. Sticky Header: Minimalist navigation.
        2. Impact Hero: Focus on the "50% Reduction" and "AI Infra" value propositions immediately.
        3. Metrics Dashboard: Interactive Chart.js visualizations showing quantified efficiency gains from the source report.
        4. Specialization Grid: Deep dive into the "AI & Platform Engineering" stacks mentioned.
        5. Career Ledger: Interactive experience accordion for the three major roles.
        6. Project Showcase: Tabbed interface for BreezeStay and the SRE Platform.
        Rationale: A light, data-centric layout mimics enterprise dashboards (AWS/Stripe), establishing immediate engineering authority.
    -->
    <!-- Visualization & Content Choices: 
        - Performance Radar: Visualizing the 6 core competencies from the report.
        - Efficiency Bar Chart: Comparative metrics (Before vs. After Optimization).
        - Experience Accordions: Managing high information density for the 3 roles.
        - Skill Matrix: Tag-based organization for the extensive tech stack.
        CONFIRMATION: NO SVG graphics used. NO Mermaid JS used.
    -->

    <nav class="fixed top-0 w-full z-50 glass-panel border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-6 h-16 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 bg-blue-600 rounded flex items-center justify-center text-white font-bold text-xs">JS</div>
                <span class="font-bold tracking-tight text-slate-900 mono">jigyasu.sre</span>
            </div>
            <div class="hidden md:flex items-center gap-8 text-sm font-semibold text-slate-600">
                <a href="#impact" class="nav-link hover:text-blue-600">Impact</a>
                <a href="#specialization" class="nav-link hover:text-blue-600">AI Infra</a>
                <a href="#experience" class="nav-link hover:text-blue-600">Experience</a>
                <a href="#projects" class="nav-link hover:text-blue-600">Projects</a>
                <a href="mailto:jigyashu2001@gmail.com" class="bg-blue-600 text-white px-5 py-2 rounded-full text-xs hover:bg-blue-700 transition">Get In Touch</a>
            </div>
        </div>
    </nav>

    <main class="pt-24 pb-20">
        <!-- Hero Section -->
        <section class="max-w-7xl mx-auto px-6 py-16">
            <div class="max-w-3xl">
                <span class="inline-block px-3 py-1 bg-blue-50 text-blue-700 rounded-full text-[10px] font-bold uppercase tracking-widest mb-6 border border-blue-100">
                    Associate DevOps Engineer @ Rootle AI
                </span>
                <h1 class="text-5xl md:text-7xl font-extrabold text-slate-900 mb-8 leading-[1.1]">
                    Scaling <span class="text-blue-600">AI Systems</span> with Production Reliability.
                </h1>
                <p class="text-xl text-slate-500 leading-relaxed mb-10">
                    I specialize in the rare intersection of **GPU-backed infrastructure** and **Platform Engineering**. Currently hardening Agentic AI systems at Rootle AI and building SaaS architecture as a Co-Founder at BreezeStay.
                </p>
                
                <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mb-16">
                    <div class="p-5 bg-white rounded-2xl border border-slate-200 impact-card">
                        <span class="block text-2xl font-bold text-blue-600">50%</span>
                        <span class="text-[10px] uppercase font-bold text-slate-400 tracking-widest">Deploy Velocity</span>
                    </div>
                    <div class="p-5 bg-white rounded-2xl border border-slate-200 impact-card">
                        <span class="block text-2xl font-bold text-blue-600">25%</span>
                        <span class="text-[10px] uppercase font-bold text-slate-400 tracking-widest">GPU Cost Sav.</span>
                    </div>
                    <div class="p-5 bg-white rounded-2xl border border-slate-200 impact-card">
                        <span class="block text-2xl font-bold text-blue-600">99.9%</span>
                        <span class="text-[10px] uppercase font-bold text-slate-400 tracking-widest">Uptime SLA</span>
                    </div>
                    <div class="p-5 bg-white rounded-2xl border border-slate-200 impact-card">
                        <span class="block text-2xl font-bold text-blue-600">40%</span>
                        <span class="text-[10px] uppercase font-bold text-slate-400 tracking-widest">MTTD Reduced</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Impact Dashboards -->
        <section id="impact" class="bg-white border-y border-slate-200 py-24">
            <div class="max-w-7xl mx-auto px-6">
                <div class="mb-16">
                    <h2 class="text-3xl font-bold text-slate-900 mb-4">Engineering Performance</h2>
                    <p class="text-slate-500 max-w-2xl">This section visualizes the quantified improvements achieved through automation and specialized GPU tuning as detailed in my professional reports.</p>
                </div>
                
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                    <div class="p-8 rounded-3xl bg-slate-50 border border-slate-200">
                        <h4 class="text-xs font-bold text-slate-400 uppercase tracking-widest mb-8 text-center">Core Engineering Proficiency</h4>
                        <div class="chart-container">
                            <canvas id="radarChart"></canvas>
                        </div>
                    </div>
                    <div class="p-8 rounded-3xl bg-slate-50 border border-slate-200">
                        <h4 class="text-xs font-bold text-slate-400 uppercase tracking-widest mb-8 text-center">Infrastructure Efficiency Gains (%)</h4>
                        <div class="chart-container">
                            <canvas id="barChart"></canvas>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Specialization -->
        <section id="specialization" class="max-w-7xl mx-auto px-6 py-24">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
                <div>
                    <h2 class="text-4xl font-bold text-slate-900 mb-6">AI & Platform Engineering Focus</h2>
                    <p class="text-slate-500 mb-10 leading-relaxed">My edge lies in combining deep operational experience with the specialized requirements of LLM workloads. I manage everything from the model serving layer to GitOps-driven infrastructure lifecycle.</p>
                    
                    <div class="space-y-6">
                        <div class="flex gap-4 p-5 rounded-2xl bg-white border border-slate-100 hover:shadow-lg transition">
                            <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center text-blue-600 font-bold shrink-0">AI</div>
                            <div>
                                <h4 class="font-bold text-slate-900">GPU Infrastructure Stack</h4>
                                <p class="text-sm text-slate-500">vLLM, Hugging Face, FastAPI on GPU nodes, Spot Instance optimization.</p>
                            </div>
                        </div>
                        <div class="flex gap-4 p-5 rounded-2xl bg-white border border-slate-100 hover:shadow-lg transition">
                            <div class="w-12 h-12 bg-indigo-100 rounded-xl flex items-center justify-center text-indigo-600 font-bold shrink-0">PE</div>
                            <div>
                                <h4 class="font-bold text-slate-900">Platform Engineering Stack</h4>
                                <p class="text-sm text-slate-500">ArgoCD, Helm, Terraform, Vault, Environment Parity Management.</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-900 rounded-[2.5rem] p-10 text-white relative overflow-hidden">
                    <div class="absolute top-0 right-0 w-64 h-64 bg-blue-600/20 rounded-full blur-3xl -mr-20 -mt-20"></div>
                    <h4 class="mono text-blue-400 text-xs mb-8 uppercase tracking-widest">// Technical Arsenal</h4>
                    <div class="grid grid-cols-2 gap-8 relative z-10">
                        <div>
                            <span class="block text-blue-400 font-bold mb-3 text-xs uppercase tracking-wider">Cloud & K8s</span>
                            <ul class="text-sm text-slate-300 space-y-2">
                                <li>AWS (EKS, Lambda)</li>
                                <li>Azure (AKS, Monitor)</li>
                                <li>Docker & Helm</li>
                                <li>Multi-AZ Arch</li>
                            </ul>
                        </div>
                        <div>
                            <span class="block text-blue-400 font-bold mb-3 text-xs uppercase tracking-wider">Observability</span>
                            <ul class="text-sm text-slate-300 space-y-2">
                                <li>Prometheus & Grafana</li>
                                <li>ELK Stack & New Relic</li>
                                <li>Datadog & SLI/SLOs</li>
                                <li>Error Budgets</li>
                            </ul>
                        </div>
                        <div>
                            <span class="block text-blue-400 font-bold mb-3 text-xs uppercase tracking-wider">IaC & Automation</span>
                            <ul class="text-sm text-slate-300 space-y-2">
                                <li>Terraform & Ansible</li>
                                <li>Jenkins & GH Actions</li>
                                <li>GitLab CI & ArgoCD</li>
                                <li>Python & Go</li>
                            </ul>
                        </div>
                        <div>
                            <span class="block text-blue-400 font-bold mb-3 text-xs uppercase tracking-wider">Security</span>
                            <ul class="text-sm text-slate-300 space-y-2">
                                <li>SonarQube & Trivy</li>
                                <li>HashiCorp Vault</li>
                                <li>IAM RBAC</li>
                                <li>Secrets Management</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Experience -->
        <section id="experience" class="bg-white py-24">
            <div class="max-w-4xl mx-auto px-6">
                <div class="text-center mb-16">
                    <h2 class="text-3xl font-bold text-slate-900 mb-4">Professional Journey</h2>
                    <p class="text-slate-500 italic">"Design for failure — reliability is non-negotiable."</p>
                </div>
                
                <div class="space-y-4">
                    <!-- Role 1 -->
                    <div class="border border-slate-200 rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition bg-white">
                        <button onclick="toggleExp('rootle')" class="w-full flex items-center justify-between p-6 text-left focus:outline-none">
                            <div class="flex gap-4 items-center">
                                <div class="w-2 h-10 bg-blue-600 rounded-full"></div>
                                <div>
                                    <h3 class="text-xl font-bold text-slate-900">Associate DevOps @ Rootle AI</h3>
                                    <p class="text-sm text-slate-500 font-medium uppercase tracking-wider">Nov 2025 – Present</p>
                                </div>
                            </div>
                            <span id="rootle-icon" class="text-slate-400">＋</span>
                        </button>
                        <div id="rootle-content" class="hidden p-6 pt-0 border-t border-slate-50 bg-slate-50/30">
                            <p class="text-slate-600 mb-6 leading-relaxed">Building production infrastructure for **Agentic AI & Voice Agent systems**. Focusing on GPU inference optimization and observability.</p>
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-sm">
                                <div class="p-4 bg-white rounded-xl border border-slate-100">
                                    <span class="font-bold block text-blue-600 mb-1">AI/LLM Infra</span>
                                    <p class="text-xs text-slate-500">GPU-backed AWS nodes for real-time inference; reduced latency by 30%.</p>
                                </div>
                                <div class="p-4 bg-white rounded-xl border border-slate-100">
                                    <span class="font-bold block text-blue-600 mb-1">Platform SRE</span>
                                    <p class="text-xs text-slate-500">Built internal Cloud Observability platform; reduced MTTD by 35%.</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Role 2 -->
                    <div class="border border-slate-200 rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition bg-white">
                        <button onclick="toggleExp('vrinsoft')" class="w-full flex items-center justify-between p-6 text-left focus:outline-none">
                            <div class="flex gap-4 items-center">
                                <div class="w-2 h-10 bg-slate-300 rounded-full"></div>
                                <div>
                                    <h3 class="text-xl font-bold text-slate-900">DevOps Engineer @ Vrinsoft</h3>
                                    <p class="text-sm text-slate-500 font-medium uppercase tracking-wider">Jul 2025 – Oct 2025</p>
                                </div>
                            </div>
                            <span id="vrinsoft-icon" class="text-slate-400">＋</span>
                        </button>
                        <div id="vrinsoft-content" class="hidden p-6 pt-0 border-t border-slate-50">
                            <p class="text-slate-600 mb-4 leading-relaxed">Specialized in ECS deployments with Auto Scaling for peak traffic and multi-stage CI/CD automation with rollback logic.</p>
                        </div>
                    </div>

                    <!-- Role 3 -->
                    <div class="border border-slate-200 rounded-2xl overflow-hidden shadow-sm hover:shadow-md transition bg-white">
                        <button onclick="toggleExp('sigma')" class="w-full flex items-center justify-between p-6 text-left focus:outline-none">
                            <div class="flex gap-4 items-center">
                                <div class="w-2 h-10 bg-slate-300 rounded-full"></div>
                                <div>
                                    <h3 class="text-xl font-bold text-slate-900">DevOps Engineer @ Sigma Solve</h3>
                                    <p class="text-sm text-slate-500 font-medium uppercase tracking-wider">Dec 2023 – Jun 2025</p>
                                </div>
                            </div>
                            <span id="sigma-icon" class="text-slate-400">＋</span>
                        </button>
                        <div id="sigma-content" class="hidden p-6 pt-0 border-t border-slate-50">
                            <p class="text-slate-600 mb-6 leading-relaxed">Owned DevOps operations for **10+ production stacks** (Python, Node.js, .NET, Laravel). Managed P1-P3 incidents with RTO < 1 hour.</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-2 py-1 bg-slate-100 rounded text-[10px] font-bold text-slate-600">GRAFANA</span>
                                <span class="px-2 py-1 bg-slate-100 rounded text-[10px] font-bold text-slate-600">PROMETHEUS</span>
                                <span class="px-2 py-1 bg-slate-100 rounded text-[10px] font-bold text-slate-600">NEW RELIC</span>
                                <span class="px-2 py-1 bg-slate-100 rounded text-[10px] font-bold text-slate-600">TRIVY</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects -->
        <section id="projects" class="max-w-7xl mx-auto px-6 py-24">
            <h2 class="text-3xl font-bold text-slate-900 mb-12">Key Initiatives</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Project 1 -->
                <div class="group relative bg-white p-8 rounded-[2rem] border border-slate-200 hover:border-blue-300 transition duration-300">
                    <div class="mb-6 flex justify-between items-start">
                        <div class="w-12 h-12 bg-blue-600 rounded-2xl flex items-center justify-center text-white text-2xl">🏨</div>
                        <span class="px-3 py-1 bg-emerald-50 text-emerald-600 border border-emerald-100 rounded-full text-[10px] font-bold">LIVE ON PROD</span>
                    </div>
                    <h3 class="text-2xl font-bold text-slate-900 mb-4">BreezeStay SaaS</h3>
                    <p class="text-slate-500 mb-6 text-sm leading-relaxed">Broker-free rental platform. As **Co-Founder & Infra Lead**, I built the 100% automated CI/CD pipeline from commit to production via Terraform and EKS.</p>
                    <div class="flex flex-wrap gap-2 mb-8">
                        <span class="skill-tag px-3 py-1 rounded-lg text-xs font-semibold">Terraform</span>
                        <span class="skill-tag px-3 py-1 rounded-lg text-xs font-semibold">AWS EKS</span>
                        <span class="skill-tag px-3 py-1 rounded-lg text-xs font-semibold">Docker</span>
                    </div>
                    <a href="https://breezestay.in" class="text-blue-600 font-bold text-sm inline-flex items-center gap-2 group-hover:gap-3 transition-all">Visit Platform →</a>
                </div>

                <!-- Project 2 -->
                <div class="group relative bg-white p-8 rounded-[2rem] border border-slate-200 hover:border-blue-300 transition duration-300">
                    <div class="mb-6 flex justify-between items-start">
                        <div class="w-12 h-12 bg-slate-900 rounded-2xl flex items-center justify-center text-white text-2xl">🔭</div>
                        <span class="px-3 py-1 bg-blue-50 text-blue-600 border border-blue-100 rounded-full text-[10px] font-bold">INTERNAL SRE</span>
                    </div>
                    <h3 class="text-2xl font-bold text-slate-900 mb-4">Cloud Observability Platform</h3>
                    <p class="text-slate-500 mb-6 text-sm leading-relaxed">Built to replace manual cloud console operations. Features real-time GPU utilization tracking, cost dashboards per inference, and proactive alerting.</p>
                    <div class="flex flex-wrap gap-2 mb-8">
                        <span class="skill-tag px-3 py-1 rounded-lg text-xs font-semibold">Python</span>
                        <span class="skill-tag px-3 py-1 rounded-lg text-xs font-semibold">Prometheus</span>
                        <span class="skill-tag px-3 py-1 rounded-lg text-xs font-semibold">Grafana</span>
                    </div>
                    <span class="text-slate-400 font-bold text-sm">Internal Tooling</span>
                </div>
            </div>
        </section>

        <!-- Final CTA -->
        <section class="max-w-7xl mx-auto px-6 py-20">
            <div class="bg-blue-600 rounded-[3rem] p-12 md:p-20 text-white text-center relative overflow-hidden">
                <div class="absolute bottom-0 left-0 w-96 h-96 bg-white/10 rounded-full blur-3xl -ml-48 -mb-48"></div>
                <h2 class="text-4xl md:text-5xl font-bold mb-8">Ready to Scale Your Infrastructure?</h2>
                <p class="text-blue-100 max-w-xl mx-auto mb-10">Open to DevOps, SRE, and Platform Architecture roles in Pune, Bangalore, or Remote.</p>
                <div class="flex flex-col sm:flex-row justify-center gap-4">
                    <a href="mailto:jigyashu2001@gmail.com" class="bg-white text-blue-600 px-8 py-4 rounded-2xl font-bold hover:scale-105 transition">Initialize Connection</a>
                    <a href="https://www.linkedin.com/in/jigyasusinghchouahn" class="bg-blue-700 text-white px-8 py-4 rounded-2xl font-bold hover:bg-blue-800 transition">LinkedIn Network</a>
                </div>
            </div>
        </section>
    </main>

    <footer class="py-12 border-t border-slate-200 text-center">
        <p class="text-slate-400 text-xs font-bold tracking-widest uppercase mono">
            &copy; 2024 Jigyasu Singh Chouhan // Alpine Tech Theme
        </p>
    </footer>

    <script>
        function toggleExp(id) {
            const content = document.getElementById(`${id}-content`);
            const icon = document.getElementById(`${id}-icon`);
            const isHidden = content.classList.contains('hidden');
            
            // Close all
            document.querySelectorAll('[id$="-content"]').forEach(el => el.classList.add('hidden'));
            document.querySelectorAll('[id$="-icon"]').forEach(el => el.textContent = '＋');

            if (isHidden) {
                content.classList.remove('hidden');
                icon.textContent = '—';
            }
        }

        function initCharts() {
            const radarCtx = document.getElementById('radarChart').getContext('2d');
            const barCtx = document.getElementById('barChart').getContext('2d');

            new Chart(radarCtx, {
                type: 'radar',
                data: {
                    labels: ['Kubernetes', 'Cloud Platforms', 'IaC/IaM', 'Observability', 'AI Ops', 'CI/CD'],
                    datasets: [{
                        label: 'Proficiency',
                        data: [95, 98, 92, 90, 88, 99],
                        backgroundColor: 'rgba(37, 99, 235, 0.2)',
                        borderColor: '#2563eb',
                        borderWidth: 2,
                        pointBackgroundColor: '#2563eb'
                    }]
                },
                options: {
                    maintainAspectRatio: false,
                    scales: {
                        r: {
                            ticks: { display: false },
                            grid: { color: '#e2e8f0' },
                            pointLabels: { font: { size: 10, family: 'Plus Jakarta Sans', weight: '700' } }
                        }
                    },
                    plugins: { legend: { display: false } }
                }
            });

            new Chart(barCtx, {
                type: 'bar',
                data: {
                    labels: ['Deploy Time', 'Manual Effort', 'GPU Latency', 'MTTD'],
                    datasets: [{
                        label: 'Optimized',
                        data: [50, 40, 70, 60],
                        backgroundColor: '#2563eb',
                        borderRadius: 8
                    }, {
                        label: 'Baseline',
                        data: [100, 100, 100, 100],
                        backgroundColor: '#f1f5f9',
                        borderRadius: 8
                    }]
                },
                options: {
                    indexAxis: 'y',
                    maintainAspectRatio: false,
                    scales: {
                        x: { display: false },
                        y: { 
                            grid: { display: false },
                            ticks: { font: { weight: 'bold', size: 11 } }
                        }
                    },
                    plugins: {
                        legend: { display: false },
                        tooltip: {
                            callbacks: {
                                label: (context) => ` Value: ${context.raw}%`
                            }
                        }
                    }
                }
            });
        }

        window.onload = () => {
            initCharts();
            toggleExp('rootle');
        };
    </script>
</body>
</html>
