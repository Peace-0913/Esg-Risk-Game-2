<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>ESG Risk Quest</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f4f8;
      padding: 20px;
      text-align: center;
    }
    .container {
      background: #fff;
      border-radius: 10px;
      padding: 20px;
      max-width: 700px;
      margin: auto;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .question {
      font-weight: bold;
    }
    .options button {
      display: block;
      margin: 10px auto;
      padding: 10px;
      border-radius: 5px;
      background: #e0e0e0;
      border: none;
      cursor: pointer;
      width: 80%;
    }
    .score {
      font-size: 1.2em;
      margin-top: 20px;
      color: green;
    }
    .hidden {
      display: none;
    }
    img {
      max-width: 100%;
      margin: 15px 0;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <!-- 免费轻音乐（Pixabay） -->
  <audio autoplay loop>
    <source src="https://cdn.pixabay.com/download/audio/2023/03/10/audio_5e4c2f3a3b.mp3?filename=calm-piano-ambient-141038.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <div class="container">
    <div id="scene"></div>
    <img id="sceneImage" src="" alt="Scene Image" class="hidden">
    <div id="options" class="options"></div>
    <div id="score" class="score hidden"></div>
  </div>

  <script>
    const scenes = [
      {
        text: "You're an ESG Risk Analyst evaluating a loan request from a palm oil company expanding into a forested area. What do you do?",
        image: "https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1350&q=80",
        options: [
          { text: "Approve — they promise to offset via carbon credits.", score: -10 },
          { text: "Reject — potential biodiversity and deforestation risk.", score: 10 },
          { text: "Ask for detailed sustainability plan and delay decision.", score: 5 }
        ]
      },
      {
        text: "You're reviewing a portfolio exposed to a carbon-intensive cement company. Their transition plan is vague. What is your next move?",
        image: "https://images.unsplash.com/photo-1581091215369-8c8b2e7e3f62?auto=format&fit=crop&w=1350&q=80",
        options: [
          { text: "Escalate to credit team for further review.", score: 10 },
          { text: "Do nothing — they're profitable for now.", score: -10 },
          { text: "Send a questionnaire about their decarbonization roadmap.", score: 5 }
        ]
      },
      {
        text: "You hear that a major borrower is accused of greenwashing their ESG disclosures. What's your step?",
        image: "https://images.unsplash.com/photo-1605882300165-c8e7b67a1ba5?auto=format&fit=crop&w=1350&q=80",
        options: [
          { text: "Raise a red flag and recommend enhanced due diligence.", score: 10 },
          { text: "Ignore — it's just a media report.", score: -10 },
          { text: "Engage the client for clarification.", score: 5 }
        ]
      }
    ];

    let currentScene = 0;
    let totalScore = 0;

    function renderScene() {
      const scene = scenes[currentScene];
      document.getElementById('scene').innerText = scene.text;
      const imgElement = document.getElementById('sceneImage');
      imgElement.src = scene.image;
      imgElement.classList.remove('hidden');

      const optionsContainer = document.getElementById('options');
      optionsContainer.innerHTML = '';
      scene.options.forEach(option => {
        const btn = document.createElement('button');
        btn.innerText = option.text;
        btn.onclick = () => {
          totalScore += option.score;
          currentScene++;
          if (currentScene < scenes.length) {
            renderScene();
          } else {
            showScore();
          }
        };
        optionsContainer.appendChild(btn);
      });
    }

    function showScore() {
      document.getElementById('scene').classList.add('hidden');
      document.getElementById('sceneImage').classList.add('hidden');
      document.getElementById('options').classList.add('hidden');
      const scoreText = `Your ESG Score: ${totalScore}\n` +
        (totalScore >= 25 ? "🌱 Excellent ESG judgment! Sustainability Champion." :
        totalScore >= 10 ? "⚠️ Fair awareness, but needs sharpening." :
        "❌ High ESG risk exposure! Rethink your strategy.");
      const scoreDisplay = document.getElementById('score');
      scoreDisplay.innerText = scoreText;
      scoreDisplay.classList.remove('hidden');
    }

    renderScene();
  </script>
</body>
</html>
