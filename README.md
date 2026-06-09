Aqui está uma implementação completa e profissional de um sistema de defesa automática com UI moderna em HTML/CSS/JS:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Auto Parry System - Defesa Automática</title>
    <style>
        /* ===== RESET & BASE ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            user-select: none;
        }

        body {
            min-height: 100vh;
            background: radial-gradient(circle at 20% 30%, #0a0a1a, #030308);
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Segoe UI', 'Poppins', 'Inter', system-ui, -apple-system, sans-serif;
            padding: 2rem;
        }

        /* ===== CANVAS (CENÁRIO DO JOGO) ===== */
        .game-container {
            position: relative;
