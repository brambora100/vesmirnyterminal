<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astrofyzikální Kvíz - Ultimate Edition</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Rajdhani:wght@400;600;700&display=swap');

        :root {
            --bg-deep: #050810;
            --panel-bg: rgba(16, 24, 43, 0.85);
            --neon-blue: #00f3ff;
            --neon-purple: #bc13fe;
            --neon-red: #ff2a2a;
            --neon-green: #00ff66;
            --text-main: #e2e8f0;
            --text-dim: #94a3b8;
        }

        body {
            font-family: 'Rajdhani', sans-serif;
            background: radial-gradient(circle at 50% 50%, #110c22 0%, var(--bg-deep) 100%);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
            background-image: 
                radial-gradient(circle at 15% 50%, rgba(0, 243, 255, 0.05) 0%, transparent 50%),
                radial-gradient(circle at 85% 30%, rgba(188, 19, 254, 0.05) 0%, transparent 50%);
        }

        .container {
            background: var(--panel-bg);
            border: 1px solid rgba(0, 243, 255, 0.2);
            border-radius: 20px;
            padding: 40px;
            max-width: 700px;
            width: 100%;
            box-shadow: 0 0 40px rgba(0, 243, 255, 0.1), inset 0 0 20px rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(15px);
            position: relative;
            overflow: hidden;
        }

        /* Top decorative line */
        .container::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0; height: 3px;
            background: linear-gradient(90deg, transparent, var(--neon-blue), transparent);
        }

        h1 {
            font-family: 'Orbitron', sans-serif;
            color: var(--neon-blue);
            font-size: 2.2rem;
            margin-top: 0;
            text-align: center;
            text-shadow: 0 0 15px rgba(0, 243, 255, 0.4);
            letter-spacing: 2px;
        }

        p {
            font-size: 1.2rem;
            color: var(--text-dim);
            text-align: center;
            line-height: 1.5;
            margin-bottom: 30px;
        }

        .mode-selector {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 20px;
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
            margin-bottom: 30px;
            text-align: center;
        }

        .stat-card {
            background: rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 15px 10px;
            border-radius: 12px;
            transition: all 0.3s;
        }

        .stat-label {
            font-size: 0.9rem;
            color: var(--text-dim);
            text-transform: uppercase;
            letter-spacing: 1.5px;
            margin-bottom: 5px;
        }

        .stat-value {
            font-size: 1.6rem;
            font-weight: bold;
            font-family: 'Orbitron', sans-serif;
            color: var(--text-main);
        }

        .timer-active { color: var(--neon-red) !important; text-shadow: 0 0 10px rgba(255, 42, 42, 0.5); }

        .question-box {
            font-size: 1.4rem;
            font-weight: 600;
            margin-bottom: 30px;
            line-height: 1.5;
            background: rgba(0, 243, 255, 0.03);
            padding: 20px;
            border-radius: 12px;
            border-left: 5px solid var(--neon-blue);
        }

        .options-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
            margin-bottom: 30px;
        }

        button {
            font-family: 'Rajdhani', sans-serif;
            outline: none;
        }

        button.option-btn {
            background: rgba(255, 255, 255, 0.03);
            color: var(--text-main);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 18px 25px;
            border-radius: 12px;
            cursor: pointer;
            text-align: left;
            font-size: 1.2rem;
            font-weight: 600;
            transition: all 0.2s ease;
            position: relative;
            overflow: hidden;
        }

        button.option-btn:hover {
            background: rgba(0, 243, 255, 0.1);
            border-color: var(--neon-blue);
            transform: translateX(5px);
            box-shadow: 0 0 15px rgba(0, 243, 255, 0.2);
        }

        .controls {
            display: flex;
            gap: 15px;
            justify-content: space-between;
        }

        button.btn-primary, button.btn-secondary, button.btn-danger {
            padding: 15px 30px;
            border-radius: 12px;
            font-size: 1.2rem;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            flex: 1;
        }

        button.btn-primary {
            background: transparent;
            color: var(--neon-blue);
            border: 2px solid var(--neon-blue);
            box-shadow: inset 0 0 10px rgba(0, 243, 255, 0.2);
        }
        button.btn-primary:hover {
            background: var(--neon-blue);
            color: #000;
            box-shadow: 0 0 20px rgba(0, 243, 255, 0.6);
        }

        button.btn-secondary {
            background: transparent;
            color: var(--neon-purple);
            border: 2px solid var(--neon-purple);
        }
        button.btn-secondary:hover {
            background: var(--neon-purple);
            color: #fff;
            box-shadow: 0 0 20px rgba(188, 19, 254, 0.6);
        }

        button.btn-danger {
            background: transparent;
            color: var(--neon-red);
            border: 2px solid var(--neon-red);
        }
        button.btn-danger:hover {
            background: var(--neon-red);
            color: #fff;
            box-shadow: 0 0 20px rgba(255, 42, 42, 0.6);
        }

        #hint-btn {
            background: transparent;
            color: var(--text-dim);
            border: 1px solid rgba(255, 255, 255, 0.2);
            flex: 1;
        }
        #hint-btn:hover { border-color: var(--text-main); color: var(--text-main); }

        .hint-text {
            display: none;
            background: rgba(188, 19, 254, 0.1);
            border: 1px solid rgba(188, 19, 254, 0.3);
            color: #e9a8ff;
            padding: 18px;
            border-radius: 12px;
            margin-bottom: 25px;
            font-style: italic;
            font-size: 1.1rem;
        }

        .screen { display: none; animation: fadeIn 0.4s ease-out; }
        .screen.active { display: block; }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .result-score {
            font-size: 4rem;
            text-align: center;
            color: var(--neon-green);
            font-weight: bold;
            font-family: 'Orbitron', sans-serif;
            margin: 30px 0;
            text-shadow: 0 0 30px rgba(0, 255, 102, 0.4);
        }

        .accuracy-display {
            font-size: 1.5rem;
            text-align: center;
            margin-bottom: 30px;
            color: var(--text-main);
        }
    </style>
</head>
<body>

<div class="container">
    <div id="start-screen" class="screen active">
        <h1>Vesmírný Terminál</h1>
        <p>Tento systém obsahuje generátor, který umí vytvořit stovky tisíc unikátních astrofyzikálních a matematických otázek. Vyber si režim simulace:</p>
        <div class="mode-selector">
            <button class="btn-primary" onclick="startQuiz('timed')">Hra na čas<br><small>(2 minuty limit)</small></button>
            <button class="btn-secondary" onclick="startQuiz('endless')">Trénink<br><small>(Nekonečno, bez stresu)</small></button>
        </div>
    </div>

    <div id="quiz-screen" class="screen">
        <div class="stats">
            <div class="stat-card" id="timer-card">
                <div class="stat-label">Čas</div>
                <div class="stat-value timer-active"><span id="timer">--</span></div>
            </div>
            <div class="stat-card">
                <div class="stat-label">Otázka</div>
                <div class="stat-value">#<span id="question-count">0</span></div>
            </div>
            <div class="stat-card">
                <div class="stat-label">Správně</div>
                <div class="stat-value" style="color: var(--neon-green)" id="score">0</div>
            </div>
            <div class="stat-card">
                <div class="stat-label">Chyby</div>
                <div class="stat-value" style="color: var(--neon-red)" id="mistakes">0</div>
            </div>
        </div>
        
        <div class="question-box" id="question-text">Načítání...</div>
        <div class="hint-text" id="hint-box"></div>
        <div class="options-grid" id="options-container"></div>
        
        <div class="controls">
            <button class="btn-primary" id="hint-btn" style="flex: 0.5" onclick="toggleHint()">Nápověda</button>
            <button class="btn-danger" style="flex: 0.5" onclick="endQuiz()">Ukončit kvíz</button>
        </div>
    </div>

    <div id="result-screen" class="screen">
        <h1>Simulace Ukončena</h1>
        <p id="end-reason">Tady je tvé celkové vyhodnocení.</p>
        
        <div class="result-score" id="final-score">0</div>
        <div class="accuracy-display" id="accuracy-text">Úspěšnost: 0 %</div>
        
        <p id="evaluation-text" style="font-size: 1.3rem; font-weight: bold; color: var(--neon-blue);"></p>
        
        <div class="controls" style="margin-top: 30px;">
            <button class="btn-primary" onclick="resetToMenu()">Zpět do menu</button>
        </div>
    </div>
</div>

<script>
    let currentMode = 'timed';
    let score = 0;
    let mistakes = 0;
    let questionCount = 0;
    let timeLeft = 120;
    let timerInterval;
    let currentCorrectAnswer = "";
    let currentHint = "";

    // Pokročilá banka šablon pro nekonečné množství otázek
    const questionTemplates = [
        // 1. Gravitační parametr
        { generate: () => {
            const r = Math.floor(Math.random() * 8) + 2; 
            const v = Math.floor(Math.random() * 20) + 10;
            const ans = (v * v * r).toFixed(1);
            return {
                text: `Sonda obíhá planetu po kruhové dráze o poloměru R = ${r} × 10⁶ m rychlostí v = ${v} km/s. Jaký je gravitační parametr (GM) planety?`,
                correct: `${ans} × 10¹² m³/s²`,
                fake: [`${(ans * 1.5).toFixed(1)} × 10¹² m³/s²`, `${(ans / 2).toFixed(1)} × 10¹² m³/s²`, `${(v * r).toFixed(1)} × 10¹² m³/s²`],
                hint: "Pro kruhovou dráhu platí v = √(GM / R). Upravením získáme GM = v² × R."
            };
        }},
        // 2. Schwarzschildův poloměr
        { generate: () => {
            const m = Math.floor(Math.random() * 15) + 3;
            const ans = (m * 2.95).toFixed(1);
            return {
                text: `Vypočítejte přibližný Schwarzschildův poloměr pro černou díru o hmotnosti M = ${m} hmotností Slunce.`,
                correct: `${ans} km`,
                fake: [`${(m * 1.5).toFixed(1)} km`, `${(m * 9.8).toFixed(1)} km`, `${(m * 5.5).toFixed(1)} km`],
                hint: "Poloměr roste lineárně s hmotností. Černá díra o hmotnosti 1 Slunce má poloměr cca 2,95 km."
            };
        }},
        // 3. Keplerův třetí zákon
        { generate: () => {
            const d = [4, 9, 16, 25][Math.floor(Math.random() * 4)];
            const ans = Math.sqrt(d * d * d);
            return {
                text: `Exoplaneta obíhá svou hvězdu (stejnou jako Slunce) ve vzdálenosti a = ${d} AU. Jak dlouhý je její oběžný rok?`,
                correct: `${ans} pozemských let`,
                fake: [`${d * 2} pozemských let`, `${d * d} pozemských let`, `${Math.floor(ans * 1.5)} pozemských let`],
                hint: "3. Keplerův zákon v naší sluneční soustavě: T² = a³. Oběžná doba T je tedy druhá odmocnina ze třetí mocniny vzdálenosti."
            };
        }},
        // 4. E=mc^2 (Ekvivalence hmotnosti a energie)
        { generate: () => {
            const m = Math.floor(Math.random() * 9) + 2;
            const ans = m * 9;
            return {
                text: `Kolik energie (E) by se uvolnilo při úplné anihilaci hmoty o hmotnosti m = ${m} kg? (Předpokládejte c = 3 × 10⁸ m/s).`,
                correct: `${ans} × 10¹⁶ J`,
                fake: [`${m * 3} × 10⁸ J`, `${ans * 2} × 10¹⁶ J`, `${m * 6} × 10¹⁶ J`],
                hint: "Použijte slavný vzorec E = m × c². Rychlost světla na druhou je (3 × 10⁸)² = 9 × 10¹⁶."
            };
        }},
        // 5. Hubbleův zákon
        { generate: () => {
            const dist = (Math.floor(Math.random() * 50) + 10) * 10;
            const h0 = 70;
            const ans = dist * h0;
            return {
                text: `Vzdálená galaxie se od nás nachází ve vzdálenosti D = ${dist} Mpc. Jakou rychlostí se od nás vzdaluje? (Předpokládejte Hubbleovu konstantu H₀ = 70 km/s/Mpc).`,
                correct: `${ans} km/s`,
                fake: [`${dist * 10} km/s`, `${Math.floor(ans / 2)} km/s`, `${ans + 1500} km/s`],
                hint: "Hubbleův zákon zní: v = H₀ × D. Stačí jednoduše vynásobit vzdálenost a konstantu."
            };
        }},
        // 6. Stefan-Boltzmann (Teplota a zářivost)
        { generate: () => {
            const t = (Math.floor(Math.random() * 5) + 3) * 1000;
            const factor = [16, 81][Math.floor(Math.random() * 2)];
            const root = Math.pow(factor, 0.25);
            return {
                text: `Povrchová teplota hvězdy je T = ${t} K. Pokud by její celkový zářivý výkon stoupl ${factor}krát (při stejném poloměru), jaká by byla její nová teplota?`,
                correct: `${t * root} K`,
                fake: [`${t * factor} K`, `${t * (root + 1)} K`, `${t * 2} K`],
                hint: "Zářivý výkon hvězdy roste se čtvrtou mocninou teploty (T⁴). Udělejte tedy 4. odmocninu z nárůstu výkonu."
            };
        }},
        // 7. Úniková rychlost
        { generate: () => {
            const v = Math.floor(Math.random() * 10) + 5;
            const ans = (v * 1.414).toFixed(1);
            return {
                text: `Kruhová rychlost na nízké oběžné dráze kolem měsíce je v = ${v} km/s. Jaká je přibližná úniková rychlost z tohoto měsíce?`,
                correct: `${ans} km/s`,
                fake: [`${v * 2} km/s`, `${(v * 2.5).toFixed(1)} km/s`, `${(v * 1.732).toFixed(1)} km/s`],
                hint: "Úniková rychlost je vždy větší než kruhová rychlost o násobek √2 (což je přibližně 1,414)."
            };
        }},
        // 8. Zákon převrácených čtverců (Záření)
        { generate: () => {
            const d = Math.floor(Math.random() * 5) + 3;
            return {
                text: `Pokud se vesmírná loď vzdálí od hvězdy do vzdálenosti, která je ${d}krát větší než její původní pozice, jak moc klesne intenzita přijímaného světla?`,
                correct: `${d * d}krát`,
                fake: [`${d}krát`, `${d * 2}krát`, `${d * d * d}krát`],
                hint: "Intenzita světla i gravitace klesá s druhou mocninou vzdálenosti od zdroje."
            };
        }}
    ];

    function startQuiz(mode) {
        currentMode = mode;
        score = 0;
        mistakes = 0;
        questionCount = 0;
        
        document.getElementById('score').innerText = score;
        document.getElementById('mistakes').innerText = mistakes;
        document.getElementById('start-screen').classList.remove('active');
        document.getElementById('result-screen').classList.remove('active');
        document.getElementById('quiz-screen').classList.add('active');
        
        if (mode === 'timed') {
            timeLeft = 120;
            document.getElementById('timer-card').style.display = 'block';
            document.getElementById('timer').innerText = timeLeft + 's';
            timerInterval = setInterval(() => {
                timeLeft--;
                document.getElementById('timer').innerText = timeLeft + 's';
                if (timeLeft <= 0) endQuiz("Čas vypršel!");
            }, 1000);
        } else {
            document.getElementById('timer-card').style.display = 'none';
        }

        nextQuestion();
    }

    function nextQuestion() {
        questionCount++;
        document.getElementById('question-count').innerText = questionCount;
        
        const hintBox = document.getElementById('hint-box');
        hintBox.style.display = 'none';

        const randomTemplate = questionTemplates[Math.floor(Math.random() * questionTemplates.length)];
        const qData = randomTemplate.generate();

        currentCorrectAnswer = qData.correct;
        currentHint = qData.hint;

        document.getElementById('question-text').innerText = qData.text;
        hintBox.innerText = currentHint;

        let options = [qData.correct, ...qData.fake];
        options.sort(() => Math.random() - 0.5);

        const container = document.getElementById('options-container');
        container.innerHTML = "";

        const labels = ['A', 'B', 'C', 'D'];
        options.forEach((opt, idx) => {
            const btn = document.createElement('button');
            btn.className = 'option-btn';
            btn.innerText = `${labels[idx]}) ${opt}`;
            btn.onclick = () => checkAnswer(opt);
            container.appendChild(btn);
        });
    }

    function checkAnswer(selected) {
        if (selected === currentCorrectAnswer) {
            score++;
            document.getElementById('score').innerText = score;
        } else {
            mistakes++;
            document.getElementById('mistakes').innerText = mistakes;
        }
        nextQuestion();
    }

    function toggleHint() {
        const hintBox = document.getElementById('hint-box');
        hintBox.style.display = (hintBox.style.display === 'none' || hintBox.style.display === '') ? 'block' : 'none';
    }

    function endQuiz(reason = "Kvíz byl ručně ukončen.") {
        if (currentMode === 'timed') clearInterval(timerInterval);
        
        document.getElementById('quiz-screen').classList.remove('active');
        document.getElementById('result-screen').classList.add('active');
        
        document.getElementById('end-reason').innerText = reason;
        document.getElementById('final-score').innerText = `${score} bodů`;
        
        const totalAnswers = score + mistakes;
        const accuracy = totalAnswers > 0 ? Math.round((score / totalAnswers) * 100) : 0;
        document.getElementById('accuracy-text').innerText = `Úspěšnost: ${accuracy} % (Zodpovězeno: ${totalAnswers})`;

        let evalText = "";
        if (totalAnswers === 0) evalText = "Nezkusil jsi ani jednu otázku!";
        else if (accuracy >= 85 && score >= 10) evalText = "Naprostá elita! Tvoje fyzikální intuice je fenomenální.";
        else if (accuracy >= 60) evalText = "Velmi solidní práce. Jsi na dobré cestě stát se expertem.";
        else evalText = "Zajímavý pokus! Vesmír je složitý, chce to jen více tréninku.";
        
        document.getElementById('evaluation-text').innerText = evalText;
    }

    function resetToMenu() {
        if (timerInterval) clearInterval(timerInterval);
        document.getElementById('result-screen').classList.remove('active');
        document.getElementById('start-screen').classList.add('active');
    }
</script>

</body>
</html>
