<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, viewport-fit=cover">
    <title>Prodiga_X // Deep Nexus</title>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            user-select: none;
        }

        body {
            background: radial-gradient(ellipse at 20% 30%, #04070f, #000000);
            font-family: 'Space Grotesk', monospace;
            height: 100vh;
            width: 100vw;
            overflow: hidden;
            position: relative;
        }

        /* cyber scanlines */
        body::after {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: repeating-linear-gradient(0deg, rgba(0,255,255,0.02) 0px, rgba(0,255,255,0.02) 1px, transparent 1px, transparent 4px);
            pointer-events: none;
            z-index: 2;
        }

        .app-router {
            width: 100vw;
            height: 100vh;
            position: relative;
            overflow: hidden;
        }

        /* page container */
        .page {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: transform 0.45s cubic-bezier(0.16, 1, 0.3, 1), opacity 0.35s ease;
            opacity: 0;
            visibility: hidden;
            transform: translateX(30px);
            pointer-events: none;
            padding: 1.8rem;
        }

        .page.active {
            opacity: 1;
            visibility: visible;
            transform: translateX(0);
            pointer-events: auto;
            z-index: 20;
        }

        .glass-master {
            background: rgba(6, 12, 24, 0.75);
            backdrop-filter: blur(20px);
            border-radius: 2.8rem;
            border: 1px solid rgba(0, 255, 255, 0.45);
            box-shadow: 0 30px 45px rgba(0, 0, 0, 0.7), 0 0 30px rgba(0, 255, 255, 0.2);
            width: 100%;
            max-width: 1300px;
            height: 85vh;
            max-height: 780px;
            display: flex;
            flex-direction: column;
            overflow: hidden;
        }

        .page-header {
            padding: 1.4rem 2rem;
            border-bottom: 1px solid rgba(0, 255, 255, 0.3);
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-shrink: 0;
        }

        .page-title {
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(125deg, #fff, #6efff0, #c084fc);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        .nav-back {
            background: rgba(255, 70, 100, 0.2);
            border: 1px solid #ff6b8a;
            padding: 0.45rem 1.2rem;
            border-radius: 2.5rem;
            color: #ffb7c5;
            font-weight: 600;
            cursor: pointer;
            transition: 0.2s;
            display: flex;
            align-items: center;
            gap: 0.6rem;
            font-size: 0.85rem;
        }

        .nav-back:hover {
            background: #ff4d6d;
            color: black;
            border-color: white;
            box-shadow: 0 0 12px #ff4d6d;
        }

        .scroll-area {
            flex: 1;
            overflow-y: auto;
            padding: 1.5rem 2rem;
            scrollbar-width: thin;
        }

        .scroll-area::-webkit-scrollbar {
            width: 4px;
        }
        .scroll-area::-webkit-scrollbar-track {
            background: #0f1422;
        }
        .scroll-area::-webkit-scrollbar-thumb {
            background: cyan;
            border-radius: 8px;
        }

        /* main menu cards */
        .cards-row {
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
            align-items: center;
            height: 100%;
            min-height: 360px;
        }

        .menu-card {
            background: rgba(12, 22, 40, 0.8);
            backdrop-filter: blur(12px);
            border-radius: 2rem;
            padding: 2rem 1.8rem;
            width: 270px;
            cursor: pointer;
            transition: all 0.25s ease;
            border: 1px solid rgba(0, 255, 255, 0.35);
            text-align: center;
        }

        .menu-card:hover {
            transform: translateY(-8px) scale(1.02);
            border-color: cyan;
            box-shadow: 0 20px 30px -8px rgba(0, 255, 255, 0.4);
        }

        /* game preview card (scripts vault list) */
        .game-preview {
            background: rgba(0, 0, 0, 0.55);
            border-radius: 1.5rem;
            padding: 1.2rem 1.5rem;
            margin-bottom: 1.5rem;
            border-left: 5px solid cyan;
            transition: 0.2s;
            cursor: pointer;
        }

        .game-preview:hover {
            background: rgba(0, 30, 40, 0.7);
            transform: translateX(5px);
        }

        .see-more-btn {
            background: rgba(0, 255, 255, 0.2);
            border: 1px solid cyan;
            padding: 0.45rem 1.2rem;
            border-radius: 2rem;
            font-weight: 500;
            cursor: pointer;
            transition: 0.2s;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            color: white;
            margin-top: 0.8rem;
        }

        .see-more-btn:hover {
            background: cyan;
            color: black;
        }

        /* detail page */
        .detail-section {
            background: rgba(0, 0, 0, 0.6);
            border-radius: 1.8rem;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
        }

        .feature-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin: 1rem 0;
        }

        .feature-pill {
            background: rgba(0, 255, 255, 0.15);
            padding: 0.25rem 1rem;
            border-radius: 40px;
            font-size: 0.75rem;
            color: #ccf5ff;
        }

        .copy-manual-area {
            background: #010a12;
            border-radius: 1rem;
            padding: 0.8rem;
            font-family: monospace;
            font-size: 0.75rem;
            word-break: break-all;
            color: #abf0ff;
            border: 1px solid cyan;
            margin-top: 0.8rem;
        }

        .btn-manual-copy {
            background: #0a4c6e;
            border: none;
            padding: 0.5rem 1.2rem;
            border-radius: 2rem;
            font-weight: bold;
            color: white;
            cursor: pointer;
            transition: 0.2s;
            margin-top: 0.6rem;
        }

        .btn-manual-copy:hover {
            background: cyan;
            color: black;
        }

        .white-text {
            color: white;
        }
        .cyan-glow {
            color: cyan;
        }
        hr {
            border-color: rgba(0,255,255,0.2);
            margin: 1rem 0;
        }
    </style>
</head>
<body>
<div class="app-router">
    <!-- PAGE 1: MAIN MENU -->
    <div id="mainMenuPage" class="page active">
        <div class="glass-master">
            <div class="page-header">
                <div class="page-title">⟡ PRODIGA_X NEXUS ⟡</div>
                <div style="font-size: 0.7rem; color: #6d8fc6;">core access v3</div>
            </div>
            <div class="scroll-area" style="display: flex; align-items: center; justify-content: center;">
                <div class="cards-row">
                    <div class="menu-card" data-nav="scripts">
                        <div class="card-icon-large"><i class="fas fa-code" style="font-size: 2.8rem; color: cyan;"></i></div>
                        <h2 style="font-size: 1.8rem; background: linear-gradient(145deg,#fff,#7efff0); background-clip:text; -webkit-background-clip:text; color:transparent;">Scripts</h2>
                        <p style="color:#b8ceff;">ESP, auto-farm, utilities</p>
                    </div>
                    <div class="menu-card" data-nav="pricing">
                        <div class="card-icon-large"><i class="fas fa-gem" style="font-size: 2.8rem; color: cyan;"></i></div>
                        <h2 style="font-size: 1.8rem; background: linear-gradient(145deg,#fff,#7efff0); background-clip:text; -webkit-background-clip:text; color:transparent;">Pricing</h2>
                        <p style="color:#b8ceff;">activation steps</p>
                    </div>
                    <div class="menu-card" data-nav="dev">
                        <div class="card-icon-large"><i class="fas fa-microchip" style="font-size: 2.8rem; color: cyan;"></i></div>
                        <h2 style="font-size: 1.8rem; background: linear-gradient(145deg,#fff,#7efff0); background-clip:text; -webkit-background-clip:text; color:transparent;">Under Development</h2>
                        <p style="color:#b8ceff;">forthcoming chaos</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- PAGE 2: SCRIPTS VAULT (game list with "Click to see more") -->
    <div id="scriptsVaultPage" class="page">
        <div class="glass-master">
            <div class="page-header">
                <div class="page-title"><i class="fas fa-scroll"></i> Script Vault</div>
                <div class="nav-back" id="backFromVault"><i class="fas fa-arrow-left"></i> Go Back</div>
            </div>
            <div class="scroll-area" id="vaultGamesList"></div>
        </div>
    </div>

    <!-- PAGE 3: GAME DETAIL (dynamic per game) -->
    <div id="gameDetailPage" class="page">
        <div class="glass-master">
            <div class="page-header">
                <div class="page-title" id="detailGameTitle">Game Name</div>
                <div class="nav-back" id="backFromDetail"><i class="fas fa-arrow-left"></i> Back to Vault</div>
            </div>
            <div class="scroll-area" id="gameDetailContent"></div>
        </div>
    </div>

    <!-- PAGE 4: PRICING (white text) -->
    <div id="pricingPage" class="page">
        <div class="glass-master">
            <div class="page-header">
                <div class="page-title"><i class="fas fa-tag"></i> Pricing & Access</div>
                <div class="nav-back" id="backFromPricing"><i class="fas fa-arrow-left"></i> Go Back</div>
            </div>
            <div class="scroll-area" id="pricingDynamicContent"></div>
        </div>
    </div>

    <!-- PAGE 5: UNDER DEVELOPMENT -->
    <div id="devPage" class="page">
        <div class="glass-master">
            <div class="page-header">
                <div class="page-title"><i class="fas fa-drafting-compass"></i> Deep Forge</div>
                <div class="nav-back" id="backFromDev"><i class="fas fa-arrow-left"></i> Go Back</div>
            </div>
            <div class="scroll-area" id="devStaticContent">
                <div style="text-align: center; padding: 2rem;">
                    <i class="fas fa-microchip" style="font-size: 4rem; color: #ff77cc;"></i>
                    <h2 style="margin-top: 1rem; color: #ffbbee;">⚡ UNDER DEVELOPMENT ⚡</h2>
                    <p style="margin-top: 1rem; color: #cdb5ff;">next-gen tools · private builds · advanced evasion</p>
                    <p style="margin-top: 2rem; font-size: 0.8rem; color: #9b9eff;"><i class="fas fa-sync-alt fa-spin"></i> status: quantum incubation</p>
                </div>
            </div>
        </div>
    </div>
</div>

<script>
    // ---------- GAME DATABASE ----------
    const GAME_LIBRARY = {
        intoTheAbyss: {
            id: "intoTheAbyss",
            name: "Into The Abyss",
            shortDesc: "Deep descent survival — ESP mastery",
            fullDesc: "Explore the abyss with absolute awareness. Dominate every lobby using supernatural ESP modules and stamina hacks. Works on every modern executor.",
            features: ["Scrap ESP", "Monster ESP", "Artifact ESP", "Trap ESP", "Elevator point ESP (WIP)", "Fullbright", "Nofog", "Infinite stamina"],
            note: "now works on every exec (expect shitsploits (downer than xeno/solara))",
            scriptCode: `loadstring(game:HttpGet('https://raw.githubusercontent.com/Prodigax/Roblox-into-the-abyss-script/refs/heads/main/into%20the%20abyss%20script'))()`,
            gameUrl: "https://www.roblox.com/games/113275514991402/Into-the-Abyss"
        },
        noMercy: {
            id: "noMercy",
            name: "No Mercy",
            shortDesc: "Auto farm + anti-threat annihilation",
            fullDesc: "Ultimate survival and auto-farming tool. Eliminate global threats, remove obstacles, and AFK farm with ease. Pair with Infinite Yield fly for optimal results.",
            features: ["Auto farm", "Anti Threats: Remove ads, No Shadow, No lasers", "Global Threats: no oxi, no spinning laser, no R-Boom-Ba", "No cars, no Cupid, no rook, no Dummy punch (Will be updated)"],
            note: "recommend to use infinite yield fly to fly away and enable everything and change auto farm type to bring for afk farming",
            scriptCode: `loadstring(game:HttpGet('https://raw.githubusercontent.com/Prodigax/NoMercyRobloxgoogoo/refs/heads/main/Wowz'))()`,
            gameUrl: "https://www.roblox.com/games/76469664755176/No-Mercy"
        }
    };

    // Helper: manual copy (using textarea)
    function manualCopyScript(scriptText, btnElement) {
        const textarea = document.createElement('textarea');
        textarea.value = scriptText;
        document.body.appendChild(textarea);
        textarea.select();
        document.execCommand('copy');
        document.body.removeChild(textarea);
        const original = btnElement.innerHTML;
        btnElement.innerHTML = '<i class="fas fa-check"></i> Copied!';
        setTimeout(() => { btnElement.innerHTML = original; }, 1500);
    }

    // Render Scripts Vault (list of games with "Click to see more")
    function renderScriptsVault() {
        const container = document.getElementById('vaultGamesList');
        if (!container) return;
        container.innerHTML = '';
        
        Object.values(GAME_LIBRARY).forEach(game => {
            const previewDiv = document.createElement('div');
            previewDiv.className = 'game-preview';
            previewDiv.setAttribute('data-game-id', game.id);
            
            const featuresPreview = game.features.slice(0, 4).map(f => `<span class="feature-pill">${f}</span>`).join('');
            previewDiv.innerHTML = `
                <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
                    <h3 style="color: #b0f0ff; font-size: 1.5rem;">🎮 ${game.name}</h3>
                </div>
                <p style="color: #cddcff; margin: 6px 0;">${game.shortDesc}</p>
                <div style="margin: 8px 0;"><span style="color:cyan;">key features:</span> ${featuresPreview}</div>
                <button class="see-more-btn" data-game="${game.id}"><i class="fas fa-eye"></i> Click to see more</button>
            `;
            const seeMoreBtn = previewDiv.querySelector('.see-more-btn');
            seeMoreBtn.addEventListener('click', (e) => {
                e.stopPropagation();
                openGameDetail(game.id);
            });
            // also whole card clickable
            previewDiv.addEventListener('click', (e) => {
                if(e.target.classList.contains('see-more-btn')) return;
                openGameDetail(game.id);
            });
            container.appendChild(previewDiv);
        });
    }

    // Open Game Detail Page (another page with full info + manual copy)
    function openGameDetail(gameId) {
        const game = GAME_LIBRARY[gameId];
        if (!game) return;
        
        // populate detail page
        const titleElem = document.getElementById('detailGameTitle');
        const contentContainer = document.getElementById('gameDetailContent');
        if (titleElem) titleElem.innerHTML = `<i class="fas fa-info-circle"></i> ${game.name} · detail`;
        
        contentContainer.innerHTML = '';
        
        const detailDiv = document.createElement('div');
        detailDiv.style.animation = "fadeSlide 0.3s ease";
        
        // full feature list
        const featuresFull = game.features.map(f => `<span class="feature-pill">⚡ ${f}</span>`).join('');
        
        detailDiv.innerHTML = `
            <div class="detail-section">
                <h2 style="color: cyan;">${game.name}</h2>
                <p style="color: #e0ecff; margin-top: 0.5rem;">${game.fullDesc || game.shortDesc}</p>
                <hr>
                <div><strong style="color: cyan;">🔧 Advanced Features:</strong></div>
                <div class="feature-grid">${featuresFull}</div>
                <div style="background: #00000066; border-radius: 1rem; padding: 0.8rem; margin: 1rem 0;">
                    <i class="fas fa-exclamation-triangle" style="color: cyan;"></i> <span style="color: #ffdd99;">${game.note}</span>
                </div>
                <div>
                    <strong style="color: cyan;"><i class="fas fa-gamepad"></i> Roblox Game Link:</strong>
                    <button id="findGameBtnDetail" style="background: #0a6b8f; border: none; padding: 0.35rem 1rem; border-radius: 2rem; margin-left: 0.8rem; cursor: pointer; color: white;">Find Game →</button>
                </div>
                <div style="margin-top: 1.8rem;">
                    <strong style="color: cyan;"><i class="fas fa-terminal"></i> Script (Manual Copy):</strong>
                    <div class="copy-manual-area" id="manualScriptText">${escapeHtml(game.scriptCode)}</div>
                    <button id="manualCopyButton" class="btn-manual-copy"><i class="far fa-copy"></i> Copy Script Manually</button>
                </div>
            </div>
        `;
        
        contentContainer.appendChild(detailDiv);
        
        const findBtn = detailDiv.querySelector('#findGameBtnDetail');
        findBtn.addEventListener('click', () => {
            window.open(game.gameUrl, '_blank');
        });
        
        const manualCopyBtn = detailDiv.querySelector('#manualCopyButton');
        manualCopyBtn.addEventListener('click', () => {
            manualCopyScript(game.scriptCode, manualCopyBtn);
        });
        
        // transition to detail page
        switchToPage('gameDetailPage');
    }
    
    function escapeHtml(str) {
        return str.replace(/[&<>]/g, function(m) {
            if (m === '&') return '&amp;';
            if (m === '<') return '&lt;';
            if (m === '>') return '&gt;';
            return m;
        }).replace(/[\uD800-\uDBFF][\uDC00-\uDFFF]/g, function(c) {
            return c;
        });
    }

    // Pricing page (white text, step by step)
    function renderPricingPage() {
        const container = document.getElementById('pricingDynamicContent');
        if (!container) return;
        container.innerHTML = '';
        
        const startDiv = document.createElement('div');
        startDiv.style.textAlign = 'center';
        startDiv.style.padding = '1.5rem';
        startDiv.innerHTML = `
            <i class="fas fa-rocket" style="font-size: 3.8rem; color: cyan;"></i>
            <h2 style="color: white; margin: 1rem 0;">Get Started</h2>
            <button id="continuePricingBtn" style="background: cyan; border: none; padding: 12px 28px; border-radius: 60px; font-weight: bold; cursor: pointer;">Continue →</button>
        `;
        container.appendChild(startDiv);
        
        const continueBtn = startDiv.querySelector('#continuePricingBtn');
        continueBtn.addEventListener('click', () => {
            container.innerHTML = '';
            const stepsCard = document.createElement('div');
            stepsCard.className = 'detail-section';
            stepsCard.style.background = "rgba(10,20,35,0.9)";
            stepsCard.innerHTML = `
                <h3 style="color: cyan;">📋 Activation Blueprint</h3>
                <div style="margin-top: 1.2rem;">
                    <div class="step-item" style="display: flex; align-items: center; gap: 1rem; margin: 1rem 0; color: white;"><span style="background: cyan; color:black; width:28px; height:28px; display:inline-flex; align-items:center; justify-content:center; border-radius:30px;">1</span> Go back to main page</div>
                    <div class="step-item" style="display: flex; align-items: center; gap: 1rem; margin: 1rem 0; color: white;"><span style="background: cyan; color:black; width:28px; height:28px; display:inline-flex; align-items:center; justify-content:center; border-radius:30px;">2</span> Click <strong style="color:cyan;">Scripts</strong> card</div>
                    <div class="step-item" style="display: flex; align-items: center; gap: 1rem; margin: 1rem 0; color: white;"><span style="background: cyan; color:black; width:28px; height:28px; display:inline-flex; align-items:center; justify-content:center; border-radius:30px;">3</span> Click "<strong style="color:cyan;">Click to see more</strong>" on your game</div>
                    <div class="step-item" style="display: flex; align-items: center; gap: 1rem; margin: 1rem 0; color: white;"><span style="background: cyan; color:black; width:28px; height:28px; display:inline-flex; align-items:center; justify-content:center; border-radius:30px;">4</span> Copy script manually & execute in executor</div>
                </div>
                <hr>
                <button id="pricingBackHome" class="nav-back" style="background:rgba(255,70,100,0.3); margin-top:1rem;"><i class="fas fa-home"></i> Go Back to Hub</button>
            `;
            container.appendChild(stepsCard);
            const backHome = stepsCard.querySelector('#pricingBackHome');
            backHome.addEventListener('click', () => switchToPage('mainMenuPage'));
        });
        
        const styleWhiteFix = document.createElement('style');
        styleWhiteFix.textContent = `#pricingDynamicContent, #pricingDynamicContent * { color: white !important; } .step-item span { color: black !important; } #continuePricingBtn { color: black; } .nav-back { color: white !important; }`;
        if(!document.querySelector('#pricingWhiteFinal')) {
            styleWhiteFix.id = 'pricingWhiteFinal';
            document.head.appendChild(styleWhiteFix);
        }
    }

    // Page transition engine
    function switchToPage(pageId) {
        const allPages = document.querySelectorAll('.page');
        allPages.forEach(page => page.classList.remove('active'));
        const target = document.getElementById(pageId);
        if(target) target.classList.add('active');
        
        // load dynamic content if needed
        if(pageId === 'scriptsVaultPage') {
            renderScriptsVault();
        } else if(pageId === 'pricingPage') {
            renderPricingPage();
        }
    }
    
    // Navigation handlers
    function bindNavigation() {
        document.getElementById('backFromVault')?.addEventListener('click', () => switchToPage('mainMenuPage'));
        document.getElementById('backFromDetail')?.addEventListener('click', () => switchToPage('scriptsVaultPage'));
        document.getElementById('backFromPricing')?.addEventListener('click', () => switchToPage('mainMenuPage'));
        document.getElementById('backFromDev')?.addEventListener('click', () => switchToPage('mainMenuPage'));
        
        // Main menu card triggers
        const mainMenu = document.getElementById('mainMenuPage');
        mainMenu.addEventListener('click', (e) => {
            const card = e.target.closest('.menu-card');
            if(!card) return;
            const nav = card.getAttribute('data-nav');
            if(nav === 'scripts') switchToPage('scriptsVaultPage');
            else if(nav === 'pricing') switchToPage('pricingPage');
            else if(nav === 'dev') switchToPage('devPage');
        });
    }
    
    // initial render
    function init() {
        renderScriptsVault();
        renderPricingPage();
        bindNavigation();
        // prefill dev static already set
        document.body.style.overflow = 'hidden';
    }
    
    init();
    
    // small animation style
    const styleAnim = document.createElement('style');
    styleAnim.textContent = `
        @keyframes fadeSlide {
            from { opacity:0; transform: translateX(6px);}
            to { opacity:1; transform: translateX(0);}
        }
        .game-preview, .detail-section { animation: fadeSlide 0.25s ease; }
    `;
    document.head.appendChild(styleAnim);
</script>
</body>
</html>
