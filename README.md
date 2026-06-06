<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ibrahim Haladu | Professional IT Portfolio</title>
    <!-- Google Fonts & FontAwesome Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --navy-primary: #1A365D;
            --blue-accent: #2B6CB0;
            --charcoal-text: #2D3748;
            --light-bg: #F7FAFC;
            --border-color: #E2E8F0;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Inter', sans-serif; color: var(--charcoal-text); line-height: 1.6; background-color: #ffffff; }
        
        /* Navigation */
        nav { background: #ffffff; padding: 1rem 2rem; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 4px rgba(0,0,0,0.05); display: flex; justify-content: space-between; align-items: center; }
        nav .brand { font-weight: 700; color: var(--navy-primary); font-size: 1.25rem; }
        nav ul { display: flex; list-style: none; gap: 1.5rem; }
        nav a { text-decoration: none; color: var(--charcoal-text); font-weight: 500; transition: color 0.2s; }
        nav a:hover { color: var(--blue-accent); }

        /* Hero Section */
        header { background: linear-gradient(135deg, var(--navy-primary) 0%, #102A43 100%); color: white; padding: 5rem 2rem; text-align: center; }
        header h1 { font-size: 2.5rem; margin-bottom: 0.5rem; font-weight: 700; letter-spacing: -0.5px; }
        header p { font-size: 1.2rem; color: #E2E8F0; margin-bottom: 1.5rem; font-weight: 300; }
        .badge-container { display: flex; justify-content: center; gap: 0.75rem; flex-wrap: wrap; }
        .badge { background: rgba(255,255,255,0.1); padding: 0.4rem 1rem; border-radius: 50px; font-size: 0.85rem; color: #fff; border: 1px solid rgba(255,255,255,0.2); }

        /* Container & Sections */
        .container { max-width: 1100px; margin: 0 auto; padding: 4rem 2rem; }
        section { margin-bottom: 2rem; }
        h2 { font-size: 1.75rem; color: var(--navy-primary); margin-bottom: 1.5rem; border-bottom: 2px solid var(--border-color); padding-bottom: 0.5rem; }

        /* Services Grid */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; }
        .card { background: var(--light-bg); border: 1px solid var(--border-color); border-radius: 8px; padding: 1.5rem; transition: transform 0.2s, box-shadow 0.2s; }
        .card:hover { transform: translateY(-3px); box-shadow: 0 4px 12px rgba(0,0,0,0.05); }
        .card i { font-size: 2rem; color: var(--blue-accent); margin-bottom: 1rem; }
        .card h3 { font-size: 1.1rem; margin-bottom: 0.5rem; color: var(--navy-primary); }
        .card p { font-size: 0.9rem; color: #4A5568; }

        /* Info Layout */
        .info-block { display: grid; grid-template-columns: 2fr 1fr; gap: 2rem; }
        @media (max-width: 768px) { .info-block { grid-template-columns: 1fr; } }
        .cert-list { list-style: none; }
        .cert-list li { padding: 0.5rem 0; border-bottom: 1px dashed var(--border-color); font-size: 0.95rem; display: flex; align-items: center; gap: 0.5rem; }
        .cert-list i { color: #38A169; }

        /* Contact Details */
        .contact-info { display: flex; flex-direction: column; gap: 0.75rem; font-size: 1rem; margin-top: 1rem; }
        .contact-info a { color: var(--blue-accent); text-decoration: none; font-weight: 600; }
        .contact-info i { width: 24px; color: var(--navy-primary); }

        /* Footer */
        footer { background: #1A202C; color: #A0AEC0; text-align: center; padding: 2rem; font-size: 0.85rem; margin-top: 4rem; }
    </style>
</head>
<body>

    <nav>
        <div class="brand">Codeminds IT Solutions</div>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#credentials">Credentials</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header>
        <h1>Ibrahim Haladu</h1>
        <p>Tech Entrepreneur & Certified Network Engineer</p>
        <div class="badge-container">
            <span class="badge"><i class="fa-solid fa-shield-halved"></i> Cybersecurity Specialist</span>
            <span class="badge"><i class="fa-solid fa-network-wired"></i> Huawei Professional (HCIP)</span>
            <span class="badge"><i class="fa-solid fa-building"></i> CAC Registered Firm</span>
        </div>
    </header>

    <div class="container">
        
        <!-- About Section -->
        <section id="about">
            <h2>Executive Biography</h2>
            <div class="info-block">
                <div>
                    <p style="margin-bottom: 1rem;">Ibrahim Haladu is an accomplished information technology specialist, network engineer, and enterprise tech consultant based in Katsina, Nigeria. As the founder and principal operator of <strong>Codeminds IT Solutions</strong> (CAC Reg: BN 7848329), he manages infrastructure rollouts and digital modernization assets for corporate, educational, and medical organizations across the North-West region.</p>
                    <p>With over five years of multi-sector deployment experience, Ibrahim merges robust theoretical expertise with rigorous hands-on capabilities in infrastructure automation, system protection layout, and enterprise network architectural defenses.</p>
                </div>
                <div class="card" style="background: #EDF2F7; border-left: 4px solid var(--blue-accent);">
                    <h3>Corporate Leadership</h3>
                    <p style="margin: 0.5rem 0; font-size:0.85rem;"><strong>Managing Director</strong><br>Codeminds IT Solutions</p>
                    <p style="margin: 0.5rem 0; font-size:0.85rem;"><strong>Director of ICT</strong><br>Intl. Human Rights Commission (Katsina)</p>
                    <p style="margin: 0.5rem 0; font-size:0.85rem;"><strong>Head of Computer Dept.</strong><br>El-Ladan Foundation</p>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Core Technical Domains</h2>
            <div class="grid">
                <div class="card">
                    <i class="fa-solid fa-network-wired"></i>
                    <h3>Network Engineering</h3>
                    <p>Structural cabling, enterprise routing, local switching architecture, and localized LAN/WAN infrastructure deployment.</p>
                </div>
                <div class="card">
                    <i class="fa-solid fa-lock"></i>
                    <h3>Cybersecurity Defenses</h3>
                    <p>Network environment isolation, firewall integration, cyber defense optimization, and malicious risk mitigation protocols.</p>
                </div>
                <div class="card">
                    <i class="fa-solid fa-video"></i>
                    <h3>CCTV Infrastructure</h3>
                    <p>Complete deployment, network line layouts, camera maintenance engineering, and automated storage backup systems.</p>
                </div>
                <div class="card">
                    <i class="fa-solid fa-tty"></i>
                    <h3>PABX Intercom Line</h3>
                    <p>End-to-end office telecommunications infrastructure wiring, device mapping, configuration, and troubleshooting logs.</p>
                </div>
            </div>
        </section>

        <!-- Education & Certifications -->
        <section id="credentials">
            <h2>Education & Industry Credentials</h2>
            <div class="info-block">
                <div>
                    <h3 style="color: var(--blue-accent); margin-bottom:0.5rem;">Academic Degrees</h3>
                    <p style="margin-bottom:0.5rem;"><strong>B.Sc. in Computer Science</strong> (Second Class Upper)<br><span style="color:#718096; font-size:0.9rem;">Annahada International University | 2023</span></p>
                    <p style="margin-bottom:1.5rem;"><strong>National Innovative Diploma in Networking & System Security</strong><br><span style="color:#718096; font-size:0.9rem;">Katsina State Institute of Technology & Management | 2018</span></p>
                    
                    <h3 style="color: var(--blue-accent); margin-bottom:0.5rem;">Honors & Recognitions</h3>
                    <p style="font-size:0.95rem; margin-bottom:0.3rem;"><i class="fa-solid fa-award" style="color:gold;"></i> <strong>Award of Excellence</strong> (2023) - International Human Rights Commission</p>
                    <p style="font-size:0.95rem;"><i class="fa-solid fa-award" style="color:gold;"></i> <strong>Outstanding Teacher Award</strong> (2022) - El-Ladan Foundation</p>
                </div>
                <div>
                    <h3 style="color: var(--blue-accent); margin-bottom:0.5rem;">Technical Badges</h3>
                    <ul class="cert-list">
                        <li><i class="fa-solid fa-circle-check"></i> Huawei HCIP (Routing & Switching)</li>
                        <li><i class="fa-solid fa-circle-check"></i> Huawei HCIA (Big Data / Storage)</li>
                        <li><i class="fa-solid fa-circle-check"></i> Fortinet NSE 1 & NSE 2</li>
                        <li><i class="fa-solid fa-circle-check"></i> Certified Network Security Specialist</li>
                        <li><i class="fa-solid fa-circle-check"></i> CCNA Cyber Security Operations</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Get In Touch</h2>
            <div class="info-block">
                <div class="contact-info">
                    <p><i class="fa-solid fa-building"></i> <strong>Registered Business:</strong> Codeminds IT Solutions (BN 7848329)</p>
                    <p><i class="fa-solid fa-location-dot"></i> No 34, Nagogo Road, Opposite Korau Cinema, Katsina, Nigeria</p>
                    <p><i class="fa-solid fa-phone"></i> <strong>Phone line:</strong> +2348030491176</p>
                    <p><i class="fa-solid fa-envelope"></i> <strong>Email inbox:</strong> <a href="mailto:ibrahimhaladubk@gmail.com">ibrahimhaladubk@gmail.com</a></p>
                    <p><i class="fa-brands fa-linkedin"></i> <strong>LinkedIn Network:</strong> <a href="https://www.linkedin.com/in/ibrahim-haladu-3b0b50175" target="_blank">Connect with me</a></p>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 Codeminds IT Solutions. All Rights Reserved. Managed by Ibrahim Haladu.</p>
    </footer>

</body>
</html>
