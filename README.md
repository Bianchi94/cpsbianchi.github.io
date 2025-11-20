<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CPS Telecomunicazioni | Fibra Ottica e Reti Integrate - Roma</title>
    <meta name="description" content="Partner Fastweb da 20+ anni. Installazione, manutenzione e giunzioni fibra ottica. Connettiamo il futuro con fili di stelle.">
    <meta name="keywords" content="fibra ottica Roma, CPS Telecomunicazioni, Fastweb partner, giunzioni ottiche, FTTH">
    <style>
        body { 
            font-family: Arial, sans-serif; 
            margin: 0; 
            background: linear-gradient(135deg, #007BFF, #28A745); /* Blu-verde dal logo */
            color: #333; 
            line-height: 1.6; 
        }
        header { 
            background: rgba(0,0,0,0.1); 
            padding: 20px; 
            text-align: center; 
            animation: fadeIn 1s ease-in; 
        }
        @keyframes fadeIn { 
            from { opacity: 0; transform: translateY(-20px); } 
            to { opacity: 1; transform: translateY(0); } 
        }
        .logo { 
            max-width: 250px; 
            height: auto; 
            transition: transform 0.3s ease; 
            border-radius: 10px; 
        }
        .logo:hover { 
            transform: scale(1.05) rotate(2deg); /* Effetto interattivo sul logo */
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
            transition: color 0.3s; 
        }
        nav a:hover { 
            color: #FFD700; /* Oro per contrasto */
        }
        section { 
            padding: 50px 20px; 
            max-width: 1200px; 
            margin: auto; 
        }
        .hero { 
            text-align: center; 
            background: rgba(255,255,255,0.9); 
            color: #333; 
            padding: 60px 20px; 
            border-radius: 10px; 
            margin: 20px; 
        }
        .slogan { 
            font-style: italic; 
            font-size: 1.8em; 
            color: #DC3545; 
            animation: pulse 2s infinite; 
        }
        @keyframes pulse { 
            0% { transform: scale(1); } 
            50% { transform: scale(1.05); } 
            100% { transform: scale(1); } 
        }
        .services { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 20px; 
        }
        .service-card { 
            background: white; 
            padding: 20px; 
            border-radius: 8px; 
            box-shadow: 0 2px 10px rgba(0,0,0,0.1); 
            transition: transform 0.3s, box-shadow 0.3s; 
            cursor: pointer; 
        }
        .service-card:hover { 
            transform: translateY(-5px); 
            box-shadow: 0 5px 20px rgba(220,53,69,0.3); /* Ombra rossa interattiva */
        }
        footer { 
            background: #333; 
            color: white; 
            text-align: center; 
            padding: 20px; 
        }
        form { 
            max-width: 400px; 
            margin: auto; 
        }
        input, textarea, button { 
            width: 100%; 
            padding: 10px; 
            margin: 5px 0; 
            border: 1px solid #ddd; 
            border-radius: 5px; 
        }
        button { 
            background: #DC3545; 
            color: white; 
            border: none; 
            cursor: pointer; 
            transition: background 0.3s; 
        }
        button:hover { 
            background: #C82333; 
        }
        @media (max-width: 768px) { 
            .slogan { font-size: 1.4em; } 
            section { padding: 30px 10px; } 
        }
    </style>
</head>
<body>
    <header>
        <img src="cps-logo.png" alt="Logo CPS Telecomunicazioni" class="logo"> <!-- Inserisci qui il tuo logo PNG -->
        <h1>CPS Telecomunicazioni S.r.l.</h1>
        <p class="slogan">Fili di stelle, connessi all'eterno.</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#chi-siamo">Chi Siamo</a>
        <a href="#servizi">Servizi</a>
        <a href="#partnership">Partnership</a>
        <a href="#contatti">Contatti</a>
    </nav>

    <section id="home" class="hero">
        <h2>Connettiamo il Futuro con Tecnologia Integrata</h2>
        <p>Società specializzata in installazione e manutenzione reti fibra ottica. Sede a Roma, partner affidabile per Fastweb e Open Fiber. Da 2007, trasformiamo infrastrutture in opportunità digitali con passione visionaria.</p>
    </section>

    <section id="chi-siamo">
        <h2>Chi Siamo</h2>
        <p>Fondata nel 2007, CPS è un consorzio a responsabilità limitata con 13 esperti e fatturato in crescita (+5,9% annuo). Focus su FTTH e backhaul, con interventi 24/7. Ispirati a visionari come Tesla: "Pensa in termini di energia e frequenza". Siamo pronti a cablare il tuo domani.</p>
    </section>

    <section id="servizi">
        <h2>I Nostri Servizi</h2>
        <div class="services">
            <div class="service-card" onclick="alert('Contattaci per un preventivo su posa cavi!')">
                <h3>Posa Cavi Fibra Ottica</h3>
                <p>Realizzazione e ampliamento reti per banda ultralarga, inclusi progetti FTH Roma. Interventi rapidi e precisi.</p>
            </div>
            <div class="service-card" onclick="alert('Scopri come risolviamo guasti in ore!')">
                <h3>Manutenzione e Giunzioni</h3>
                <p>Splicing, brettellaggio e riparazioni guasti – 101 ticket gestiti in 24h. Zero downtime garantito.</p>
            </div>
            <div class="service-card" onclick="alert('Testing avanzato per la tua rete!')">
                <h3>Testing e Troubleshooting</h3>
                <p>Misure OTDR, verifiche tratte e ottimizzazione backhaul. Massima affidabilità per le tue connessioni.</p>
            </div>
        </div>
    </section>

    <section id="partnership">
        <h2>Le Nostre Partnership</h2>
        <p>System partner Fastweb da oltre 20 anni per FTTH e emergenze. Collaborazione con Open Fiber (dal 2019) per accesso reciproco reti, coprendo aree bianche in Italia.</p>
        <ul>
            <li><strong>Fastweb:</strong> Posa cavi, gestione centrali, risoluzione interruzioni – efficienza comprovata.</li>
            <li><strong>Open Fiber:</strong> Backhaul e integrazioni PON per banda ultralarga. Copertura nazionale.</li>
        </ul>
    </section>

    <section id="contatti">
        <h2>Contattaci</h2>
        <p>Via Maso Finiguerra 31, 00173 Roma | Tel: +39 06 1234567 | Email: <a href="mailto:info@cpsbianchi.it" style="color: #DC3545;">info@cpsbianchi.it</a></p>
        <p>PEC: <a href="mailto:cpstelecomunicazioni@legalmail.it" style="color: #DC3545;">cpstelecomunicazioni@legalmail.it</a> | Reperibilità 24/7</p>
        <form id="contactForm">
            <input type="text" id="name" placeholder="Il tuo Nome" required>
            <input type="email" id="email" placeholder="La tua Email" required>
            <textarea id="message" placeholder="Il tuo Messaggio" rows="4" required></textarea>
            <button type="submit">Invia Messaggio</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 CPS Telecomunicazioni S.r.l. | P.IVA 09539361007 | Tutti i diritti riservati. | <a href="#" style="color: #FFD700;">Privacy Policy</a></p>
        <p>Seguici su <a href="https://linkedin.com/company/cps-telecom" style="color: #FFD700;">LinkedIn</a> | Sviluppato con passione per la connessione.</p>
    </footer>

    <script>
        // Nav scroll suave
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({ behavior: 'smooth' });
            });
        });

        // Form interattivo (simulazione invio – sostituisci con backend reale)
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            if (name && email && message) {
                alert(`Grazie, ${name}! Il tuo messaggio è stato inviato a info@cpsbianchi.it. Ti contatteremo presto.`);
                this.reset(); // Reset form
            } else {
                alert('Compila tutti i campi, per favore!');
            }
        });
    </script>
</body>
</html>
