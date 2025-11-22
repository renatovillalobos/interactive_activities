<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sound Speed Explorer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        h1 {
            font-size: 24px;
        }
        .instruction {
            font-size: 14px;
            margin-bottom: 10px;
        }
        .goal {
            background-color: #ffe0a0;
            padding: 5px 10px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .interactive-zone {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
            position: relative;
        }
        .container {
            width: 100px;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 10px;
            box-shadow: 0 0 5px #ccc;
            margin: 0 10px;
            cursor: pointer;
        }
        .air { background-color: #fdefc7; }
        .water { background-color: #c7eafc; }
        .solid { background-color: #facd63; }
        .play-button {
            background-color: #facd63;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
        }
        .play-button:hover {
            background-color: #e6b650;
        }
        .response {
            background-color: #c7f7ca;
            padding: 5px 10px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sound Speed Explorer</h1>
        <div class="instruction">Drag the objects and see how the waves change.</div>
        <div class="goal">Explore Sound Speed</div>
    </header>
    
    <div class="interactive-zone">
        <div class="container air" id="air">
            <img src="tuning-fork.png" alt="Tuning Fork" id="tuning-fork">
        </div>
        <div class="container water" id="water"></div>
        <div class="container solid" id="solid"></div>
    </div>
    
    <div class="play-button" id="play-button">
        <img src="play-icon.png" alt="Play">
    </div>
    
    <div class="response" id="response">Good!</div>

    <script>
        const airContainer = document.getElementById('air');
        const waterContainer = document.getElementById('water');
        const solidContainer = document.getElementById('solid');
        const playButton = document.getElementById('play-button');
        const response = document.getElementById('response');
        const tuningFork = document.getElementById('tuning-fork');

        let currentContainer = null;
        let soundAnimating = false;

        function animateSound(container) {
            if (soundAnimating) return;
            soundAnimating = true;
            const wave = document.createElement('div');
            wave.style.position = 'absolute';
            wave.style.width = '10px';
            wave.style.height = '10px';
            wave.style.borderRadius = '50%';
            wave.style.backgroundColor = '#555';
            container.appendChild(wave);
            let w = 10;

            function expand() {
                if (w > 80) {
                    container.removeChild(wave);
                    soundAnimating = false;
                    return;
                }
                w += 2;
                wave.style.width = `${w}px`;
                wave.style.height = `${w}px`;
                wave.style.left = `${50 - w / 2}px`;
                wave.style.top = `${50 - w / 2}px`;
                requestAnimationFrame(expand);
            }

            expand();
        }

        airContainer.addEventListener('click', () => {
            currentContainer = airContainer;
            animateSound(airContainer);
            response.textContent = "Air: Slower sound waves";
        });

        waterContainer.addEventListener('click', () => {
            currentContainer = waterContainer;
            animateSound(waterContainer);
            response.textContent = "Water: Moderate sound waves";
        });

        solidContainer.addEventListener('click', () => {
            currentContainer = solidContainer;
            animateSound(solidContainer);
            response.textContent = "Solid: Fast sound waves";
        });

        tuningFork.addEventListener('dragstart', (event) => {
            event.dataTransfer.setData('text/plain', null);
        });

        playButton.addEventListener('click', () => {
            if (currentContainer) {
                animateSound(currentContainer);
            }
        });
    </script>
</body>
</html>