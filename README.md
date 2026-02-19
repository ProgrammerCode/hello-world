<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Emergency plumber Wandsworth - Southstar Plumbers offers 24/7 emergency plumbing services in South West London. Fast response for leaks, burst pipes, blocked drains in Wandsworth, Clapham, Battersea, Balham, Fulham & Putney. Call 020 8877 3363 now.">
    <meta name="keywords" content="Emergency plumber Wandsworth, 24/7 plumber London, South West London plumbing services, burst pipe repair Wandsworth, blocked drain Clapham, leak detection Battersea">
    <title>Emergency Plumber Wandsworth | 24/7 South West London | Southstar Plumbers</title>
    
    <!-- Preconnect for performance -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #005eb8;
            --primary-dark: #004a8f;
            --secondary: #e63946;
            --accent: #ff6b35;
            --dark: #1a1a2e;
            --light: #f8f9fa;
            --gray: #6c757d;
            --success: #28a745;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            --shadow-lg: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background: #fff;
            overflow-x: hidden;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255, 255, 255, 0.98);
            backdrop-filter: blur(10px);
            z-index: 1000;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            text-decoration: none;
            color: var(--dark);
            font-weight: 800;
            font-size: 1.25rem;
        }

        .logo-icon {
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
            align-items: center;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            transition: color 0.3s;
            font-size: 0.95rem;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        .nav-phone {
            background: var(--secondary);
            color: white !important;
            padding: 0.75rem 1.5rem;
            border-radius: 50px;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--dark);
        }

        /* Hero Section */
        .hero {
            margin-top: 70px;
            background: linear-gradient(135deg, var(--dark) 0%, #16213e 100%);
            color: white;
            padding: 4rem 2rem;
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
            background: url('data:image/svg+xml,<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg"><path d="M0 100 L100 0" stroke="rgba(255,255,255,0.03)" stroke-width="1"/></svg>');
            opacity: 0.5;
        }

        .hero-container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
            position: relative;
            z-index: 1;
        }

        .hero-badge {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            background: rgba(230, 57, 70, 0.2);
            color: #ff6b6b;
            padding: 0.5rem 1rem;
            border-radius: 50px;
            font-size: 0.875rem;
            font-weight: 600;
            margin-bottom: 1.5rem;
            border: 1px solid rgba(230, 57, 70, 0.3);
        }

        .hero h1 {
            font-size: 3rem;
            font-weight: 800;
            line-height: 1.1;
            margin-bottom: 1.5rem;
            background: linear-gradient(to right, #fff, #cbd5e1);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero-subtitle {
            font-size: 1.25rem;
            color: #94a3b8;
            margin-bottom: 2rem;
            line-height: 1.6;
        }

        .hero-features {
            display: flex;
            gap: 2rem;
            margin-bottom: 2.5rem;
            flex-wrap: wrap;
        }

        .feature-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-weight: 500;
        }

        .feature-icon {
            width: 24px;
            height: 24px;
            background: var(--success);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.75rem;
        }

        .cta-group {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
        }

        .btn-primary {
            background: var(--secondary);
            color: white;
            padding: 1.25rem 2.5rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            font-size: 1.1rem;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            transition: all 0.3s;
            box-shadow: 0 10px 20px rgba(230, 57, 70, 0.3);
            border: none;
            cursor: pointer;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 15px 30px rgba(230, 57, 70, 0.4);
        }

        .btn-secondary {
            background: transparent;
            color: white;
            padding: 1.25rem 2.5rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            border: 2px solid rgba(255, 255, 255, 0.3);
            transition: all 0.3s;
        }

        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.1);
            border-color: white;
        }

        .hero-image {
            position: relative;
        }

        .hero-image img {
            width: 100%;
            border-radius: 20px;
            box-shadow: var(--shadow-lg);
            transform: perspective(1000px) rotateY(-5deg);
            transition: transform 0.3s;
        }

        .hero-image:hover img {
            transform: perspective(1000px) rotateY(0deg);
        }

        .floating-card {
            position: absolute;
            background: white;
            color: var(--dark);
            padding: 1rem 1.5rem;
            border-radius: 12px;
            box-shadow: var(--shadow-lg);
            display: flex;
            align-items: center;
            gap: 1rem;
            animation: float 3s ease-in-out infinite;
        }

        .floating-card.card-1 {
            bottom: -20px;
            left: -20px;
            animation-delay: 0s;
        }

        .floating-card.card-2 {
            top: 20px;
            right: -20px;
            animation-delay: 1.5s;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .card-icon {
            width: 40px;
            height: 40px;
            background: var(--primary);
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.25rem;
        }

        /* Emergency Bar */
        .emergency-bar {
            background: var(--secondary);
            color: white;
            text-align: center;
            padding: 1rem;
            font-weight: 600;
            position: sticky;
            top: 70px;
            z-index: 100;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 1rem;
            flex-wrap: wrap;
        }

        .emergency-bar a {
            color: white;
            text-decoration: underline;
            font-weight: 700;
            font-size: 1.1rem;
        }

        /* Services Section */
        .services {
            padding: 5rem 2rem;
            background: var(--light);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-header {
            text-align: center;
            margin-bottom: 3rem;
        }

        .section-header h2 {
            font-size: 2.5rem;
            font-weight: 800;
            margin-bottom: 1rem;
            color: var(--dark);
        }

        .section-header p {
            color: var(--gray);
            font-size: 1.125rem;
            max-width: 600px;
            margin: 0 auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: white;
            padding: 2.5rem;
            border-radius: 16px;
            box-shadow: var(--shadow);
            transition: all 0.3s;
            border: 1px solid #e5e7eb;
            position: relative;
            overflow: hidden;
        }

        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: linear-gradient(90deg, var(--primary), var(--accent));
            transform: scaleX(0);
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-lg);
        }

        .service-card:hover::before {
            transform: scaleX(1);
        }

        .service-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.75rem;
            margin-bottom: 1.5rem;
        }

        .service-card h3 {
            font-size: 1.25rem;
            font-weight: 700;
            margin-bottom: 0.75rem;
            color: var(--dark);
        }

        .service-card p {
            color: var(--gray);
            line-height: 1.6;
        }

        .service-tag {
            display: inline-block;
            background: #dbeafe;
            color: var(--primary);
            padding: 0.25rem 0.75rem;
            border-radius: 50px;
            font-size: 0.75rem;
            font-weight: 600;
            margin-top: 1rem;
        }

        /* About Section */
        .about {
            padding: 5rem 2rem;
            background: white;
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }

        .about-image {
            position: relative;
        }

        .about-image img {
            width: 100%;
            border-radius: 20px;
            box-shadow: var(--shadow-lg);
        }

        .experience-badge {
            position: absolute;
            bottom: -20px;
            right: -20px;
            background: var(--primary);
            color: white;
            padding: 2rem;
            border-radius: 20px;
            text-align: center;
            box-shadow: var(--shadow-lg);
        }

        .experience-badge .number {
            font-size: 3rem;
            font-weight: 800;
            display: block;
            line-height: 1;
        }

        .experience-badge .text {
            font-size: 0.875rem;
            opacity: 0.9;
        }

        .about-content h2 {
            font-size: 2.5rem;
            font-weight: 800;
            margin-bottom: 1.5rem;
            color: var(--dark);
        }

        .about-content p {
            color: var(--gray);
            font-size: 1.125rem;
            line-height: 1.8;
            margin-bottom: 1.5rem;
        }

        .about-features {
            list-style: none;
            margin-top: 2rem;
        }

        .about-features li {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            margin-bottom: 1rem;
            font-weight: 500;
        }

        .check-icon {
            width: 24px;
            height: 24px;
            background: var(--success);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.75rem;
            flex-shrink: 0;
        }

        /* Coverage Area */
        .coverage {
            padding: 4rem 2rem;
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white;
            text-align: center;
        }

        .coverage h2 {
            font-size: 2rem;
            margin-bottom: 2rem;
        }

        .areas-grid {
            display: flex;
            justify-content: center;
            gap: 1rem;
            flex-wrap: wrap;
            max-width: 800px;
            margin: 0 auto;
        }

        .area-tag {
            background: rgba(255, 255, 255, 0.2);
            padding: 0.75rem 1.5rem;
            border-radius: 50px;
            font-weight: 600;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.3);
            transition: all 0.3s;
        }

        .area-tag:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-2px);
        }

        /* Contact Section */
        .contact {
            padding: 5rem 2rem;
            background: var(--light);
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
        }

        .contact-info h2 {
            font-size: 2.5rem;
            font-weight: 800;
            margin-bottom: 1rem;
            color: var(--dark);
        }

        .contact-info > p {
            color: var(--gray);
            font-size: 1.125rem;
            margin-bottom: 2rem;
        }

        .contact-methods {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .contact-method {
            display: flex;
            align-items: center;
            gap: 1rem;
            padding: 1.5rem;
            background: white;
            border-radius: 12px;
            box-shadow: var(--shadow);
            transition: all 0.3s;
        }

        .contact-method:hover {
            transform: translateX(5px);
            box-shadow: var(--shadow-lg);
        }

        .contact-icon {
            width: 50px;
            height: 50px;
            background: var(--primary);
            color: white;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.25rem;
        }

        .contact-method div strong {
            display: block;
            color: var(--dark);
            font-weight: 700;
            margin-bottom: 0.25rem;
        }

        .contact-method div span, .contact-method div a {
            color: var(--gray);
            text-decoration: none;
        }

        .contact-method div a:hover {
            color: var(--primary);
        }

        .contact-form {
            background: white;
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: var(--shadow-lg);
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--dark);
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 0.875rem 1rem;
            border: 2px solid #e5e7eb;
            border-radius: 8px;
            font-family: inherit;
            font-size: 1rem;
            transition: all 0.3s;
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(0, 94, 184, 0.1);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 120px;
        }

        .submit-btn {
            width: 100%;
            background: var(--primary);
            color: white;
            padding: 1rem;
            border: none;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
        }

        .submit-btn:hover {
            background: var(--primary-dark);
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(0, 94, 184, 0.2);
        }

        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 3rem 2rem 1rem;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            max-width: 1200px;
            margin: 0 auto 3rem;
        }

        .footer-section h3 {
            font-size: 1.25rem;
            margin-bottom: 1.5rem;
            color: white;
        }

        .footer-section p, .footer-section a {
            color: #94a3b8;
            text-decoration: none;
            line-height: 1.8;
            transition: color 0.3s;
        }

        .footer-section a:hover {
            color: white;
        }

        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid #334155;
            color: #64748b;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Mobile Responsive */
        @media (max-width: 968px) {
            .nav-links {
                display: none;
                position: absolute;
                top: 100%;
                left: 0;
                right: 0;
                background: white;
                flex-direction: column;
                padding: 2rem;
                gap: 1.5rem;
                box-shadow: var(--shadow);
            }

            .nav-links.active {
                display: flex;
            }

            .mobile-menu-btn {
                display: block;
            }

            .hero-container {
                grid-template-columns: 1fr;
                text-align: center;
            }

            .hero h1 {
                font-size: 2.25rem;
            }

            .hero-features {
                justify-content: center;
            }

            .cta-group {
                justify-content: center;
            }

            .hero-image {
                order: -1;
                max-width: 500px;
                margin: 0 auto;
            }

            .floating-card {
                display: none;
            }

            .about-grid,
            .contact-grid {
                grid-template-columns: 1fr;
                gap: 3rem;
            }

            .experience-badge {
                right: 0;
                bottom: -10px;
            }
        }

        @media (max-width: 640px) {
            .hero h1 {
                font-size: 1.875rem;
            }

            .section-header h2,
            .about-content h2,
            .contact-info h2 {
                font-size: 1.875rem;
            }

            .services-grid {
                grid-template-columns: 1fr;
            }

            .btn-primary, .btn-secondary {
                width: 100%;
                justify-content: center;
            }
        }

        /* Utility Classes */
        .text-center {
            text-align: center;
        }

        .mt-2 {
            margin-top: 2rem;
        }

        /* Loading Animation */
        .loading {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 3px solid rgba(255,255,255,.3);
            border-radius: 50%;
            border-top-color: white;
            animation: spin 1s ease-in-out infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        /* Success Message */
        .success-message {
            background: var(--success);
            color: white;
            padding: 1rem;
            border-radius: 8px;
            margin-bottom: 1rem;
            display: none;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav id="navbar">
        <div class="nav-container">
            <a href="#" class="logo">
                <div class="logo-icon">★</div>
                <span>Southstar Plumbers</span>
            </a>
            
            <button class="mobile-menu-btn" onclick="toggleMenu()">☰</button>
            
            <ul class="nav-links" id="navLinks">
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="tel:02088773363" class="nav-phone">📞 020 8877 3363</a></li>
            </ul>
        </div>
    </nav>

    <!-- Emergency Sticky Bar -->
    <div class="emergency-bar">
        <span>🚨 Emergency Plumbing Available 24/7</span>
        <a href="tel:02088773363">Call Now: 020 8877 3363</a>
    </div>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-container">
            <div class="hero-content">
                <div class="hero-badge">
                    <span>⚡</span>
                    <span>Available Now - 24/7 Service</span>
                </div>
                
                <h1>24/7 Emergency Plumbing in South West London</h1>
                
                <p class="hero-subtitle">
                    Fast response for leak repairs, burst pipes, blocked drains. Local plumbers serving Wandsworth, Clapham, Battersea & surrounding areas with rapid 30-minute response times.
                </p>
                
                <div class="hero-features">
                    <div class="feature-item">
                        <div class="feature-icon">✓</div>
                        <span>30 Min Response</span>
                    </div>
                    <div class="feature-item">
                        <div class="feature-icon">✓</div>
                        <span>No Call-Out Fee</span>
                    </div>
                    <div class="feature-item">
                        <div class="feature-icon">✓</div>
                        <span>Fixed Price Quotes</span>
                    </div>
                </div>
                
                <div class="cta-group">
                    <a href="tel:02088773363" class="btn-primary">
                        <span>📞</span>
                        Call Emergency Line
                    </a>
                    <a href="#contact" class="btn-secondary">Get Free Quote</a>
                </div>
            </div>
            
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1585704032915-c3400ca199e7?w=800&auto=format&fit=crop&q=80" alt="Professional plumber fixing sink in South West London home">
                
                <div class="floating-card card-1">
                    <div class="card-icon">🛠️</div>
                    <div>
                        <strong>Emergency Repairs</strong>
                        <div style="font-size: 0.875rem; color: var(--gray);">Available Now</div>
                    </div>
                </div>
                
                <div class="floating-card card-2">
                    <div class="card-icon">⭐</div>
                    <div>
                        <strong>5-Star Rated</strong>
                        <div style="font-size: 0.875rem; color: var(--gray);">200+ Reviews</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-header">
                <h2>Our Emergency Plumbing Services</h2>
                <p>Comprehensive plumbing solutions for homes and businesses across South West London. Available 24 hours a day, 7 days a week.</p>
            </div>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">🚨</div>
                    <h3>Emergency Plumbing & Repairs</h3>
                    <p>Burst pipes, major leaks, or plumbing disasters? Our emergency team responds within 30 minutes to prevent damage to your property.</p>
                    <span class="service-tag">24/7 Available</span>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">💧</div>
                    <h3>Leak Detection & Fix</h3>
                    <p>Advanced leak detection technology to find hidden leaks behind walls or under floors. Fast repair to stop water damage and save on bills.</p>
                    <span class="service-tag">Same Day Service</span>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">🚰</div>
                    <h3>Blocked Drain & Toilet Services</h3>
                    <p>Cleared fast using high-pressure jetting and professional equipment. We handle blocked sinks, toilets, drains, and sewers with guaranteed results.</p>
                    <span class="service-tag">Fixed Price</span>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">🔧</div>
                    <h3>Tap, Sink & Shower Repairs</h3>
                    <p>Dripping taps, faulty showers, or broken sinks repaired quickly. We carry common parts to fix most issues on the first visit.</p>
                    <span class="service-tag">First Visit Fix</span>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">🛁</div>
                    <h3>Bathroom Installation & Fittings</h3>
                    <p>Complete bathroom installations, upgrades, and renovations. From new suites to tiling and plumbing, we handle the entire project.</p>
                    <span class="service-tag">Full Service</span>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">🔥</div>
                    <h3>Boiler & Heating Services</h3>
                    <p>Boiler repairs, servicing, and installations. Gas Safe registered engineers for all your central heating and hot water needs.</p>
                    <span class="service-tag">Gas Safe Reg</span>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-grid">
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?w=800&auto=format&fit=crop&q=80" alt="Southstar Plumbers team in South West London">
                    <div class="experience-badge">
                        <span class="number">15+</span>
                        <span class="text">Years Experience</span>
                    </div>
                </div>
                
                <div class="about-content">
                    <h2>Your Local South West London Plumbers</h2>
                    <p>
                        Southstar Plumbers has been serving the South West London community for over 15 years. Based in Wandsworth, we understand the unique plumbing challenges of Victorian and modern properties across the area.
                    </p>
                    <p>
                        Our team of fully qualified, Gas Safe registered engineers live locally, meaning we can reach you quickly when emergencies strike. We pride ourselves on transparent pricing, quality workmanship, and treating your home with respect.
                    </p>
                    <p>
                        From emergency call-outs at 2 AM to planned bathroom renovations, we bring the same level of professionalism and care to every job. We're not just plumbers—we're your neighbours.
                    </p>
                    
                    <ul class="about-features">
                        <li>
                            <div class="check-icon">✓</div>
                            <span>Fully insured and Gas Safe registered</span>
                        </li>
                        <li>
                            <div class="check-icon">✓</div>
                            <span>30-minute emergency response time</span>
                        </li>
                        <li>
                            <div class="check-icon">✓</div>
                            <span>Fixed price quotes - no hidden fees</span>
                        </li>
                        <li>
                            <div class="check-icon">✓</div>
                            <span>12-month guarantee on all work</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Coverage Area -->
    <section class="coverage">
        <div class="container">
            <h2>Serving All of South West London</h2>
            <div class="areas-grid">
                <div class="area-tag">Wandsworth</div>
                <div class="area-tag">Clapham</div>
                <div class="area-tag">Battersea</div>
                <div class="area-tag">Balham</div>
                <div class="area-tag">Fulham</div>
                <div class="area-tag">Putney</div>
                <div class="area-tag">Earlsfield</div>
                <div class="area-tag">Tooting</div>
                <div class="area-tag">Streatham</div>
                <div class="area-tag">Brixton</div>
            </div>
            <p style="margin-top: 2rem; opacity: 0.9;">And all surrounding SW London postcodes</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="contact-grid">
                <div class="contact-info">
                    <h2>Get In Touch</h2>
                    <p>Need an emergency plumber or want to book a service? Call us 24/7 or fill out the form and we'll get back to you within 15 minutes.</p>
                    
                    <div class="contact-methods">
                        <div class="contact-method">
                            <div class="contact-icon">📞</div>
                            <div>
                                <strong>Emergency Hotline</strong>
                                <a href="tel:02088773363">020 8877 3363</a>
                            </div>
                        </div>
                        
                        <div class="contact-method">
                            <div class="contact-icon">📍</div>
                            <div>
                                <strong>Location</strong>
                                <span>Wandsworth, London, SW18</span>
                            </div>
                        </div>
                        
                        <div class="contact-method">
                            <div class="contact-icon">🕐</div>
                            <div>
                                <strong>Working Hours</strong>
                                <span>24 Hours / 7 Days a Week</span>
                            </div>
                        </div>
                    </div>
                    
                    <div style="background: white; padding: 1.5rem; border-radius: 12px; box-shadow: var(--shadow);">
                        <strong style="color: var(--dark); display: block; margin-bottom: 0.5rem;">Emergency?</strong>
                        <p style="color: var(--gray); font-size: 0.95rem; margin-bottom: 1rem;">Don't wait - call our emergency line now for immediate assistance.</p>
                        <a href="tel:02088773363" class="btn-primary" style="width: 100%; justify-content: center;">Call 020 8877 3363</a>
                    </div>
                </div>
                
                <div class="contact-form">
                    <div class="success-message" id="successMessage">
                        ✅ Thank you! We'll call you back within 15 minutes.
                    </div>
                    
                    <form id="contactForm" onsubmit="handleSubmit(event)">
                        <div class="form-group">
                            <label for="name">Full Name *</label>
                            <input type="text" id="name" name="name" required placeholder="John Smith">
                        </div>
                        
                        <div class="form-group">
                            <label for="phone">Phone Number *</label>
                            <input type="tel" id="phone" name="phone" required placeholder="020 0000 0000">
                        </div>
                        
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" name="email" placeholder="john@example.com">
                        </div>
                        
                        <div class="form-group">
                            <label for="service">Service Required *</label>
                            <select id="service" name="service" required>
                                <option value="">Select a service...</option>
                                <option value="emergency">Emergency Plumbing</option>
                                <option value="leak">Leak Detection</option>
                                <option value="blockage">Blocked Drain/Toilet</option>
                                <option value="repair">Tap/Sink/Shower Repair</option>
                                <option value="bathroom">Bathroom Installation</option>
                                <option value="boiler">Boiler/Heating Issue</option>
                                <option value="other">Other</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="postcode">Postcode *</label>
                            <input type="text" id="postcode" name="postcode" required placeholder="SW18 1AA" style="text-transform: uppercase;">
                        </div>
                        
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" name="message" placeholder="Describe your plumbing issue..."></textarea>
                        </div>
                        
                        <button type="submit" class="submit-btn" id="submitBtn">
                            Request Callback
                        </button>
                        
                        <p style="margin-top: 1rem; font-size: 0.875rem; color: var(--gray); text-align: center;">
                            We respect your privacy. No spam, ever.
                        </p>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-grid">
            <div class="footer-section">
                <h3>Southstar Plumbers</h3>
                <p>Your trusted 24/7 emergency plumbing service in South West London. Fast, reliable, and professional.</p>
                <p style="margin-top: 1rem;">Gas Safe Registered<br>Fully Insured<br>Local Engineers</p>
            </div>
            
            <div class="footer-section">
                <h3>Quick Links</h3>
                <p><a href="#services">Our Services</a></p>
                <p><a href="#about">About Us</a></p>
                <p><a href="#contact">Contact</a></p>
                <p><a href="tel:02088773363">Emergency Call</a></p>
            </div>
            
            <div class="footer-section">
                <h3>Service Areas</h3>
                <p>Wandsworth • Clapham<br>
                Battersea • Balham<br>
                Fulham • Putney<br>
                And surrounding areas</p>
            </div>
            
            <div class="footer-section">
                <h3>Contact</h3>
                <p>📞 <a href="tel:02088773363">020 8877 3363</a></p>
                <p>📍 Wandsworth, London SW18</p>
                <p>🕐 Open 24/7</p>
            </div>
        </div>
        
        <div class="footer-bottom">
            <p>&copy; 2026 Southstar Plumbers. All rights reserved. | Emergency Plumber London</p>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        function toggleMenu() {
            const navLinks = document.getElementById('navLinks');
            navLinks.classList.toggle('active');
        }

        // Close mobile menu when clicking on a link
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                document.getElementById('navLinks').classList.remove('active');
            });
        });

        // Navbar scroll effect
        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.style.boxShadow = '0 4px 6px -1px rgba(0, 0, 0, 0.1)';
            } else {
                navbar.style.boxShadow = '0 1px 3px rgba(0,0,0,0.1)';
            }
        });

        // Form submission
        function handleSubmit(e) {
            e.preventDefault();
            
            const submitBtn = document.getElementById('submitBtn');
            const originalText = submitBtn.innerHTML;
            
            // Show loading
            submitBtn.innerHTML = '<span class="loading"></span> Sending...';
            submitBtn.disabled = true;
            
            // Simulate form submission
            setTimeout(() => {
                document.getElementById('successMessage').style.display = 'block';
                document.getElementById('contactForm').reset();
                submitBtn.innerHTML = originalText;
                submitBtn.disabled = false;
                
                // Scroll to success message
                document.getElementById('successMessage').scrollIntoView({ behavior: 'smooth', block: 'nearest' });
                
                // Hide success message after 5 seconds
                setTimeout(() => {
                    document.getElementById('successMessage').style.display = 'none';
                }, 5000);
            }, 1500);
        }

        // Smooth scroll for anchor links
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

        // Postcode auto-formatting
        document.getElementById('postcode').addEventListener('input', function(e) {
            this.value = this.value.toUpperCase();
        });
    </script>
</body>
</html>
