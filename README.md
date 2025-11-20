<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CPS Telecomunicazioni S.r.l. | Progettazione e Installazione Reti Fibra Ottica - Roma</title>
    <meta name="description" content="CPS Telecomunicazioni S.r.l., società italiana con sede a Roma, specializzata in progettazione, installazione, manutenzione e giunzione di reti in fibra ottica. System partner di Fastweb da oltre 20 anni.">
    <meta name="keywords" content="fibra ottica Roma, CPS Telecomunicazioni, partner Fastweb, giunzioni ottiche, FTTH, manutenzione reti">
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            background: linear-gradient(135deg, #007BFF, #28A745); /* Blu-verde ispirato al logo */
            color: #333; 
            line-height: 1.6; 
        }
        header { 
            background: rgba(0,0,0,0.1); 
            padding: 20px; 
            text-align: center; 
            animation: fadeInDown 1s ease-out; 
        }
        @keyframes fadeInDown { 
            from { opacity: 0; transform: translateY(-30px); } 
            to { opacity: 1; transform: translateY(0); } 
        }
        .logo { 
            max-width: 250px; 
            height: auto; 
            transition: transform 0.4s ease; 
            border-radius: 10px; 
            filter: drop-shadow(0 4px 8px rgba(0,0,0,0.2)); 
        }
        .logo:hover { 
            transform: scale(1.1) rotate(360deg); /* Animazione rotante interattiva */
        }
        nav { 
            background: #DC3545; /* Rosso dal logo */
            padding: 10px; 
            text-align: center; 
        }
        nav a { 
            color: white; 
            margin: 0 15px; 
            text-decoration: none; 
            transition: color 0.3s, transform 0.3s; 
        }
        nav a:hover { 
            color: #FFD700; 
            transform: scale(1.1); 
        }
        section { 
            padding: 50px 20px; 
            max-width: 1200px; 
            margin: auto; 
        }
        .hero { 
            text-align: center; 
            background: rgba(255,255,255,0.95); 
            color: #333; 
            padding: 60px 20px; 
            border-radius: 15px; 
            margin: 20px; 
            animation: slideInUp 1.5s ease-out; 
        }
        @keyframes slideInUp { 
            from { opacity: 0; transform: translateY(50px); } 
            to { opacity: 1; transform: translateY(0); } 
        }
        .slogan { 
            font-style: italic; 
            font-size: 1.8em; 
            color: #DC3545; 
            animation: pulseGlow 2s infinite alternate; 
        }
        @keyframes pulseGlow { 
            0% { transform: scale(1); text-shadow: 0 0 5px #DC3545; } 
            100% { transform: scale(1.05); text-shadow: 0 0 20px #DC3545; } 
        }
        .services { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 20px; 
        }
        .service-card { 
            background: white; 
            padding: 25px; 
            border-radius: 12px; 
            box-shadow: 0 4px 15px rgba(0,0,0,0.1); 
            transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94); 
            cursor: pointer; 
            position: relative; 
            overflow: hidden; 
        }
        .service-card::before { 
            content: ''; 
            position: absolute; 
            top: 0; 
            left: -100%; 
            width: 100%; 
            height: 100%; 
            background: linear-gradient(90deg, transparent, rgba(220,53,69,0.1), transparent); 
            transition: left 0.5s; 
        }
        .service-card:hover::before { 
            left: 100%; /* Effetto shimmer animato */
        }
        .service-card:hover { 
            transform: translateY(-10px) rotateX(5deg); 
            box-shadow: 0 10px 30px rgba(220,53,69,0.3); 
        }
        footer { 
            background: #333; 
            color: white; 
            text-align: center; 
            padding: 20px; 
            animation: fadeIn 2s ease-in; 
        }
        form { 
            max-width: 400px; 
            margin: auto; 
        }
        input, textarea, button { 
            width: 100%; 
            padding: 12px; 
            margin: 8px 0; 
            border: 1px solid #ddd; 
            border-radius: 6px; 
            transition: border-color 0.3s; 
        }
        input:focus, textarea:focus { 
            border-color: #DC3545; 
            outline: none; 
        }
        button { 
            background: #DC3545; 
            color: white; 
            border: none; 
            cursor: pointer; 
            transition: background 0.3s, transform 0.2s; 
        }
        button:hover { 
            background: #C82333; 
            transform: scale(1.02); 
        }
        @media (max-width: 768px) { 
            .slogan { font-size: 1.4em; } 
            section { padding: 30px 10px; } 
        }
    </style>
</head>
<body>
    <header>
        <img src="cps-logo.png" alt="Logo CPS Telecomunicazioni S.r.l." class="logo"> <!-- Inserisci qui il tuo logo PNG -->
        <h1>CPS Telecomunicazioni S.r.l.</h1>
        <p class="slogan">CONNESSI SEMPRE.</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#chi-siamo">Chi Siamo</a>
        <a href="#servizi">Servizi</a>
        <a href="#partnership">Partnership</a>
        <a href="#contatti">Contatti</a>
    </nav>

    <section id="home" class="hero">
        <h2>Connettiamo il Futuro</h2>
        <p>Specializzati in telecomunicazioni digitali, trasformiamo infrastrutture in reti veloci e affidabili. Sede a Roma, pronti per i tuoi progetti FTTH.</p>
    </section>

    <section id="chi-siamo">
        <h2>Chi Siamo</h2>
        <p>CPS Telecomunicazioni S.r.l. è una società italiana con sede a Roma, specializzata nel settore delle telecomunicazioni, in particolare nei lavori di progettazione, installazione, manutenzione e giunzione di reti in fibra ottica. Opera principalmente come partner di grandi operatori delle telecomunicazioni, con un focus su interventi edili e infrastrutturali legati alle comunicazioni digitali. Con 13 esperti e un fatturato in crescita (+5,9% annuo), garantiamo soluzioni innovative e reperibilità 24/7.</p>
    </section>

    <section id="servizi">
        <h2>I Nostri Servizi</h2>
        <div class="services">
            <div class="service-card" onclick="alert('Esplora i nostri servizi di progettazione!')">
                <h3>Progettazione Reti</h3>
                <p>Pianificazione personalizzata di infrastrutture fibra ottica per progetti complessi e scalabili.</p>
            </div>
            <div class="service-card" onclick="alert('Installazione rapida e precisa!')">
                <h3>Installazione e Posa</h3>
                <p>Realizzazione e ampliamento reti FTTH, con interventi edili efficienti e minimamente invasivi.</p>
            </div>
            <div class="service-card" onclick="alert('Manutenzione 24/7 per zero interruzioni!')">
                <h3>Manutenzione e Giunzione</h3>
                <p>Splicing, riparazioni e troubleshooting per garantire continuità e performance ottimali.</p>
            </div>
        </div>
    </section>

    <section id="partnership">
        <h2>Le Nostre Partnership</h2>
        <p>System partner di Fastweb da oltre 20 anni, collaboriamo per l'espansione di reti ultraveloci in Italia. Focus su FTTH, backhaul e aree bianche, con accesso reciproco a infrastrutture per innovazione condivisa.</p>
        <ul>
            <li><strong>Fastweb:</strong> Progettazione, installazione e manutenzione reti – oltre 20 anni di fiducia e risultati.</li>
            <li><strong>Altri Operatori:</strong> Partnership strategiche per comunicazioni digitali sostenibili.</li>
        </ul>
    </section>

    <section id="contatti">
        <h2>Contattaci</h2>
        <p>Via Maso Finiguerra 31, 00173 Roma | Tel: +39 06 1234567 | Email: <a href="mailto:info@cpsbianchi.it" style="color: #DC3545;">info@cpsbianchi.it</a></p>
        <p>PEC: <a href="mailto:cpstelecomunicazioni@legalmail.it" style="color: #DC3545;">cpstelecomunicazioni@legalmail.it</a> | Reperibilità 24/7 per emergenze</p>
        <form id="contactForm">
            <input type="text" id="name" placeholder="Il tuo Nome" required>
            <input type="email" id="email" placeholder="La tua Email" required>
            <textarea id="message" placeholder="Descrivi il tuo progetto..." rows="4" required></textarea>
            <button type="submit">Invia Richiesta</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 CPS Telecomunicazioni S.r.l. | P.IVA 09539361007 | Tutti i diritti riservati. | <a href="#" style="color: #FFD700;">Privacy Policy</a></p>
        <p>Seguici su <a href="https://linkedin.com/company/cps-telecom" style="color: #FFD700;">LinkedIn</a> | Connettiamo l'Italia, un cavo alla volta.</p>
    </footer>

    <script>
        // Nav scroll suave con animazione
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({ behavior: 'smooth' });
                target.style.animation = 'slideInUp 0.8s ease-out'; // Animazione su scroll
            });
        });

        // Form dinamico con validazione e feedback
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            if (name && email && message) {
                alert(`Grazie, ${name}! La tua richiesta è stata inviata. Ti risponderemo entro 24h.`);
                this.reset();
            } else {
                alert('Compila tutti i campi per procedere!');
            }
        });
    </script>
</body>
</html>
