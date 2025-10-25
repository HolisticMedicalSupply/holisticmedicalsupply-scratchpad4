<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Holistic Medical Supply - Complete DME Portfolio | 36 BOC-Licensed Categories</title>
    <meta name="description" content="Complete DME business portfolio with 11 growth strategies, 36 BOC-licensed categories, and $2.8M-$5.9M Year 1 revenue potential. Multi-language support: English, Russian, Uzbek.">
    <style>
        :root {
            --primary-blue: #1e3c72;
            --secondary-blue: #2a5298;
            --accent-purple: #667eea;
            --accent-violet: #764ba2;
            --success-green: #27ae60;
            --warning-orange: #f39c12;
            --danger-red: #e74c3c;
            --light-bg: #f8f9fa;
            --white: #ffffff;
            --text-dark: #333333;
            --text-light: #666666;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background: linear-gradient(135deg, var(--accent-purple) 0%, var(--accent-violet) 100%);
            padding: 20px;
        }

        .container {
            max-width: 1800px;
            margin: 0 auto;
            background: var(--white);
            border-radius: 20px;
            box-shadow: 0 20px 80px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        /* Language Toggle */
        .language-toggle {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: rgba(255, 255, 255, 0.98);
            backdrop-filter: blur(10px);
            padding: 20px 40px;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
            border-bottom: 3px solid var(--accent-purple);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }

        .lang-btn {
            padding: 14px 35px;
            border: 2px solid var(--accent-purple);
            background: var(--white);
            color: var(--accent-purple);
            border-radius: 10px;
            cursor: pointer;
            font-size: 1.1em;
            font-weight: bold;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .lang-btn:hover {
            background: #f0f0ff;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.3);
        }

        .lang-btn.active {
            background: linear-gradient(135deg, var(--accent-purple), var(--accent-violet));
            color: var(--white);
            border-color: var(--accent-violet);
        }

        .lang-content {
            display: none;
        }

        .lang-content.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--secondary-blue) 100%);
            color: var(--white);
            padding: 80px 60px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120"><path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".1" fill="%23ffffff"/></svg>') no-repeat bottom;
            background-size: cover;
            opacity: 0.1;
        }

        .hero h1 {
            font-size: 4.5em;
            margin-bottom: 20px;
            font-weight: 800;
            letter-spacing: -1px;
            position: relative;
            z-index: 1;
        }

        .hero .tagline {
            font-size: 2em;
            margin-bottom: 30px;
            font-weight: 300;
            opacity: 0.95;
        }

        .hero .value-prop {
            font-size: 1.4em;
            max-width: 900px;
            margin: 0 auto 40px;
            line-height: 1.8;
            opacity: 0.9;
        }

        .hero .cta-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 40px;
        }

        .cta-btn {
            padding: 18px 45px;
            font-size: 1.2em;
            font-weight: bold;
            border-radius: 10px;
            text-decoration: none;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .cta-btn.primary {
            background: var(--success-green);
            color: var(--white);
            border: 2px solid var(--success-green);
        }

        .cta-btn.primary:hover {
            background: #229954;
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(39, 174, 96, 0.4);
        }

        .cta-btn.secondary {
            background: transparent;
            color: var(--white);
            border: 2px solid var(--white);
        }

        .cta-btn.secondary:hover {
            background: rgba(255, 255, 255, 0.1);
            transform: translateY(-3px);
        }

        /* Success Banner */
        .success-banner {
            background: linear-gradient(135deg, var(--success-green) 0%, #229954 100%);
            color: var(--white);
            padding: 50px 40px;
            text-align: center;
            font-size: 1.8em;
            font-weight: bold;
            letter-spacing: 0.5px;
            box-shadow: 0 4px 15px rgba(39, 174, 96, 0.3);
        }

        /* Stats Dashboard */
        .stats-dashboard {
            padding: 60px 40px;
            background: linear-gradient(135deg, var(--light-bg) 0%, #e9ecef 100%);
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            max-width: 1400px;
            margin: 0 auto;
        }

        .stat-card {
            background: var(--white);
            padding: 40px 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            border-top: 5px solid var(--accent-purple);
        }

        .stat-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.15);
        }

        .stat-icon {
            font-size: 3.5em;
            margin-bottom: 15px;
        }

        .stat-number {
            font-size: 3.5em;
            font-weight: 800;
            color: var(--accent-purple);
            display: block;
            margin-bottom: 10px;
            line-height: 1;
        }

        .stat-label {
            font-size: 1.2em;
            color: var(--text-light);
            font-weight: 600;
        }

        /* Section Styling */
        .section {
            padding: 70px 60px;
        }

        .section:nth-child(even) {
            background: var(--light-bg);
        }

        .section-header {
            text-align: center;
            margin-bottom: 60px;
        }

        .section-title {
            font-size: 3em;
            color: var(--primary-blue);
            margin-bottom: 20px;
            font-weight: 800;
            position: relative;
            display: inline-block;
            padding-bottom: 20px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 120px;
            height: 5px;
            background: linear-gradient(90deg, var(--accent-purple), var(--accent-violet));
            border-radius: 3px;
        }

        .section-subtitle {
            font-size: 1.3em;
            color: var(--text-light);
            max-width: 800px;
            margin: 20px auto 0;
            line-height: 1.8;
        }

        /* Card Grid */
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
            gap: 35px;
            margin-top: 50px;
        }

        .card {
            background: var(--white);
            border-radius: 18px;
            padding: 40px;
            box-shadow: 0 10px 35px rgba(0, 0, 0, 0.1);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
            border-top: 6px solid;
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 6px;
            background: linear-gradient(90deg, var(--accent-purple), var(--accent-violet));
            transform: scaleX(0);
            transition: transform 0.4s ease;
        }

        .card:hover::before {
            transform: scaleX(1);
        }

        .card:hover {
            transform: translateY(-15px);
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
        }

        .card-badge {
            display: inline-block;
            padding: 8px 18px;
            border-radius: 20px;
            font-size: 0.85em;
            font-weight: bold;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .badge-new {
            background: #e74c3c;
            color: var(--white);
        }

        .badge-updated {
            background: var(--success-green);
            color: var(--white);
        }

        .badge-critical {
            background: var(--warning-orange);
            color: var(--white);
        }

        .card-icon {
            font-size: 3em;
            margin-bottom: 20px;
            display: block;
        }

        .card h3 {
            font-size: 1.8em;
            margin-bottom: 18px;
            color: var(--primary-blue);
            font-weight: 700;
        }

        .card p {
            color: var(--text-light);
            margin-bottom: 25px;
            line-height: 1.8;
            font-size: 1.05em;
        }

        .revenue-box {
            background: linear-gradient(135deg, var(--success-green) 0%, #229954 100%);
            color: var(--white);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            font-size: 1.4em;
            font-weight: bold;
            margin: 25px 0;
            box-shadow: 0 5px 20px rgba(39, 174, 96, 0.3);
        }

        .info-box {
            background: var(--light-bg);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            border-left: 4px solid var(--accent-purple);
        }

        .info-box ul {
            list-style: none;
            margin-top: 10px;
        }

        .info-box li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }

        .info-box li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--success-green);
            font-weight: bold;
        }

        .view-link {
            display: block;
            background: linear-gradient(135deg, var(--accent-purple), var(--accent-violet));
            color: var(--white);
            text-align: center;
            padding: 16px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            transition: all 0.3s ease;
            margin-top: 25px;
        }

        .view-link:hover {
            background: linear-gradient(135deg, var(--accent-violet), var(--accent-purple));
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.4);
        }

        .view-link::after {
            content: ' →';
            display: inline-block;
            transition: transform 0.3s ease;
        }

        .view-link:hover::after {
            transform: translateX(5px);
        }

        /* Strategy Grid */
        .strategy-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 35px;
            margin-top: 50px;
        }

        .strategy-card {
            background: var(--white);
            border-radius: 18px;
            padding: 35px;
            box-shadow: 0 10px 35px rgba(0, 0, 0, 0.1);
            border-top: 6px solid;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
        }

        .strategy-card:hover {
            transform: translateY(-15px) scale(1.02);
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
        }

        .strategy-number {
            position: absolute;
            top: 20px;
            right: 20px;
            background: rgba(102, 126, 234, 0.1);
            color: var(--accent-purple);
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5em;
            font-weight: bold;
        }

        .strategy-icon {
            font-size: 3.5em;
            margin-bottom: 20px;
            display: block;
        }

        .strategy-card h3 {
            font-size: 1.7em;
            margin-bottom: 15px;
            color: var(--primary-blue);
            font-weight: 700;
        }

        .strategy-card p {
            color: var(--text-light);
            margin-bottom: 20px;
            line-height: 1.7;
        }

        .strategy-details {
            background: var(--light-bg);
            padding: 15px;
            border-radius: 8px;
            margin: 15px 0;
            font-size: 0.95em;
        }

        .strategy-details strong {
            color: var(--primary-blue);
        }

        /* Footer */
        .footer {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--secondary-blue) 100%);
            color: var(--white);
            padding: 60px 60px 40px;
        }

        .footer-content {
            max-width: 1400px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 50px;
            margin-bottom: 40px;
        }

        .footer-section h3 {
            font-size: 1.5em;
            margin-bottom: 20px;
            font-weight: 700;
        }

        .footer-section p,
        .footer-section li {
            opacity: 0.9;
            line-height: 1.8;
            margin-bottom: 10px;
        }

        .footer-section ul {
            list-style: none;
        }

        .footer-section a {
            color: var(--white);
            text-decoration: none;
            transition: opacity 0.3s ease;
        }

        .footer-section a:hover {
            opacity: 0.7;
        }

        .footer-bottom {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
            opacity: 0.8;
        }

        /* Responsive Design */
        @media (max-width: 1200px) {
            .hero h1 { font-size: 3.5em; }
            .hero .tagline { font-size: 1.6em; }
            .section-title { font-size: 2.5em; }
        }

        @media (max-width: 768px) {
            body { padding: 10px; }
            .hero { padding: 50px 30px; }
            .hero h1 { font-size: 2.5em; }
            .hero .tagline { font-size: 1.3em; }
            .hero .value-prop { font-size: 1.1em; }
            .section { padding: 40px 30px; }
            .section-title { font-size: 2em; }
            .card-grid, .strategy-grid { 
                grid-template-columns: 1fr; 
                gap: 25px;
            }
            .stats-grid { grid-template-columns: repeat(2, 1fr); }
            .language-toggle { padding: 15px 20px; flex-wrap: wrap; }
            .lang-btn { padding: 10px 20px; font-size: 0.95em; }
            .cta-buttons { flex-direction: column; }
        }

        @media (max-width: 480px) {
            .hero h1 { font-size: 2em; }
            .stats-grid { grid-template-columns: 1fr; }
            .stat-number { font-size: 2.5em; }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Language Toggle -->
        <div class="language-toggle">
            <button class="lang-btn active" onclick="switchLanguage('en')" data-lang="en">
                🇺🇸 English
            </button>
            <button class="lang-btn" onclick="switchLanguage('ru')" data-lang="ru">
                🇷🇺 Русский
            </button>
            <button class="lang-btn" onclick="switchLanguage('uz')" data-lang="uz">
                🇺🇿 O'zbek
            </button>
        </div>

        <!-- ENGLISH CONTENT -->
        <div class="lang-content active" id="content-en">
            <!-- Hero Section -->
            <div class="hero">
                <h1>🏥 Holistic Medical Supply</h1>
                <p class="tagline">Complete DME Business Portfolio</p>
                <p class="value-prop">
                    Comprehensive business strategy covering 36 BOC-licensed DME categories with 11 proven growth strategies. 
                    Projected Year 1 revenue: $2.8M - $5.9M with 70-80% from licensed equipment and 20-30% from complementary products.
                </p>
                <div class="cta-buttons">
                    <a href="#core-documents" class="cta-btn primary">
                        <span>📊</span> Explore Revenue Projections
                    </a>
                    <a href="#all-strategies" class="cta-btn secondary">
                        <span>🎯</span> View All 11 Strategies
                    </a>
                </div>
            </div>

            <!-- Success Banner -->
            <div class="success-banner">
                ✅ ALL STRATEGIES UPDATED: Licensed DME Equipment (70-80%) + Complementary Products (20-30%)
            </div>

            <!-- Stats Dashboard -->
            <div class="stats-dashboard">
                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-icon">🏥</div>
                        <span class="stat-number">36</span>
                        <span class="stat-label">BOC-Licensed Categories</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">🎯</div>
                        <span class="stat-number">11</span>
                        <span class="stat-label">Growth Strategies</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">💰</div>
                        <span class="stat-number">$2.8M-5.9M</span>
                        <span class="stat-label">Year 1 Realistic Target</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">📈</div>
                        <span class="stat-number">70-80%</span>
                        <span class="stat-label">Revenue from Licensed DME</span>
                    </div>
                </div>
            </div>

            <!-- Core Documents Section -->
            <div class="section" id="core-documents">
                <div class="section-header">
                    <h2 class="section-title">🎯 Core Strategy Documents</h2>
                    <p class="section-subtitle">
                        Essential documents providing complete financial breakdown, product portfolio details, and strategic pricing models
                    </p>
                </div>
                
                <div class="card-grid">
                    <div class="card" style="border-top-color: #e74c3c;">
                        <span class="card-badge badge-updated">UPDATED</span>
                        <span class="card-badge badge-critical">CRITICAL</span>
                        <span class="card-icon">📊</span>
                        <h3>Complete Revenue Summary</h3>
                        <p>
                            Full breakdown showing realistic revenue with all 36 BOC codes integrated across all 11 strategies. 
                            Includes conservative, realistic, and optimistic scenarios.
                        </p>
                        <div class="info-box">
                            <strong>Key Features:</strong>
                            <ul>
                                <li>Strategy-by-strategy revenue analysis</li>
                                <li>Licensed DME vs Complementary breakdown</li>
                                <li>5-year financial projections</li>
                                <li>Margin analysis by category</li>
                            </ul>
                        </div>
                        <div class="revenue-box">Year 1: $2.8M - $5.9M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad5/" class="view-link" target="_blank">View Complete Revenue Analysis</a>
                    </div>

                    <div class="card" style="border-top-color: #3498db;">
                        <span class="card-badge badge-new">ESSENTIAL</span>
                        <span class="card-icon">🏥</span>
                        <h3>DME Product Portfolio</h3>
                        <p>
                            Deep dive into all 36 BOC-licensed categories with product examples, pricing ranges, and revenue estimates. 
                            The foundation of your entire business model.
                        </p>
                        <div class="info-box">
                            <strong>Includes:</strong>
                            <ul>
                                <li>All 36 BOC codes defined</li>
                                <li>Product examples with pricing</li>
                                <li>Revenue estimates by category</li>
                                <li>Integration with each strategy</li>
                            </ul>
                        </div>
                        <div class="revenue-box">36 BOC Categories</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad6/" class="view-link" target="_blank">Explore Product Portfolio</a>
                    </div>

                    <div class="card" style="border-top-color: #f39c12;">
                        <span class="card-badge badge-critical">STRATEGIC</span>
                        <span class="card-icon">💰</span>
                        <h3>4-Tier Pricing Strategy</h3>
                        <p>
                            Comprehensive visual documentation of Economy, Value, US-Made, and Luxury pricing tiers. 
                            Strategic positioning for maximum market penetration.
                        </p>
                        <div class="info-box">
                            <strong>Pricing Tiers:</strong>
                            <ul>
                                <li>Economy: Budget-conscious segment</li>
                                <li>Value: Recommended default tier</li>
                                <li>US-Made: Premium domestic products</li>
                                <li>Luxury: Highest quality & service</li>
                            </ul>
                        </div>
                        <div class="revenue-box">Market Positioning</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad7/" class="view-link" target="_blank">View Pricing Strategy</a>
                    </div>
                </div>
            </div>

            <!-- All 11 Strategies Section -->
            <div class="section" id="all-strategies">
                <div class="section-header">
                    <h2 class="section-title">🎯 All 11 Growth Strategies</h2>
                    <p class="section-subtitle">
                        Comprehensive implementation blueprints for each revenue-generating strategy. 
                        Start with 4 primary strategies and scale to all 11 for maximum market coverage.
                    </p>
                </div>

                <div class="strategy-grid">
                    <!-- Strategy 1 -->
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <div class="strategy-number">1</div>
                        <span class="strategy-icon">🚨</span>
                        <h3>Emergency Hospital Delivery</h3>
                        <p>2-4 hour guaranteed delivery to hospitals and discharge units</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Wheelchairs, hospital beds, patient lifts, walkers, commodes, orthotic braces
                            <br><strong>Target Market:</strong> 3-5 hospitals, discharge departments
                            <br><strong>Implementation:</strong> 2-3 months to full operation
                        </div>
                        <div class="revenue-box">$560K - $1.6M Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad8/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 2 -->
                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <div class="strategy-number">2</div>
                        <span class="strategy-icon">⛳</span>
                        <h3>Golf Course Programs</h3>
                        <p>On-site medical supply stations at premium golf courses</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Orthotic braces, compression stockings, diabetic shoes, mobility aids
                            <br><strong>Target Market:</strong> Affluent 55-75+ golf demographic
                            <br><strong>Implementation:</strong> 3-4 months, partnership-based
                        </div>
                        <div class="revenue-box">$280K - $700K Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad9/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 3 -->
                    <div class="strategy-card" style="border-top-color: #e67e22;">
                        <div class="strategy-number">3</div>
                        <span class="strategy-icon">🛡️</span>
                        <h3>Resilient Medical Supply</h3>
                        <p>Professional-grade emergency preparedness market</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Oxygen equipment, wound VAC, suction pumps, blood glucose monitors
                            <br><strong>Target Market:</strong> High-net-worth preppers, medical professionals
                            <br><strong>Implementation:</strong> 4-6 months, specialized marketing
                        </div>
                        <div class="revenue-box">$500K - $1.0M Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad10/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 4 -->
                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <div class="strategy-number">4</div>
                        <span class="strategy-icon">🔄</span>
                        <h3>Equipment Rental Programs</h3>
                        <p>Monthly recurring revenue model with 80-90% predictable income</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Power wheelchairs, hospital beds, patient lifts, CPAP machines
                            <br><strong>Target Market:</strong> 200-400 active rental units
                            <br><strong>Implementation:</strong> 3-5 months, insurance-reimbursed
                        </div>
                        <div class="revenue-box">$600K - $1.1M Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad11/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 5 -->
                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <div class="strategy-number">5</div>
                        <span class="strategy-icon">🏢</span>
                        <h3>Facility Storage Cabinets</h3>
                        <p>Automated inventory management for senior living facilities</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Wheelchairs, walkers, commodes, compression stockings, diabetic supplies
                            <br><strong>Target Market:</strong> 5-8 facilities (assisted living, nursing homes)
                            <br><strong>Implementation:</strong> 4-6 months, recurring restocking revenue
                        </div>
                        <div class="revenue-box">$450K - $1.05M Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad12/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 6 -->
                    <div class="strategy-card" style="border-top-color: #1abc9c;">
                        <div class="strategy-number">6</div>
                        <span class="strategy-icon">💻</span>
                        <h3>Telehealth E-Commerce</h3>
                        <p>Complete digital catalog with virtual consultations</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> All 36 BOC categories online, top sellers: wheelchairs, walkers, CPAP
                            <br><strong>Target Market:</strong> Regional and national online customers
                            <br><strong>Implementation:</strong> 3-4 months, full e-commerce platform
                        </div>
                        <div class="revenue-box">$900K - $1.8M Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad13/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 7 -->
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <div class="strategy-number">7</div>
                        <span class="strategy-icon">💊</span>
                        <h3>Pharmacy Partnerships</h3>
                        <p>DME displays in 8-12 independent pharmacies</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Canes, crutches, walkers, compression stockings, diabetic shoes
                            <br><strong>Target Market:</strong> Independent pharmacy customers
                            <br><strong>Implementation:</strong> 2-4 months, consignment model
                        </div>
                        <div class="revenue-box">$280K - $700K Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad14/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 8 -->
                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <div class="strategy-number">8</div>
                        <span class="strategy-icon">🎖️</span>
                        <h3>Specialty Divisions</h3>
                        <p>Dedicated divisions: Pediatric, Veteran, Bariatric, Sports Medicine</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Specialized equipment for each demographic segment
                            <br><strong>Target Market:</strong> Underserved specialty markets
                            <br><strong>Implementation:</strong> 4-6 months per division
                        </div>
                        <div class="revenue-box">$750K - $1.5M Year 1 Combined</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad15/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 9 -->
                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <div class="strategy-number">9</div>
                        <span class="strategy-icon">🏠</span>
                        <h3>Home Modification Services</h3>
                        <p>DME equipment sales + high-margin installation services</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> Hospital beds, patient lifts, stair lifts, bathroom safety equipment
                            <br><strong>Target Market:</strong> Aging-in-place homeowners
                            <br><strong>Implementation:</strong> 3-5 months, skilled labor team
                        </div>
                        <div class="revenue-box">$250K - $550K Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad16/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 10 -->
                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <div class="strategy-number">10</div>
                        <span class="strategy-icon">📱</span>
                        <h3>Virtual Care Platform</h3>
                        <p>Remote monitoring + telehealth + equipment delivery</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> CPAP machines, oxygen concentrators, blood glucose monitors with telehealth
                            <br><strong>Target Market:</strong> Chronic disease management patients
                            <br><strong>Implementation:</strong> 5-7 months, tech platform development
                        </div>
                        <div class="revenue-box">$500K - $850K Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad17/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>

                    <!-- Strategy 11 -->
                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <div class="strategy-number">11</div>
                        <span class="strategy-icon">🏥</span>
                        <h3>General Medical Products</h3>
                        <p>Complete DME showroom for direct-to-consumer sales</p>
                        <div class="strategy-details">
                            <strong>Primary BOC Products:</strong> All 36 BOC categories, walk-in showroom + delivery
                            <br><strong>Target Market:</strong> General public, direct insurance billing
                            <br><strong>Implementation:</strong> 4-6 months, retail location required
                        </div>
                        <div class="revenue-box">$350K - $700K Year 1</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad18/" class="view-link" target="_blank">View Full Strategy</a>
                    </div>
                </div>
            </div>

            <!-- Additional Resources Section -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">📚 Additional Resources</h2>
                    <p class="section-subtitle">
                        Supporting documentation, visual mockups, and specialized strategic additions
                    </p>
                </div>

                <div class="card-grid">
                    <div class="card" style="border-top-color: #9b59b6;">
                        <span class="card-icon">🎨</span>
                        <h3>Visual Strategy Mockups</h3>
                        <p>
                            Comprehensive visual presentations including infographics, process flows, customer journey maps, 
                            and operational mockups for all strategies.
                        </p>
                        <a href="#visual-mockups" class="view-link">View Visual Mockups</a>
                    </div>

                    <div class="card" style="border-top-color: #e67e22;">
                        <span class="card-icon">📋</span>
                        <h3>Implementation Roadmap</h3>
                        <p>
                            Detailed timeline for launching strategies in phases. Start with 4 primary strategies, 
                            then scale systematically to maximize resource efficiency.
                        </p>
                        <a href="#implementation" class="view-link">View Implementation Plan</a>
                    </div>

                    <div class="card" style="border-top-color: #1abc9c;">
                        <span class="card-icon">🐾</span>
                        <h3>Pet Medical Supply Addition</h3>
                        <p>
                            Specialized opportunity: veterinary medical supplies and pet DME equipment. 
                            Expands addressable market with complementary product line.
                        </p>
                        <a href="#pet-medical" class="view-link">Explore Pet Medical Strategy</a>
                    </div>
                </div>
            </div>

            <!-- Implementation Phases -->
            <div class="section">
                <div class="section-header">
                    <h2 class="section-title">🚀 Recommended Implementation Phases</h2>
                    <p class="section-subtitle">
                        Strategic rollout plan for optimal resource allocation and risk management
                    </p>
                </div>

                <div class="card-grid">
                    <div class="card" style="border-top-color: #27ae60;">
                        <span class="card-badge badge-critical">PHASE 1</span>
                        <span class="card-icon">🎯</span>
                        <h3>First 4 Strategies (Months 1-6)</h3>
                        <div class="info-box">
                            <strong>Focus Strategies:</strong>
                            <ul>
                                <li>Emergency Hospital Delivery ($560K-$1.6M)</li>
                                <li>Equipment Rental Programs ($600K-$1.1M)</li>
                                <li>Specialty Divisions ($750K-$1.5M)</li>
                                <li>General Medical Products ($350K-$700K)</li>
                            </ul>
                        </div>
                        <div class="revenue-box">Combined: $2.8M - $5.9M Year 1</div>
                        <p style="margin-top: 15px;">
                            <strong>Rationale:</strong> Highest revenue potential, established demand, manageable implementation complexity
                        </p>
                    </div>

                    <div class="card" style="border-top-color: #f39c12;">
                        <span class="card-badge badge-updated">PHASE 2</span>
                        <span class="card-icon">📈</span>
                        <h3>Next 4 Strategies (Months 7-12)</h3>
                        <div class="info-box">
                            <strong>Expansion Strategies:</strong>
                            <ul>
                                <li>Telehealth E-Commerce ($900K-$1.8M)</li>
                                <li>Golf Course Programs ($280K-$700K)</li>
                                <li>Resilient Medical Supply ($500K-$1.0M)</li>
                                <li>Virtual Care Platform ($500K-$850K)</li>
                            </ul>
                        </div>
                        <div class="revenue-box">Combined: $2.2M - $4.4M Additional</div>
                        <p style="margin-top: 15px;">
                            <strong>Rationale:</strong> Leverages established operations, adds diversification, moderate complexity
                        </p>
                    </div>

                    <div class="card" style="border-top-color: #3498db;">
                        <span class="card-badge badge-new">PHASE 3</span>
                        <span class="card-icon">🎯</span>
                        <h3>Final 3 Strategies (Months 13-18)</h3>
                        <div class="info-box">
                            <strong>Optimization Strategies:</strong>
                            <ul>
                                <li>Facility Storage Cabinets ($450K-$1.05M)</li>
                                <li>Pharmacy Partnerships ($280K-$700K)</li>
                                <li>Home Modification Services ($250K-$550K)</li>
                            </ul>
                        </div>
                        <div class="revenue-box">Combined: $980K - $2.3M Additional</div>
                        <p style="margin-top: 15px;">
                            <strong>Rationale:</strong> Maximum market coverage, optimized operations, full portfolio deployment
                        </p>
                    </div>
                </div>
            </div>

            <!-- Footer -->
            <div class="footer">
                <div class="footer-content">
                    <div class="footer-section">
                        <h3>📞 Contact Information</h3>
                        <p>Holistic Medical Supply</p>
                        <p>Nassau County, New York</p>
                        <p>Email: contact@holisticmedicalsupply.com</p>
                        <p>Phone: (555) 123-4567</p>
                    </div>

                    <div class="footer-section">
                        <h3>📋 License Information</h3>
                        <p>BOC-Licensed DME Supplier</p>
                        <p>36 Licensed Product Categories</p>
                        <p>Medicare & Medicaid Approved</p>
                        <p>Insurance Accepted</p>
                    </div>

                    <div class="footer-section">
                        <h3>🔗 Quick Links</h3>
                        <ul>
                            <li><a href="#core-documents">Core Documents</a></li>
                            <li><a href="#all-strategies">All Strategies</a></li>
                            <li><a href="#implementation">Implementation Plan</a></li>
                            <li><a href="#contact">Contact Us</a></li>
                        </ul>
                    </div>

                    <div class="footer-section">
                        <h3>📊 Business Overview</h3>
                        <p>Year 1 Target: $2.8M - $5.9M</p>
                        <p>11 Growth Strategies</p>
                        <p>36 BOC-Licensed Categories</p>
                        <p>Multi-Language Support</p>
                    </div>
                </div>

                <div class="footer-bottom">
                    <p>&copy; 2025 Holistic Medical Supply. All rights reserved.</p>
                    <p>Last Updated: October 25, 2025 | Version 2.0</p>
                </div>
            </div>
        </div>

        <!-- RUSSIAN CONTENT -->
        <div class="lang-content" id="content-ru">
            <!-- Hero Section -->
            <div class="hero">
                <h1>🏥 Holistic Medical Supply</h1>
                <p class="tagline">Полный портфель бизнеса DME</p>
                <p class="value-prop">
                    Комплексная бизнес-стратегия, охватывающая 36 лицензированных категорий BOC DME с 11 проверенными стратегиями роста. 
                    Прогнозируемая выручка за 1-й год: $2.8M - $5.9M, где 70-80% от лицензированного оборудования и 20-30% от дополнительных продуктов.
                </p>
                <div class="cta-buttons">
                    <a href="#core-documents" class="cta-btn primary">
                        <span>📊</span> Изучить прогнозы доходов
                    </a>
                    <a href="#all-strategies" class="cta-btn secondary">
                        <span>🎯</span> Посмотреть все 11 стратегий
                    </a>
                </div>
            </div>

            <!-- Success Banner -->
            <div class="success-banner">
                ✅ ВСЕ СТРАТЕГИИ ОБНОВЛЕНЫ: Лицензированное оборудование DME (70-80%) + Дополнительные продукты (20-30%)
            </div>

            <!-- Stats Dashboard -->
            <div class="stats-dashboard">
                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-icon">🏥</div>
                        <span class="stat-number">36</span>
                        <span class="stat-label">Лицензированных категорий BOC</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">🎯</div>
                        <span class="stat-number">11</span>
                        <span class="stat-label">Стратегий роста</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">💰</div>
                        <span class="stat-number">$2.8M-5.9M</span>
                        <span class="stat-label">Реалистичная цель на 1-й год</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">📈</div>
                        <span class="stat-number">70-80%</span>
                        <span class="stat-label">Доход от лицензированного DME</span>
                    </div>
                </div>
            </div>

            <!-- Core Documents Section -->
            <div class="section" id="core-documents">
                <div class="section-header">
                    <h2 class="section-title">🎯 Основные стратегические документы</h2>
                    <p class="section-subtitle">
                        Основные документы, содержащие полную финансовую разбивку, детали портфеля продуктов и стратегические модели ценообразования
                    </p>
                </div>
                
                <div class="card-grid">
                    <div class="card" style="border-top-color: #e74c3c;">
                        <span class="card-badge badge-updated">ОБНОВЛЕНО</span>
                        <span class="card-badge badge-critical">КРИТИЧНО</span>
                        <span class="card-icon">📊</span>
                        <h3>Полная сводка доходов</h3>
                        <p>
                            Полная разбивка, показывающая реалистичный доход со всеми 36 кодами BOC, интегрированными во все 11 стратегий. 
                            Включает консервативные, реалистичные и оптимистичные сценарии.
                        </p>
                        <div class="info-box">
                            <strong>Ключевые особенности:</strong>
                            <ul>
                                <li>Анализ доходов по каждой стратегии</li>
                                <li>Разбивка лицензированного DME и дополнительных продуктов</li>
                                <li>5-летние финансовые прогнозы</li>
                                <li>Анализ маржи по категориям</li>
                            </ul>
                        </div>
                        <div class="revenue-box">1-й год: $2.8M - $5.9M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad5/" class="view-link" target="_blank">Просмотреть полный анализ доходов</a>
                    </div>

                    <div class="card" style="border-top-color: #3498db;">
                        <span class="card-badge badge-new">НЕОБХОДИМО</span>
                        <span class="card-icon">🏥</span>
                        <h3>Портфель продуктов DME</h3>
                        <p>
                            Глубокое погружение во все 36 лицензированных категорий BOC с примерами продуктов, диапазонами цен и оценками доходов. 
                            Основа всей вашей бизнес-модели.
                        </p>
                        <div class="info-box">
                            <strong>Включает:</strong>
                            <ul>
                                <li>Все 36 кодов BOC определены</li>
                                <li>Примеры продуктов с ценами</li>
                                <li>Оценка доходов по категориям</li>
                                <li>Интеграция с каждой стратегией</li>
                            </ul>
                        </div>
                        <div class="revenue-box">36 категорий BOC</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad6/" class="view-link" target="_blank">Изучить портфель продуктов</a>
                    </div>

                    <div class="card" style="border-top-color: #f39c12;">
                        <span class="card-badge badge-critical">СТРАТЕГИЯ</span>
                        <span class="card-icon">💰</span>
                        <h3>4-уровневая стратегия ценообразования</h3>
                        <p>
                            Комплексная визуальная документация уровней ценообразования: Эконом, Ценность, Произведено в США и Люкс. 
                            Стратегическое позиционирование для максимального проникновения на рынок.
                        </p>
                        <div class="info-box">
                            <strong>Уровни ценообразования:</strong>
                            <ul>
                                <li>Эконом: Бюджетный сегмент</li>
                                <li>Ценность: Рекомендуемый уровень по умолчанию</li>
                                <li>Произведено в США: Премиум отечественные продукты</li>
                                <li>Люкс: Высочайшее качество и сервис</li>
                            </ul>
                        </div>
                        <div class="revenue-box">Позиционирование на рынке</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad7/" class="view-link" target="_blank">Просмотреть стратегию ценообразования</a>
                    </div>
                </div>
            </div>

            <!-- All 11 Strategies Section -->
            <div class="section" id="all-strategies">
                <div class="section-header">
                    <h2 class="section-title">🎯 Все 11 стратегий роста</h2>
                    <p class="section-subtitle">
                        Комплексные чертежи реализации для каждой стратегии получения дохода. 
                        Начните с 4 основных стратегий и масштабируйте до всех 11 для максимального охвата рынка.
                    </p>
                </div>

                <div class="strategy-grid">
                    <!-- Strategy 1 -->
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <div class="strategy-number">1</div>
                        <span class="strategy-icon">🚨</span>
                        <h3>Экстренная доставка в больницы</h3>
                        <p>Гарантированная доставка в больницы и отделения выписки за 2-4 часа</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Инвалидные коляски, больничные кровати, подъемники для пациентов, ходунки, туалеты, ортопедические брекеты
                            <br><strong>Целевой рынок:</strong> 3-5 больниц, отделения выписки
                            <br><strong>Реализация:</strong> 2-3 месяца до полной работы
                        </div>
                        <div class="revenue-box">$560K - $1.6M 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad8/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 2 -->
                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <div class="strategy-number">2</div>
                        <span class="strategy-icon">⛳</span>
                        <h3>Программы для гольф-клубов</h3>
                        <p>Станции медицинских принадлежностей на территории премиум-гольф-клубов</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Ортопедические брекеты, компрессионные чулки, диабетическая обувь, средства передвижения
                            <br><strong>Целевой рынок:</strong> Состоятельная демографическая группа гольфистов 55-75+
                            <br><strong>Реализация:</strong> 3-4 месяца, на основе партнерства
                        </div>
                        <div class="revenue-box">$280K - $700K 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad9/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 3 -->
                    <div class="strategy-card" style="border-top-color: #e67e22;">
                        <div class="strategy-number">3</div>
                        <span class="strategy-icon">🛡️</span>
                        <h3>Надежное медицинское снабжение</h3>
                        <p>Рынок профессиональной готовности к чрезвычайным ситуациям</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Кислородное оборудование, вакуумные раны, отсасывающие насосы, мониторы глюкозы крови
                            <br><strong>Целевой рынок:</strong> Преперы с высоким уровнем дохода, медицинские работники
                            <br><strong>Реализация:</strong> 4-6 месяцев, специализированный маркетинг
                        </div>
                        <div class="revenue-box">$500K - $1.0M 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad10/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 4 -->
                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <div class="strategy-number">4</div>
                        <span class="strategy-icon">🔄</span>
                        <h3>Программы аренды оборудования</h3>
                        <p>Модель ежемесячного повторяющегося дохода с 80-90% предсказуемым доходом</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Электрические инвалидные коляски, больничные кровати, подъемники для пациентов, аппараты CPAP
                            <br><strong>Целевой рынок:</strong> 200-400 активных единиц аренды
                            <br><strong>Реализация:</strong> 3-5 месяцев, с возмещением страховки
                        </div>
                        <div class="revenue-box">$600K - $1.1M 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad11/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 5 -->
                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <div class="strategy-number">5</div>
                        <span class="strategy-icon">🏢</span>
                        <h3>Шкафы для хранения в учреждениях</h3>
                        <p>Автоматизированное управление запасами для учреждений для пожилых людей</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Инвалидные коляски, ходунки, туалеты, компрессионные чулки, диабетические принадлежности
                            <br><strong>Целевой рынок:</strong> 5-8 учреждений (дома престарелых, дома престарелых)
                            <br><strong>Реализация:</strong> 4-6 месяцев, повторяющийся доход от пополнения запасов
                        </div>
                        <div class="revenue-box">$450K - $1.05M 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad12/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 6 -->
                    <div class="strategy-card" style="border-top-color: #1abc9c;">
                        <div class="strategy-number">6</div>
                        <span class="strategy-icon">💻</span>
                        <h3>Электронная коммерция телемедицины</h3>
                        <p>Полный цифровой каталог с виртуальными консультациями</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Все 36 категорий BOC онлайн, топ-продажи: инвалидные коляски, ходунки, CPAP
                            <br><strong>Целевой рынок:</strong> Региональные и национальные онлайн-клиенты
                            <br><strong>Реализация:</strong> 3-4 месяца, полная платформа электронной коммерции
                        </div>
                        <div class="revenue-box">$900K - $1.8M 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad13/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 7 -->
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <div class="strategy-number">7</div>
                        <span class="strategy-icon">💊</span>
                        <h3>Партнерства с аптеками</h3>
                        <p>Дисплеи DME в 8-12 независимых аптеках</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Трости, костыли, ходунки, компрессионные чулки, диабетическая обувь
                            <br><strong>Целевой рынок:</strong> Клиенты независимых аптек
                            <br><strong>Реализация:</strong> 2-4 месяца, модель консигнации
                        </div>
                        <div class="revenue-box">$280K - $700K 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad14/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 8 -->
                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <div class="strategy-number">8</div>
                        <span class="strategy-icon">🎖️</span>
                        <h3>Специализированные подразделения</h3>
                        <p>Специализированные подразделения: Педиатрия, Ветераны, Бариатрия, Спортивная медицина</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Специализированное оборудование для каждого демографического сегмента
                            <br><strong>Целевой рынок:</strong> Недостаточно обслуживаемые специализированные рынки
                            <br><strong>Реализация:</strong> 4-6 месяцев на подразделение
                        </div>
                        <div class="revenue-box">$750K - $1.5M 1-й год в сумме</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad15/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 9 -->
                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <div class="strategy-number">9</div>
                        <span class="strategy-icon">🏠</span>
                        <h3>Услуги по модификации дома</h3>
                        <p>Продажа оборудования DME + высокомаржинальные услуги по установке</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Больничные кровати, подъемники для пациентов, лестничные подъемники, оборудование для безопасности в ванной
                            <br><strong>Целевой рынок:</strong> Домовладельцы, стареющие на месте
                            <br><strong>Реализация:</strong> 3-5 месяцев, команда квалифицированного труда
                        </div>
                        <div class="revenue-box">$250K - $550K 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad16/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 10 -->
                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <div class="strategy-number">10</div>
                        <span class="strategy-icon">📱</span>
                        <h3>Платформа виртуального ухода</h3>
                        <p>Удаленный мониторинг + телемедицина + доставка оборудования</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Аппараты CPAP, концентраторы кислорода, мониторы глюкозы крови с телемедициной
                            <br><strong>Целевой рынок:</strong> Пациенты с хроническими заболеваниями
                            <br><strong>Реализация:</strong> 5-7 месяцев, разработка технологической платформы
                        </div>
                        <div class="revenue-box">$500K - $850K 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad17/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>

                    <!-- Strategy 11 -->
                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <div class="strategy-number">11</div>
                        <span class="strategy-icon">🏥</span>
                        <h3>Общие медицинские продукты</h3>
                        <p>Полный выставочный зал DME для прямых продаж потребителям</p>
                        <div class="strategy-details">
                            <strong>Основные продукты BOC:</strong> Все 36 категорий BOC, выставочный зал + доставка
                            <br><strong>Целевой рынок:</strong> Широкая публика, прямое страховое выставление счетов
                            <br><strong>Реализация:</strong> 4-6 месяцев, требуется розничное местоположение
                        </div>
                        <div class="revenue-box">$350K - $700K 1-й год</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad18/" class="view-link" target="_blank">Просмотреть полную стратегию</a>
                    </div>
                </div>
            </div>

            <!-- Footer -->
            <div class="footer">
                <div class="footer-content">
                    <div class="footer-section">
                        <h3>📞 Контактная информация</h3>
                        <p>Holistic Medical Supply</p>
                        <p>Округ Нассау, Нью-Йорк</p>
                        <p>Email: contact@holisticmedicalsupply.com</p>
                        <p>Телефон: (555) 123-4567</p>
                    </div>

                    <div class="footer-section">
                        <h3>📋 Информация о лицензии</h3>
                        <p>Лицензированный поставщик BOC DME</p>
                        <p>36 лицензированных категорий продуктов</p>
                        <p>Одобрено Medicare и Medicaid</p>
                        <p>Принимается страховка</p>
                    </div>

                    <div class="footer-section">
                        <h3>🔗 Быстрые ссылки</h3>
                        <ul>
                            <li><a href="#core-documents">Основные документы</a></li>
                            <li><a href="#all-strategies">Все стратегии</a></li>
                            <li><a href="#implementation">План реализации</a></li>
                            <li><a href="#contact">Свяжитесь с нами</a></li>
                        </ul>
                    </div>

                    <div class="footer-section">
                        <h3>📊 Обзор бизнеса</h3>
                        <p>Цель 1-го года: $2.8M - $5.9M</p>
                        <p>11 стратегий роста</p>
                        <p>36 лицензированных категорий BOC</p>
                        <p>Многоязычная поддержка</p>
                    </div>
                </div>

                <div class="footer-bottom">
                    <p>&copy; 2025 Holistic Medical Supply. Все права защищены.</p>
                    <p>Последнее обновление: 25 октября 2025 г. | Версия 2.0</p>
                </div>
            </div>
        </div>

        <!-- UZBEK CONTENT -->
        <div class="lang-content" id="content-uz">
            <!-- Hero Section -->
            <div class="hero">
                <h1>🏥 Holistic Medical Supply</h1>
                <p class="tagline">To'liq DME biznes portfeli</p>
                <p class="value-prop">
                    36 ta litsenziyalangan BOC DME toifalari va 11 ta tasdiqlangan o'sish strategiyalarini o'z ichiga olgan kompleks biznes strategiyasi. 
                    1-yil prognoz daromadi: $2.8M - $5.9M, 70-80% litsenziyalangan uskunalardan va 20-30% qo'shimcha mahsulotlardan.
                </p>
                <div class="cta-buttons">
                    <a href="#core-documents" class="cta-btn primary">
                        <span>📊</span> Daromad prognozlarini o'rganish
                    </a>
                    <a href="#all-strategies" class="cta-btn secondary">
                        <span>🎯</span> Barcha 11 strategiyani ko'rish
                    </a>
                </div>
            </div>

            <!-- Success Banner -->
            <div class="success-banner">
                ✅ BARCHA STRATEGIYALAR YANGILANDI: Litsenziyalangan DME uskunalari (70-80%) + Qo'shimcha mahsulotlar (20-30%)
            </div>

            <!-- Stats Dashboard -->
            <div class="stats-dashboard">
                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-icon">🏥</div>
                        <span class="stat-number">36</span>
                        <span class="stat-label">BOC litsenziyalangan toifalari</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">🎯</div>
                        <span class="stat-number">11</span>
                        <span class="stat-label">O'sish strategiyalari</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">💰</div>
                        <span class="stat-number">$2.8M-5.9M</span>
                        <span class="stat-label">1-yil real maqsad</span>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">📈</div>
                        <span class="stat-number">70-80%</span>
                        <span class="stat-label">Litsenziyalangan DME dan daromad</span>
                    </div>
                </div>
            </div>

            <!-- Core Documents Section -->
            <div class="section" id="core-documents">
                <div class="section-header">
                    <h2 class="section-title">🎯 Asosiy strategik hujjatlar</h2>
                    <p class="section-subtitle">
                        To'liq moliyaviy taqsimot, mahsulot portfeli tafsilotlari va strategik narx modellari bilan muhim hujjatlar
                    </p>
                </div>
                
                <div class="card-grid">
                    <div class="card" style="border-top-color: #e74c3c;">
                        <span class="card-badge badge-updated">YANGILANDI</span>
                        <span class="card-badge badge-critical">MUHIM</span>
                        <span class="card-icon">📊</span>
                        <h3>To'liq daromad xulosasi</h3>
                        <p>
                            Barcha 11 strategiyada birlashtirilgan barcha 36 BOC kodlari bilan real daromadni ko'rsatadigan to'liq taqsimot. 
                            Konservativ, real va optimistik stsenariylarni o'z ichiga oladi.
                        </p>
                        <div class="info-box">
                            <strong>Asosiy xususiyatlari:</strong>
                            <ul>
                                <li>Har bir strategiya bo'yicha daromad tahlili</li>
                                <li>Litsenziyalangan DME va qo'shimcha taqsimot</li>
                                <li>5 yillik moliyaviy prognozlar</li>
                                <li>Toifalar bo'yicha marja tahlili</li>
                            </ul>
                        </div>
                        <div class="revenue-box">1-yil: $2.8M - $5.9M</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad5/" class="view-link" target="_blank">To'liq daromad tahlilini ko'rish</a>
                    </div>

                    <div class="card" style="border-top-color: #3498db;">
                        <span class="card-badge badge-new">ZARUR</span>
                        <span class="card-icon">🏥</span>
                        <h3>DME mahsulot portfeli</h3>
                        <p>
                            Mahsulot namunalari, narx oralig'i va daromad taxminlari bilan barcha 36 litsenziyalangan BOC toifalariga chuqur sho'ng'ish. 
                            Butun biznes modelingizning asosi.
                        </p>
                        <div class="info-box">
                            <strong>O'z ichiga oladi:</strong>
                            <ul>
                                <li>Barcha 36 BOC kodlari aniqlanadi</li>
                                <li>Narxlar bilan mahsulot namunalari</li>
                                <li>Toifalar bo'yicha daromad taxminlari</li>
                                <li>Har bir strategiya bilan integratsiya</li>
                            </ul>
                        </div>
                        <div class="revenue-box">36 BOC toifalari</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad6/" class="view-link" target="_blank">Mahsulot portfelini o'rganish</a>
                    </div>

                    <div class="card" style="border-top-color: #f39c12;">
                        <span class="card-badge badge-critical">STRATEGIK</span>
                        <span class="card-icon">💰</span>
                        <h3>4 darajali narx strategiyasi</h3>
                        <p>
                            Iqtisodiy, Qiymat, AQShda ishlab chiqarilgan va Hashamatli narx darajalarining kompleks vizual hujjatlari. 
                            Maksimal bozorga kirish uchun strategik pozitsiyalash.
                        </p>
                        <div class="info-box">
                            <strong>Narx darajalari:</strong>
                            <ul>
                                <li>Iqtisodiy: Byudjetga oid segment</li>
                                <li>Qiymat: Tavsiya etilgan standart daraja</li>
                                <li>AQShda ishlab chiqarilgan: Premium mahalliy mahsulotlar</li>
                                <li>Hashamatli: Eng yuqori sifat va xizmat</li>
                            </ul>
                        </div>
                        <div class="revenue-box">Bozor pozitsiyasi</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad7/" class="view-link" target="_blank">Narx strategiyasini ko'rish</a>
                    </div>
                </div>
            </div>

            <!-- All 11 Strategies Section -->
            <div class="section" id="all-strategies">
                <div class="section-header">
                    <h2 class="section-title">🎯 Barcha 11 o'sish strategiyalari</h2>
                    <p class="section-subtitle">
                        Har bir daromad keltiradigan strategiya uchun kompleks amalga oshirish rejalari. 
                        4 ta asosiy strategiya bilan boshlang va maksimal bozor qamroviga erishish uchun barcha 11 ga kengaytiring.
                    </p>
                </div>

                <div class="strategy-grid">
                    <!-- Strategy 1 -->
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <div class="strategy-number">1</div>
                        <span class="strategy-icon">🚨</span>
                        <h3>Shoshilinch kasalxonaga yetkazib berish</h3>
                        <p>Kasalxonalar va chiqish bo'linmalariga 2-4 soat kafolatlangan yetkazib berish</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Nogironlar aravachalari, kasalxona to'shaklari, bemorlarni ko'taruvchilar, piyodalar, tuvaletlar, ortopedik breklar
                            <br><strong>Maqsadli bozor:</strong> 3-5 kasalxona, chiqish bo'limlari
                            <br><strong>Amalga oshirish:</strong> To'liq ishlashgacha 2-3 oy
                        </div>
                        <div class="revenue-box">$560K - $1.6M 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad8/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 2 -->
                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <div class="strategy-number">2</div>
                        <span class="strategy-icon">⛳</span>
                        <h3>Golf kurslari dasturlari</h3>
                        <p>Premium golf kurslarida tibbiy ta'minot stansiyalari</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Ortopedik breklar, kompression paypoqlar, diabetik poyabzal, harakat vositalari
                            <br><strong>Maqsadli bozor:</strong> Boy 55-75+ golf demografiyasi
                            <br><strong>Amalga oshirish:</strong> 3-4 oy, hamkorlikka asoslangan
                        </div>
                        <div class="revenue-box">$280K - $700K 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad9/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 3 -->
                    <div class="strategy-card" style="border-top-color: #e67e22;">
                        <div class="strategy-number">3</div>
                        <span class="strategy-icon">🛡️</span>
                        <h3>Ishonchli tibbiy ta'minot</h3>
                        <p>Professional darajadagi favqulodda vaziyatlarga tayyorgarlik bozori</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Kislorod uskunalari, yara VAC, so'rg'ich nasoslari, qon glyukoza monitorlari
                            <br><strong>Maqsadli bozor:</strong> Yuqori daromadli prepperlar, tibbiyot xodimlari
                            <br><strong>Amalga oshirish:</strong> 4-6 oy, ixtisoslashtirilgan marketing
                        </div>
                        <div class="revenue-box">$500K - $1.0M 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad10/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 4 -->
                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <div class="strategy-number">4</div>
                        <span class="strategy-icon">🔄</span>
                        <h3>Uskunalarni ijaraga berish dasturlari</h3>
                        <p>80-90% bashorat qilinadigan daromad bilan oylik takrorlanuvchi daromad modeli</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Elektr nogironlar aravachalari, kasalxona to'shaklari, bemorlarni ko'taruvchilar, CPAP apparatlari
                            <br><strong>Maqsadli bozor:</strong> 200-400 faol ijara birliklari
                            <br><strong>Amalga oshirish:</strong> 3-5 oy, sug'urta kompensatsiyasi bilan
                        </div>
                        <div class="revenue-box">$600K - $1.1M 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad11/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 5 -->
                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <div class="strategy-number">5</div>
                        <span class="strategy-icon">🏢</span>
                        <h3>Muassasa saqlash shkaflarini</h3>
                        <p>Keksalar yashash muassasalari uchun avtomatlashtirilgan inventarizatsiya boshqaruvi</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Nogironlar aravachalari, piyodalar, tuvaletlar, kompression paypoqlar, diabetik buyumlar
                            <br><strong>Maqsadli bozor:</strong> 5-8 muassasa (yordamlashuvchi yashash, qariyalar uylari)
                            <br><strong>Amalga oshirish:</strong> 4-6 oy, takrorlanuvchi to'ldirish daromadi
                        </div>
                        <div class="revenue-box">$450K - $1.05M 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad12/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 6 -->
                    <div class="strategy-card" style="border-top-color: #1abc9c;">
                        <div class="strategy-number">6</div>
                        <span class="strategy-icon">💻</span>
                        <h3>Telehealth elektron tijorat</h3>
                        <p>Virtual konsultatsiyalar bilan to'liq raqamli katalog</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Barcha 36 BOC toifalari onlayn, top sotuvlar: nogironlar aravachalari, piyodalar, CPAP
                            <br><strong>Maqsadli bozor:</strong> Mintaqaviy va milliy onlayn mijozlar
                            <br><strong>Amalga oshirish:</strong> 3-4 oy, to'liq elektron tijorat platformasi
                        </div>
                        <div class="revenue-box">$900K - $1.8M 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad13/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 7 -->
                    <div class="strategy-card" style="border-top-color: #e74c3c;">
                        <div class="strategy-number">7</div>
                        <span class="strategy-icon">💊</span>
                        <h3>Dorixona hamkorliklari</h3>
                        <p>8-12 mustaqil dorixonalarda DME displeylari</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Tayoqlar, baldaqlar, piyodalar, kompression paypoqlar, diabetik poyabzal
                            <br><strong>Maqsadli bozor:</strong> Mustaqil dorixona mijozlari
                            <br><strong>Amalga oshirish:</strong> 2-4 oy, konsignatsiya modeli
                        </div>
                        <div class="revenue-box">$280K - $700K 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad14/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 8 -->
                    <div class="strategy-card" style="border-top-color: #f39c12;">
                        <div class="strategy-number">8</div>
                        <span class="strategy-icon">🎖️</span>
                        <h3>Maxsus bo'linmalar</h3>
                        <p>Maxsus bo'linmalar: Pediatrik, Veteran, Bariatrik, Sport tibbiyoti</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Har bir demografik segment uchun maxsus uskunalar
                            <br><strong>Maqsadli bozor:</strong> Kam xizmat ko'rsatiladigan maxsus bozorlar
                            <br><strong>Amalga oshirish:</strong> Har bir bo'linma uchun 4-6 oy
                        </div>
                        <div class="revenue-box">$750K - $1.5M 1-yil jami</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad15/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 9 -->
                    <div class="strategy-card" style="border-top-color: #9b59b6;">
                        <div class="strategy-number">9</div>
                        <span class="strategy-icon">🏠</span>
                        <h3>Uyni o'zgartirish xizmatlari</h3>
                        <p>DME uskunalar sotilishi + yuqori marja o'rnatish xizmatlari</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Kasalxona to'shaklari, bemorlarni ko'taruvchilar, zinali ko'taruvchilar, vannaxona xavfsizlik uskunalari
                            <br><strong>Maqsadli bozor:</strong> Joyida qaridigan uy egalari
                            <br><strong>Amalga oshirish:</strong> 3-5 oy, malakali mehnat jamoasi
                        </div>
                        <div class="revenue-box">$250K - $550K 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad16/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 10 -->
                    <div class="strategy-card" style="border-top-color: #3498db;">
                        <div class="strategy-number">10</div>
                        <span class="strategy-icon">📱</span>
                        <h3>Virtual g'amxo'rlik platformasi</h3>
                        <p>Masofaviy monitoring + telettibiyot + uskunalarni yetkazib berish</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> CPAP apparatlari, kislorod konsentratorlari, telettibiyot bilan qon glyukoza monitorlari
                            <br><strong>Maqsadli bozor:</strong> Surunkali kasalliklarni boshqarish bemorlari
                            <br><strong>Amalga oshirish:</strong> 5-7 oy, texnologik platforma rivojlantirish
                        </div>
                        <div class="revenue-box">$500K - $850K 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad17/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>

                    <!-- Strategy 11 -->
                    <div class="strategy-card" style="border-top-color: #27ae60;">
                        <div class="strategy-number">11</div>
                        <span class="strategy-icon">🏥</span>
                        <h3>Umumiy tibbiy mahsulotlar</h3>
                        <p>To'g'ridan-to'g'ri iste'molchiga sotish uchun to'liq DME ko'rgazma zali</p>
                        <div class="strategy-details">
                            <strong>Asosiy BOC mahsulotlari:</strong> Barcha 36 BOC toifalari, ko'rgazma zali + yetkazib berish
                            <br><strong>Maqsadli bozor:</strong> Umumiy xalq, to'g'ridan-to'g'ri sug'urta hisob-fakturasi
                            <br><strong>Amalga oshirish:</strong> 4-6 oy, chakana savdo joyi talab qilinadi
                        </div>
                        <div class="revenue-box">$350K - $700K 1-yil</div>
                        <a href="https://holisticmedicalsupply.github.io/holisticmedicalsupply-scratchpad18/" class="view-link" target="_blank">To'liq strategiyani ko'rish</a>
                    </div>
                </div>
            </div>

            <!-- Footer -->
            <div class="footer">
                <div class="footer-content">
                    <div class="footer-section">
                        <h3>📞 Aloqa ma'lumotlari</h3>
                        <p>Holistic Medical Supply</p>
                        <p>Nassau tumani, Nyu-York</p>
                        <p>Email: contact@holisticmedicalsupply.com</p>
                        <p>Telefon: (555) 123-4567</p>
                    </div>

                    <div class="footer-section">
                        <h3>📋 Litsenziya ma'lumotlari</h3>
                        <p>BOC litsenziyalangan DME yetkazib beruvchisi</p>
                        <p>36 litsenziyalangan mahsulot toifalari</p>
                        <p>Medicare va Medicaid tasdiqlangan</p>
                        <p>Sug'urta qabul qilinadi</p>
                    </div>

                    <div class="footer-section">
                        <h3>🔗 Tez havolalar</h3>
                        <ul>
                            <li><a href="#core-documents">Asosiy hujjatlar</a></li>
                            <li><a href="#all-strategies">Barcha strategiyalar</a></li>
                            <li><a href="#implementation">Amalga oshirish rejasi</a></li>
                            <li><a href="#contact">Biz bilan bog'laning</a></li>
                        </ul>
                    </div>

                    <div class="footer-section">
                        <h3>📊 Biznes sharhi</h3>
                        <p>1-yil maqsadi: $2.8M - $5.9M</p>
                        <p>11 o'sish strategiyalari</p>
                        <p>36 litsenziyalangan BOC toifalari</p>
                        <p>Ko'p tilli yordam</p>
                    </div>
                </div>

                <div class="footer-bottom">
                    <p>&copy; 2025 Holistic Medical Supply. Barcha huquqlar himoyalangan.</p>
                    <p>Oxirgi yangilanish: 25-oktabr 2025 | Versiya 2.0</p>
                </div>
            </div>
        </div>
    </div>

    <!-- JavaScript for Language Switching -->
    <script>
        function switchLanguage(lang) {
            // Hide all content
            document.querySelectorAll('.lang-content').forEach(content => {
                content.classList.remove('active');
            });
            
            // Remove active class from all buttons
            document.querySelectorAll('.lang-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            
            // Show selected language content
            document.getElementById('content-' + lang).classList.add('active');
            
            // Activate selected button
            document.querySelector('.lang-btn[data-lang="' + lang + '"]').classList.add('active');
            
            // Store preference in localStorage
            localStorage.setItem('preferredLanguage', lang);
        }

        // Load saved language preference on page load
        window.addEventListener('DOMContentLoaded', function() {
            const savedLang = localStorage.getItem('preferredLanguage');
            if (savedLang && ['en', 'ru', 'uz'].includes(savedLang)) {
                switchLanguage(savedLang);
            }
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
