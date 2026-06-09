<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Quiz Interativo de Imunologia</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background: #f0f2f5; padding: 20px; line-height: 1.6; }
        .container { max-width: 700px; margin: auto; background: white; padding: 25px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .question { margin-bottom: 20px; border-bottom: 1px solid #eee; padding-bottom: 15px; }
        .options { list-style: none; padding: 0; }
        .options li { margin: 8px 0; padding: 10px; border: 1px solid #ddd; border-radius: 5px; cursor: pointer; transition: 0.3s; }
        .options li:hover { background: #e7f3ff; }
        button { display: block; width: 100%; padding: 15px; background: #28a745; color: white; border: none; border-radius: 5px; font-size: 1.1em; cursor: pointer; }
        #result { margin-top: 20px; text-align: center; font-size: 1.3em; font-weight: bold; }
    </style>
</head>
<body>

<div class="container">
    <h1>Quiz de Imunologia (40 Questões)</h1>
    <div id="quiz-container"></div>
    <button onclick="calculateScore()">Verificar Respostas</button>
    <div id="result"></div>
</div>

<script>
    // O JSON das 40 questões (Preencha as opções conforme o material)
    const quizData = {
        "questions": [
            { "id": 1, "question": "O que caracteriza a imunização ativa?", "options": ["Indução de resposta imune adaptativa", "Transferência de anticorpos prontos"], "correct": 0 },
            { "id": 2, "question": "Qual a função das células M no GALT?", "options": ["Amostragem de antígenos", "Produção de muco"], "correct": 0 }
            // Adicione as outras 38 questões aqui seguindo o mesmo formato
        ]
    };

    const container = document.getElementById('quiz-container');

    quizData.questions.forEach((item, index) => {
        let optionsHtml = item.options.map((opt, i) => 
            `<li><input type="radio" name="q${index}" value="${i}"> ${opt}</li>`
        ).join('');
        
        container.innerHTML += `<div class="question">
            <p><strong>${item.id}. ${item.question}</strong></p>
            <ul class="options">${optionsHtml}</ul>
        </div>`;
    });

    function calculateScore() {
        let score = 0;
        quizData.questions.forEach((item, index) => {
            const selected = document.querySelector(`input[name="q${index}"]:checked`);
            if (selected && parseInt(selected.value) === item.correct) score++;
        });
        document.getElementById('result').innerHTML = `Pontuação Final: ${score} / ${quizData.questions.length}`;
    }
</script>
</body>
</html>
