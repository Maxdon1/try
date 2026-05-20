<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A1 Electricals & Plumbing Solutions Ltd. | Ghana - Professional Services</title>
    <meta name="description" content="Professional electrical, plumbing, and dish installation services in Ghana. 24/7 emergency response. Licensed, insured technicians serving Accra and surrounding areas.">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Base Styles */
        :root {
            --primary: #0056b3;
            --secondary: #ff6600;
            --dark: #333;
            --light: #f8f9fa;
            --gray: #6c757d;
            --success: #28a745;
            --ghana-red: #CE1126;
            --ghana-yellow: #FCD116;
            --ghana-green: #006B3F;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
            overflow-x: hidden;
        }
        
        a {
            text-decoration: none;
            color: inherit;
        }
        
        ul {
            list-style: none;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 25px;
            background-color: var(--secondary);
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s ease;
            text-align: center;
        }
        
        .btn:hover {
            background-color: #e55a00;
            transform: translateY(-2px);
        }
        
        .btn-primary {
            background-color: var(--primary);
        }
        
        .btn-primary:hover {
            background-color: #004494;
        }
        
        .btn-success {
            background-color: var(--success);
        }
        
        .btn-success:hover {
            background-color: #218838;
        }
        
        .btn-ghana {
            background: linear-gradient(to right, var(--ghana-red) 33%, var(--ghana-yellow) 33%, var(--ghana-yellow) 66%, var(--ghana-green) 66%);
            color: white;
            font-weight: bold;
        }
        
        section {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 15px;
        }
        
        .section-title p {
            color: var(--gray);
            max-width: 700px;
            margin: 0 auto;
        }
        
        /* Header Styles */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
        }
        
        .logo h1 {
            font-size: 1.8rem;
            color: var(--primary);
        }
        
        .logo span {
            color: var(--secondary);
        }
        
        .nav-menu {
            display: flex;
        }
        
        .nav-menu li {
            margin-left: 25px;
        }
        
        .nav-menu a {
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-menu a:hover {
            color: var(--secondary);
        }
        
        .mobile-toggle {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
        }
        
        /* Social Media Header */
        .social-header {
            background: var(--dark);
            color: white;
            padding: 8px 0;
            font-size: 0.9rem;
        }
        
        .social-header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .social-text {
            font-weight: 500;
        }
        
        .social-icons {
            display: flex;
            gap: 15px;
        }
        
        .social-icons a {
            color: white;
            transition: color 0.3s ease;
        }
        
        .social-icons a:hover {
            color: var(--secondary);
        }
        
        /* Emergency Banner */
        .emergency-banner {
            background: linear-gradient(90deg, var(--secondary), #ff8533);
            color: white;
            padding: 10px 0;
            text-align: center;
            font-weight: 600;
            margin-top: 104px;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(22, 23, 24, 0.7), rgba(0,0,0,0.7)), url('img/A1b.jpeg') no-repeat center center/cover;
            color: white;
            height: 90vh;
            display: flex;
            align-items: center;
            text-align: center;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        
        .hero-btns {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        /* Trust Badges */
        .trust-badges {
            background: white;
            padding: 30px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .badges-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .badge {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            max-width: 200px;
        }
        
        .badge-icon {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 10px;
        }
        
        .badge h3 {
            font-size: 1rem;
            margin-bottom: 5px;
        }
        
        .badge p {
            font-size: 0.9rem;
            color: var(--gray);
        }
        
        /* Services Section */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
            position: relative;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-img {
            height: 200px;
            overflow: hidden;
        }
        
        .service-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .service-card:hover .service-img img {
            transform: scale(1.1);
        }
        
        .service-content {
            padding: 25px;
        }
        
        .service-content h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--primary);
        }
        
        .service-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            z-index: 2000;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        
        .modal-content {
            background: white;
            width: 90%;
            max-width: 800px;
            border-radius: 8px;
            padding: 30px;
            position: relative;
            max-height: 90vh;
            overflow-y: auto;
        }
        
        .close-modal {
            position: absolute;
            top: 15px;
            right: 15px;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--gray);
        }
        
        /* Service Tabs */
        .service-tabs {
            margin-bottom: 40px;
        }
        
        .tab-buttons {
            display: flex;
            justify-content: center;
            margin-bottom: 30px;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .tab-btn {
            padding: 12px 25px;
            background: #f1f1f1;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        
        .tab-btn.active {
            background: var(--primary);
            color: white;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
        
        /* Wiring Comparison */
        .wiring-comparison {
            background: white;
            border-radius: 8px;
            padding: 30px;
            margin-top: 40px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .comparison-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        
        .comparison-table th, .comparison-table td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #eee;
        }
        
        .comparison-table th {
            background-color: var(--primary);
            color: white;
        }
        
        .comparison-table tr:nth-child(even) {
            background-color: #f8f9fa;
        }
        
        /* Plumbing Services */
        .plumbing-services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .plumbing-service {
            background: white;
            border-radius: 8px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .plumbing-service:hover {
            transform: translateY(-5px);
        }
        
        .plumbing-service h3 {
            color: var(--primary);
            margin-bottom: 15px;
            font-size: 1.3rem;
        }
        
        .plumbing-service ul {
            margin-left: 20px;
            margin-bottom: 20px;
        }
        
        .plumbing-service ul li {
            list-style-type: disc;
            margin-bottom: 8px;
        }
        
        /* Direct Contact Options */
        .contact-options {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .contact-option {
            background: white;
            border-radius: 8px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .contact-option:hover {
            transform: translateY(-5px);
        }
        
        .contact-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .contact-option.whatsapp .contact-icon {
            color: #25D366;
        }
        
        .contact-option.call .contact-icon {
            color: var(--secondary);
        }
        
        .contact-option h3 {
            margin-bottom: 15px;
            color: var(--primary);
        }
        
        /* Team Section */
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .team-member {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .member-img {
            height: 250px;
            overflow: hidden;
        }
        
        .member-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .member-info {
            padding: 20px;
        }
        
        .member-info h3 {
            margin-bottom: 5px;
            color: var(--primary);
        }
        
        .member-role {
            color: var(--secondary);
            font-weight: 600;
            margin-bottom: 10px;
        }
        
        .member-certs {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }
        
        .cert-badge {
            background: #f1f1f1;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
        }
        
        /* Service Areas */
        .areas-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        
        .area-group {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .area-group h3 {
            color: var(--primary);
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid #eee;
        }
        
        .area-list {
            list-style: none;
        }
        
        .area-list li {
            margin-bottom: 8px;
            display: flex;
            align-items: center;
        }
        
        .area-list li i {
            color: var(--secondary);
            margin-right: 10px;
        }
        
        /* FAQ Section */
        .faq-container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .faq-item {
            background: white;
            margin-bottom: 15px;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .faq-question {
            padding: 20px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 600;
        }
        
        .faq-answer {
            padding: 0 20px;
            max-height: 0;
            overflow: hidden;
            transition: all 0.3s ease;
        }
        
        .faq-item.active .faq-answer {
            padding: 0 20px 20px;
            max-height: 500px;
        }
        
        .faq-item.active .faq-question i {
            transform: rotate(180deg);
        }
        
        /* WhatsApp Chat Button */
        .whatsapp-chat {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 1000;
            display: flex;
            flex-direction: column;
            align-items: flex-end;
        }
        
        .whatsapp-btn {
            background-color: #25D366;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            transition: all 0.3s ease;
            cursor: pointer;
        }
        
        .whatsapp-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 15px rgba(0,0,0,0.3);
        }
        
        .whatsapp-tooltip {
            background: var(--dark);
            color: white;
            padding: 8px 15px;
            border-radius: 4px;
            margin-bottom: 10px;
            font-size: 0.9rem;
            opacity: 0;
            transform: translateY(10px);
            transition: all 0.3s ease;
            pointer-events: none;
        }
        
        .whatsapp-chat:hover .whatsapp-tooltip {
            opacity: 1;
            transform: translateY(0);
        }
        
        /* About Section */
        .about {
            background-color: white;
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
            align-items: center;
        }
        
        .about-text h2 {
            font-size: 2.2rem;
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .about-features {
            margin-top: 30px;
        }
        
        .feature {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .feature i {
            color: var(--secondary);
            margin-right: 10px;
            font-size: 1.2rem;
        }
        
        .about-img {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .about-img img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        /* Gallery Section */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
        }
        
        .gallery-item {
            border-radius: 8px;
            overflow: hidden;
            height: 250px;
            position: relative;
        }
        
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .gallery-item:hover img {
            transform: scale(1.1);
        }
        
        .gallery-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,86,179,0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .gallery-item:hover .gallery-overlay {
            opacity: 1;
        }
        
        .gallery-overlay h3 {
            color: white;
            text-align: center;
        }
        
        /* Testimonials Section */
        .testimonials {
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url('https://images.unsplash.com/photo-1558618047-3c8c76ca7d13?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            color: white;
            text-align: center;
        }
        
        .testimonial-slider {
            max-width: 800px;
            margin: 0 auto;
            position: relative;
        }
        
        .testimonial {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 8px;
            margin-bottom: 30px;
            backdrop-filter: blur(5px);
        }
        
        .testimonial p {
            font-style: italic;
            margin-bottom: 20px;
        }
        
        .client-info {
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .client-img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 15px;
        }
        
        .client-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .client-details h4 {
            margin-bottom: 5px;
        }
        
        .slider-controls {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        
        .slider-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: rgba(255,255,255,0.5);
            cursor: pointer;
            transition: background 0.3s ease;
        }
        
        .slider-dot.active {
            background: var(--secondary);
        }
        
        /* Contact Section */
        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
        }
        
        .contact-info h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .contact-details {
            margin-bottom: 30px;
        }
        
        .contact-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
        }
        
        .contact-icon {
            background: var(--primary);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            flex-shrink: 0;
        }
        
        /* Social Media Section */
        .social-section {
            background: white;
            text-align: center;
        }
        
        .social-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .social-card {
            background: #f8f9fa;
            border-radius: 8px;
            padding: 30px;
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .social-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .social-card.facebook {
            border-top: 4px solid #3b5998;
        }
        
        .social-card.instagram {
            border-top: 4px solid #e4405f;
        }
        
        .social-card.twitter {
            border-top: 4px solid #1da1f2;
        }
        
        .social-card.linkedin {
            border-top: 4px solid #0077b5;
        }
        
        .social-card.tiktok {
            border-top: 4px solid #000000;
        }
        
        .social-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        
        .social-card.facebook .social-icon {
            color: #3b5998;
        }
        
        .social-card.instagram .social-icon {
            color: #e4405f;
        }
        
        .social-card.twitter .social-icon {
            color: #1da1f2;
        }
        
        .social-card.linkedin .social-icon {
            color: #0077b5;
        }
        
        .social-card.tiktok .social-icon {
            color: #000000;
        }
        
        .social-card h3 {
            margin-bottom: 10px;
            color: var(--dark);
        }
        
        .social-card p {
            margin-bottom: 20px;
            color: var(--gray);
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 60px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-col h3 {
            font-size: 1.3rem;
            margin-bottom: 20px;
            color: var(--secondary);
        }
        
        .footer-col ul li {
            margin-bottom: 10px;
        }
        
        .footer-col ul li a:hover {
            color: var(--secondary);
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background: rgba(255,255,255,0.1);
            border-radius: 50%;
            transition: background 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--secondary);
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255,255,255,0.1);
        }
        
        /* Dish Installation Specific Styles */
        .dish-packages {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .package-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .package-card:hover {
            transform: translateY(-5px);
        }
        
        .package-header {
            background: var(--primary);
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        .package-header h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }
        
        .package-price {
            font-size: 2rem;
            font-weight: bold;
        }
        
        .package-features {
            padding: 20px;
        }
        
        .package-features ul {
            list-style: none;
        }
        
        .package-features li {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }
        
        .package-features li i {
            color: var(--success);
            margin-right: 10px;
        }
        
        /* Responsive Styles - IMPROVED */
        @media (max-width: 1200px) {
            .container {
                width: 95%;
            }
            
            .hero h1 {
                font-size: 3rem;
            }
        }
        
        @media (max-width: 992px) {
            .about-content, .contact-container {
                grid-template-columns: 1fr;
            }
            
            .about-img {
                order: -1;
            }
            
            .badges-container {
                justify-content: center;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .section-title h2 {
                font-size: 2.2rem;
            }
        }
        
        @media (max-width: 768px) {
            .mobile-toggle {
                display: block;
            }
            
            .nav-menu {
                position: fixed;
                top: 104px;
                left: -100%;
                width: 80%;
                height: calc(100vh - 104px);
                background: white;
                flex-direction: column;
                align-items: center;
                padding-top: 50px;
                transition: left 0.3s ease;
                box-shadow: 2px 0 10px rgba(0,0,0,0.1);
            }
            
            .nav-menu.active {
                left: 0;
            }
            
            .nav-menu li {
                margin: 15px 0;
            }
            
            .hero {
                height: 70vh;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .hero-btns {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 100%;
                max-width: 250px;
                margin-bottom: 10px;
            }
            
            .whatsapp-btn {
                width: 50px;
                height: 50px;
                font-size: 1.5rem;
            }
            
            .whatsapp-chat {
                bottom: 20px;
                right: 20px;
            }
            
            .tab-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .tab-btn {
                width: 100%;
                max-width: 300px;
            }
            
            .comparison-table {
                display: block;
                overflow-x: auto;
            }
            
            .social-header {
                display: none;
            }
            
            .emergency-banner {
                margin-top: 70px;
                font-size: 0.9rem;
            }
            
            section {
                padding: 60px 0;
            }
            
            .section-title h2 {
                font-size: 1.8rem;
            }
        }
        
        @media (max-width: 576px) {
            .section-title h2 {
                font-size: 1.6rem;
            }
            
            .hero h1 {
                font-size: 1.8rem;
            }
            
            .service-card, .contact-form {
                padding: 20px;
            }
            
            .modal-content {
                padding: 20px;
            }
            
            .hero {
                height: 60vh;
            }
            
            .trust-badges {
                padding: 20px 0;
            }
            
            .badge {
                max-width: 150px;
            }
            
            .badge-icon {
                font-size: 2rem;
            }
            
            .service-img {
                height: 180px;
            }
            
            .member-img {
                height: 200px;
            }
            
            .gallery-item {
                height: 200px;
            }
        }
        
        @media (max-width: 400px) {
            .logo h1 {
                font-size: 1.4rem;
            }
            
            .hero h1 {
                font-size: 1.5rem;
            }
            
            .section-title h2 {
                font-size: 1.4rem;
            }
            
            .services-grid {
                grid-template-columns: 1fr;
            }
            
            .plumbing-services, .contact-options, .team-grid, .areas-container, .social-grid, .dish-packages {
                grid-template-columns: 1fr;
            }
        }
        
        body{
            background-color: whitesmoke;
        }
    </style>
</head>
<body>
    <!-- Social Media Header -->
    <div class="social-header">
        <div class="container social-header-container">
            <div class="social-text">
                Follow us on social media for updates and tips
            </div>
            <div class="social-icons">
                <a href="https://facebook.com/a1electricalsplumbing" target="_blank"><i class="fab fa-facebook-f"></i></a>
                <a href="https://instagram.com/a1electricalsplumbing" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="https://twitter.com/a1electricalsplumbing" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="https://linkedin.com/company/a1electricalsplumbing" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                <a href="https://tiktok.com/@a1electricalsplumbing" target="_blank"><i class="fab fa-tiktok"></i></a>
            </div>
        </div>
    </div>

    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <h1>A1 <span>Electricals & Plumbing</span></h1>
            </div>
            <div class="mobile-toggle">
                <i class="fas fa-bars"></i>
            </div>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#team">Team</a></li>
                <li><a href="#areas">Areas</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </header>

    <!-- Emergency Banner -->
    <div class="emergency-banner">
        <div class="container">
            <p><i class="fas fa-bolt"></i> 24/7 Emergency Services Available | Response Time: Under 60 Minutes | Call Now: <a href="tel:+233257945238" style="color: black; text-decoration: underline;">+233 257 945 238</a></p>
        </div>
    </div>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container hero-content">
            <h1>Professional Electrical, Plumbing & Dish Installation in Ghana</h1>
            <p>24/7 emergency services with fully qualified and certified technicians. Serving Accra and surrounding areas.</p>
            <div class="hero-btns">
                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20your%20services" target="_blank" class="btn">Chat on WhatsApp</a>
                <a href="tel:+233257945238" class="btn btn-primary">Call Emergency Line</a>
                <a href="#contact" class="btn btn-ghana">Contact Us</a>
            </div>
        </div>
    </section>

    <!-- Trust Badges -->
    <section class="trust-badges">
        <div class="container badges-container">
            <div class="badge">
                <div class="badge-icon">
                    <i class="fas fa-award"></i>
                </div>
                <h3>Licensed & Insured</h3>
                <p>Fully certified and insured for your peace of mind</p>
            </div>
            <div class="badge">
                <div class="badge-icon">
                    <i class="fas fa-clock"></i>
                </div>
                <h3>24/7 Availability</h3>
                <p>Emergency services whenever you need us</p>
            </div>
            <div class="badge">
                <div class="badge-icon">
                    <i class="fas fa-user-check"></i>
                </div>
                <h3>Expert Technicians</h3>
                <p>Highly trained and experienced professionals</p>
            </div>
            <div class="badge">
                <div class="badge-icon">
                    <i class="fas fa-shield-alt"></i>
                </div>
                <h3>1-Year Guarantee</h3>
                <p>All our work comes with a satisfaction guarantee</p>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <div class="section-title">
                <h2>Our Services</h2>
                <p>Comprehensive electrical, plumbing, and dish installation solutions for residential and commercial properties across Ghana</p>
            </div>

            <div class="service-tabs">
                <div class="tab-buttons">
                    <button class="tab-btn active" data-tab="electrical">Electrical Services</button>
                    <button class="tab-btn" data-tab="plumbing">Plumbing Services</button>
                    <button class="tab-btn" data-tab="wiring">Wiring Solutions</button>
                    <button class="tab-btn" data-tab="dish">Dish Installation</button>
                    <button class="tab-btn" data-tab="emergency">Emergency Services</button>
                </div>

                <div class="tab-content active" id="electrical-tab">
                    <div class="services-grid">
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/e work site.png" alt="Electrical Installation" onerror="this.src='https://via.placeholder.com/400x200?text=Electrical+Installation'">
                            </div>
                            <div class="service-content">
                                <h3>Electrical Installation</h3>
                                <p>Complete electrical system installation for new constructions and renovations.</p>
                                <button class="btn learn-more-btn" data-service="electrical">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/repair.jpg" alt="Electrical Repairs" onerror="this.src='https://via.placeholder.com/400x200?text=Electrical+Repairs'">
                            </div>
                            <div class="service-content">
                                <h3>Electrical Repairs</h3>
                                <p>Diagnose and fix electrical issues, from faulty wiring to circuit breaker problems.</p>
                                <button class="btn learn-more-btn" data-service="electrical-repairs">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/electric pannel.jpg" alt="Panel Upgrades" onerror="this.src='https://via.placeholder.com/400x200?text=Panel+Upgrades'">
                            </div>
                            <div class="service-content">
                                <h3>Panel Upgrades</h3>
                                <p>Upgrade your electrical panel to meet modern safety standards and increased power demands.</p>
                                <button class="btn learn-more-btn" data-service="panel-upgrades">Learn More</button>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="plumbing-tab">
                    <div class="services-grid">
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/drain.jpg" alt="Plumbing Repair" onerror="this.src='https://via.placeholder.com/400x200?text=Plumbing+Repair'">
                            </div>
                            <div class="service-content">
                                <h3>Plumbing Repair</h3>
                                <p>Fast and reliable plumbing repairs for leaks, clogs, and other issues.</p>
                                <button class="btn learn-more-btn" data-service="plumbing">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/drain-cleaning.jpg" alt="Drain Cleaning" onerror="this.src='https://via.placeholder.com/400x200?text=Drain+Cleaning'">
                            </div>
                            <div class="service-content">
                                <h3>Drain Cleaning</h3>
                                <p>Professional drain cleaning services to clear stubborn clogs and prevent future blockages.</p>
                                <button class="btn learn-more-btn" data-service="drain-cleaning">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/heater.jpg" alt="Water Heater Services" onerror="this.src='https://via.placeholder.com/400x200?text=Water+Heater+Services'">
                            </div>
                            <div class="service-content">
                                <h3>Water Heater Services</h3>
                                <p>Installation, repair, and maintenance of water heaters for optimal performance.</p>
                                <button class="btn learn-more-btn" data-service="water-heater">Learn More</button>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Enhanced Plumbing Services Section -->
                    <div class="plumbing-services">
                        <div class="plumbing-service">
                            <h3>Residential Plumbing</h3>
                            <ul>
                                <li>Pipe installation and repair</li>
                                <li>Fixture installation (sinks, toilets, showers)</li>
                                <li>Water pressure adjustment</li>
                                <li>Leak detection and repair</li>
                                <li>Water filtration system installation</li>
                            </ul>
                            <a href="https://wa.me/233538222176?text=Hello%2C%20I%20need%20residential%20plumbing%20services" target="_blank" class="btn">Book Service</a>
                        </div>
                        <div class="plumbing-service">
                            <h3>Commercial Plumbing</h3>
                            <ul>
                                <li>Commercial pipe systems</li>
                                <li>Industrial-grade fixtures</li>
                                <li>Backflow prevention</li>
                                <li>Water conservation systems</li>
                                <li>Regular maintenance contracts</li>
                            </ul>
                            <a href="https://wa.me/233538222176?text=Hello%2C%20I%20need%20commercial%20plumbing%20services" target="_blank" class="btn btn-primary">Book Service</a>
                        </div>
                        <div class="plumbing-service">
                            <h3>Emergency Plumbing</h3>
                            <ul>
                                <li>24/7 emergency response</li>
                                <li>Burst pipe repairs</li>
                                <li>Sewage backup cleanup</li>
                                <li>Water damage mitigation</li>
                                <li>Emergency shut-off valve installation</li>
                            </ul>
                            <a href="tel:+233257945238" class="btn">Call Emergency</a>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="wiring-tab">
                    <div class="services-grid">
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/black w electrician.jpg" alt="House Wiring" onerror="this.src='https://via.placeholder.com/400x200?text=House+Wiring'">
                            </div>
                            <div class="service-content">
                                <h3>House Wiring</h3>
                                <p>Complete residential wiring solutions for new homes, renovations, and upgrades.</p>
                                <button class="btn learn-more-btn" data-service="house-wiring">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/industrial wiring.jpg" alt="Industrial Wiring" onerror="this.src='https://via.placeholder.com/400x200?text=Industrial+Wiring'">
                            </div>
                            <div class="service-content">
                                <h3>Industrial Wiring</h3>
                                <p>Professional wiring solutions for factories, warehouses, and industrial facilities.</p>
                                <button class="btn learn-more-btn" data-service="industrial-wiring">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/commercial-wiring.jpg" alt="Commercial Wiring" onerror="this.src='https://via.placeholder.com/400x200?text=Commercial+Wiring'">
                            </div>
                            <div class="service-content">
                                <h3>Commercial Wiring</h3>
                                <p>Electrical wiring for offices, retail spaces, and commercial buildings.</p>
                                <button class="btn learn-more-btn" data-service="commercial-wiring">Learn More</button>
                            </div>
                        </div>
                    </div>

                    <div class="wiring-comparison">
                        <h3>House vs. Industrial Wiring Comparison</h3>
                        <table class="comparison-table">
                            <thead>
                                <tr>
                                    <th>Feature</th>
                                    <th>House Wiring</th>
                                    <th>Industrial Wiring</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>Voltage Requirements</td>
                                    <td>120V/240V Single Phase</td>
                                    <td>240V/415V Three Phase</td>
                                </tr>
                                <tr>
                                    <td>Wire Gauge</td>
                                    <td>14 AWG to 6 AWG</td>
                                    <td>10 AWG to 500 MCM</td>
                                </tr>
                                <tr>
                                    <td>Circuit Protection</td>
                                    <td>Standard Breakers</td>
                                    <td>Industrial MCCBs & Fuses</td>
                                </tr>
                                <tr>
                                    <td>Installation Standards</td>
                                    <td>NEC Residential Code</td>
                                    <td>NEC Industrial Code & Safety Standards</td>
                                </tr>
                                <tr>
                                    <td>Typical Applications</td>
                                    <td>Homes, Apartments</td>
                                    <td>Factories, Plants, Large Facilities</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>

                <!-- Dish Installation Tab -->
                <div class="tab-content" id="dish-tab">
                    <div class="services-grid">
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/dish.jpg" alt="Satellite Dish Installation" onerror="this.src='https://via.placeholder.com/400x200?text=Satellite+Dish+Installation'">
                            </div>
                            <div class="service-content">
                                <h3>Satellite Dish Installation</h3>
                                <p>Professional installation of satellite dishes for clear TV reception and multiple channel options.</p>
                                <button class="btn learn-more-btn" data-service="satellite-dish">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/dish alignment.jpg" alt="Dish Alignment" onerror="this.src='https://via.placeholder.com/400x200?text=Dish+Alignment'">
                            </div>
                            <div class="service-content">
                                <h3>Dish Alignment & Repairs</h3>
                                <p>Precise alignment and repair services to ensure optimal signal strength and picture quality.</p>
                                <button class="btn learn-more-btn" data-service="dish-alignment">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/multi room.jpg" alt="Multi-Room Setup" onerror="this.src='https://via.placeholder.com/400x200?text=Multi-Room+Setup'">
                            </div>
                            <div class="service-content">
                                <h3>Multi-Room Setup</h3>
                                <p>Installation of satellite TV systems for multiple rooms with centralized dish connection.</p>
                                <button class="btn learn-more-btn" data-service="multi-room">Learn More</button>
                            </div>
                        </div>
                    </div>

                    <div class="dish-packages">
                        <div class="package-card">
                            <div class="package-header">
                                <h3>Basic Package</h3>
                                <div class="package-price">₵ 250</div>
                            </div>
                            <div class="package-features">
                                <ul>
                                    <li><i class="fas fa-check"></i> Standard Satellite Dish Installation</li>
                                    <li><i class="fas fa-check"></i> Single TV Connection</li>
                                    <li><i class="fas fa-check"></i> Basic Cable Routing</li>
                                    <li><i class="fas fa-check"></i> Signal Optimization</li>
                                    <li><i class="fas fa-check"></i> 3-Month Warranty</li>
                                </ul>
                                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20Basic%20Dish%20Installation%20Package" target="_blank" class="btn" style="width: 100%; margin-top: 20px;">Book This Package</a>
                            </div>
                        </div>
                        <div class="package-card">
                            <div class="package-header">
                                <h3>Premium Package</h3>
                                <div class="package-price">₵ 450</div>
                            </div>
                            <div class="package-features">
                                <ul>
                                    <li><i class="fas fa-check"></i> Premium Satellite Dish Installation</li>
                                    <li><i class="fas fa-check"></i> Up to 3 TV Connections</li>
                                    <li><i class="fas fa-check"></i> Professional Cable Management</li>
                                    <li><i class="fas fa-check"></i> Signal Booster Installation</li>
                                    <li><i class="fas fa-check"></i> 6-Month Warranty</li>
                                </ul>
                                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20Premium%20Dish%20Installation%20Package" target="_blank" class="btn btn-primary" style="width: 100%; margin-top: 20px;">Book This Package</a>
                            </div>
                        </div>
                        <div class="package-card">
                            <div class="package-header">
                                <h3>Commercial Package</h3>
                                <div class="package-price">₵ 850</div>
                            </div>
                            <div class="package-features">
                                <ul>
                                    <li><i class="fas fa-check"></i> Commercial-Grade Dish Installation</li>
                                    <li><i class="fas fa-check"></i> Up to 8 TV Connections</li>
                                    <li><i class="fas fa-check"></i> Professional Distribution System</li>
                                    <li><i class="fas fa-check"></i> Weather-Proof Installation</li>
                                    <li><i class="fas fa-check"></i> 1-Year Warranty</li>
                                </ul>
                                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20Commercial%20Dish%20Installation%20Package" target="_blank" class="btn" style="width: 100%; margin-top: 20px;">Book This Package</a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="emergency-tab">
                    <div class="services-grid">
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/247.jpg" alt="Emergency Services" onerror="this.src='https://via.placeholder.com/400x200?text=Emergency+Services'">
                            </div>
                            <div class="service-content">
                                <h3>24/7 Emergency Services</h3>
                                <p>Round-the-clock emergency electrical and plumbing services when you need them most.</p>
                                <button class="btn learn-more-btn" data-service="emergency">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/burst pipe.jpg" alt="Burst Pipes" onerror="this.src='https://via.placeholder.com/400x200?text=Burst+Pipes'">
                            </div>
                            <div class="service-content">
                                <h3>Burst Pipe Repair</h3>
                                <p>Emergency response for burst pipes to prevent water damage and restore water flow.</p>
                                <button class="btn learn-more-btn" data-service="burst-pipes">Learn More</button>
                            </div>
                        </div>
                        <div class="service-card">
                            <div class="service-img">
                                <img src="img/power-outage.jpg" alt="Power Outages" onerror="this.src='https://via.placeholder.com/400x200?text=Power+Outages'">
                            </div>
                            <div class="service-content">
                                <h3>Power Outage Response</h3>
                                <p>Quick diagnosis and repair of electrical issues causing power outages in your home or business.</p>
                                <button class="btn learn-more-btn" data-service="power-outage">Learn More</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Service Modals -->
    <div class="service-modal" id="electrical-modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h2>Electrical Installation Services</h2>
            <p>Our certified electricians provide comprehensive electrical installation services for both residential and commercial properties.</p>
            <h3>Our electrical services include:</h3>
            <ul>
                <li>Complete home and office wiring</li>
                <li>Electrical panel upgrades and replacements</li>
                <li>Lighting installation and design</li>
                <li>Outlet and switch installation</li>
                <li>Ceiling fan installation</li>
                <li>Smart home system integration</li>
                <li>Electrical safety inspections</li>
            </ul>
            <p>We use only high-quality materials and follow all safety codes and regulations to ensure your electrical system is safe and reliable.</p>
            <div style="margin-top: 20px;">
                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20electrical%20installation%20services" target="_blank" class="btn">Contact on WhatsApp</a>
                <a href="tel:+233257945238" class="btn btn-primary">Call Now</a>
            </div>
        </div>
    </div>

    <!-- House Wiring Modal -->
    <div class="service-modal" id="house-wiring-modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h2>House Wiring Services</h2>
            <p>Our expert electricians specialize in complete residential wiring solutions for homes, apartments, and residential buildings across Ghana.</p>
            
            <h3>Our House Wiring Services Include:</h3>
            <ul>
                <li>New construction electrical wiring</li>
                <li>Home renovation and rewiring</li>
                <li>Electrical panel installation and upgrades</li>
                <li>Lighting circuit installation</li>
                <li>Power outlet and switch installation</li>
                <li>Grounding and earthing systems</li>
                <li>Surge protection installation</li>
                <li>Smart home wiring solutions</li>
                <li>Backup generator wiring</li>
                <li>Electrical safety inspections and certifications</li>
            </ul>
            
            <h3>Why Choose Our House Wiring Services?</h3>
            <ul>
                <li>Energy Commission certified electricians</li>
                <li>Compliance with Ghana electrical codes</li>
                <li>High-quality materials and workmanship</li>
                <li>Safety-first approach to all installations</li>
                <li>Competitive pricing with transparent quotes</li>
                <li>1-year warranty on all workmanship</li>
            </ul>
            
            <p>We ensure your home's electrical system is safe, efficient, and meets all regulatory requirements for peace of mind.</p>
            
            <div style="margin-top: 20px;">
                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20house%20wiring%20services" target="_blank" class="btn">Contact on WhatsApp</a>
                <a href="tel:+233257945238" class="btn btn-primary">Call Now</a>
            </div>
        </div>
    </div>

    <!-- Industrial Wiring Modal -->
    <div class="service-modal" id="industrial-wiring-modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h2>Industrial Wiring Services</h2>
            <p>We provide professional industrial electrical wiring solutions for factories, manufacturing plants, warehouses, and large commercial facilities throughout Ghana.</p>
            
            <h3>Our Industrial Wiring Services Include:</h3>
            <ul>
                <li>Three-phase power distribution systems</li>
                <li>Motor control center (MCC) installation</li>
                <li>Industrial lighting systems</li>
                <li>Heavy machinery wiring and connections</li>
                <li>Power factor correction systems</li>
                <li>Emergency power and backup systems</li>
                <li>Cable tray and conduit systems</li>
                <li>Industrial control panel wiring</li>
                <li>High-voltage electrical systems</li>
                <li>Electrical safety systems and grounding</li>
            </ul>
            
            <h3>Industries We Serve:</h3>
            <ul>
                <li>Manufacturing and production facilities</li>
                <li>Warehousing and logistics centers</li>
                <li>Food processing plants</li>
                <li>Pharmaceutical facilities</li>
                <li>Mining operations</li>
                <li>Oil and gas facilities</li>
                <li>Commercial agriculture operations</li>
            </ul>
            
            <h3>Our Industrial Wiring Advantages:</h3>
            <ul>
                <li>Experienced industrial electricians</li>
                <li>Compliance with international safety standards</li>
                <li>Custom solutions for specific industrial needs</li>
                <li>Minimal disruption to your operations</li>
                <li>Comprehensive project management</li>
                <li>24/7 emergency industrial support</li>
            </ul>
            
            <p>We understand the critical nature of industrial operations and provide reliable electrical solutions that keep your business running smoothly.</p>
            
            <div style="margin-top: 20px;">
                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20industrial%20wiring%20services" target="_blank" class="btn">Contact on WhatsApp</a>
                <a href="tel:+233257945238" class="btn btn-primary">Call Now</a>
            </div>
        </div>
    </div>

    <!-- Dish Installation Modal -->
    <div class="service-modal" id="satellite-dish-modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h2>Satellite Dish Installation Services</h2>
            <p>Our expert technicians provide professional satellite dish installation services for homes and businesses across Ghana.</p>
            
            <h3>Our Dish Installation Services Include:</h3>
            <ul>
                <li>Professional satellite dish mounting and alignment</li>
                <li>Signal strength optimization for clear reception</li>
                <li>Cable routing and management</li>
                <li>Multi-room TV connections</li>
                <li>Dish network setup and configuration</li>
                <li>Weather-proof installations</li>
                <li>Signal booster installation for weak areas</li>
                <li>Troubleshooting and repairs</li>
                <li>Regular maintenance services</li>
            </ul>
            
            <h3>Why Choose Our Dish Installation Services?</h3>
            <ul>
                <li>Experienced and certified technicians</li>
                <li>High-quality equipment and materials</li>
                <li>Guaranteed signal strength and quality</li>
                <li>Professional cable management</li>
                <li>Competitive pricing with package options</li>
                <li>Warranty on all installations</li>
            </ul>
            
            <h3>Popular Satellite Services We Install:</h3>
            <ul>
                <li>DStv Ghana</li>
                <li>MultiTV</li>
                <li>Free-to-air satellite systems</li>
                <li>Digital satellite television</li>
                <li>International satellite services</li>
            </ul>
            
            <p>We ensure your satellite dish is properly installed and aligned for the best possible TV viewing experience.</p>
            
            <div style="margin-top: 20px;">
                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20satellite%20dish%20installation%20services" target="_blank" class="btn">Contact on WhatsApp</a>
                <a href="tel:+233257945238" class="btn btn-primary">Call Now</a>
            </div>
        </div>
    </div>
    
    <!-- Plumbing Services Modal -->
    <div class="service-modal" id="plumbing-modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h2>Comprehensive Plumbing Services</h2>
            <p>Our licensed plumbers provide complete plumbing solutions for residential and commercial properties across Ghana.</p>
            
            <h3>Our Plumbing Services Include:</h3>
            <ul>
                <li>Pipe installation, repair, and replacement</li>
                <li>Leak detection and repair</li>
                <li>Drain cleaning and unclogging</li>
                <li>Water heater installation and repair</li>
                <li>Fixture installation (sinks, toilets, showers, faucets)</li>
                <li>Water pressure adjustment and testing</li>
                <li>Sewer line inspection and repair</li>
                <li>Backflow prevention installation</li>
                <li>Water filtration system installation</li>
                <li>Emergency plumbing services</li>
            </ul>
            
            <h3>Why Choose Our Plumbing Services?</h3>
            <ul>
                <li>GWCL certified plumbers</li>
                <li>Latest tools and equipment</li>
                <li>Quality materials and workmanship</li>
                <li>Emergency services available 24/7</li>
                <li>Competitive pricing with no hidden fees</li>
                <li>1-year warranty on all plumbing work</li>
            </ul>
            
            <p>We ensure your plumbing system functions efficiently and meets all regulatory standards for safety and performance.</p>
            
            <div style="margin-top: 20px;">
                <a href="https://wa.me/233538222176?text=Hello%2C%20I%20am%20interested%20in%20your%20plumbing%20services" target="_blank" class="btn">Contact on WhatsApp</a>
                <a href="tel:+233257945238" class="btn btn-primary">Call Now</a>
            </div>
        </div>
    </div>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <h2>About A1 Electricals & Plumbing Solutions</h2>
                    <p>With over 15 years of experience, A1 Electricals & Plumbing Solutions Ltd. has been providing top-quality electrical, plumbing, and dish installation services to residential and commercial clients throughout Ghana.</p>
                    <p>Our team of certified professionals is committed to delivering exceptional workmanship, using the latest tools and techniques to ensure your complete satisfaction.</p>
                    <div class="about-features">
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <p>Licensed and insured professionals</p>
                        </div>
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <p>24/7 emergency services available</p>
                        </div>
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <p>Competitive pricing with no hidden fees</p>
                        </div>
                        <div class="feature">
                            <i class="fas fa-check-circle"></i>
                            <p>100% satisfaction guarantee</p>
                        </div>
                    </div>
                    <a href="#contact" class="btn" style="margin-top: 20px;">Contact Us</a>
                </div>
                <div class="about-img">
                    <img src="img/A1 .jpeg" alt="Our Team" onerror="this.src='https://via.placeholder.com/600x400?text=Our+Team'">
                </div>
            </div>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team" style="background-color: whitesmoke;">
        <div class="container">
            <div class="section-title">
                <h2>Our Expert Team</h2>
                <p>Meet our licensed and certified professionals</p>
            </div>
            <div class="team-grid">
                <div class="team-member">
                    <div class="member-img">
                        <img src="img/El master.jpeg" alt="Kwame Mensah" onerror="this.src='https://via.placeholder.com/300x300?text=Kwame+Mensah'">
                    </div>
                    <div class="member-info">
                        <h3>Kwame Mensah</h3>
                        <p class="member-role">Master Electrician</p>
                        <p>15+ years of experience in residential and commercial electrical systems.</p>
                        <div class="member-certs">
                            <span class="cert-badge">Licensed Electrician</span>
                            <span class="cert-badge">Energy Commission Certified</span>
                        </div>
                    </div>
                </div>
                <div class="team-member">
                    <div class="member-img">
                        <img src="img/pl master.jpeg" alt="Abena Osei" onerror="this.src='https://via.placeholder.com/300x300?text=Abena+Osei'">
                    </div>
                    <div class="member-info">
                        <h3>Abena Osei</h3>
                        <p class="member-role">Lead Plumber</p>
                        <p>Specialized in complex plumbing systems and emergency repairs.</p>
                        <div class="member-certs">
                            <span class="cert-badge">Master Plumber</span>
                            <span class="cert-badge">GWCL Certified</span>
                        </div>
                    </div>
                </div>
                <div class="team-member">
                    <div class="member-img">
                        <img src="img/dish master.jpeg" alt="Kofi Asare" onerror="this.src='https://via.placeholder.com/300x300?text=Kofi+Asare'">
                    </div>
                    <div class="member-info">
                        <h3>Kofi Asare</h3>
                        <p class="member-role">Dish Installation Specialist</p>
                        <p>Expert in satellite dish installation and alignment with 8+ years experience.</p>
                        <div class="member-certs">
                            <span class="cert-badge">Satellite Technician</span>
                            <span class="cert-badge">Signal Optimization</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Social Media Section -->
    <section class="social-section">
        <div class="container">
            <div class="section-title">
                <h2>Follow Us on Social Media</h2>
                <p>Stay connected for updates, tips, and special offers</p>
            </div>
            <div class="social-grid">
                <div class="social-card facebook">
                    <div class="social-icon">
                        <i class="fab fa-facebook-f"></i>
                    </div>
                    <h3>Facebook</h3>
                    <p>Follow us for electrical safety tips and service updates</p>
                    <a href="https://facebook.com/a1electricalsplumbing" target="_blank" class="btn">Follow</a>
                </div>
                <div class="social-card instagram">
                    <div class="social-icon">
                        <i class="fab fa-instagram"></i>
                    </div>
                    <h3>Instagram</h3>
                    <p>See our latest projects and behind-the-scenes work</p>
                    <a href="https://instagram.com/a1electricalsplumbing" target="_blank" class="btn">Follow</a>
                </div>
                <div class="social-card twitter">
                    <div class="social-icon">
                        <i class="fab fa-twitter"></i>
                    </div>
                    <h3>Twitter</h3>
                    <p>Get quick updates and industry news</p>
                    <a href="https://twitter.com/a1electricalsplumbing" target="_blank" class="btn">Follow</a>
                </div>
                <div class="social-card tiktok">
                    <div class="social-icon">
                        <i class="fab fa-tiktok"></i>
                    </div>
                    <h3>TikTok</h3>
                    <p>Watch short videos of our work and DIY tips</p>
                    <a href="https://tiktok.com/@a1electricalsplumbing" target="_blank" class="btn">Follow</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Service Areas Section -->
    <section id="areas">
        <div class="container">
            <div class="section-title">
                <h2>Areas We Serve in Ghana</h2>
                <p>We provide electrical, plumbing, and dish installation services throughout Greater Accra and surrounding regions</p>
            </div>
            <div class="areas-container">
                <div class="area-group">
                    <h3>Accra Central</h3>
                    <ul class="area-list">
                        <li><i class="fas fa-map-marker-alt"></i> Osu</li>
                        <li><i class="fas fa-map-marker-alt"></i> Cantonments</li>
                        <li><i class="fas fa-map-marker-alt"></i> Airport Residential</li>
                        <li><i class="fas fa-map-marker-alt"></i> Roman Ridge</li>
                    </ul>
                </div>
                <div class="area-group">
                    <h3>Accra West</h3>
                    <ul class="area-list">
                        <li><i class="fas fa-map-marker-alt"></i> Dansoman</li>
                        <li><i class="fas fa-map-marker-alt"></i> Kaneshie</li>
                        <li><i class="fas fa-map-marker-alt"></i> Odorkor</li>
                        <li><i class="fas fa-map-marker-alt"></i> McCarthy Hill</li>
                    </ul>
                </div>
                <div class="area-group">
                    <h3>Accra East</h3>
                    <ul class="area-list">
                        <li><i class="fas fa-map-marker-alt"></i> Labone</li>
                        <li><i class="fas fa-map-marker-alt"></i> East Legon</li>
                        <li><i class="fas fa-map-marker-alt"></i> Adenta</li>
                        <li><i class="fas fa-map-marker-alt"></i> Madina</li>
                    </ul>
                </div>
                <div class="area-group">
                    <h3>Other Areas</h3>
                    <ul class="area-list">
                        <li><i class="fas fa-map-marker-alt"></i> Tema</li>
                        <li><i class="fas fa-map-marker-alt"></i> Kasoa</li>
                        <li><i class="fas fa-map-marker-alt"></i> Amasaman</li>
                        <li><i class="fas fa-map-marker-alt"></i> Dodowa</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Direct Contact Options -->
    <section id="contact-options" style="background-color: #f8f9fa;">
        <div class="container">
            <div class="section-title">
                <h2>Get In Touch</h2>
                <p>Contact us directly through any of these methods</p>
            </div>
            <div class="contact-options">
                <div class="contact-option whatsapp">
                    <div class="contact-icon">
                        <i class="fab fa-whatsapp"></i>
                    </div>
                    <h3>WhatsApp</h3>
                    <p>Chat with us directly for quick responses and service inquiries</p>
                    <a href="https://wa.me/233538222176?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20your%20services" target="_blank" class="btn">Start Chat</a>
                </div>
                <div class="contact-option call">
                    <div class="contact-icon">
                        <i class="fas fa-phone-alt"></i>
                    </div>
                    <h3>Call Us</h3>
                    <p>Speak directly with our customer service team</p>
                    <a href="tel:+233257945238" class="btn btn-primary">Call Now</a>
                </div>
                <div class="contact-option">
                    <div class="contact-icon">
                        <i class="fas fa-envelope"></i>
                    </div>
                    <h3>Email</h3>
                    <p>Send us an email for detailed inquiries</p>
                    <a href="mailto:info@a1electricalsplumbing.com.gh" class="btn">Send Email</a>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq">
        <div class="container">
            <div class="section-title">
                <h2>Frequently Asked Questions</h2>
                <p>Find answers to common questions about our services</p>
            </div>
            <div class="faq-container">
                <div class="faq-item">
                    <div class="faq-question">
                        <span>What areas in Ghana do you serve?</span>
                        <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        <p>We serve the entire Greater Accra Region including Tema, Kasoa, and surrounding areas. Check our Service Areas section for a complete list of neighborhoods we cover.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>What's the difference between house wiring and industrial wiring?</span>
                        <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        <p>House wiring is designed for residential properties with standard voltage requirements (120V/240V), while industrial wiring handles higher voltages (up to 415V three-phase), heavier loads, and specialized equipment found in factories and large facilities. Industrial wiring also requires more robust safety systems and follows stricter codes.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Do you offer dish installation services?</span>
                        <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        <p>Yes, we offer professional satellite dish installation services including mounting, alignment, cable routing, and multi-room setups. We work with various satellite services including DStv, MultiTV, and free-to-air systems.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Are your technicians licensed and insured?</span>
                        <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        <p>Yes, all our technicians are fully licensed by the Energy Commission of Ghana and other relevant authorities. We carry comprehensive liability insurance for your protection.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Do you offer emergency services?</span>
                        <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        <p>Yes, we offer 24/7 emergency services for both electrical and plumbing issues. Our average response time is under 60 minutes for emergency calls in Accra.</p>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question">
                        <span>How do I request a service?</span>
                        <i class="fas fa-chevron-down"></i>
                    </div>
                    <div class="faq-answer">
                        <p>You can request service by calling our main line, messaging us on WhatsApp, or sending an email. For emergencies, call our 24/7 emergency line.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>What Our Clients Say</h2>
                <p>Don't just take our word for it - hear from our satisfied customers across Ghana.</p>
            </div>
            <div class="testimonial-slider">
                <div class="testimonial">
                    <p>"A1 Electricals & Plumbing solved our emergency plumbing issue at 2 AM on a Sunday. Their response was incredibly fast and professional. Highly recommended!"</p>
                    <div class="client-info">
                        <div class="client-img">
                            <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Kwaku Boateng">
                        </div>
                        <div class="client-details">
                            <h4>Kwaku Boateng</h4>
                            <p>Residential Client, East Legon</p>
                        </div>
                    </div>
                </div>
                <div class="slider-controls">
                    <div class="slider-dot active"></div>
                    <div class="slider-dot"></div>
                    <div class="slider-dot"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us</h2>
                <p>Get in touch with us for all your electrical, plumbing, and dish installation needs in Ghana.</p>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <p>We're here to help with all your electrical, plumbing, and dish installation requirements. Contact us today for a free quote or emergency service.</p>
                    <div class="contact-details">
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <h4>Our Address</h4>
                                <p>123 Service Street, East Legon, Accra, Ghana</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-phone"></i>
                            </div>
                            <div>
                                <h4>Phone Number</h4>
                                <p>+233 257 945 238</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div>
                                <h4>Email Address</h4>
                                <p>info@a1electricalsplumbing.com.gh</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-clock"></i>
                            </div>
                            <div>
                                <h4>Working Hours</h4>
                                <p>24/7 Emergency Services Available</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="contact-info">
                    <h3>Quick Contact Options</h3>
                    <p>Choose the most convenient way to reach us:</p>
                    <div style="display: flex; flex-direction: column; gap: 15px; margin-top: 20px;">
                        <a href="tel:+233257945238" class="btn btn-primary" style="text-align: center;">
                            <i class="fas fa-phone"></i> Call Now
                        </a>
                        <a href="https://wa.me/233538222176?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20your%20services" target="_blank" class="btn" style="text-align: center;">
                            <i class="fab fa-whatsapp"></i> WhatsApp
                        </a>
                        <a href="mailto:info@a1electricalsplumbing.com.gh" class="btn" style="text-align: center;">
                            <i class="fas fa-envelope"></i> Send Email
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-col">
                    <h3>A1 Electricals & Plumbing</h3>
                    <p>Your trusted partner for all electrical, plumbing, and dish installation solutions in Ghana. Quality service you can count on.</p>
                    <div class="social-links">
                        <a href="https://facebook.com/a1electricalsplumbing" target="_blank"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://instagram.com/a1electricalsplumbing" target="_blank"><i class="fab fa-instagram"></i></a>
                        <a href="https://twitter.com/a1electricalsplumbing" target="_blank"><i class="fab fa-twitter"></i></a>
                        <a href="https://tiktok.com/@a1electricalsplumbing" target="_blank"><i class="fab fa-tiktok"></i></a>
                    </div>
                </div>
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#team">Our Team</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Our Services</h3>
                    <ul>
                        <li><a href="#" class="service-link" data-service="electrical">Electrical Installation</a></li>
                        <li><a href="#" class="service-link" data-service="house-wiring">House Wiring</a></li>
                        <li><a href="#" class="service-link" data-service="industrial-wiring">Industrial Wiring</a></li>
                        <li><a href="#" class="service-link" data-service="satellite-dish">Dish Installation</a></li>
                        <li><a href="#" class="service-link" data-service="plumbing">Plumbing Services</a></li>
                        <li><a href="#" class="service-link" data-service="emergency">Emergency Services</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Contact Info</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> 123 Service Street, East Legon, Accra</li>
                        <li><i class="fas fa-phone"></i> +233 257 945 238</li>
                        <li><i class="fas fa-envelope"></i> info@a1electricalsplumbing.com.gh</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 A1 Electricals & Plumbing Solutions Ltd. All Rights Reserved. | Energy Commission License #: EC12345</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Chat Button -->
    <div class="whatsapp-chat">
        <div class="whatsapp-tooltip">Chat with us on WhatsApp</div>
        <a href="https://wa.me/233538222176?text=Hello%2C%20I%20would%20like%20to%20inquire%20about%20your%20services" target="_blank" class="whatsapp-btn">
            <i class="fab fa-whatsapp"></i>
        </a>
    </div>

    <script>
        // Mobile Navigation Toggle
        const mobileToggle = document.querySelector('.mobile-toggle');
        const navMenu = document.querySelector('.nav-menu');
        
        mobileToggle.addEventListener('click', () => {
            navMenu.classList.toggle('active');
            mobileToggle.querySelector('i').classList.toggle('fa-bars');
            mobileToggle.querySelector('i').classList.toggle('fa-times');
        });
        
        // Close mobile menu when clicking on a link
        document.querySelectorAll('.nav-menu a').forEach(link => {
            link.addEventListener('click', () => {
                navMenu.classList.remove('active');
                mobileToggle.querySelector('i').classList.add('fa-bars');
                mobileToggle.querySelector('i').classList.remove('fa-times');
            });
        });
        
        // Service Tabs
        const tabBtns = document.querySelectorAll('.tab-btn');
        const tabContents = document.querySelectorAll('.tab-content');
        
        tabBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                // Remove active class from all buttons and contents
                tabBtns.forEach(b => b.classList.remove('active'));
                tabContents.forEach(c => c.classList.remove('active'));
                
                // Add active class to clicked button
                btn.classList.add('active');
                
                // Show corresponding content
                const tabId = btn.getAttribute('data-tab') + '-tab';
                document.getElementById(tabId).classList.add('active');
            });
        });
        
        // Service Modal Functionality - FIXED
        const learnMoreBtns = document.querySelectorAll('.learn-more-btn');
        const serviceModals = document.querySelectorAll('.service-modal');
        const closeModalBtns = document.querySelectorAll('.close-modal');
        const serviceLinks = document.querySelectorAll('.service-link');
        
        // Open modal when Learn More button is clicked - FIXED
        learnMoreBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                const serviceType = btn.getAttribute('data-service');
                const modal = document.getElementById(`${serviceType}-modal`);
                if (modal) {
                    modal.style.display = 'flex';
                    document.body.style.overflow = 'hidden';
                } else {
                    // Fallback for services without specific modals
                    const defaultModal = document.getElementById('electrical-modal');
                    if (defaultModal) {
                        defaultModal.style.display = 'flex';
                        document.body.style.overflow = 'hidden';
                    }
                }
            });
        });
        
        // Open modal when service link in footer is clicked
        serviceLinks.forEach(link => {
            link.addEventListener('click', (e) => {
                e.preventDefault();
                const serviceType = link.getAttribute('data-service');
                const modal = document.getElementById(`${serviceType}-modal`);
                if (modal) {
                    modal.style.display = 'flex';
                    document.body.style.overflow = 'hidden';
                } else {
                    // Fallback for services without specific modals
                    const defaultModal = document.getElementById('electrical-modal');
                    if (defaultModal) {
                        defaultModal.style.display = 'flex';
                        document.body.style.overflow = 'hidden';
                    }
                }
            });
        });
        
        // Close modal when close button is clicked
        closeModalBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                serviceModals.forEach(modal => {
                    modal.style.display = 'none';
                    document.body.style.overflow = 'auto';
                });
            });
        });
        
        // Close modal when clicking outside the modal content
        serviceModals.forEach(modal => {
            modal.addEventListener('click', (e) => {
                if (e.target === modal) {
                    modal.style.display = 'none';
                    document.body.style.overflow = 'auto';
                }
            });
        });
        
        // FAQ Accordion
        const faqItems = document.querySelectorAll('.faq-item');
        
        faqItems.forEach(item => {
            const question = item.querySelector('.faq-question');
            
            question.addEventListener('click', () => {
                // Close all other items
                faqItems.forEach(otherItem => {
                    if (otherItem !== item) {
                        otherItem.classList.remove('active');
                    }
                });
                
                // Toggle current item
                item.classList.toggle('active');
            });
        });
        
        // Testimonial Slider
        const testimonials = [
            {
                text: "A1 Electricals & Plumbing solved our emergency plumbing issue at 2 AM on a Sunday. Their response was incredibly fast and professional. Highly recommended!",
                name: "Kwaku Boateng",
                role: "Residential Client, East Legon",
                image: "https://randomuser.me/api/portraits/men/32.jpg"
            },
            {
                text: "The team at A1 did an excellent job rewiring our entire office building. They were efficient, clean, and minimized disruption to our business operations.",
                name: "Akosua Adomako",
                role: "Commercial Client, Osu",
                image: "https://randomuser.me/api/portraits/women/44.jpg"
            },
            {
                text: "We hired A1 for dish installation and were impressed with their professionalism. The signal quality is excellent and the installation was clean and tidy.",
                name: "Yaw Asante",
                role: "Homeowner, Tema",
                image: "https://randomuser.me/api/portraits/men/22.jpg"
            }
        ];
        
        const testimonialElement = document.querySelector('.testimonial');
        const dots = document.querySelectorAll('.slider-dot');
        let currentTestimonial = 0;
        
        function updateTestimonial(index) {
            const testimonial = testimonials[index];
            testimonialElement.innerHTML = `
                <p>"${testimonial.text}"</p>
                <div class="client-info">
                    <div class="client-img">
                        <img src="${testimonial.image}" alt="${testimonial.name}">
                    </div>
                    <div class="client-details">
                        <h4>${testimonial.name}</h4>
                        <p>${testimonial.role}</p>
                    </div>
                </div>
            `;
            
            // Update active dot
            dots.forEach((dot, i) => {
                dot.classList.toggle('active', i === index);
            });
        }
        
        // Add click events to dots
        dots.forEach((dot, index) => {
            dot.addEventListener('click', () => {
                currentTestimonial = index;
                updateTestimonial(currentTestimonial);
            });
        });
        
        // Auto-rotate testimonials
        setInterval(() => {
            currentTestimonial = (currentTestimonial + 1) % testimonials.length;
            updateTestimonial(currentTestimonial);
        }, 5000);
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if(targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if(targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Initialize the first testimonial
        updateTestimonial(0);
    </script>
</body>
</html>
