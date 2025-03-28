<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Wyników Strzeleckich</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary: #0c7cd5;
            --primary-light: #2196f3;
            --primary-dark: #0d47a1;
            --accent: #00bcd4;
            --text: #fff;
            --dark-text: #333;
            --background: #121212;
            --card-bg: #1e1e1e;
            --border-radius: 12px;
            --shadow: 0 4px 20px rgba(0, 123, 255, 0.3);
            --glow: 0 0 15px rgba(33, 150, 243, 0.7);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--background);
            color: var(--text);
            line-height: 1.6;
            padding-bottom: 80px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 20px 0;
            background: linear-gradient(135deg, var(--primary-dark), var(--primary));
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
        }

        header h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }

        .tab-section {
            display: none;
        }

        .tab-section.active {
            display: block;
        }

        .card {
            background-color: var(--card-bg);
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
            padding: 25px;
            margin-bottom: 30px;
            border: 1px solid rgba(33, 150, 243, 0.2);
            transition: all 0.3s ease;
        }

        .card:hover {
            box-shadow: var(--glow);
            transform: translateY(-5px);
        }

        .card-header {
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            padding-bottom: 15px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
        }

        .card-icon {
            font-size: 2rem;
            margin-right: 15px;
            color: var(--primary-light);
        }

        h2 {
            color: var(--primary-light);
            font-size: 1.8rem;
            font-weight: 600;
        }

        h3 {
            color: var(--accent);
            font-size: 1.4rem;
            margin-bottom: 15px;
            font-weight: 500;
        }

        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: var(--primary-light);
        }

        .icon-label {
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .icon-label i {
            color: var(--accent);
        }

        input, select {
            width: 100%;
            padding: 12px 15px;
            margin-bottom: 20px;
            border: none;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 6px;
            color: var(--text);
            font-size: 1rem;
            transition: all 0.3s;
            border: 1px solid rgba(33, 150, 243, 0.2);
        }

        input:focus, select:focus {
            outline: none;
            box-shadow: 0 0 0 2px var(--primary-light);
            background-color: rgba(255, 255, 255, 0.15);
        }

        button {
            background: linear-gradient(to right, var(--primary-dark), var(--primary));
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: 600;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-right: 10px;
            margin-bottom: 10px;
        }

        button:hover {
            background: linear-gradient(to right, var(--primary), var(--accent));
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.2);
            transform: translateY(-2px);
        }

        button i {
            margin-right: 8px;
        }

        .button-group {
            display: flex;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }

        .result-box {
            background-color: rgba(0, 123, 255, 0.1);
            border-radius: 8px;
            padding: 15px;
            margin-top: 20px;
            border-left: 4px solid var(--primary);
        }

        .result-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            padding-bottom: 10px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .result-item:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }

        .result-label {
            font-weight: 500;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .result-label i {
            color: var(--accent);
        }

        .result-value {
            font-weight: 700;
            color: var(--primary-light);
        }

        .collapsible {
            cursor: pointer;
            padding: 10px 15px;
            width: 100%;
            text-align: left;
            background-color: rgba(0, 123, 255, 0.1);
            border: none;
            border-radius: 6px;
            outline: none;
            font-size: 1rem;
            transition: 0.4s;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 10px;
        }

        .collapsible:hover {
            background-color: rgba(0, 123, 255, 0.2);
        }

        .collapsible:after {
            content: '+';
            color: var(--primary-light);
            font-weight: bold;
            float: right;
            margin-left: 5px;
        }

        .active:after {
            content: "-";
        }

        .content {
            padding: 0 18px;
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 0 0 6px 6px;
        }

        .content-padding {
            padding: 15px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 20px;
        }

        .tabs {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 20px;
        }

        .tab-button {
            background-color: rgba(0, 123, 255, 0.1);
            border: 1px solid rgba(33, 150, 243, 0.2);
            border-radius: 6px;
            padding: 10px 20px;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .tab-button i {
            color: var(--accent);
        }

        .tab-button.active {
            background-color: var(--primary);
            border-color: var(--primary);
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
        }

        .specs-grid {
            display: grid;
            grid-template-columns: auto 1fr;
            gap: 10px;
            margin: 20px 0;
        }

        .specs-grid div:nth-child(odd) {
            font-weight: 600;
            color: var(--primary-light);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .specs-grid div:nth-child(odd) i {
            color: var(--accent);
        }

        .mobile-menu {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            background-color: var(--card-bg);
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
            box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.2);
            z-index: 100;
        }

        .menu-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            color: var(--text);
            text-decoration: none;
            font-size: 0.8rem;
            opacity: 0.7;
            transition: all 0.3s;
            cursor: pointer;
        }

        .menu-item i {
            font-size: 1.5rem;
            margin-bottom: 4px;
        }

        .menu-item.active, .menu-item:hover {
            opacity: 1;
            color: var(--primary-light);
        }

        .ammo-pattern {
            display: flex;
            flex-wrap: wrap;
            margin-top: 10px;
            gap: 10px;
        }
        
        .ammo-round {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            font-weight: bold;
        }
        
        .regular-ammo {
            background-color: rgba(33, 150, 243, 0.3);
            border: 2px solid var(--primary-light);
        }
        
        .tracer-ammo {
            background-color: rgba(244, 67, 54, 0.3);
            border: 2px solid #f44336;
            color: #f44336;
        }

        @media (max-width: 768px) {
            h2 {
                font-size: 1.5rem;
            }

            .card {
                padding: 20px;
            }

            .button-group {
                flex-direction: column;
            }

            button {
                width: 100%;
                margin-right: 0;
            }

            .grid {
                grid-template-columns: 1fr;
            }
        }

        /* Animation */
        @keyframes pulse {
            0% {
                box-shadow: 0 0 0 0 rgba(33, 150, 243, 0.7);
            }
            70% {
                box-shadow: 0 0 0 10px rgba(33, 150, 243, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(33, 150, 243, 0);
            }
        }

        .pulse {
            animation: pulse 2s infinite;
        }

        /* Loader */
        .loader {
            border: 4px solid rgba(33, 150, 243, 0.3);
            border-radius: 50%;
            border-top: 4px solid var(--primary-light);
            width: 30px;
            height: 30px;
            animation: spin 1s linear infinite;
            margin: 20px auto;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-bullseye" style="color: #ff9800;"></i> Kalkulator Wyników Strzeleckich</h1>
        </header>

        <section id="calculator" class="tab-section active card">
            <div class="card-header">
                <i class="fas fa-calculator card-icon" style="color: #4caf50;"></i>
                <h2>Kalkulator Wyników</h2>
            </div>
            
            <div>
                <label class="icon-label" for="shooters"><i class="fas fa-users"></i> Liczba strzelających:</label>
                <input type="number" id="shooters" min="0" value="0">
                
                <label class="icon-label" for="very-good"><i class="fas fa-medal" style="color: gold;"></i> Bardzo dobrych:</label>
                <input type="number" id="very-good" min="0" value="0">
                
                <label class="icon-label" for="good"><i class="fas fa-thumbs-up" style="color: #4caf50;"></i> Dobrych:</label>
                <input type="number" id="good" min="0" value="0">
                
                <label class="icon-label" for="satisfactory"><i class="fas fa-check" style="color: #2196f3;"></i> Dostatecznych:</label>
                <input type="number" id="satisfactory" min="0" value="0">
                
                <label class="icon-label" for="unsatisfactory"><i class="fas fa-times" style="color: #f44336;"></i> Niedostatecznych:</label>
                <input type="number" id="unsatisfactory" min="0" value="0">
                
                <button id="calculate-btn" onclick="calculateResults()">
                    <i class="fas fa-calculator"></i>
                    Oblicz wyniki
                </button>
                
                <div id="results" class="result-box" style="display: none;">
                    <h3><i class="fas fa-chart-pie" style="color: #e91e63;"></i> Zestawienie wyników:</h3>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-users"></i> Strzelało:</span>
                        <span class="result-value" id="result-shooters">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-medal" style="color: gold;"></i> Bardzo dobrych:</span>
                        <span class="result-value" id="result-very-good">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-thumbs-up" style="color: #4caf50;"></i> Dobrych:</span>
                        <span class="result-value" id="result-good">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-check" style="color: #2196f3;"></i> Dostatecznych:</span>
                        <span class="result-value" id="result-satisfactory">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-times" style="color: #f44336;"></i> Niedostatecznych:</span>
                        <span class="result-value" id="result-unsatisfactory">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-percent" style="color: #9c27b0;"></i> Procent wykonania:</span>
                        <span class="result-value" id="result-percentage">0%</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-calculator" style="color: #ff5722;"></i> Ocena średnia arytmetyczna:</span>
                        <span class="result-value" id="result-average">0.00</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-award" style="color: #ffeb3b;"></i> Ocena ogólna:</span>
                        <span class="result-value" id="result-overall">Niedostateczna</span>
                    </div>

                    <button type="button" class="collapsible"><i class="fas fa-info-circle" style="margin-right: 10px;"></i> Pokaż szczegóły</button>
                    <div class="content">
                        <div class="content-padding" id="details-content">
                            <p>Aby wyświetlić szczegółowe obliczenia, kliknij przycisk "Oblicz wyniki".</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="ammunition" class="tab-section card">
            <div class="card-header">
                <i class="fas fa-boxes card-icon" style="color: #ff9800;"></i>
                <h2>Zużycie Amunicji</h2>
            </div>
            
            <div>
                <label class="icon-label" for="ammo-shooters"><i class="fas fa-users"></i> Liczba strzelających:</label>
                <input type="number" id="ammo-shooters" min="0" value="0">
                
                <label class="icon-label" for="exercise-type"><i class="fas fa-list-ul" style="color: #9c27b0;"></i> Rodzaj strzelania:</label>
                <select id="exercise-type">
                    <option value="">Wybierz rodzaj strzelania</option>
                    <option value="cp">1. ĆWICZENIE PRZYGOTOWAWCZE</option>
                    <option value="ss">2. STRZELANIE SZKOLNE</option>
                    <option value="sb">3. STRZELANIE BOJOWE</option>
                    <option value="rgr">4. RZUCANIE GRANATAMI RĘCZNYMI</option>
                    <option value="ss">5. STRZELANIE SYTUACYJNE</option>
                </select>
                
                <label class="icon-label" for="specific-exercise"><i class="fas fa-bullseye" style="color: #e91e63;"></i> Konkretne ćwiczenie:</label>
                <select id="specific-exercise" disabled>
                    <option value="">Najpierw wybierz rodzaj strzelania</option>
                </select>
                
                <div class="button-group">
                    <button id="calculate-ammo-btn" onclick="calculateAmmo(false)">
                        <i class="fas fa-calculator"></i>
                        Oblicz zużycie amunicji (bez smugowej)
                    </button>
                    
                    <button id="calculate-ammo-with-tracer-btn" onclick="calculateAmmo(true)" style="background: linear-gradient(to right, var(--primary-dark), #f44336);">
                        <i class="fas fa-fire"></i>
                        Oblicz zużycie amunicji (z smugową)
                    </button>
                </div>
                
                <div id="ammo-results" class="result-box" style="display: none;">
                    <h3><i class="fas fa-boxes" style="color: #ff9800;"></i> Zużycie amunicji:</h3>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-users"></i> Liczba strzelających:</span>
                        <span class="result-value" id="ammo-result-shooters">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-clipboard-list" style="color: #4caf50;"></i> Ćwiczenie:</span>
                        <span class="result-value" id="ammo-result-exercise"></span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-user-shield" style="color: #2196f3;"></i> Amunicja na osobę:</span>
                        <span class="result-value" id="ammo-per-person">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-boxes" style="color: #ff9800;"></i> Całkowite zużycie amunicji:</span>
                        <span class="result-value" id="ammo-total">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-box" style="color: #9e9e9e;"></i> Amunicja zwykła:</span>
                        <span class="result-value" id="ammo-regular">0</span>
                    </div>
                    <div class="result-item">
                        <span class="result-label"><i class="fas fa-fire" style="color: #f44336;"></i> Amunicja smugowa:</span>
                        <span class="result-value" id="ammo-tracer">0</span>
                    </div>
                    
                    <!-- Nowy element do wyświetlania wzorca rozmieszczenia amunicji -->
                    <div class="result-item" id="tracer-pattern-container" style="display: none; flex-direction: column; align-items: flex-start;">
                        <div class="result-label" style="margin-bottom: 10px;"><i class="fas fa-list-ol" style="color: #9c27b0;"></i> Rozmieszczenie amunicji:</div>
                        <div id="ammo-pattern" class="ammo-pattern"></div>
                    </div>
                </div>
            </div>
        </section>

        <section id="conditions" class="tab-section card">
            <div class="card-header">
                <i class="fas fa-crosshairs card-icon" style="color: #f44336;"></i>
                <h2>Warunki Strzelania</h2>
            </div>
            
            <div>
                <label class="icon-label" for="shooting-category"><i class="fas fa-folder-open" style="color: #9c27b0;"></i> Kategoria strzelania:</label>
                <select id="shooting-category" onchange="updateExercises()">
                    <option value="">Wybierz kategorię</option>
                    <option value="preparatory">1. ĆWICZENIE PRZYGOTOWAWCZE</option>
                    <option value="school">2. STRZELANIE SZKOLNE</option>
                    <option value="combat">3. STRZELANIE BOJOWE</option>
                    <option value="grenade">4. RZUCANIE GRANATAMI RĘCZNYMI</option>
                    <option value="situational">5. STRZELANIE SYTUACYJNE</option>
                </select>
                
                <label class="icon-label" for="exercise-select"><i class="fas fa-tasks" style="color: #4caf50;"></i> Ćwiczenie:</label>
                <select id="exercise-select" onchange="showExerciseDetails()" disabled>
                    <option value="">Najpierw wybierz kategorię</option>
                </select>
                
                <div id="exercise-details" class="result-box" style="display: none;">
                    <h3 id="exercise-title"><i class="fas fa-info-circle" style="color: #2196f3; margin-right: 10px;"></i> Szczegóły ćwiczenia</h3>
                    <div id="exercise-content">
                        <p>Wybierz ćwiczenie, aby zobaczyć szczegóły.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="specifications" class="tab-section card">
            <div class="card-header">
                <i class="fas fa-info-circle card-icon" style="color: #2196f3;"></i>
                <h2>Dane Taktyczno-Techniczne</h2>
            </div>
            
            <div class="tabs">
                <button class="tab-button active" onclick="openTab(event, 'beryl')"><i class="fas fa-gun"></i> BERYL</button>
                <button class="tab-button" onclick="openTab(event, 'ukm')"><i class="fas fa-gun"></i> UKM</button>
                <button class="tab-button" onclick="openTab(event, 'vis100')"><i class="fas fa-gun"></i> VIS 100</button>
                <button class="tab-button" onclick="openTab(event, 'grot')"><i class="fas fa-gun"></i> MSBS GROT</button>
            </div>
            
            <div id="beryl" class="tab-content active">
                <h3><i class="fas fa-gun" style="color: #4caf50; margin-right: 10px;"></i> Dane taktyczno-techniczne karabinka szturmowego wz. 96 Beryl</h3>
                <div class="specs-grid">
                    <div><i class="fas fa-bullseye"></i> Amunicja</div>
                    <div>5,56 x 45 mm NATO</div>
                    <div><i class="fas fa-tachometer-alt"></i> Prędkość wylotowa dla pocisku SS109</div>
                    <div>V0 = 920 m/s</div>
                    <div><i class="fas fa-bolt"></i> Energia wylotowa dla pocisku SS109</div>
                    <div>E0 = 1690 J</div>
                    <div><i class="fas fa-fire"></i> Rodzaj ognia</div>
                    <div>pojedynczy, seria 3-strzałowa, ciągły</div>
                    <div><i class="fas fa-fast-forward"></i> Szybkostrzelność teoretyczna</div>
                    <div>700 strz./min.</div>
                    <div><i class="fas fa-crosshairs"></i> Donośność skuteczna</div>
                    <div>600 m</div>
                    <div><i class="fas fa-eye"></i> Zakres nastaw celownika</div>
                    <div>100 - 1000 m</div>
                    <div><i class="fas fa-box"></i> Pojemność magazynka</div>
                    <div>30 naboi</div>
                    <div><i class="fas fa-cogs"></i> Zasada działania</div>
                    <div>odprowadzanie gazów przez boczny otwór w lufie</div>
                    <div><i class="fas fa-circle-notch"></i> Liczba bruzd w lufie</div>
                    <div>6</div>
                    <div><i class="fas fa-sync"></i> Skok gwintu lufy</div>
                    <div>228 mm</div>
                    <div><i class="fas fa-ruler-horizontal"></i> Długość z kolbą rozłożoną</div>
                    <div>980 mm</div>
                    <div><i class="fas fa-compress-arrows-alt"></i> Długość z kolbą złożoną</div>
                    <div>910 mm</div>
                    <div><i class="fas fa-ruler"></i> Długość lufy</div>
                    <div>457 mm</div>
                    <div><i class="fas fa-arrows-alt-h"></i> Długość linii celowniczej</div>
                    <div>372 mm</div>
                    <div><i class="fas fa-weight-hanging"></i> Karabin bez magazynka</div>
                    <div>ok. 3650 g</div>
                    <div><i class="fas fa-weight"></i> Magazynek 30-nabojowy pusty</div>
                    <div>ok. 185 g</div>
                    <div><i class="fas fa-balance-scale"></i> Magazynek 30-nabojowy załadowany</div>
                    <div>ok. 554 g</div>
                </div>
            </div>
            
            <div id="ukm" class="tab-content">
                <h3><i class="fas fa-gun" style="color: #ff9800; margin-right: 10px;"></i> Dane taktyczno-techniczne UKM</h3>
                <p>Dane techniczne zostaną dodane wkrótce.</p>
            </div>
            
            <div id="vis100" class="tab-content">
                <h3><i class="fas fa-gun" style="color: #e91e63; margin-right: 10px;"></i> Dane taktyczno-techniczne VIS 100</h3>
                <div class="specs-grid">
                    <div><i class="fas fa-bullseye"></i> Kaliber</div>
                    <div>9 x 19 mm</div>
                    
                    <div><i class="fas fa-cogs"></i> Zasada działania</div>
                    <div>Krótki odrzut lufy ryglowanej przez przekoszenie lufy</div>
                    
                    <div><i class="fas fa-hand-pointer"></i> System spustu</div>
                    <div>Single Action / Double Action (z kurkiem zewnętrznym)</div>
                    
                    <div><i class="fas fa-weight-hanging"></i> Siła spustu</div>
                    <div>SA/DA 25N/50N</div>
                    
                    <div><i class="fas fa-arrows-alt-h"></i> Droga spustu</div>
                    <div>ok. 14 mm</div>
                    
                    <div><i class="fas fa-box"></i> Pojemność magazynka</div>
                    <div>15/17 naboi</div>
                    
                    <div><i class="fas fa-tachometer-alt"></i> Prędkość wylotowa pocisku</div>
                    <div>V⁰: ~360 m/s</div>
                    
                    <div><i class="fas fa-bolt"></i> Energia wylotowa pocisku</div>
                    <div>E⁰: ~518 J</div>
                    
                    <div><i class="fas fa-exclamation-triangle"></i> Zasięg zagrożenia</div>
                    <div>ok. 2000 m</div>
                    
                    <div><i class="fas fa-crosshairs"></i> Przyrządy celownicze</div>
                    <div>Otwarte, szczerbinkowe, wyregulowane na 25 m, światłowodowe</div>
                    
                    <div><i class="fas fa-bullseye"></i> Taktyczny zasięg rażenia</div>
                    <div>ok. 150 m</div>
                    
                    <div><i class="fas fa-shield-alt"></i> Zabezpieczenie</div>
                    <div>Automatyczna, wewnętrzna blokada iglicy, sterowana spustem. Zwalniacz kurka. Przerywacz</div>
                    
                    <div><i class="fas fa-cog"></i> Mechanizm spustowo-uderzeniowy</div>
                    <div>SA/DA (z kurkiem zewnętrznym)</div>
                    
                    <div style="grid-column: 1 / -1; margin-top: 15px; padding-top: 10px; border-top: 1px solid rgba(255, 255, 255, 0.1);">
                        <h4 style="color: var(--primary-light);"><i class="fas fa-ruler-combined" style="margin-right: 8px;"></i> WYMIARY:</h4>
                    </div>
                    
                    <div><i class="fas fa-arrows-alt-v"></i> Wysokość</div>
                    <div>136 mm (bez magazynka)</div>
                    
                    <div><i class="fas fa-ruler-horizontal"></i> Długość</div>
                    <div>193 mm</div>
                    
                    <div><i class="fas fa-arrows-alt-h"></i> Szerokość</div>
                    <div>34 mm</div>
                    
                    <div><i class="fas fa-ruler"></i> Długość lufy</div>
                    <div>110 mm</div>
                    
                    <div><i class="fas fa-sync"></i> Skok gwintu lufy</div>
                    <div>250 mm</div>
                    
                    <div><i class="fas fa-arrows-alt-h"></i> Długość linii celowania</div>
                    <div>156 mm</div>
                    
                    <div style="grid-column: 1 / -1; margin-top: 15px; padding-top: 10px; border-top: 1px solid rgba(255, 255, 255, 0.1);">
                        <h4 style="color: var(--primary-light);"><i class="fas fa-weight-hanging" style="margin-right: 8px;"></i> MASA:</h4>
                    </div>
                    
                    <div><i class="fas fa-weight-hanging"></i> Masa pistoletu bez magazynka</div>
                    <div>695 g</div>
                    
                    <div><i class="fas fa-weight"></i> Masa magazynka pustego</div>
                    <div>90 g</div>
                </div>
            </div>
            
            <div id="grot" class="tab-content">
                <h3><i class="fas fa-gun" style="color: #4caf50; margin-right: 10px;"></i> Funkcjonalność i cechy karabinów MSBS GROT</h3>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Ryflowana lufa o długości 16 cali</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Ergonomiczna konstrukcja z obustronnymi manipulatorami</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Możliwość łatwego ustawienia wyrzutnika łusek na lewą lub prawą stronę</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Zmodyfikowany system gazowy z krótkim skokiem tłoka</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Regulator gazowy typu otwartego</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Modułowe łoże w systemie M-LOK</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Górna szyna Picatinny</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Składana, teleskopowa kolba</li>
                    <li><i class="fas fa-check" style="color: #4caf50; margin-right: 8px;"></i> Tłumik płomienia z przeciwnakrętką</li>
                </ul>
                
                <h3><i class="fas fa-clipboard-list" style="color: #2196f3; margin-right: 10px;"></i> Cechy produktu</h3>
                <div class="specs-grid">
                    <div><i class="fas fa-bullseye"></i> Kaliber</div>
                    <div>5.56x45mm / .223REM</div>
                    <div><i class="fas fa-ruler-horizontal"></i> Długość całkowita</div>
                    <div>865 - 924 mm</div>
                    <div><i class="fas fa-compress-arrows-alt"></i> Długość ze złożoną kolbą</div>
                    <div>700 mm</div>
                    <div><i class="fas fa-arrows-alt-h"></i> Szerokość</div>
                    <div>39 mm (z rączkami napinacza 86 mm)</div>
                    <div><i class="fas fa-arrows-alt-v"></i> Wysokość</div>
                    <div>206 mm</div>
                    <div><i class="fas fa-ruler"></i> Długość lufy</div>
                    <div>406 mm (16 cali)</div>
                    <div><i class="fas fa-ruler-combined"></i> Długość łoża</div>
                    <div>230 mm</div>
                    <div><i class="fas fa-weight-hanging"></i> Waga</div>
                    <div>3700 g</div>
                    <div><i class="fas fa-box"></i> Pojemność magazynka</div>
                    <div>10 sztuk</div>
                    <div><i class="fas fa-circle-notch"></i> Typ lufy</div>
                    <div>Gwintowana 6-krotna, prawoskrętny, 178mm</div>
                    <div><i class="fas fa-cogs"></i> System gazowy</div>
                    <div>Tłokowy</div>
                    <div><i class="fas fa-tools"></i> Łoże</div>
                    <div>Modułowe, w systemie M-LOK</div>
                    <div><i class="fas fa-chair"></i> Kolba</div>
                    <div>Polimerowa, regulowana</div>
                </div>
            </div>
        </section>
    </div>

    <nav class="mobile-menu">
        <div class="menu-item active" onclick="switchTab('calculator', this)">
            <i class="fas fa-calculator" style="color: #4caf50;"></i>
            <span>Kalkulator</span>
        </div>
        <div class="menu-item" onclick="switchTab('ammunition', this)">
            <i class="fas fa-boxes" style="color: #ff9800;"></i>
            <span>Amunicja</span>
        </div>
        <div class="menu-item" onclick="switchTab('conditions', this)">
            <i class="fas fa-crosshairs" style="color: #f44336;"></i>
            <span>Warunki</span>
        </div>
        <div class="menu-item" onclick="switchTab('specifications', this)">
            <i class="fas fa-info-circle" style="color: #2196f3;"></i>
            <span>Dane tech.</span>
        </div>
    </nav>

    <script>
        // Definicje ćwiczeń
        const exercisesData = {
            preparatory: [
                {
                    id: "cp1",
                    title: "ĆP z karabinka do pełnienia służby wartowniczej",
                    details: {
                        cele: "nr 1 - 2 x figura bojowa nr 40 (biegnący) ukazuje i ukrywa się na komendę kierownika strzelania; nr 2 - figura bojowa nr 23 (popiersie); nr 3 - figura bojowa nr 30 (klęczący); Cele nr 2 i 3 ukazują się jednocześnie na 25 sekund po 10 sekundach od ukrycia się celu nr 1.",
                        odleglosc: "nr 1 - 150 m; nr 2 - 75 m; nr 3 - 100 m.",
                        naboje: "6 szt.",
                        czas: "ograniczony ukazywaniem się celów.",
                        postawa: "nr 1 - stojąca; nr 2 i 3 - klęcząca za ukryciem.",
                        rodzaj_ognia: "ogień pojedynczy.",
                        ocena: "\"bardzo dobrze\" - trafić dwa cele; \"dobrze\" - trafić cel nr 2; \"dostatecznie\" - trafić cel nr 3.",
                        warunki: "dzień, noc."
                    },
                    ammo: 6
                },
                {
                    id: "cp2",
                    title: "ĆP z karabinka Mini Beryl do pełnienia służby wartowniczej",
                    details: {
                        cele: "nr 1 - 2 x figura bojowa nr 40 (biegnący) ukazuje i ukrywa się na komendę kierownika strzelania; nr 2 - figura bojowa nr 23 (popiersie); nr 3 - figura bojowa nr 30 (klęczący). Cele nr 2 i 3 ukazują się jednocześnie na 25 sekund po 10 sekundach od ukrycia się celu nr 1.",
                        odleglosc: "nr 1 - 150 m; nr 2 - 50 m; nr 3 - 75 m.",
                        naboje: "6 szt. (w pistoletach, które nie mają przełącznika rodzaju ognia - 12 szt.).",
                        czas: "ograniczony ukazywaniem się celów.",
                        postawa: "nr 1 - stojąca; nr 2 i 3 - klęcząca za ukryciem.",
                        rodzaj_ognia: "ogień pojedynczy (w pistoletach, które nie mają przełącznika rodzaju ognia - krótkimi seriami).",
                        ocena: "\"bardzo dobrze\" - trafić dwa cele; \"dobrze\" - trafić cel nr 2; \"dostatecznie\" - trafić cel nr 3.",
                        warunki: "dzień, noc."
                    },
                    ammo: 6
                },
                {
                    id: "cp3",
                    title: "ĆP z pistoletu maszynowego do pełnienia służby wartowniczej",
                    details: {
                        cele: "nr 1 - figura bojowa nr TS-10 ukazuje się dwa razy; pierwsze ukazanie - na 20 sekund; drugie ukazanie na 10 sekund, bezpośrednio po trafieniu lub ukryciu się celu nr 2; nr 2 - figura bojowa TS-10, ukazuje się na 10 sekund, po 5 sekundach od trafienia lub ukryciu się celu nr 1 po jego pierwszym ukazaniu; nr 3 - figura bojowa nr TS-10, ukazuje się na 10 sekund, cel ukazuje się bezpośrednio po trafieniu lub ukryciu się celu nr 1 po jego drugim ukazaniu.",
                        odleglosc: "nr 1 i 2 - 40-50 m; nr 3 - 20-25 m.",
                        naboje: "5 szt.",
                        czas: "ograniczony ukazywaniem się celów.",
                        postawa: "dowolna (według decyzji strzelającego).",
                        rodzaj_ognia: "ogień pojedynczy.",
                        ocena: "\"bardzo dobrze\" - trafić trzy cele; \"dobrze\" - trafić dwa cele; \"dostatecznie\" - trafić jeden cel.",
                        warunki: "dzień."
                    },
                    ammo: 5
                }
            ],
            school: [
                {
                    id: "ss1",
                    title: "SSz Nr 1 Tor - strzelanie na celność i skupienie",
                    details: {
                        cele: "2 tarcze 23p na ekranie 1x1,5 m lub na 2 ekranach 0,75x0,75 m.",
                        odleglosc: "400, 600, 800m (300m sprawdzenie przystrzelenia).",
                        naboje: "40 szt. - 10 szt. na każdą odległość, 10 szt. na sprawdzenie przystrzelenia; Amunicja 12,7x99 o ulepszonym skupieniu.",
                        czas: "10 minut - sprawdzenie przystrzelenia broni - 300m. 30 minut - 10 minut na każdą odległość.",
                        postawa: "leżąca z podpórką, leżąca z dwójnogiem.",
                        ocena: "\"bdb\" - uzyskać wymagane skupienie i minimum 48 punktów na 400 m, \"db\" - uzyskać wymagane skupienia i minimum 44 punkty, \"dst\" - uzyskać wymagane skupienia.",
                        warunki: "dzień, wiatr do 6m/s."
                    },
                    ammo: 40
                },
                {
                    id: "ss2",
                    title: "SSz Nr 1 z karabinu wyborowego SWD - strzelanie na celność",
                    details: {
                        cele: "3 x obserwator (3 x figura bojowa nr 20), z których każdy ukazuje się raz na 20 sekund z przerwami 20-to sekundowymi.",
                        odleglosc: "200-300 m.",
                        naboje: "6 szt.",
                        czas: "ograniczony ukazywaniem się celów.",
                        postawa: "dowolna ze zmianą SO.",
                        rodzaj_ognia: "pojedynczy.",
                        ocena: "\"bardzo dobrze\" - trafić trzy cele; \"dobrze\" - trafić dwa cele; \"dostatecznie\" - trafić cel.",
                        warunki: "dzień, noc, w maskach."
                    },
                    ammo: 6
                },
                {
                    id: "ss3",
                    title: "SSz Nr 1 - strzelanie w postawie siedzącej z 40 mm granatnika MK-19",
                    details: {
                        cele: "Grupa piechoty: 4 x biegnący (4 x figura bojowa nr 40) rozmieszczony w środku pola prostokąta o szerokości 10 m i głębokości 20 m.",
                        odleglosc: "400-450 m.",
                        naboje: "6 szt.",
                        czas: "nieograniczony.",
                        postawa: "siedząca.",
                        rodzaj_ognia: "pojedynczy.",
                        ocena: "\"bardzo dobrze\" - trafić w pole cztery razy, \"dobrze\" - trafić w pole 3 razy, \"dostatecznie\" - trafić w pole.",
                        warunki: "dzień."
                    },
                    ammo: 6
                },
                {
                    id: "ss4",
                    title: "SSz Nr 2 - strzelanie w postawie siedzącej z 40 mm granatnika MK-19",
                    details: {
                        cele: "Moździerz z obsługą (figura bojowa nr 34)",
                        odleglosc: "600 m.",
                        naboje: "6 szt.",
                        czas: "nieograniczony.",
                        postawa: "siedząca.",
                        rodzaj_ognia: "wg decyzji strzelającego.",
                        ocena: "\"bardzo dobrze\" - trafić cel trzy razy, \"dobrze\" - trafić cel dwa razy, \"dostatecznie\" - trafić cel raz.",
                        warunki: "dzień, noc."
                    },
                    ammo: 6
                },
                {
                    id: "ss5",
                    title: "SSz Nr 1 - rażenie celu nieruchomego ogniem półpośrednim z przygotowanego stanowiska ogniowego 60 mm moździerza LM - 60 D",
                    details: {
                        cele: "piechota (3 figury bojowe nr 30, 40 lub 40a) lub karabin maszynowy (figura bojowa nr 27) lub granatnik ciężki (figura bojowa nr 36) lub pancerzownica (figura bojowa nr 31).",
                        odleglosc: "od minimalnej do maksymalnej",
                        naboje: "pocisk odłamkowy; zużycie amunicji na wstrzeliwanie - 5 szt.",
                        czas: "bdb: 4', db: 5', dst: 6'",
                        ocena: "Zadanie ogólnej ocenia się na podstawie średniej za czas i dokładność ognia skutecznego."
                    },
                    ammo: 5
                }
            ],
            combat: [
                {
                    id: "sb1",
                    title: "SB dla karabinów wyborowych: SWD oraz TRG21, TRG 22 z celownikami PM1 Nr B1",
                    details: {
                        cele: "nr 1 - obserwator (figura bojowa nr 20) ukazuje się na 50 sekund; nr 2 - głowa (figura bojowa nr 22) ukazuje się na 60 sekund, cel ukazuje się po 20 sekundach od trafienia lub ukrycia się celu nr 1; nr 3 - popiersie (figura bojowa nr 23) ukazuje się na 1 minutę, cel ukazuje się po 10 sekundach od trafienia lub ukrycia się celu nr 2; nr 4 - biegnący (figura bojowa nr 40a), porusza się ruchem poprzecznym lub skośnym na odcinku 2 x 50 m. Cel rozpoczyna ruch po 10 sekundach od trafienia lub ukrycia się celu nr 3.",
                        odleglosc: "nr 1 - 300-400 m; nr 2 - 300-400 m; nr 3 - 500 m; nr 4 - 400-500 m.",
                        naboje: "7 szt.",
                        czas: "ograniczony ukazywaniem się celów.",
                        postawa: "leżąca z wykorzystaniem podpórki.",
                        ocena: "\"bardzo dobrze\" - trafić wszystkie cele; \"dobrze\" - trafić trzy cele; \"dostatecznie\" - trafić dwa cele, w tym cel nr 1.",
                        warunki: "dzień, noc."
                    },
                    ammo: 7
                },
                {
                    id: "sb2",
                    title: "SB nr B1 - strzelanie do wielu celów w postawie siedzącej z 40 mm granatnika MK-19",
                    details: {
                        cele: "nr 1 - transporter opancerzony rozpoznawczy (figura bojowa nr 49) rozmieszczony w kwadracie o boku 3 m, ukazujący się na 30 sekund; nr 2 - moździerz z obsługą (figura bojowa 34) rozmieszczony w kole o promieniu 5 m, ukazujący się na 20 sekund. Cel ukazuje się po 20 sekundach od trafienia lub ukrycia się celu nr 1; nr 3 - granatnik ciężki (figura bojowa nr 36) rozmieszczony w kole o promieniu 5 m, ukazująca się na 20 sekund. Cel ukazuje się po 20 sekundach od trafienia lub ukrycia się celu nr 2.",
                        odleglosc: "nr 1 - 700-800 m; nr 2 - 500-600 m; nr 3 - 400-500 m.",
                        naboje: "10 szt.",
                        czas: "ograniczony czasem ukazywania się celów.",
                        postawa: "siedząca.",
                        rodzaj_ognia: "według decyzji strzelającego.",
                        ocena: "\"bardzo dobrze\" - trafić trzy cele; \"dobrze\" - trafić cel nr 1 i 2 lub nr 3; \"dostatecznie\" - trafić cel nr 1.",
                        warunki: "dzień, noc."
                    },
                    ammo: 10
                },
                {
                    id: "sb3",
                    title: "SB Nr 1 - rażenie celu nieruchomego ogniem półpośrednim z nieprzygotowanego stanowiska ogniowego z 60 mm moździerza LM - 60 D",
                    details: {
                        cele: "piechota (3 figury bojowe nr 30, 40 lub 40a) lub karabin maszynowy (figura bojowa nr 27) lub granatnik ciężki (figura bojowa nr 36) lub pancerzownica (figura bojowa nr 31).",
                        odleglosc: "od minimalnej do maksymalnej",
                        naboje: "pocisk odłamkowy; zużycie amunicji na wstrzeliwanie - 5 szt.",
                        czas: "bdb: 10', db: 11', dst: 12'",
                        ocena: "Zadanie ogólnej ocenia się na podstawie średniej za czas i dokładność ognia skutecznego."
                    },
                    ammo: 5
                }
            ],
            grenade: [
                {
                    id: "rgr1",
                    title: "RGR na odległość w różnych postawach",
                    details: {
                        cele: "biegnący (figura bojowa nr 40) ustawiony na kierunku rzutu.",
                        odleglosc: "40 m.",
                        granaty: "3 szkolne (zaczepne lub obronne).",
                        postawa: "stojąca w okopie, klęcząca i leżąca.",
                        czas: "nieograniczony.",
                        ocena: "stojąca w okopie - bdb: 30m, db: 25m, dst: 20m; klęcząca - bdb: 25m, db: 20m, dst: 15m; leżąca - bdb: 20m, db: 15m, dst: 10m;",
                        warunki: "dzień."
                    },
                    ammo: 3
                },
                {
                    id: "rgr2",
                    title: "RGR w marszu",
                    details: {
                        cele: "grupa piechoty - 3 x biegnący (3 x figura bojowa nr 40) - ustawiony w okopie (widoczne popiersia) wzdłuż frontu w polu o szerokości 10 m i głębokości 5 m.",
                        odleglosc: "40 m (rzut granatem od 35 m do 25 m).",
                        granaty: "1 szkolny/ćwiczebny.",
                        postawa: "w marszu bez zatrzymania się.",
                        czas: "30 s liczony od komendy \"Do ataku - Naprzód\" do komendy \"STÓJ\".",
                        ocena: "\"wykonał\" - trafił w pole.",
                        warunki: "dzień."
                    },
                    ammo: 1
                },
                {
                    id: "rgr3",
                    title: "RGR z wozu bojowego",
                    details: {
                        cele: "grupa piechoty - 3 x biegnący (3 x figura bojowa nr 40) - ustawiony na otwartej przestrzeni w kole o promieniu 2 m. Ponadto, wokół celu wyznacza się dodatkowo koła o promieniu 4 i 6 m.",
                        odleglosc: "20 m.",
                        granaty: "1 szkolny/ćwiczebny.",
                        postawa: "z wozu bojowego (samochodu).",
                        czas: "10 s liczony od komendy \"Granatem - ognia\" do zaryglowania włazu (ukrycia się za burtą samochodu).",
                        ocena: "\"bardzo dobrze\" - trafić w pole o promieniu 2 m; \"dobrze\" - trafić w pole o promieniu 4 m; \"dostatecznie\" - trafić w pole o promieniu 6 m.",
                        warunki: "dzień."
                    },
                    ammo: 1
                },
                {
                    id: "rgr4",
                    title: "Rzut granatem bojowym",
                    details: {
                        cele: "grupa piechoty - 3 x biegnący (3 x figura bojowe nr 40) - rozstawiony wzdłuż frontu na odcinku 5 m, w środkowej części pola długości 10 m i głębokości 5 m.",
                        odleglosc: "20 m.",
                        granaty: "1 bojowy (zaczepny lub obronny).",
                        postawa: "stojąca w okopie.",
                        czas: "nieograniczony.",
                        ocena: "\"wykonał\" - gdy wybuch granatu nastąpi w polu celu.",
                        warunki: "dzień."
                    },
                    ammo: 1
                }
            ],
            situational: [
                {
                    id: "ss1",
                    title: "SS S1 - strzelanie dynamiczne z pistoletu wojskowego",
                    details: {
                        cele: "popiersie (figura bojowa 23), cel stały.",
                        odleglosc: "15 m.",
                        naboje: "3 szt.",
                        czas: "3 sekundy (dobycie broni i oddanie strzałów) dla broni bezkurkowej i z kaburą otwartą lub 5 sekund (dobycie broni, odbezpieczenie, odciągnięcie kurka i oddanie strzału) dla pozostałych typów pistoletów.",
                        postawa: "stojąca z wolnej ręki lub oburącz.",
                        rodzaj_ognia: "pojedynczy.",
                        ocena: "\"bardzo dobrze\" - trafić cel 3 razy; \"dobrze\" - trafić cel 2 razy; \"dostatecznie\" - trafić cel.",
                        warunki: "dzień."
                    },
                    ammo: 3
                },
                {
                    id: "ss2",
                    title: "SS S2 - strzelanie z pistoletu wojskowego do celów ukazujących się",
                    details: {
                        cele: "3 x biegnący (3 x figura bojowa nr 40) lub 3 x tarcze sportowe TS-10 rozstawione na odcinku o szerokości do 15 m, ukazujące się przemiennie w losowej kolejności pojedynczo dla pistoletów bezkurkowych na 10 sekund (dla pozostałych pistoletów na 13 sekund) z przerwą 3 sekundy.",
                        odleglosc: "25 m.",
                        naboje: "6 szt.",
                        czas: "ograniczony czasem ukazywania się celów.",
                        postawa: "stojąca z wolnej ręki lub oburącz.",
                        rodzaj_ognia: "pojedynczy.",
                        ocena: "\"bardzo dobrze\" - trafić 3 cele; \"dobrze\" - trafić 2 cele; \"dostatecznie\" - trafić cel.",
                        warunki: "dzień."
                    },
                    ammo: 6
                },
                {
                    id: "ss3",
                    title: "SS S3 - strzelanie dynamiczne z pistoletu maszynowego",
                    details: {
                        cele: "klęczący (figura bojowa nr 30), cel stały.",
                        odleglosc: "15 m.",
                        naboje: "3 szt.",
                        czas: "5 sekund.",
                        postawa: "stojąca oburącz.",
                        rodzaj_ognia: "pojedynczy.",
                        ocena: "\"bardzo dobrze\" - trafić cel 3 razy; \"dobrze\" - trafić cel 2 razy; \"dostatecznie\" - trafić cel.",
                        warunki: "dzień."
                    },
                    ammo: 3
                },
                {
                    id: "ss4",
                    title: "SS S4 - strzelanie z pistoletu maszynowego dynamiczne z dobiegiem",
                    details: {
                        cele: "biegnący (figura bojowa nr 40) lub tarcza sportowa TS-10, cel stały.",
                        odleglosc: "25 m.",
                        naboje: "8 szt. (po 4 szt. w magazynku).",
                        czas: "1 minuta.",
                        postawa: "stojąca i klęcząca (pistolet trzymany oburącz).",
                        rodzaj_ognia: "według decyzji strzelającego.",
                        ocena: "\"bardzo dobrze\" - trafić cel 6 razy; \"dobrze\" - trafić cel 4 razy; \"dostatecznie\" - trafić cel 3 razy.",
                        warunki: "dzień."
                    },
                    ammo: 8
                },
                {
                    id: "ss5",
                    title: "SS S5 - strzelanie na krótkich odległościach z karabinka / pistoletu maszynowego",
                    details: {
                        cele: "nr 1 - popiersie (figura bojowa nr 23), ukazująca się na 15 sekund; nr 2 - klęczący (figura bojowa nr 30), ukazujący się na 15 sekund, cel ukazuje się po 5 sekundach od trafienia lub ukrycia się celu nr 1; nr 3 - popiersie z granatem (figura bojowa 23g), ukazująca się na 15 sekund, cel ukazuje się po 15 sekundach od trafienia lub ukrycia się celu nr 2; nr 4 - pancerzownica (figura bojowa nr 31), ukazująca się na 15 sekund, cel ukazuje się po 5 sekundach od trafienia lub ukrycia się celu nr 3.",
                        odleglosc: "nr 1 i 3 - 20-40 m; nr 2 i 4 - 40-60 m.",
                        naboje: "20 szt.",
                        czas: "ograniczony czasem ukazywania się celów.",
                        postawa: "nr 1 i 2 - klęcząca; nr 3 i 4 - leżąca.",
                        rodzaj_ognia: "według decyzji strzelającego.",
                        ocena: "\"bardzo dobrze\" - trafić wszystkie cele; \"dobrze\" - trafić dwa cele; \"dostatecznie\" - trafić cel.",
                        warunki: "dzień, noc."
                    },
                    ammo: 20
                }
            ]
        };

        // Definicje dla kalkulatora amunicji
        const exercisesAmmo = {
            cp: [
                { id: "cp1", title: "ĆP z karabinka do pełnienia służby wartowniczej", ammo: 6 },
                { id: "cp2", title: "ĆP z karabinka Mini Beryl do pełnienia służby wartowniczej", ammo: 6 },
                { id: "cp3", title: "ĆP z pistoletu maszynowego do pełnienia służby wartowniczej", ammo: 5 }
            ],
            ss: [
                { id: "ss1", title: "SSz Nr 1 Tor - strzelanie na celność i skupienie", ammo: 40 },
                { id: "ss2", title: "SSz Nr 1 z karabinu wyborowego SWD - strzelanie na celność", ammo: 6 },
                { id: "ss3", title: "SSz Nr 1 - strzelanie w postawie siedzącej z 40 mm granatnika MK-19", ammo: 6 },
                { id: "ss4", title: "SSz Nr 2 - strzelanie w postawie siedzącej z 40 mm granatnika MK-19", ammo: 6 },
                { id: "ss5", title: "SSz Nr 1 - rażenie celu nieruchomego ogniem półpośrednim z przygotowanego stanowiska ogniowego 60 mm moździerza LM - 60 D", ammo: 5 },
                { id: "ss1", title: "SS S1 - strzelanie dynamiczne z pistoletu wojskowego", ammo: 3 },
                { id: "ss2", title: "SS S2 - strzelanie z pistoletu wojskowego do celów ukazujących się", ammo: 6 },
                { id: "ss3", title: "SS S3 - strzelanie dynamiczne z pistoletu maszynowego", ammo: 3 },
                { id: "ss4", title: "SS S4 - strzelanie z pistoletu maszynowego dynamiczne z dobiegiem", ammo: 8 },
                { id: "ss5", title: "SS S5 - strzelanie na krótkich odległościach z karabinka / pistoletu maszynowego", ammo: 20 }
            ],
            sb: [
                { id: "sb1", title: "SB dla karabinów wyborowych: SWD oraz TRG21", ammo: 7 },
                { id: "sb2", title: "SB nr B1 - strzelanie do wielu celów w postawie siedzącej z 40 mm granatnika MK-19", ammo: 10 },
                { id: "sb3", title: "SB Nr 1 - rażenie celu nieruchomego ogniem półpośrednim z nieprzygotowanego stanowiska ogniowego z 60 mm moździerza LM - 60 D", ammo: 5 }
            ],
            rgr: [
                { id: "rgr1", title: "RGR na odległość w różnych postawach", ammo: 3 },
                { id: "rgr2", title: "RGR w marszu", ammo: 1 },
                { id: "rgr3", title: "RGR z wozu bojowego", ammo: 1 },
                { id: "rgr4", title: "Rzut granatem bojowym", ammo: 1 }
            ]
        };

        // Funkcja przełączania zakładek
        function switchTab(tabId, menuItem) {
            // Ukrycie wszystkich sekcji
            const sections = document.getElementsByClassName('tab-section');
            for (let i = 0; i < sections.length; i++) {
                sections[i].classList.remove('active');
            }
            
            // Pokazanie wybranej sekcji
            document.getElementById(tabId).classList.add('active');
            
            // Aktualizacja menu
            const menuItems = document.getElementsByClassName('menu-item');
            for (let i = 0; i < menuItems.length; i++) {
                menuItems[i].classList.remove('active');
            }
            
            // Dodanie aktywnej klasy do klikniętego elementu
            menuItem.classList.add('active');
        }

        // Funkcja do obliczenia wyników
        function calculateResults() {
            const shooters = parseInt(document.getElementById('shooters').value) || 0;
            const veryGood = parseInt(document.getElementById('very-good').value) || 0;
            const good = parseInt(document.getElementById('good').value) || 0;
            const satisfactory = parseInt(document.getElementById('satisfactory').value) || 0;
            const unsatisfactory = parseInt(document.getElementById('unsatisfactory').value) || 0;
            
            // Sprawdzenie poprawności danych
            const totalResults = veryGood + good + satisfactory + unsatisfactory;
            if (totalResults > shooters) {
                alert("Liczba wyników nie może przekraczać liczby strzelających!");
                return;
            }
            
            // Obliczenie procentu wykonania
            const successCount = veryGood + good + satisfactory;
            const percentage = shooters > 0 ? (successCount / shooters * 100).toFixed(2) : 0;
            
            // Obliczenie średniej arytmetycznej
            // Bardzo dobry (5), dobry (4), dostateczny (3), niedostateczny (2)
            const totalScore = veryGood * 5 + good * 4 + satisfactory * 3 + unsatisfactory * 2;
            const average = totalResults > 0 ? (totalScore / totalResults).toFixed(2) : 0;
            
            // Określenie oceny ogólnej
            let overallRating = "Niedostateczna";
            if (average >= 4.51) {
                overallRating = "Bardzo dobra";
            } else if (average >= 3.51) {
                overallRating = "Dobra";
            } else if (average >= 2.51) {
                overallRating = "Dostateczna";
            }
            
            // Wyświetlenie wyników
            document.getElementById('result-shooters').textContent = shooters;
            document.getElementById('result-very-good').textContent = veryGood;
            document.getElementById('result-good').textContent = good;
            document.getElementById('result-satisfactory').textContent = satisfactory;
            document.getElementById('result-unsatisfactory').textContent = unsatisfactory;
            document.getElementById('result-percentage').textContent = percentage + "%";
            document.getElementById('result-average').textContent = average;
            document.getElementById('result-overall').textContent = overallRating;
            
            // Przygotowanie szczegółowych obliczeń
            const details = `
                <h4>Szczegółowe obliczenia:</h4>
                <p><strong>Procent wykonania:</strong> (${veryGood} + ${good} + ${satisfactory}) / ${shooters} × 100% = ${percentage}%</p>
                <p><strong>Średnia arytmetyczna:</strong> (${veryGood} × 5 + ${good} × 4 + ${satisfactory} × 3 + ${unsatisfactory} × 2) / ${totalResults} = ${average}</p>
                <p><strong>Ocena ogólna:</strong> 
                    ${average >= 4.51 ? "średnia ≥ 4.51 → Bardzo dobra" : 
                      average >= 3.51 ? "3.51 ≤ średnia < 4.51 → Dobra" : 
                      average >= 2.51 ? "2.51 ≤ średnia < 3.51 → Dostateczna" : 
                      "średnia < 2.51 → Niedostateczna"}
                </p>
            `;
            
            document.getElementById('details-content').innerHTML = details;
            document.getElementById('results').style.display = 'block';
        }

        // Funkcja do obliczenia zużycia amunicji
        function calculateAmmo(useTracer = false) {
            const shooters = parseInt(document.getElementById('ammo-shooters').value) || 0;
            const exerciseType = document.getElementById('exercise-type').value;
            const specificExercise = document.getElementById('specific-exercise').value;
            
            if (!exerciseType || !specificExercise || shooters <= 0) {
                alert("Wypełnij wszystkie pola!");
                return;
            }
            
            // Znalezienie konkretnego ćwiczenia
            const exerciseList = exercisesAmmo[exerciseType];
            const exercise = exerciseList.find(ex => ex.id === specificExercise);
            
            if (!exercise) {
                alert("Nie znaleziono wybranego ćwiczenia!");
                return;
            }
            
            const ammoPerPerson = exercise.ammo;
            const totalAmmo = ammoPerPerson * shooters;
            
            // Obliczenie amunicji zwykłej i smugowej
            let regularAmmo, tracerAmmo;
            
            if (useTracer) {
                // Co trzeci nabój jest smugowy (stosunek 1:3)
                tracerAmmo = Math.floor(totalAmmo / 3);
                regularAmmo = totalAmmo - tracerAmmo;
            } else {
                // Bez amunicji smugowej
                regularAmmo = totalAmmo;
                tracerAmmo = 0;
            }
            
            // Wyświetlenie wyników
            document.getElementById('ammo-result-shooters').textContent = shooters;
            document.getElementById('ammo-result-exercise').textContent = exercise.title;
            document.getElementById('ammo-per-person').textContent = ammoPerPerson;
            document.getElementById('ammo-total').textContent = totalAmmo;
            document.getElementById('ammo-regular').textContent = regularAmmo;
            document.getElementById('ammo-tracer').textContent = tracerAmmo;
            
            // Wyświetlanie wzorca rozmieszczenia amunicji
            const patternContainer = document.getElementById('tracer-pattern-container');
            const patternDiv = document.getElementById('ammo-pattern');
            
            if (useTracer && tracerAmmo > 0) {
                // Czyszczenie istniejącego wzorca
                patternDiv.innerHTML = '';
                
                // Tworzenie wizualizacji wzorca (maksymalnie 18 naboi dla czytelności)
                const maxDisplay = Math.min(ammoPerPerson, 18);
                for (let i = 1; i <= maxDisplay; i++) {
                    const ammoElement = document.createElement('div');
                    ammoElement.className = 'ammo-round';
                    
                    if (i % 3 === 0) {
                        // Smugowy (co trzeci)
                        ammoElement.classList.add('tracer-ammo');
                        ammoElement.innerHTML = i + '<br>S';
                    } else {
                        // Zwykły
                        ammoElement.classList.add('regular-ammo');
                        ammoElement.innerHTML = i + '<br>Z';
                    }
                    
                    patternDiv.appendChild(ammoElement);
                }
                
                // Pokazanie wzorca
                patternContainer.style.display = 'flex';
            } else {
                // Ukrycie wzorca jeśli nie używamy amunicji smugowej
                patternContainer.style.display = 'none';
            }
            
            document.getElementById('ammo-results').style.display = 'block';
        }

        // Aktualizacja listy ćwiczeń po wyborze kategorii
        function updateExercises() {
            const category = document.getElementById('shooting-category').value;
            const exerciseSelect = document.getElementById('exercise-select');
            
            // Wyczyszczenie listy
            exerciseSelect.innerHTML = '';
            exerciseSelect.disabled = true;
            
            if (!category) {
                exerciseSelect.innerHTML = '<option value="">Najpierw wybierz kategorię</option>';
                return;
            }
            
            // Dodanie opcji "Wybierz ćwiczenie"
            const defaultOption = document.createElement('option');
            defaultOption.value = '';
            defaultOption.textContent = 'Wybierz ćwiczenie';
            exerciseSelect.appendChild(defaultOption);
            
            // Dodanie ćwiczeń z wybranej kategorii
            const exercises = exercisesData[category];
            if (exercises && exercises.length > 0) {
                exercises.forEach(exercise => {
                    const option = document.createElement('option');
                    option.value = exercise.id;
                    option.textContent = exercise.title;
                    exerciseSelect.appendChild(option);
                });
                
                exerciseSelect.disabled = false;
            } else {
                exerciseSelect.innerHTML = '<option value="">Brak ćwiczeń w tej kategorii</option>';
            }
            
            // Ukrycie szczegółów ćwiczenia
            document.getElementById('exercise-details').style.display = 'none';
        }

        // Wyświetlenie szczegółów ćwiczenia
        function showExerciseDetails() {
            const category = document.getElementById('shooting-category').value;
            const exerciseId = document.getElementById('exercise-select').value;
            
            if (!category || !exerciseId) {
                document.getElementById('exercise-details').style.display = 'none';
                return;
            }
            
            // Znalezienie ćwiczenia
            const exercises = exercisesData[category];
            const exercise = exercises.find(ex => ex.id === exerciseId);
            
            if (!exercise) {
                document.getElementById('exercise-details').style.display = 'none';
                return;
            }
            
            // Przygotowanie zawartości
            document.getElementById('exercise-title').innerHTML = '<i class="fas fa-info-circle" style="color: #2196f3; margin-right: 10px;"></i>' + exercise.title;
            
            let content = '';
            const details = exercise.details;
            
            // Dodanie wszystkich dostępnych szczegółów z ikonami
            if (details.cele) content += `<div class="result-item"><span class="result-label"><i class="fas fa-bullseye" style="color: #f44336;"></i> Cele:</span><span>${details.cele}</span></div>`;
            if (details.odleglosc) content += `<div class="result-item"><span class="result-label"><i class="fas fa-ruler-horizontal" style="color: #4caf50;"></i> Odległość:</span><span>${details.odleglosc}</span></div>`;
            if (details.naboje) content += `<div class="result-item"><span class="result-label"><i class="fas fa-boxes" style="color: #ff9800;"></i> Liczba nabojów:</span><span>${details.naboje}</span></div>`;
            if (details.granaty) content += `<div class="result-item"><span class="result-label"><i class="fas fa-bomb" style="color: #9c27b0;"></i> Liczba granatów:</span><span>${details.granaty}</span></div>`;
            if (details.czas) content += `<div class="result-item"><span class="result-label"><i class="fas fa-clock" style="color: #2196f3;"></i> Czas:</span><span>${details.czas}</span></div>`;
            if (details.postawa) content += `<div class="result-item"><span class="result-label"><i class="fas fa-user" style="color: #e91e63;"></i> Postawa:</span><span>${details.postawa}</span></div>`;
            if (details.rodzaj_ognia) content += `<div class="result-item"><span class="result-label"><i class="fas fa-fire" style="color: #f44336;"></i> Rodzaj ognia:</span><span>${details.rodzaj_ognia}</span></div>`;
            if (details.ocena) content += `<div class="result-item"><span class="result-label"><i class="fas fa-star" style="color: #ffeb3b;"></i> Ocena:</span><span>${details.ocena}</span></div>`;
            if (details.warunki) content += `<div class="result-item"><span class="result-label"><i class="fas fa-cloud-sun" style="color: #03a9f4;"></i> Warunki strzelania:</span><span>${details.warunki}</span></div>`;
            
            document.getElementById('exercise-content').innerHTML = content;
            document.getElementById('exercise-details').style.display = 'block';
        }

        // Aktualizacja konkretnych ćwiczeń po wyborze rodzaju strzelania
        document.getElementById('exercise-type').addEventListener('change', function() {
            const exerciseType = this.value;
            const specificExerciseSelect = document.getElementById('specific-exercise');
            
            // Wyczyszczenie listy
            specificExerciseSelect.innerHTML = '';
            specificExerciseSelect.disabled = true;
            
            if (!exerciseType) {
                specificExerciseSelect.innerHTML = '<option value="">Najpierw wybierz rodzaj strzelania</option>';
                return;
            }
            
            // Dodanie opcji "Wybierz ćwiczenie"
            const defaultOption = document.createElement('option');
            defaultOption.value = '';
            defaultOption.textContent = 'Wybierz ćwiczenie';
            specificExerciseSelect.appendChild(defaultOption);
            
            // Dodanie ćwiczeń z wybranego rodzaju
            const exercises = exercisesAmmo[exerciseType];
            if (exercises && exercises.length > 0) {
                exercises.forEach(exercise => {
                    const option = document.createElement('option');
                    option.value = exercise.id;
                    option.textContent = exercise.title;
                    specificExerciseSelect.appendChild(option);
                });
                
                specificExerciseSelect.disabled = false;
            } else {
                specificExerciseSelect.innerHTML = '<option value="">Brak ćwiczeń w tej kategorii</option>';
            }
        });

        // Obsługa zakładek w specyfikacjach technicznych
        function openTab(evt, tabName) {
            // Ukrycie wszystkich zakładek
            const tabContents = document.getElementsByClassName("tab-content");
            for (let i = 0; i < tabContents.length; i++) {
                tabContents[i].classList.remove("active");
            }
            
            // Usunięcie aktywnej klasy z przycisków zakładek
            const tabButtons = document.getElementsByClassName("tab-button");
            for (let i = 0; i < tabButtons.length; i++) {
                tabButtons[i].classList.remove("active");
            }
            
            // Pokazanie wybranej zakładki i uaktywnienie przycisku
            document.getElementById(tabName).classList.add("active");
            evt.currentTarget.classList.add("active");
        }

        // Obsługa elementów zwijanych
        const collapsibles = document.getElementsByClassName("collapsible");
        for (let i = 0; i < collapsibles.length; i++) {
            collapsibles[i].addEventListener("click", function() {
                this.classList.toggle("active");
                const content = this.nextElementSibling;
                if (content.style.maxHeight) {
                    content.style.maxHeight = null;
                } else {
                    content.style.maxHeight = content.scrollHeight + "px";
                }
            });
        }
    </script>
</body>
</html>
