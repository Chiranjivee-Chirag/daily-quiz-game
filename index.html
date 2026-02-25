<!DOCTYPE html>
<html>
<head>
  <title>Daily Quiz Challenge</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #f4f6f9;
      padding: 20px;
    }
    .quiz-box {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
      max-width: 400px;
      margin: auto;
    }
    button {
      padding: 10px 15px;
      margin: 5px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      background: #007bff;
      color: white;
    }
    button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>

<div class="quiz-box">
  <h2>Daily Quiz Challenge</h2>

  <div id="start-screen">
    <p>Test your knowledge with our daily quiz!</p>
    <button onclick="startQuiz()">Start Quiz</button>
  </div>

  <div id="quiz-screen" style="display:none;">
    <p id="question"></p>
    <div id="options"></div>
    <p id="result"></p>
    <p id="score"></p>
  </div>

</div>

<script>
  const quiz = [
    {
      question: "What is 2 + 2?",
      options: ["3", "4", "5"],
      answer: "4"
    },
    {
      question: "Capital of India?",
      options: ["Delhi", "Mumbai", "Kolkata"],
      answer: "Delhi"
    },
    {
      question: "HTML stands for?",
      options: ["Hyper Text Markup Language", "High Text Machine Language", "Home Tool Markup Language"],
      answer: "Hyper Text Markup Language"
    }
  ];

  let currentQuestion = 0;
  let score = 0;

  function startQuiz() {
    document.getElementById("start-screen").style.display = "none";
    document.getElementById("quiz-screen").style.display = "block";
    loadQuestion();
  }

  function loadQuestion() {
    const q = quiz[currentQuestion];
    document.getElementById("question").innerText = q.question;

    const optionsDiv = document.getElementById("options");
    optionsDiv.innerHTML = "";

    q.options.forEach(option => {
      const button = document.createElement("button");
      button.innerText = option;
      button.onclick = () => checkAnswer(option);
      optionsDiv.appendChild(button);
    });
  }

  function checkAnswer(selected) {
    if (selected === quiz[currentQuestion].answer) {
      score++;
      document.getElementById("result").innerText = "Correct!";
    } else {
      document.getElementById("result").innerText = "Wrong!";
    }

    currentQuestion++;

    if (currentQuestion < quiz.length) {
      setTimeout(() => {
        document.getElementById("result").innerText = "";
        loadQuestion();
      }, 800);
    } else {
      document.getElementById("question").innerText = "Quiz Finished!";
      document.getElementById("options").innerHTML = "";
      document.getElementById("score").innerText = "Your Score: " + score + "/" + quiz.length;
    }
  }
</script>

</body>
</html>
