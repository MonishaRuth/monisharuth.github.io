<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Monisha Ruth - Doctoral candidate in applied economics researching AI impacts on firm performance and the future of work">
    <title>Monisha Ruth | Applied Economics Researcher</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #2563eb;
            --primary-dark: #1e40af;
            --text-dark: #1f2937;
            --text-light: #6b7280;
            --bg-light: #f9fafb;
            --border: #e5e7eb;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background: #ffffff;
        }

        nav {
            background: white;
            border-bottom: 1px solid var(--border);
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
        }

        nav .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h1 {
            font-size: 1.5rem;
            font-weight: 600;
            color: var(--text-dark);
        }

        nav ul {
            display: flex;
            gap: 2rem;
            list-style: none;
        }

        nav a {
            color: var(--text-light);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--primary);
        }

        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('YOUR_NATURE_PHOTO_URL_HERE.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: white;
            padding: 4rem 2rem;
            text-align: center;
        }

        .hero .container {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            font-weight: 700;
        }

        .hero .subtitle {
            font-size: 1.25rem;
            opacity: 0.95;
            margin-bottom: 2rem;
        }

        .hero .affiliation {
            font-size: 1rem;
            opacity: 0.9;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 2rem;
            flex-wrap: wrap;
            margin-top: 2rem;
        }

        .contact-links a {
            color: var(--primary);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 1rem;
            transition: color 0.3s;
        }

        .contact-links a:hover {
            color: var(--primary-dark);
        }

        .contact-links svg {
            width: 20px;
            height: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }

        section {
            margin-bottom: 4rem;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: var(--text-dark);
            font-weight: 600;
            position: relative;
            padding-bottom: 0.5rem;
        }

        h2::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 60px;
            height: 3px;
            background: var(--primary);
        }

        .about-content {
            display: grid;
            grid-template-columns: 200px 1fr;
            gap: 2rem;
            align-items: start;
        }

        .profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            color: white;
            font-weight: 600;
        }

        .bio {
            color: var(--text-light);
            font-size: 1.1rem;
            line-height: 1.8;
        }

        .research-interests {
            background: var(--bg-light);
            padding: 1.5rem;
            border-radius: 8px;
            margin-top: 1.5rem;
        }

        .research-interests h3 {
            font-size: 1.2rem;
            margin-bottom: 1rem;
            color: var(--text-dark);
        }

        .research-interests ul {
            list-style: none;
            display: grid;
            gap: 0.5rem;
        }

        .research-interests li {
            padding-left: 1.5rem;
            position: relative;
            color: var(--text-light);
        }

        .research-interests li::before {
            content: '→';
            position: absolute;
            left: 0;
            color: var(--primary);
            font-weight: bold;
        }

        .card {
            background: white;
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 1rem;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .card:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .card h3 {
            color: var(--text-dark);
            margin-bottom: 0.5rem;
            font-size: 1.3rem;
        }

        .card p {
            color: var(--text-light);
            margin-bottom: 0.5rem;
        }

        .card .meta {
            color: var(--text-light);
            font-size: 0.9rem;
            font-style: italic;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .contact-item {
            background: var(--bg-light);
            padding: 1.5rem;
            border-radius: 8px;
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .contact-item strong {
            color: var(--text-dark);
            font-size: 1.1rem;
        }

        .contact-item a {
            color: var(--primary);
            text-decoration: none;
            transition: color 0.3s;
        }

        .contact-item a:hover {
            color: var(--primary-dark);
            text-decoration: underline;
        }

        .btn {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            background: var(--primary);
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 500;
            transition: background 0.3s;
        }

        .btn:hover {
            background: var(--primary-dark);
        }

        footer {
            background: var(--text-dark);
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
        }

        @media (max-width: 768px) {
            nav ul {
                gap: 1rem;
                font-size: 0.9rem;
            }

            .hero h2 {
                font-size: 2rem;
            }

            .about-content {
                grid-template-columns: 1fr;
                text-align: center;
            }

            .profile-image {
                margin: 0 auto;
            }

            h2::after {
                left: 50%;
                transform: translateX(-50%);
            }
        }
    </style>
</head>
<body>
    <nav>
        <div class="container">
            <h1>Monisha Ruth</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#teaching">Teaching</a></li>
                <li><a href="YOUR_GOOGLE_DRIVE_LINK_HERE" target="_blank">CV</a></li>
            </ul>
        </div>
    </nav>

    <div class="hero">
        <div class="container">
            <h2>Monisha Ruth</h2>
            <p class="subtitle">Doctoral Candidate in Applied Economics</p>
            <p class="affiliation">University of Antwerp | AI-EconLab Research Fellow</p>
        </div>
    </div>

    <div class="container">
        <section id="home">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="profile-image">MR</div>
                <div>
                    <div class="bio">
                        <p>I'm a doctoral candidate in applied economics at the <a href="https://www.uantwerpen.be/en/staff/monisha-punith_24540/" target="_blank" style="color: var(--primary);">Department of Economics</a> at the University of Antwerp, Belgium. I am also a research fellow at the <a href="https://www.ai-econlab.com/people" target="_blank" style="color: var(--primary);">AI-EconLab</a>.</p>
                        
                        <p style="margin-top: 1rem;">My research exists between applied microeconometrics, causal machine learning, and technological change, attempting to broaden our understanding of the impacts of Artificial Intelligence on firm performance, the future of work, structural policies, and growth.</p>
                        
                        <p style="margin-top: 1rem; display: flex; align-items: center; gap: 0.5rem;">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="#dc2626" viewBox="0 0 24 24" stroke="#dc2626" style="width: 20px; height: 20px; flex-shrink: 0;">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                            </svg>
                            Currently on research visit to Sweden for Spring and Fall 2025.
                        </p>
                    </div>
                    
                    <div class="research-interests">
                        <h3>Research Interests</h3>
                        <ul>
                            <li>Applied Microeconometrics</li>
                            <li>Causal Machine Learning</li>
                            <li>AI & Technological Change</li>
                            <li>Firm Performance & Productivity</li>
                            <li>Future of Work</li>
                            <li>Structural Policies & Economic Growth</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section id="research">
            <h2>Research</h2>
            
            <div class="card">
                <h3>Working Papers</h3>
                <p>Information about your current research projects and working papers will appear here.</p>
                <p class="meta">Add your papers with titles, co-authors, and brief descriptions</p>
            </div>

            <div class="card">
                <h3>Publications</h3>
                <p>Your published research will be listed here.</p>
                <p class="meta">Include journal names, publication years, and links</p>
            </div>

            <div class="card">
                <h3>Work in Progress</h3>
                <p>Early-stage research projects and ideas you're currently developing.</p>
                <p class="meta">Brief descriptions of ongoing research</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <div class="contact-grid">
                <div class="contact-item">
                    <strong>Email</strong>
                    <a href="mailto:monisha.punith@uantwerpen.be">monisha.punith@uantwerpen.be</a>
                </div>
                
                <div class="contact-item">
                    <strong>Office</strong>
                    <span>Department of Economics<br>University of Antwerp<br>Belgium</span>
                </div>
                
                <div class="contact-item">
                    <strong>Links</strong>
                    <a href="https://www.uantwerpen.be/en/staff/monisha-punith_24540/" target="_blank">University Profile</a>
                    <a href="https://www.ai-econlab.com/people" target="_blank">AI-EconLab</a>
                </div>
            </div>
            
            <div class="contact-links">
                <a href="https://www.google.com/maps/place/University+of+Antwerp" target="_blank">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                    </svg>
                    Antwerp, Belgium
                </a>
                
                <a href="mailto:monisha.punith@uantwerpen.be">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                    </svg>
                    Email
                </a>
                
                <a href="https://www.linkedin.com/in/YOUR_LINKEDIN" target="_blank">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                    LinkedIn
                </a>
                
                <a href="https://twitter.com/YOUR_TWITTER" target="_blank">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
                    </svg>
                    Twitter
                </a>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Monisha Ruth. All rights reserved.</p>
    </footer>
</body>
</html>
