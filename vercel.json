<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create Art Online | Free Digital Drawing Studio & Canvas</title>
    <meta name="description" content="Create stunning digital art online with our free drawing studio. Professional canvas tools, brushes, shapes & colors. No download required. Start drawing instantly at CreatingArtOnline.com!">
    <meta name="keywords" content="create art online, digital drawing, online canvas, free drawing tool, digital art studio, paint online, sketch online, browser drawing app">
    <meta name="author" content="CreatingArtOnline.com">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://creatingartonline.com/">
    <meta property="og:title" content="Create Art Online | Free Digital Drawing Studio">
    <meta property="og:description" content="Professional digital drawing tools right in your browser. Create, sketch & paint online for free. No signup required!">
    <meta property="og:site_name" content="CreatingArtOnline.com">
    
    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://creatingartonline.com/">
    <meta property="twitter:title" content="Create Art Online | Free Digital Drawing Studio">
    <meta property="twitter:description" content="Professional digital drawing tools right in your browser. Create, sketch & paint online for free!">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://creatingartonline.com/">
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800&family=Space+Grotesk:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #6366f1;
            --primary-dark: #4f46e5;
            --secondary: #ec4899;
            --accent: #f59e0b;
            --dark: #0f172a;
            --darker: #020617;
            --light: #f8fafc;
            --gray: #64748b;
            --success: #10b981;
            --gradient-primary: linear-gradient(135deg, #6366f1 0%, #8b5cf6 50%, #ec4899 100%);
            --gradient-dark: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            --shadow-glow: 0 0 40px rgba(99, 102, 241, 0.3);
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
            font-family: 'Outfit', sans-serif;
            background: var(--darker);
            color: var(--light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        h1, h2, h3, h4 {
            font-family: 'Space Grotesk', sans-serif;
            font-weight: 700;
            line-height: 1.2;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            background: rgba(15, 23, 42, 0.8);
            backdrop-filter: blur(20px);
            border-bottom: 1px solid rgba(255,255,255,0.1);
            transition: all 0.3s;
        }

        nav.scrolled {
            padding: 15px 5%;
            background: rgba(15, 23, 42, 0.95);
        }

        .logo {
            font-family: 'Space Grotesk', sans-serif;
            font-size: 26px;
            font-weight: 700;
            background: var(--gradient-primary);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
        }

        .nav-links {
            display: flex;
            gap: 40px;
            list-style: none;
        }

        .nav-links a {
            color: rgba(255,255,255,0.8);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s;
            position: relative;
            font-size: 15px;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--gradient-primary);
            transition: width 0.3s;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .nav-cta {
            padding: 12px 28px;
            background: var(--gradient-primary);
            color: white;
            border: none;
            border-radius: 30px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            font-size: 15px;
            box-shadow: 0 4px 15px rgba(99, 102, 241, 0.4);
        }

        .nav-cta:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(99, 102, 241, 0.5);
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: white;
            font-size: 24px;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            padding: 120px 5% 80px;
            overflow: hidden;
        }

        .hero-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 50%, rgba(99, 102, 241, 0.15) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(236, 72, 153, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 40% 20%, rgba(139, 92, 246, 0.1) 0%, transparent 50%);
            z-index: 0;
        }

        .hero-grid {
            position: absolute;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
                linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
            background-size: 50px 50px;
            z-index: 1;
        }

        .hero-content {
            text-align: center;
            z-index: 2;
            max-width: 900px;
            position: relative;
        }

        .badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 20px;
            background: rgba(99, 102, 241, 0.1);
            border: 1px solid rgba(99, 102, 241, 0.3);
            border-radius: 50px;
            font-size: 14px;
            color: var(--primary);
            margin-bottom: 30px;
            font-weight: 500;
        }

        .hero h1 {
            font-size: clamp(40px, 6vw, 72px);
            margin-bottom: 24px;
            line-height: 1.1;
            background: linear-gradient(to right, #fff 0%, #cbd5e1 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero h1 span {
            background: var(--gradient-primary);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            font-size: 20px;
            color: rgba(255,255,255,0.7);
            margin-bottom: 40px;
            line-height: 1.6;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .hero-buttons {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin-bottom: 60px;
            flex-wrap: wrap;
        }

        .btn-primary {
            padding: 16px 40px;
            background: var(--gradient-primary);
            color: white;
            border: none;
            border-radius: 30px;
            font-weight: 600;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            box-shadow: 0 4px 20px rgba(99, 102, 241, 0.4);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 30px rgba(99, 102, 241, 0.5);
        }

        .btn-secondary {
            padding: 16px 40px;
            background: transparent;
            color: white;
            border: 2px solid rgba(255,255,255,0.2);
            border-radius: 30px;
            font-weight: 600;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }

        .btn-secondary:hover {
            background: rgba(255,255,255,0.1);
            border-color: rgba(255,255,255,0.4);
        }

        .hero-stats {
            display: flex;
            justify-content: center;
            gap: 60px;
            margin-top: 40px;
            flex-wrap: wrap;
        }

        .stat {
            text-align: center;
        }

        .stat-number {
            font-size: 42px;
            font-weight: 800;
            background: var(--gradient-primary);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1;
        }

        .stat-label {
            color: rgba(255,255,255,0.6);
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 5px;
        }

        /* Drawing App Section */
        .studio-section {
            padding: 100px 5%;
            background: var(--dark);
            position: relative;
        }

        .section-header {
            text-align: center;
            margin-bottom: 60px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }

        .section-header h2 {
            font-size: clamp(32px, 4vw, 48px);
            margin-bottom: 16px;
        }

        .section-header p {
            color: rgba(255,255,255,0.6);
            font-size: 18px;
        }

        .drawing-app {
            max-width: 1400px;
            margin: 0 auto;
            background: rgba(255,255,255,0.03);
            border-radius: 24px;
            overflow: hidden;
            box-shadow: var(--shadow-glow), 0 25px 80px rgba(0,0,0,0.5);
            border: 1px solid rgba(255,255,255,0.1);
        }

        .app-header {
            background: rgba(0,0,0,0.3);
            padding: 20px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            flex-wrap: wrap;
            gap: 20px;
        }

        .app-title {
            font-size: 20px;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 12px;
            color: white;
        }

        .app-title span {
            font-size: 28px;
        }

        .app-tools {
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
        }

        .tool-btn {
            width: 48px;
            height: 48px;
            border: none;
            background: rgba(255,255,255,0.1);
            color: white;
            border-radius: 12px;
            cursor: pointer;
            font-size: 22px;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .tool-btn:hover, .tool-btn.active {
            background: var(--primary);
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(99, 102, 241, 0.4);
        }

        .app-body {
            display: flex;
            height: 700px;
        }

        .tools-panel {
            width: 300px;
            background: rgba(0,0,0,0.2);
            padding: 30px;
            overflow-y: auto;
            border-right: 1px solid rgba(255,255,255,0.1);
        }

        .panel-section {
            margin-bottom: 30px;
        }

        .panel-title {
            font-size: 12px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: rgba(255,255,255,0.5);
            margin-bottom: 15px;
            font-weight: 600;
        }

        .color-grid {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 10px;
            margin-bottom: 15px;
        }

        .color-btn {
            width: 42px;
            height: 42px;
            border-radius: 50%;
            border: 3px solid transparent;
            cursor: pointer;
            transition: all 0.2s;
        }

        .color-btn:hover { transform: scale(1.1); }
        .color-btn.active { 
            border-color: white; 
            box-shadow: 0 0 0 2px var(--primary);
        }

        .color-custom-wrapper {
            position: relative;
            height: 50px;
            border-radius: 12px;
            overflow: hidden;
        }

        .color-custom {
            width: 100%;
            height: 100%;
            border: none;
            cursor: pointer;
            padding: 0;
        }

        .slider-group {
            margin-bottom: 20px;
        }

        .slider-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            font-size: 14px;
            color: rgba(255,255,255,0.8);
        }

        .slider {
            width: 100%;
            height: 6px;
            border-radius: 3px;
            background: rgba(255,255,255,0.1);
            outline: none;
            -webkit-appearance: none;
        }

        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: var(--primary);
            cursor: pointer;
            box-shadow: 0 0 10px rgba(99, 102, 241, 0.5);
            transition: transform 0.2s;
        }

        .slider::-webkit-slider-thumb:hover {
            transform: scale(1.2);
        }

        .preview-box {
            width: 100%;
            height: 80px;
            background: rgba(0,0,0,0.3);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 15px;
            border: 1px solid rgba(255,255,255,0.1);
        }

        .brush-preview {
            background: var(--primary);
            border-radius: 50%;
            transition: all 0.2s;
        }

        .action-group {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .panel-btn {
            padding: 12px;
            border: none;
            border-radius: 10px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            font-size: 14px;
        }

        .panel-btn.secondary {
            background: rgba(255,255,255,0.1);
            color: white;
        }

        .panel-btn.secondary:hover {
            background: rgba(255,255,255,0.2);
        }

        .panel-btn.danger {
            background: rgba(239, 68, 68, 0.2);
            color: #ef4444;
        }

        .panel-btn.danger:hover {
            background: rgba(239, 68, 68, 0.3);
        }

        .canvas-wrapper {
            flex: 1;
            background: #0a0a0a;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 40px;
            position: relative;
        }

        #drawingCanvas {
            background: white;
            border-radius: 12px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.5);
            cursor: crosshair;
            max-width: 100%;
            max-height: 100%;
        }

        .floating-actions {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 15px;
            background: rgba(0,0,0,0.8);
            padding: 15px 25px;
            border-radius: 50px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.1);
        }

        .fab {
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 14px;
        }

        .fab.secondary {
            background: rgba(255,255,255,0.1);
            color: white;
        }

        .fab.secondary:hover {
            background: rgba(255,255,255,0.2);
            transform: translateY(-2px);
        }

        .fab.primary {
            background: var(--gradient-primary);
            color: white;
            box-shadow: 0 4px 15px rgba(99, 102, 241, 0.4);
        }

        .fab.primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(99, 102, 241, 0.5);
        }

        /* Features Section */
        .features {
            padding: 100px 5%;
            background: var(--darker);
        }

        .features-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
        }

        .feature-card {
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.1);
            border-radius: 20px;
            padding: 40px;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }

        .feature-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 3px;
            background: var(--gradient-primary);
            transform: scaleX(0);
            transition: transform 0.3s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            background: rgba(255,255,255,0.08);
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }

        .feature-card:hover::before {
            transform: scaleX(1);
        }

        .feature-icon {
            width: 60px;
            height: 60px;
            background: var(--gradient-primary);
            border-radius: 16px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            margin-bottom: 24px;
        }

        .feature-card h3 {
            font-size: 24px;
            margin-bottom: 12px;
            color: white;
        }

        .feature-card p {
            color: rgba(255,255,255,0.6);
            line-height: 1.6;
        }

        /* How It Works */
        .how-it-works {
            padding: 100px 5%;
            background: var(--dark);
        }

        .steps {
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            position: relative;
        }

        .steps::before {
            content: '';
            position: absolute;
            top: 40px;
            left: 0;
            right: 0;
            height: 2px;
            background: rgba(255,255,255,0.1);
            z-index: 0;
        }

        .step {
            text-align: center;
            position: relative;
            z-index: 1;
            flex: 1;
            max-width: 250px;
        }

        .step-number {
            width: 80px;
            height: 80px;
            background: var(--gradient-primary);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 32px;
            font-weight: 800;
            margin: 0 auto 20px;
            box-shadow: 0 0 30px rgba(99, 102, 241, 0.4);
        }

        .step h3 {
            font-size: 20px;
            margin-bottom: 10px;
        }

        .step p {
            color: rgba(255,255,255,0.6);
            font-size: 15px;
        }

        /* Testimonials */
        .testimonials {
            padding: 100px 5%;
            background: var(--darker);
        }

        .testimonials-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
        }

        .testimonial {
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.1);
            border-radius: 20px;
            padding: 30px;
        }

        .testimonial-text {
            font-size: 18px;
            color: rgba(255,255,255,0.9);
            margin-bottom: 20px;
            line-height: 1.6;
            font-style: italic;
        }

        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .author-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: var(--gradient-primary);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            font-size: 20px;
        }

        .author-info h4 {
            font-size: 16px;
            margin-bottom: 4px;
        }

        .author-info p {
            color: rgba(255,255,255,0.5);
            font-size: 14px;
        }

        /* CTA Section */
        .cta-section {
            padding: 100px 5%;
            text-align: center;
            background: var(--gradient-dark);
            position: relative;
            overflow: hidden;
        }

        .cta-section::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(99, 102, 241, 0.1) 0%, transparent 70%);
            animation: pulse 4s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 0.5; }
            50% { transform: scale(1.1); opacity: 0.8; }
        }

        .cta-content {
            position: relative;
            z-index: 1;
            max-width: 700px;
            margin: 0 auto;
        }

        .cta-section h2 {
            font-size: clamp(32px, 4vw, 48px);
            margin-bottom: 20px;
        }

        .cta-section p {
            color: rgba(255,255,255,0.7);
            font-size: 18px;
            margin-bottom: 40px;
        }

        /* Footer */
        footer {
            background: #020617;
            padding: 60px 5% 30px;
            border-top: 1px solid rgba(255,255,255,0.1);
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 2fr 1fr 1fr 1fr;
            gap: 60px;
            margin-bottom: 40px;
        }

        .footer-brand h3 {
            font-size: 24px;
            margin-bottom: 15px;
            background: var(--gradient-primary);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .footer-brand p {
            color: rgba(255,255,255,0.6);
            line-height: 1.6;
            margin-bottom: 20px;
        }

        .social-links {
            display: flex;
            gap: 15px;
        }

        .social-links a {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(255,255,255,0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            transition: all 0.3s;
        }

        .social-links a:hover {
            background: var(--primary);
            transform: translateY(-3px);
        }

        .footer-links h4 {
            font-size: 16px;
            margin-bottom: 20px;
            color: white;
        }

        .footer-links ul {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 12px;
        }

        .footer-links a {
            color: rgba(255,255,255,0.6);
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer-links a:hover {
            color: var(--primary);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: rgba(255,255,255,0.4);
            font-size: 14px;
        }

        /* Responsive */
        @media (max-width: 1024px) {
            .app-body { flex-direction: column; height: auto; }
            .tools-panel { width: 100%; border-right: none; border-bottom: 1px solid rgba(255,255,255,0.1); }
            .canvas-wrapper { min-height: 500px; }
            .footer-content { grid-template-columns: 1fr 1fr; }
            .steps { flex-direction: column; align-items: center; gap: 40px; }
            .steps::before { display: none; }
        }

        @media (max-width: 768px) {
            .nav-links { display: none; }
            .mobile-menu-btn { display: block; }
            .hero { padding: 100px 5% 60px; }
            .hero-buttons { flex-direction: column; align-items: center; }
            .hero-stats { gap: 30px; }
            .stat-number { font-size: 32px; }
            .features-grid, .testimonials-grid { grid-template-columns: 1fr; }
            .footer-content { grid-template-columns: 1fr; gap: 40px; }
            .floating-actions { flex-wrap: wrap; justify-content: center; }
        }

        /* Animations */
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .animate-in {
            animation: fadeInUp 0.6s ease-out forwards;
        }

        /* Toast Notification */
        .toast {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: var(--success);
            color: white;
            padding: 16px 24px;
            border-radius: 12px;
            font-weight: 600;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            transform: translateY(100px);
            opacity: 0;
            transition: all 0.3s;
            z-index: 3000;
        }

        .toast.show {
            transform: translateY(0);
            opacity: 1;
        }

        /* Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }

        ::-webkit-scrollbar-track {
            background: rgba(255,255,255,0.05);
        }

        ::-webkit-scrollbar-thumb {
            background: var(--primary);
            border-radius: 4px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: var(--primary-dark);
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav id="navbar">
        <a href="#" class="logo">
            <span>🎨</span>
            CreatingArtOnline.com
        </a>
        
        <ul class="nav-links">
            <li><a href="#studio">Drawing Studio</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#how-it-works">How It Works</a></li>
            <li><a href="#testimonials">Reviews</a></li>
        </ul>
        
        <a href="#studio" class="nav-cta">Start Drawing</a>
        
        <button class="mobile-menu-btn" onclick="toggleMobileMenu()">☰</button>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-bg"></div>
        <div class="hero-grid"></div>
        
        <div class="hero-content">
            <div class="badge">
                <span>✨</span>
                Free Online Drawing Tool - No Signup Required
            </div>
            
            <h1>Create Stunning Art <span>Online</span> Instantly</h1>
            
            <p>Unleash your creativity with our professional digital drawing studio. Powerful tools, infinite canvas, zero downloads. Start creating masterpieces in seconds.</p>
            
            <div class="hero-buttons">
                <a href="#studio" class="btn-primary">
                    <span>🎨</span>
                    Launch Drawing Studio
                </a>
                <a href="#features" class="btn-secondary">
                    <span>📖</span>
                    Learn More
                </a>
            </div>

            <div class="hero-stats">
                <div class="stat">
                    <div class="stat-number">100%</div>
                    <div class="stat-label">Free Forever</div>
                </div>
                <div class="stat">
                    <div class="stat-number">0</div>
                    <div class="stat-label">Downloads Needed</div>
                </div>
                <div class="stat">
                    <div class="stat-number">∞</div>
                    <div class="stat-label">Creativity</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Drawing Studio Section -->
    <section class="studio-section" id="studio">
        <div class="section-header">
            <h2>Professional Drawing Studio</h2>
            <p>Everything you need to create digital art. Professional tools, intuitive interface, instant results.</p>
        </div>

        <div class="drawing-app">
            <div class="app-header">
                <div class="app-title">
                    <span>🎨</span>
                    CreatingArtOnline Studio
                </div>
                
                <div class="app-tools">
                    <button class="tool-btn active" data-tool="brush" title="Brush Tool">✏️</button>
                    <button class="tool-btn" data-tool="line" title="Line Tool">📏</button>
                    <button class="tool-btn" data-tool="rect" title="Rectangle Tool">⬜</button>
                    <button class="tool-btn" data-tool="circle" title="Circle Tool">⭕</button>
                    <button class="tool-btn" data-tool="eraser" title="Eraser">🧹</button>
                </div>
            </div>

            <div class="app-body">
                <div class="tools-panel">
                    <div class="panel-section">
                        <div class="panel-title">Colors</div>
                        <div class="color-grid">
                            <button class="color-btn active" style="background: #000000" data-color="#000000"></button>
                            <button class="color-btn" style="background: #ffffff" data-color="#ffffff"></button>
                            <button class="color-btn" style="background: #ef4444" data-color="#ef4444"></button>
                            <button class="color-btn" style="background: #f97316" data-color="#f97316"></button>
                            <button class="color-btn" style="background: #f59e0b" data-color="#f59e0b"></button>
                            <button class="color-btn" style="background: #84cc16" data-color="#84cc16"></button>
                            <button class="color-btn" style="background: #10b981" data-color="#10b981"></button>
                            <button class="color-btn" style="background: #06b6d4" data-color="#06b6d4"></button>
                            <button class="color-btn" style="background: #3b82f6" data-color="#3b82f6"></button>
                            <button class="color-btn" style="background: #8b5cf6" data-color="#8b5cf6"></button>
                            <button class="color-btn" style="background: #d946ef" data-color="#d946ef"></button>
                            <button class="color-btn" style="background: #f43f5e" data-color="#f43f5e"></button>
                            <button class="color-btn" style="background: #6366f1" data-color="#6366f1"></button>
                            <button class="color-btn" style="background: #64748b" data-color="#64748b"></button>
                            <button class="color-btn" style="background: #94a3b8" data-color="#94a3b8"></button>
                        </div>
                        <div class="color-custom-wrapper">
                            <input type="color" class="color-custom" id="customColor" value="#6366f1">
                        </div>
                    </div>

                    <div class="panel-section">
                        <div class="panel-title">Brush Settings</div>
                        
                        <div class="slider-group">
                            <div class="slider-header">
                                <span>Size</span>
                                <span id="sizeValue">5px</span>
                            </div>
                            <input type="range" class="slider" id="brushSize" min="1" max="100" value="5">
                        </div>

                        <div class="slider-group">
                            <div class="slider-header">
                                <span>Opacity</span>
                                <span id="opacityValue">100%</span>
                            </div>
                            <input type="range" class="slider" id="opacity" min="1" max="100" value="100">
                        </div>

                        <div class="preview-box">
                            <div class="brush-preview" id="brushPreview" style="width: 10px; height: 10px;"></div>
                        </div>
                    </div>

                    <div class="panel-section">
                        <div class="panel-title">Actions</div>
                        <div class="action-group">
                            <button class="panel-btn secondary" onclick="undo()">
                                <span>↩️</span> Undo
                            </button>
                            <button class="panel-btn secondary" onclick="redo()">
                                <span>↪️</span> Redo
                            </button>
                            <button class="panel-btn danger" onclick="clearCanvas()">
                                <span>🗑️</span> Clear Canvas
                            </button>
                        </div>
                    </div>
                </div>

                <div class="canvas-wrapper">
                    <canvas id="drawingCanvas" width="1000" height="700"></canvas>
                    
                    <div class="floating-actions">
                        <button class="fab secondary" onclick="undo()">
                            <span>↩️</span> Undo
                        </button>
                        <button class="fab secondary" onclick="clearCanvas()">
                            <span>🗑️</span> Clear
                        </button>
                        <button class="fab primary" onclick="saveImage()">
                            <span>💾</span> Save Artwork
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="section-header">
            <h2>Why Artists Love Us</h2>
            <p>Professional features designed for creators of all skill levels</p>
        </div>

        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">⚡</div>
                <h3>Lightning Fast</h3>
                <p>Zero lag drawing experience powered by HTML5 Canvas. Smooth strokes, instant response, professional performance.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">🎨</div>
                <h3>Professional Tools</h3>
                <p>Brushes, shapes, erasers, and precision controls. Everything you need to create stunning digital artwork.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">💾</div>
                <h3>Auto-Save</h3>
                <p>Never lose your work. Automatic local storage saves your progress as you draw. Return anytime to continue.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">📱</div>
                <h3>Works Everywhere</h3>
                <p>Desktop, tablet, or mobile. Touch and stylus support included. Create art on any device, anywhere.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">🌈</div>
                <h3>Unlimited Colors</h3>
                <p>Full spectrum color picker with opacity control. Create the perfect palette for your masterpiece.</p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">🔒</div>
                <h3>100% Private</h3>
                <p>Your art stays on your device. No account required, no data uploaded. Create with complete privacy.</p>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="how-it-works" id="how-it-works">
        <div class="section-header">
            <h2>Start Creating in 3 Steps</h2>
            <p>No downloads, no signup, no hassle</p>
        </div>

        <div class="steps">
            <div class="step">
                <div class="step-number">1</div>
                <h3>Choose Your Tool</h3>
                <p>Select from brushes, shapes, and colors in our intuitive toolbar</p>
            </div>
            
            <div class="step">
                <div class="step-number">2</div>
                <h3>Create Your Art</h3>
                <p>Draw, sketch, and design on our professional canvas</p>
            </div>
            
            <div class="step">
                <div class="step-number">3</div>
                <h3>Save & Share</h3>
                <p>Export your masterpiece as PNG and share with the world</p>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials" id="testimonials">
        <div class="section-header">
            <h2>Loved by Creators</h2>
            <p>See what artists are saying about CreatingArtOnline.com</p>
        </div>

        <div class="testimonials-grid">
            <div class="testimonial">
                <p class="testimonial-text">"Finally, a free drawing tool that actually works! The interface is clean, the tools are responsive, and I love that I don't need to download anything."</p>
                <div class="testimonial-author">
                    <div class="author-avatar">SM</div>
                    <div class="author-info">
                        <h4>Sarah Mitchell</h4>
                        <p>Digital Artist</p>
                    </div>
                </div>
            </div>

            <div class="testimonial">
                <p class="testimonial-text">"I use this for quick sketches and mockups. The auto-save feature has saved me countless times. Highly recommended for any creative!"</p>
                <div class="testimonial-author">
                    <div class="author-avatar">JD</div>
                    <div class="author-info">
                        <h4>James Davidson</h4>
                        <p>UI Designer</p>
                    </div>
                </div>
            </div>

            <div class="testimonial">
                <p class="testimonial-text">"Perfect for teaching my students digital art basics. No accounts needed, works on Chromebooks, and exports easily. A game changer!"</p>
                <div class="testimonial-author">
                    <div class="author-avatar">ER</div>
                    <div class="author-info">
                        <h4>Emma Rodriguez</h4>
                        <p>Art Teacher</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta-section">
        <div class="cta-content">
            <h2>Ready to Create Something Amazing?</h2>
            <p>Join thousands of artists who trust CreatingArtOnline.com for their digital creativity. Free forever, no strings attached.</p>
            <a href="#studio" class="btn-primary" style="font-size: 18px; padding: 18px 48px;">
                <span>🚀</span>
                Start Drawing Now - It's Free!
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-brand">
                <h3>CreatingArtOnline.com</h3>
                <p>Empowering creativity through accessible digital art tools. Free, private, and powerful online drawing studio for everyone.</p>
                <div class="social-links">
                    <a href="#" title="Twitter">𝕏</a>
                    <a href="#" title="Facebook">f</a>
                    <a href="#" title="Instagram">📷</a>
                    <a href="#" title="YouTube">▶</a>
                </div>
            </div>

            <div class="footer-links">
                <h4>Product</h4>
                <ul>
                    <li><a href="#studio">Drawing Studio</a></li>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#">Updates</a></li>
                    <li><a href="#">Roadmap</a></li>
                </ul>
            </div>

            <div class="footer-links">
                <h4>Resources</h4>
                <ul>
                    <li><a href="#">Help Center</a></li>
                    <li><a href="#">Tutorials</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Community</a></li>
                </ul>
            </div>

            <div class="footer-links">
                <h4>Company</h4>
                <ul>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms of Service</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </div>
        </div>

        <div class="footer-bottom">
            <p>&copy; 2024 CreatingArtOnline.com. All rights reserved. Made with ❤️ for artists everywhere.</p>
        </div>
    </footer>

    <!-- Toast Notification -->
    <div class="toast" id="toast">Artwork saved successfully!</div>

    <script>
        // Canvas Setup
        const canvas = document.getElementById('drawingCanvas');
        const ctx = canvas.getContext('2d');
        
        // Set canvas size based on container
        function resizeCanvas() {
            const wrapper = canvas.parentElement;
            const maxWidth = wrapper.clientWidth - 80;
            const maxHeight = wrapper.clientHeight - 80;
            const aspectRatio = 1000 / 700;
            
            let width = maxWidth;
            let height = width / aspectRatio;
            
            if (height > maxHeight) {
                height = maxHeight;
                width = height * aspectRatio;
            }
            
            canvas.style.width = width + 'px';
            canvas.style.height = height + 'px';
        }

        // Initialize
        ctx.fillStyle = '#ffffff';
        ctx.fillRect(0, 0, canvas.width, canvas.height);
        resizeCanvas();
        window.addEventListener('resize', resizeCanvas);

        // State
        let isDrawing = false;
        let currentTool = 'brush';
        let currentColor = '#000000';
        let currentSize = 5;
        let currentOpacity = 1;
        let startX, startY;
        let snapshot;
        let history = [];
        let historyStep = -1;

        // Save initial state
        saveState();

        // Tool Selection
        document.querySelectorAll('.tool-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('.tool-btn').forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                currentTool = btn.dataset.tool;
            });
        });

        // Color Selection
        document.querySelectorAll('.color-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('.color-btn').forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                currentColor = btn.dataset.color;
                updatePreview();
            });
        });

        document.getElementById('customColor').addEventListener('input', (e) => {
            currentColor = e.target.value;
            document.querySelectorAll('.color-btn').forEach(b => b.classList.remove('active'));
            updatePreview();
        });

        // Brush Size
        const sizeSlider = document.getElementById('brushSize');
        const sizeValue = document.getElementById('sizeValue');
        
        sizeSlider.addEventListener('input', (e) => {
            currentSize = parseInt(e.target.value);
            sizeValue.textContent = currentSize + 'px';
            updatePreview();
        });

        // Opacity
        const opacitySlider = document.getElementById('opacity');
        const opacityValue = document.getElementById('opacityValue');
        
        opacitySlider.addEventListener('input', (e) => {
            currentOpacity = parseInt(e.target.value) / 100;
            opacityValue.textContent = Math.round(currentOpacity * 100) + '%';
        });

        function updatePreview() {
            const preview = document.getElementById('brushPreview');
            preview.style.width = currentSize + 'px';
            preview.style.height = currentSize + 'px';
            preview.style.background = currentColor;
            preview.style.opacity = currentOpacity;
        }

        // Drawing Functions
        function getPos(e) {
            const rect = canvas.getBoundingClientRect();
            const scaleX = canvas.width / rect.width;
            const scaleY = canvas.height / rect.height;
            return {
                x: (e.clientX - rect.left) * scaleX,
                y: (e.clientY - rect.top) * scaleY
            };
        }

        function startDrawing(e) {
            isDrawing = true;
            const pos = getPos(e);
            startX = pos.x;
            startY = pos.y;
            
            ctx.beginPath();
            ctx.lineCap = 'round';
            ctx.lineJoin = 'round';
            ctx.lineWidth = currentSize;
            
            const r = parseInt(currentColor.slice(1, 3), 16);
            const g = parseInt(currentColor.slice(3, 5), 16);
            const b = parseInt(currentColor.slice(5, 7), 16);
            ctx.strokeStyle = `rgba(${r}, ${g}, ${b}, ${currentOpacity})`;
            ctx.fillStyle = `rgba(${r}, ${g}, ${b}, ${currentOpacity})`;

            if (currentTool === 'brush') {
                ctx.globalCompositeOperation = 'source-over';
                ctx.moveTo(startX, startY);
            } else if (currentTool === 'eraser') {
                ctx.globalCompositeOperation = 'destination-out';
                ctx.moveTo(startX, startY);
            } else {
                snapshot = ctx.getImageData(0, 0, canvas.width, canvas.height);
            }
        }

        function draw(e) {
            if (!isDrawing) return;
            const pos = getPos(e);

            if (currentTool === 'brush' || currentTool === 'eraser') {
                ctx.lineTo(pos.x, pos.y);
                ctx.stroke();
            } else if (currentTool === 'line') {
                ctx.putImageData(snapshot, 0, 0);
                ctx.beginPath();
                ctx.moveTo(startX, startY);
                ctx.lineTo(pos.x, pos.y);
                ctx.stroke();
            } else if (currentTool === 'rect') {
                ctx.putImageData(snapshot, 0, 0);
                ctx.beginPath();
                ctx.strokeRect(startX, startY, pos.x - startX, pos.y - startY);
            } else if (currentTool === 'circle') {
                ctx.putImageData(snapshot, 0, 0);
                ctx.beginPath();
                const radius = Math.sqrt(Math.pow(pos.x - startX, 2) + Math.pow(pos.y - startY, 2));
                ctx.arc(startX, startY, radius, 0, 2 * Math.PI);
                ctx.stroke();
            }
        }

        function stopDrawing() {
            if (isDrawing) {
                isDrawing = false;
                ctx.globalCompositeOperation = 'source-over';
                saveState();
            }
        }

        // Event Listeners
        canvas.addEventListener('mousedown', startDrawing);
        canvas.addEventListener('mousemove', draw);
        canvas.addEventListener('mouseup', stopDrawing);
        canvas.addEventListener('mouseout', stopDrawing);

        // Touch Support
        canvas.addEventListener('touchstart', (e) => {
            e.preventDefault();
            const touch = e.touches[0];
            canvas.dispatchEvent(new MouseEvent('mousedown', {
                clientX: touch.clientX,
                clientY: touch.clientY
            }));
        });

        canvas.addEventListener('touchmove', (e) => {
            e.preventDefault();
            const touch = e.touches[0];
            canvas.dispatchEvent(new MouseEvent('mousemove', {
                clientX: touch.clientX,
                clientY: touch.clientY
            }));
        });

        canvas.addEventListener('touchend', () => {
            canvas.dispatchEvent(new MouseEvent('mouseup', {}));
        });

        // History Management
        function saveState() {
            historyStep++;
            if (historyStep < history.length) history.length = historyStep;
            history.push(canvas.toDataURL());
            if (history.length > 30) {
                history.shift();
                historyStep--;
            }
            localStorage.setItem('creatingartonline-drawing', history[historyStep]);
        }

        function undo() {
            if (historyStep > 0) {
                historyStep--;
                restoreState();
            }
        }

        function redo() {
            if (historyStep < history.length - 1) {
                historyStep++;
                restoreState();
            }
        }

        function restoreState() {
            const img = new Image();
            img.src = history[historyStep];
            img.onload = () => {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                ctx.drawImage(img, 0, 0);
            };
        }

        function clearCanvas() {
            if (confirm('Clear your canvas? This cannot be undone.')) {
                ctx.fillStyle = '#ffffff';
                ctx.fillRect(0, 0, canvas.width, canvas.height);
                saveState();
            }
        }

        function saveImage() {
            const link = document.createElement('a');
            link.download = 'creatingartonline-masterpiece-' + Date.now() + '.png';
            link.href = canvas.toDataURL();
            link.click();
            
            showToast('Artwork saved successfully! 🎨');
        }

        function showToast(message) {
            const toast = document.getElementById('toast');
            toast.textContent = message;
            toast.classList.add('show');
            setTimeout(() => toast.classList.remove('show'), 3000);
        }

        // Load saved drawing
        window.addEventListener('load', () => {
            const saved = localStorage.getItem('creatingartonline-drawing');
            if (saved) {
                const img = new Image();
                img.src = saved;
                img.onload = () => {
                    ctx.drawImage(img, 0, 0);
                    saveState();
                };
            }
        });

        // Keyboard Shortcuts
        document.addEventListener('keydown', (e) => {
            if ((e.ctrlKey || e.metaKey) && e.key === 'z') {
                e.preventDefault();
                undo();
            }
            if ((e.ctrlKey || e.metaKey) && e.key === 'y') {
                e.preventDefault();
                redo();
            }
            if ((e.ctrlKey || e.metaKey) && e.key === 's') {
                e.preventDefault();
                saveImage();
            }
        });

        // Navigation scroll effect
        window.addEventListener('scroll', () => {
            const nav = document.getElementById('navbar');
            if (window.scrollY > 50) {
                nav.classList.add('scrolled');
            } else {
                nav.classList.remove('scrolled');
            }
        });

        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });

        // Intersection Observer for animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animate-in');
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.feature-card, .testimonial, .step').forEach(el => {
            observer.observe(el);
        });

        // Mobile menu toggle
        function toggleMobileMenu() {
            alert('Mobile menu - implement as needed');
        }
    </script>
</body>
</html>