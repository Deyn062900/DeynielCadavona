<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adrianne Deyniel Cadavona | Professional Resume</title>
    <style>
        :root {
            --primary-blue: #003366;
            --secondary-blue: #00509d;
            --light-blue: #e6f0ff;
            --accent-gold: #ffcc00;
            --text-dark: #333;
            --text-light: #f4f4f4;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: var(--text-dark);
            background-color: #f0f2f5;
        }

        header {
            background: var(--primary-blue);
            color: var(--text-light);
            padding: 3rem 1rem;
            text-align: center;
            border-bottom: 5px solid var(--accent-gold);
        }

        header h1 { margin: 0; font-size: 2.5rem; letter-spacing: 1px; }
        header p { margin: 10px 0; font-size: 1.1rem; opacity: 0.9; }

        .container { max-width: 1000px; margin: 20px auto; padding: 0 20px; }

        /* Interactive Results Section */
        .results-bar {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: -40px;
            margin-bottom: 40px;
        }

        .result-card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-top: 4px solid var(--secondary-blue);
            transition: transform 0.3s ease;
        }

        .result-card:hover { transform: translateY(-5px); }
        .result-card h2 { color: var(--secondary-blue); font-size: 2.2rem; margin: 0; }
        .result-card p { font-size: 0.9rem; font-weight: bold; color: #666; margin: 5px 0 0; }

        section {
            background: white;
            padding: 30px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        h3 {
            color: var(--primary-blue);
            border-bottom: 2px solid var(--light-blue);
            padding-bottom: 10px;
            text-transform: uppercase;
            font-size: 1.2rem;
        }

        .exp-item { margin-bottom: 25px; }
        .exp-header { display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; }
        .exp-title { font-weight: bold; color: var(--secondary-blue); font-size: 1.1rem; }
        .exp-meta { font-style: italic; color: #777; font-size: 0.9rem; }

        ul { padding-left: 20px; }
        li { margin-bottom: 8px; }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 10px;
        }

        .skill-tag {
            background: var(--light-blue);
            color: var(--primary-blue);
            padding: 8px 12px;
            border-radius: 4px;
            font-size: 0.85rem;
            font-weight: 600;
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 40px;
            color: #777;
            font-size: 0.9rem;
        }

        .contact-links a {
            color: var(--text-light);
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        /* Interaction - Simple Highlight */
        .highlight { color: var(--secondary-blue); font-weight: bold; }

    </style>
</head>
<body>

<header>
    <h1>Adrianne Deyniel Cadavona</h1>
    <p>Strategic Sales Account & Marketing Operations Specialist</p>
    <div class="contact-links">
        <a href="mailto:dcadavona29@gmail.com">Email</a> | 
        <a href="https://linkedin.com/in/deynielcorpuz/" target="_blank">LinkedIn</a> | 
        <span>+639999739190</span>
    </div>
</header>

<div class="container">
    <!-- Interactive Results Section -->
    <div class="results-bar">
        <div class="result-card">
            <h2 id="efficiency">80%</h2>
            <p>Operational Improvement</p>
        </div>
        <div class="result-card">
            <h2 id="traffic">1200%</h2>
            <p>Media Traffic Growth</p>
        </div>
        <div class="result-card">
            <h2>3</h2>
            <p>Business Branches Scaled</p>
        </div>
        <div class="result-card">
            <h2>1.73</h2>
            <p>BS Mgmt Econ GWA</p>
        </div>
    </div>

    <section id="summary">
        <h3>Professional Summary</h3>
        <p>Strategic and analytical specialist with proven experience in <span class="highlight">marketing efficiency, automation, and performance optimization</span>. Expert in managing multi-brand operations across global markets including SEA, Africa, and Russia [1, 3].</p>
    </section>

    <section id="experience">
        <h3>Professional Experience</h3>
        
        <div class="exp-item">
            <div class="exp-header">
                <span class="exp-title">Marketing Operations Specialist | Transsion Holdings</span>
                <span class="exp-meta">Dec 2024 – Dec 2025</span>
            </div>
            <ul>
                <li>Managed digital ad campaigns for <span class="highlight">TECNO, Infinix, and itel</span> brands across global regions [1].</li>
                <li>Overhauled SOPs for the entire ad lifecycle, improving overseas operations by <span class="highlight">80%</span> [1].</li>
                <li>Developed marketing dashboards to monitor KPIs and ROI using <span class="highlight">Appsflyer, Apollo, and Eaglwin</span> [1].</li>
            </ul>
        </div>

        <div class="exp-item">
            <div class="exp-header">
                <span class="exp-title">Sales and Marketing Consultant | 18 Degrees North</span>
                <span class="exp-meta">July 2022 – July 2024</span>
            </div>
            <ul>
                <li>Drove a <span class="highlight">1200% increase in media traffic</span> via Meta Business Suite optimization [4, Chat History].</li>
                <li>Scaled business from <span class="highlight">one branch to three</span> and grew team from 8 to 18 employees [2].</li>
                <li>Acted as Manager for one year, overseeing all business processes and creative production [2].</li>
            </ul>
        </div>
    </section>

    <section id="skills">
        <h3>Technical Skills</h3>
        <div class="skills-grid">
            <div class="skill-tag">Google Analytics</div>
            <div class="skill-tag">Meta Business Suite</div>
            <div class="skill-tag">Appsflyer / Adjust</div>
            <div class="skill-tag">Apollo (Sales Intel)</div>
            <div class="skill-tag">SPSS / R Studio</div>
            <div class="skill-tag">Adobe Premiere Pro</div>
            <div class="skill-tag">Photoshop / Canva</div>
            <div class="skill-tag">Trello / Notion / Lark</div>
        </div>
    </section>

    <section id="education">
        <h3>Education & Honors</h3>
        <p><strong>Bachelor of Science in Management Economics</strong><br>
        University of the Philippines - Baguio | 1.73 GWA [4]</p>
        <p><strong>Other:</strong> UN Movers Programme Fellow, UNESCO & UNDP Volunteer [5]</p>
    </section>
</div>

<footer>
    <p>&copy; 2026 Adrianne Deyniel Cadavona | Built for Operational Excellence</p>
</footer>

<script>
    // Simple interactive effect: Click a result card to see a console alert or change color
    const cards = document.querySelectorAll('.result-card');
    cards.forEach(card => {
        card.addEventListener('click', () => {
            card.style.borderColor = '#ffcc00';
            console.log("Exploring Adrianne's metrics...");
        });
    });
</script>

</body>
</html>
