<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>✨ Joyal M | Aesthetic Introduction ✨</title>
    <!-- Google Fonts for modern typography -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700&family=Space+Grotesk:wght@400;500;600&display=swap" rel="stylesheet">
    <!-- Font Awesome 6 (free icons) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            background: linear-gradient(145deg, #f9f4ea 0%, #f0e7db 100%);
            font-family: 'Inter', 'Space Grotesk', system-ui, -apple-system, sans-serif;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 2rem;
            position: relative;
            overflow-x: hidden;
        }

        /* animated grain texture */
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: radial-gradient(rgba(0, 0, 0, 0.03) 1.2px, transparent 1px);
            background-size: 32px 32px;
            pointer-events: none;
            z-index: 0;
        }

        /* floating blobs - aesthetic background */
        .blob {
            position: fixed;
            border-radius: 50%;
            filter: blur(70px);
            z-index: 0;
            opacity: 0.5;
            animation: floatBlob 18s infinite alternate ease-in-out;
        }

        .blob-1 {
            width: 400px;
            height: 400px;
            background: #ffd6b0;
            top: -150px;
            left: -100px;
        }

        .blob-2 {
            width: 500px;
            height: 500px;
            background: #c7e3d4;
            bottom: -200px;
            right: -150px;
            animation-duration: 24s;
            opacity: 0.45;
        }

        .blob-3 {
            width: 280px;
            height: 280px;
            background: #e3c9bc;
            top: 40%;
            right: 10%;
            animation-duration: 20s;
            filter: blur(90px);
            opacity: 0.4;
        }

        @keyframes floatBlob {
            0% { transform: translate(0px, 0px) scale(1); }
            100% { transform: translate(40px, 30px) scale(1.1); }
        }

        /* main card container */
        .card {
            position: relative;
            z-index: 10;
            max-width: 780px;
            width: 100%;
            background: rgba(255, 252, 245, 0.85);
            backdrop-filter: blur(12px);
            border-radius: 3rem;
            box-shadow: 0 30px 50px rgba(0, 0, 0, 0.08), 0 10px 25px rgba(0, 0, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.6);
            padding: 2rem 2rem 2.5rem;
            border: 1px solid rgba(255, 245, 225, 0.7);
            transition: all 0.3s ease;
        }

        /* decorative lines */
        .card::after {
            content: '';
            position: absolute;
            bottom: 20px;
            right: 30px;
            width: 120px;
            height: 120px;
            background: radial-gradient(circle, rgba(210, 180, 140, 0.15) 1px, transparent 1px);
            background-size: 18px 18px;
            border-radius: 50%;
            pointer-events: none;
            z-index: -1;
        }

        /* header area */
        .greeting {
            display: flex;
            align-items: baseline;
            gap: 0.5rem;
            flex-wrap: wrap;
            margin-bottom: 1rem;
        }

        .wave {
            font-size: 2.8rem;
            display: inline-block;
            animation: waveHand 1.8s infinite ease;
            transform-origin: 70% 70%;
        }

        @keyframes waveHand {
            0% { transform: rotate(0deg); }
            20% { transform: rotate(12deg); }
            40% { transform: rotate(-6deg); }
            60% { transform: rotate(8deg); }
            80% { transform: rotate(-2deg); }
            100% { transform: rotate(0deg); }
        }

        .name-title {
            font-size: 1.1rem;
            font-weight: 500;
            letter-spacing: 0.3px;
            color: #b87c4f;
            background: rgba(184, 124, 79, 0.12);
            padding: 0.2rem 1rem;
            border-radius: 40px;
            backdrop-filter: blur(4px);
        }

        .hero {
            margin: 1.2rem 0 1rem;
        }

        .hi-line {
            font-size: 1.8rem;
            font-weight: 400;
            color: #5e3e2b;
            letter-spacing: -0.3px;
            margin-bottom: 0.25rem;
        }

        .big-name {
            font-size: 4.5rem;
            font-weight: 700;
            font-family: 'Space Grotesk', monospace;
            background: linear-gradient(135deg, #2c221b, #a05e3a, #c7865f);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            line-height: 1.1;
            letter-spacing: -0.02em;
            margin: 0.25rem 0 0.5rem;
            text-shadow: 2px 2px 12px rgba(160, 94, 58, 0.1);
        }

        .title-tag {
            font-size: 1.3rem;
            font-weight: 500;
            color: #7c5a42;
            border-left: 4px solid #e6b17e;
            padding-left: 1rem;
            margin: 0.75rem 0 1rem;
            display: flex;
            align-items: center;
            gap: 10px;
            flex-wrap: wrap;
        }

        .title-tag i {
            color: #d49466;
            font-size: 1.2rem;
        }

        .description {
            font-size: 1rem;
            line-height: 1.6;
            color: #4b3a2c;
            font-weight: 400;
            background: rgba(250, 245, 235, 0.6);
            padding: 1.2rem 1.5rem;
            border-radius: 2rem;
            margin: 1.5rem 0 1.8rem;
            backdrop-filter: blur(4px);
            border: 1px solid rgba(230, 177, 126, 0.3);
        }

        .stats-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: space-between;
            margin: 2rem 0 2rem;
        }

        .stat-item {
            flex: 1;
            min-width: 100px;
            background: rgba(255, 248, 235, 0.7);
            border-radius: 1.5rem;
            padding: 0.8rem 0.5rem;
            text-align: center;
            backdrop-filter: blur(2px);
            transition: all 0.2s;
            border: 1px solid rgba(210, 170, 120, 0.25);
        }

        .stat-item i {
            font-size: 1.6rem;
            color: #c28254;
            margin-bottom: 0.4rem;
            display: inline-block;
        }

        .stat-number {
            font-weight: 700;
            font-size: 1.3rem;
            color: #4e3222;
            letter-spacing: -0.3px;
        }

        .stat-label {
            font-size: 0.75rem;
            font-weight: 500;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: #8e6a4e;
            margin-top: 0.2rem;
        }

        .social-links {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
            margin: 2rem 0 1.5rem;
        }

        .social-btn {
            background: rgba(245, 235, 220, 0.8);
            backdrop-filter: blur(8px);
            padding: 0.7rem 1.3rem;
            border-radius: 60px;
            display: inline-flex;
            align-items: center;
            gap: 12px;
            font-weight: 500;
            font-size: 0.9rem;
            color: #5a3c28;
            text-decoration: none;
            transition: all 0.25s ease;
            border: 1px solid rgba(200, 160, 120, 0.3);
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.02);
        }

        .social-btn i {
            font-size: 1.2rem;
            color: #b56f44;
            transition: transform 0.2s;
        }

        .social-btn:hover {
            background: #ffffffcc;
            border-color: #d69e6e;
            transform: translateY(-3px);
            box-shadow: 0 12px 18px -10px rgba(100, 60, 30, 0.2);
        }

        .social-btn:hover i {
            transform: scale(1.05);
            color: #aa6a3e;
        }

        .quote {
            text-align: center;
            margin-top: 2rem;
            font-size: 0.85rem;
            font-style: italic;
            color: #8c6b4c;
            border-top: 1px dashed rgba(160, 110, 70, 0.25);
            padding-top: 1.5rem;
            letter-spacing: 0.2px;
        }

        .quote i {
            color: #ca8f60;
            margin: 0 4px;
        }

        /* subtle responsive */
        @media (max-width: 620px) {
            body {
                padding: 1rem;
            }
            .card {
                padding: 1.5rem;
            }
            .big-name {
                font-size: 2.8rem;
            }
            .hi-line {
                font-size: 1.4rem;
            }
            .stats-grid {
                gap: 0.7rem;
            }
            .social-btn {
                padding: 0.5rem 1rem;
                font-size: 0.8rem;
            }
            .description {
                padding: 1rem;
            }
        }

        /* custom cursor / aesthetic dot */
        .cursor-dot {
            width: 6px;
            height: 6px;
            background: #c58f62;
            border-radius: 50%;
            position: fixed;
            pointer-events: none;
            z-index: 999;
            transition: transform 0.05s linear;
            opacity: 0.6;
        }

        @media (max-width: 768px) {
            .cursor-dot {
                display: none;
            }
        }
    </style>
</head>
<body>

<div class="blob blob-1"></div>
<div class="blob blob-2"></div>
<div class="blob blob-3"></div>

<div class="card">
    <!-- Header with wave & badge -->
    <div class="greeting">
        <span class="wave">👋🏼</span>
        <span class="name-title">digital artisan / creative coder</span>
    </div>

    <div class="hero">
        <div class="hi-line">Hi, I'm</div>
        <h1 class="big-name">Joyal M</h1>
        <div class="title-tag">
            <i class="fas fa-code"></i> 
            <span>crafting digital experiences & minimal aesthetics</span>
            <i class="fas fa-sparkle" style="font-size: 0.9rem;"></i>
        </div>
    </div>

    <div class="description">
        <i class="fas fa-feather-alt" style="margin-right: 8px; opacity: 0.7;"></i>
        A passionate designer-developer hybrid who believes in the poetry of code and the elegance of simplicity. 
        I build interactive web things, design systems, and occasionally write about design philosophy. 
        Currently exploring generative aesthetics & human-centered interfaces.
    </div>

    <!-- decorative mini stats (github style) -->
    <div class="stats-grid">
        <div class="stat-item">
            <i class="fab fa-github-alt"></i>
            <div class="stat-number">14+</div>
            <div class="stat-label">projects</div>
        </div>
        <div class="stat-item">
            <i class="fas fa-crown"></i>
            <div class="stat-number">design</div>
            <div class="stat-label">first mindset</div>
        </div>
        <div class="stat-item">
            <i class="fas fa-mug-hot"></i>
            <div class="stat-number">∞</div>
            <div class="stat-label">coffee fueled</div>
        </div>
        <div class="stat-item">
            <i class="fas fa-globe"></i>
            <div class="stat-number">open</div>
            <div class="stat-label">for collab</div>
        </div>
    </div>

    <!-- social / contact links - realistic and elegant -->
    <div class="social-links">
        <a href="#" class="social-btn" id="githubLink">
            <i class="fab fa-github"></i> <span>github/joyalm</span>
        </a>
        <a href="#" class="social-btn" id="twitterLink">
            <i class="fab fa-twitter"></i> <span>@joyal_m</span>
        </a>
        <a href="#" class="social-btn" id="linkedinLink">
            <i class="fab fa-linkedin-in"></i> <span>joyal-m</span>
        </a>
        <a href="#" class="social-btn" id="portfolioLink">
            <i class="fas fa-palette"></i> <span>portfolio</span>
        </a>
    </div>

    <div class="quote">
        <i class="fas fa-quote-left"></i>  code with soul, design with intention  <i class="fas fa-quote-right"></i><br>
        <span style="font-size: 0.7rem; opacity: 0.7;">✦ always learning, always building ✦</span>
    </div>
</div>

<!-- small cursor dot (optional) -->
<div class="cursor-dot" id="cursorDot"></div>

<script>
    // === Aesthetic interactions: custom cursor dot (only on desktop, subtle) ===
    const cursor = document.getElementById('cursorDot');
    if (cursor && window.innerWidth > 768) {
        document.addEventListener('mousemove', (e) => {
            cursor.style.transform = `translate(${e.clientX - 3}px, ${e.clientY - 3}px)`;
        });
        document.addEventListener('mouseleave', () => {
            cursor.style.opacity = '0';
        });
        document.addEventListener('mouseenter', () => {
            cursor.style.opacity = '0.6';
        });
    }

    // ===== Smooth alert / readme-friendly behavior =====
    // For GitHub README.md simulation: instead of actual broken links we provide info & open demo placeholder
    // Since this is a static HTML for README preview, we can show a nice toast or alert with personal message
    // But also we want to mimic that in the actual markdown preview it's stylish. 
    // For better UX, we'll make links open a small modal or show a friendly "coming soon" message.
    // However, the client requested "create html based aesthetic hi i m joyal m text to add on readme.md github" 
    // So we'll make sure when someone clicks any social button it shows a subtle custom notification that represents profile links 
    // OR we can simulate that they lead to actual placeholder but not break the vibe.
    // I'll implement a minimal non-intrusive snackbar that says "🔗 connect with Joyal — profile coming soon ✨" 
    // and also provide real hover effect. So it remains clean and github-pages friendly.
    
    function showToast(message, icon = "✨") {
        // create toast element
        const toast = document.createElement('div');
        toast.innerText = `${icon}  ${message}`;
        toast.style.position = 'fixed';
        toast.style.bottom = '25px';
        toast.style.left = '50%';
        toast.style.transform = 'translateX(-50%)';
        toast.style.backgroundColor = '#2f241e';
        toast.style.color = '#f7ede3';
        toast.style.padding = '0.8rem 1.6rem';
        toast.style.borderRadius = '60px';
        toast.style.fontFamily = "'Inter', system-ui";
        toast.style.fontSize = '0.85rem';
        toast.style.fontWeight = '500';
        toast.style.backdropFilter = 'blur(12px)';
        toast.style.background = 'rgba(30, 22, 18, 0.85)';
        toast.style.border = '1px solid rgba(210, 160, 110, 0.4)';
        toast.style.zIndex = '1000';
        toast.style.boxShadow = '0 8px 20px rgba(0,0,0,0.1)';
        toast.style.letterSpacing = '0.2px';
        toast.style.pointerEvents = 'none';
        document.body.appendChild(toast);
        setTimeout(() => {
            toast.style.opacity = '0';
            toast.style.transition = 'opacity 0.3s ease';
            setTimeout(() => toast.remove(), 400);
        }, 2300);
    }

    // Define link actions: For README we want to show that it's a demo card / but user can replace with actual links
    // I'll make them trigger toast and also optionally open a placeholder in new tab? but since it's just HTML component for readme, 
    // we keep non-disruptive and aesthetic: show message and simulate external link if desired
    // but best: just give elegant notification and optionally console.info.
    // However many github profiles use actual links, but we want to ensure it's "aesthetic". We'll also store a simple config.
    // For real use, anyone can replace "#" with actual URLs.
    
    const githubBtn = document.getElementById('githubLink');
    const twitterBtn = document.getElementById('twitterLink');
    const linkedinBtn = document.getElementById('linkedinLink');
    const portfolioBtn = document.getElementById('portfolioLink');
    
    // default placeholder interaction: just show toast and optionally new tab demo - but not redirect unless they customize
    // But we can add a custom event to preserve original URL? For safe readme display, we'll prevent default and show a friendly message,
    // and also provide an optional copy hint. For GitHub readme it's better to let user edit links manually later, 
    // but this demo communicates Joyal's presence.
    
    function handleSocialClick(event, platform) {
        event.preventDefault();
        let msg = '';
        let icon = '💫';
        if (platform === 'github') msg = 'Check out Joyal\'s GitHub repositories → github.com/joyalm (demo)';
        else if (platform === 'twitter') msg = 'Follow @joyal_m for design & dev insights ✨';
        else if (platform === 'linkedin') msg = 'Let\'s connect on LinkedIn → Joyal M — builder & creator';
        else if (platform === 'portfolio') msg = 'Portfolio showcase: creative projects & case studies (soon)';
        showToast(msg, '🔗');
        // Also you could open a placeholder link? but not to break, we keep as informational.
        // For complete experience you could replace actual links in production, but we present beautifully.
    }
    
    githubBtn.addEventListener('click', (e) => handleSocialClick(e, 'github'));
    twitterBtn.addEventListener('click', (e) => handleSocialClick(e, 'twitter'));
    linkedinBtn.addEventListener('click', (e) => handleSocialClick(e, 'linkedin'));
    portfolioBtn.addEventListener('click', (e) => handleSocialClick(e, 'portfolio'));
    
    // Add a subtle ripple effect to stat items if desired
    const statItems = document.querySelectorAll('.stat-item');
    statItems.forEach(item => {
        item.addEventListener('click', () => {
            showToast('✨ ' + item.querySelector('.stat-label')?.innerText + ' vibe active', '💡');
        });
    });
    
    // Small additional: copy the name or quote? just for delight: double click on name shows fun message
    const nameEl = document.querySelector('.big-name');
    if(nameEl) {
        nameEl.addEventListener('dblclick', () => {
            showToast('💛 Joyal M — crafting with intention', '🌟');
        });
    }
    
    // Also make description interactive? just optional
    console.log("✨ Aesthetic README card for Joyal M — ready to embed in GitHub markdown");
    
    // Optional: add 'last updated' vibe but not needed. All smooth.
    
    // Since this is meant for GitHub README.md, you can directly embed this HTML structure inside your markdown 
    // using <div align="center"> or raw HTML. We made fully responsive and self-contained.
    
    // Additional floating effect on card load
    const card = document.querySelector('.card');
    if(card) {
        card.style.opacity = '0';
        card.style.transform = 'translateY(18px)';
        setTimeout(() => {
            card.style.transition = 'opacity 0.7s cubic-bezier(0.2, 0.9, 0.4, 1.1), transform 0.6s ease';
            card.style.opacity = '1';
            card.style.transform = 'translateY(0)';
        }, 100);
    }
    
    // blob animation subtle extra
    const blobs = document.querySelectorAll('.blob');
    blobs.forEach((blob, idx) => {
        blob.style.animationDelay = `${idx * 0.4}s`;
    });
    
    // little sparkle effect for title-tag icons
    const icons = document.querySelectorAll('.title-tag i');
    if(icons.length) {
        setInterval(() => {
            icons.forEach(icon => {
                icon.style.transform = 'scale(1.05)';
                setTimeout(() => { icon.style.transform = 'scale(1)'; }, 300);
            });
        }, 3000);
    }
</script>
</body>
</html>

---

![image_alt](https://github.com/joyalmaxwell/joyalmaxwell/blob/6c78e2800d9b38fd14150e9b5422990e781fdb2f/Thumbnail/20260401_122811.png)

---

## Highlights
- Clean CLI designs
- Automation workflows
- System utilities

---

![Automation](https://img.shields.io/badge/Automation-black)
![CLI](https://img.shields.io/badge/CLI-grey)
![Workflow](https://img.shields.io/badge/Workflow-black)
