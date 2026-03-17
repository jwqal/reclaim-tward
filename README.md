<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>#ReclaimTWard | Mulund 2026</title>
    <style>
        :root {
            --neon-purple: #A020F0;
            --deep-black: #050505;
            --raw-white: #f0f0f0;
            --accent-gray: #222;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Helvetica Neue', Arial, sans-serif; cursor: crosshair; }
        
        body { background: var(--deep-black); color: var(--raw-white); line-height: 1.5; overflow-x: hidden; }

        /* Typography */
        h1, h2, h3 { font-family: 'Courier New', Courier, monospace; text-transform: uppercase; font-weight: 900; }
        .glitch-text { color: var(--neon-purple); letter-spacing: -3px; font-size: 8vw; line-height: 0.8; margin-bottom: 20px; }
        
        /* Layout Sections */
        section { padding: 100px 5%; min-height: 80vh; display: flex; flex-direction: column; justify-content: center; }
        .container { max-width: 1200px; margin: auto; }

        /* Hero Section */
        .hero { text-align: left; border-bottom: 5px solid var(--neon-purple); background: url('https://www.transparenttextures.com/patterns/stardust.png'); }
        .manifesto-badge { display: inline-block; background: var(--neon-purple); padding: 5px 15px; font-weight: bold; margin-bottom: 20px; font-size: 0.9rem; }

        /* The Policy Grid */
        .policy-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 40px; margin-top: 50px; }
        .policy-card { border: 2px solid var(--neon-purple); padding: 30px; transition: 0.3s; position: relative; overflow: hidden; }
        .policy-card:hover { background: var(--neon-purple); color: white; transform: translateY(-10px); }
        .policy-card h3 { font-size: 1.5rem; margin-bottom: 15px; }
        .policy-number { position: absolute; top: -10px; right: 10px; font-size: 4rem; opacity: 0.1; font-weight: 900; }

        /* Archive Section (The Researcher Vibe) */
        .archive { background: var(--raw-white); color: var(--deep-black); border-radius: 50px 0 0 0; }
        .archive h2 { color: var(--deep-black); border-bottom: 10px solid var(--neon-purple); display: inline-block; }
        .doc-item { margin-top: 30px; border-left: 5px solid var(--deep-black); padding-left: 20px; }

        /* Interactive Counter */
        .counter-box { text-align: center; background: #111; padding: 50px; border: 2px dashed var(--neon-purple); }
        .stress-level { font-size: 4rem; color: var(--neon-purple); font-weight: bold; }

        /* CTA */
        .cta { background: var(--neon-purple); text-align: center; padding: 80px 20px; }
        .btn { border: 3px solid white; padding: 20px 40px; display: inline-block; text-decoration: none; color: white; font-weight: bold; font-size: 1.2rem; margin-top: 20px; transition: 0.3s; }
        .btn:hover { background: white; color: var(--neon-purple); }

        /* Mobile */
        @media (max-width: 768px) { .glitch-text { font-size: 15vw; } }
    </style>
</head>
<body>

    <section class="hero">
        <div class="container">
            <span class="manifesto-badge">MARCH 2026 | T-WARD | MULUND</span>
            <h1 class="glitch-text">RECLAIM<br>THE CITY.</h1>
            <p style="font-size: 1.5rem; max-width: 600px;">
                You are not a "voter." You are a shareholder in Asia's richest city. 
                Why are you living with 1970s infrastructure in a 2026 economy?
            </p>
        </div>
    </section>

    <section id="policy">
        <div class="container">
            <h2>The 2026 Mandate</h2>
            <div class="policy-grid">
                <div class="policy-card">
                    <span class="policy-number">01</span>
                    <h3>Infrastructure Moratorium</h3>
                    <p>Stop the high-rise "Gold Rush." No new towers in T-Ward until we audit the water pressure and sewer capacity. Development without drainage is just a flood waiting to happen.</p>
                </div>
                <div class="policy-card">
                    <span class="policy-number">02</span>
                    <h3>The Pedestrian Zone</h3>
                    <p>Station Area Management. A 500m radius of clear, walkable, vendor-regulated streets. We reclaim Gokhale Road and Mulund Station West from the chaos.</p>
                </div>
                <div class="policy-card">
                    <span class="policy-number">03</span>
                    <h3>M.T. Agarwal Independence</h3>
                    <p>Opposing the "PPP" model. We keep our hospital public, fully staffed, and equipped with a 24/7 cardiac unit. Health is not a subscription service.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="archive">
        <div class="container">
            <h2>The Research Archive</h2>
            <p><i>Deciphering the BMC's "Bureaucratic Jargon" into Marathi & English.</i></p>
            
            <div class="doc-item">
                <p><strong>[DOCUMENT 106-A]:</strong> The PAP Relocation Fallacy.</p>
                <p>Mulund East is being treated as a dumping ground for the city's planning failures. We fight for equitable distribution, not T-Ward saturation.</p>
            </div>

            <div class="doc-item">
                <p><strong>[DOCUMENT 047-B]:</strong> The Veena Nagar Bottleneck.</p>
                <p>A 1967 DP Road that still doesn't exist. We stop the painting of trees and start the pouring of concrete where it actually matters.</p>
            </div>
        </div>
    </section>

    <section>
        <div class="container counter-box">
            <h3>MULUND'S INFRASTRUCTURE STRESS</h3>
            <div class="stress-level">94%</div>
            <p>Carrying capacity is at a breaking point. Every new high-rise reduces your water pressure by 2%.</p>
        </div>
    </section>

    <section class="cta">
        <div class="container">
            <h2>THE DOCUMENTARY OF OUR DAILY COMMUTE IS A TRAGEDY.</h2>
            <p>LETS CHANGE THE SCRIPT.</p>
            <a href="#" class="btn">JOIN THE RESISTANCE</a>
            <p style="margin-top: 20px; font-size: 0.8rem;">#ReclaimTWard | Election 2026</p>
        </div>
    </section>

    <footer style="padding: 20px; text-align: center; font-size: 0.8rem; background: #000; border-top: 1px solid #333;">
        &copy; 2026 Mulund Social Movement | Authenticated via Street-Level Truths
    </footer>

</body>
</html>
