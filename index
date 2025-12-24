<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <title>Nytårs Jeopardy</title>
    <style>
        body { font-family: sans-serif; background-color: #000839; color: white; text-align: center; }
        .grid { display: grid; grid-template-columns: repeat(5, 1fr); gap: 10px; padding: 20px; }
        .header { font-weight: bold; background-color: #0012c2; padding: 20px; border: 2px solid white; }
        .cell { background-color: #060ce9; border: 2px solid white; padding: 40px 10px; font-size: 24px; cursor: pointer; }
        .cell:hover { background-color: #3339ff; }
        .cell.used { color: #0012c2; cursor: default; }
    </style>
</head>
<body>
    <h1>GODT NYTÅR JEOPARDY 2025</h1>
    <div class="grid">
        <div class="header">2024 Minder</div>
        <div class="header">Nytårstraditioner</div>
        <div class="header">Musik & Film</div>
        <div class="header">Gæt en gæst</div>
        <div class="header">Blandet</div>

        <div class="cell" onclick="showQ('Hvem vandt EM i herrefodbold?', this)">100</div>
        <div class="cell" onclick="showQ('Hvad spiser man typisk kl. 24?', this)">100</div>
        <div class="cell" onclick="showQ('Hvilken film vandt en Oscar i år?', this)">100</div>
        <div class="cell" onclick="showQ('Hvem har fødselsdag i dag?', this)">100</div>
        <div class="cell" onclick="showQ('Hvor mange dage er der i et skudår?', this)">100</div>
    </div>

    <script>
        function showQ(question, element) {
            if (!element.classList.contains('used')) {
                alert(question);
                element.classList.add('used');
                element.innerText = ""; // Fjerner pointene efter spørgsmålet er stillet
            }
        }
    </script>
</body>
</html>
