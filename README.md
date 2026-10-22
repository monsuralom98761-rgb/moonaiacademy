
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Moon AI Academy | Learn AI A to Z</title>
<style>
*{box-sizing:border-box}
body{margin:0;font-family:Arial,sans-serif;background:#0b1020;color:#eef2ff;line-height:1.7}
header{padding:24px 7%;background:#121a30;border-bottom:1px solid #293552}
.logo{font-size:25px;font-weight:bold;color:#8ba7ff}
nav{margin-top:12px;display:flex;gap:16px;flex-wrap:wrap}
a{color:#a9bdff;text-decoration:none}
.hero{padding:65px 7%;background:linear-gradient(135deg,#172554,#312e81)}
.hero h1{font-size:clamp(32px,6vw,54px);line-height:1.2}
.hero p{max-width:700px}
.btn{display:inline-block;background:#718cff;color:#081126;padding:11px 18px;border-radius:9px;font-weight:bold;border:0;cursor:pointer}
main{max-width:1100px;margin:auto;padding:25px}
section,.lesson{background:#121a30;border:1px solid #293552;padding:22px;margin:20px 0;border-radius:15px}
h2,h3{color:#a9bdff}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px}
.card{background:#19243e;padding:17px;border-radius:12px}
li{margin:7px 0}
input[type=radio]{margin-right:8px}
footer{text-align:center;padding:30px;color:#b6c0d8}
.progress{height:9px;background:#293552;border-radius:9px;overflow:hidden}
#bar{height:100%;width:0;background:#8ba7ff;transition:width .3s}
.small{color:#c4cde2;font-size:14px}
</style>
</head>
<body>
<header>
  <div class="logo">🌙 Moon AI Academy</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#lesson">First Lesson</a>
    <a href="#roadmap">Learning Roadmap</a>
    <a href="#quiz">AI Quiz</a>
  </nav>
</header>

<div class="hero" id="home">
  <p>YOUR AI LEARNING JOURNEY STARTS HERE</p>
  <h1>Learn Artificial Intelligence<br>From A to Z</h1>
  <p>Understand AI in simple language, explore real-world examples,
  practise your skills and build your first AI projects step by step.</p>
  <a class="btn" href="#lesson">Start Learning</a>
</div>

<main>
<section>
  <h2>Welcome to Moon AI Academy</h2>
  <p>This academy is designed for beginners. You do not need advanced
  mathematics or programming knowledge to start learning AI.</p>
  <div class="progress"><div id="bar"></div></div>
  <p class="small" id="progressText">Lesson progress: 0%</p>
  <button class="btn" onclick="markLesson()">Mark Lesson as Completed</button>
</section>

<section id="lesson" class="lesson">
  <h2>Lesson 1: What Is Artificial Intelligence?</h2>
  <h3>1. What is AI?</h3>
  <p>Artificial Intelligence (AI) is a field of computer science that
  develops systems capable of performing tasks that normally require
  human-like abilities, such as understanding language, recognizing
  images, finding patterns and generating content.</p>

  <h3>2. How does AI work?</h3>
  <ol>
    <li><b>Data:</b> A system receives examples, text, images or other data.</li>
    <li><b>Training:</b> A learning algorithm adjusts a model using data.</li>
    <li><b>Model:</b> The trained system learns patterns from its examples.</li>
    <li><b>Input:</b> A person asks a question or provides new information.</li>
    <li><b>Output:</b> The model produces a prediction, answer or result.</li>
    <li><b>Evaluation:</b> Developers test quality, safety and reliability.</li>
  </ol>
  <p>Not every AI system learns in the same way. Some use rules, some
  learn from data, and others combine different techniques.</p>

  <h3>3. Who invented AI?</h3>
  <p>AI was not invented by just one person. It developed through the
  work of many researchers. Alan Turing helped shape early ideas about
  machine intelligence. The term “Artificial Intelligence” was proposed
  for the 1956 Dartmouth research project associated with John McCarthy
  and other researchers.</p>

  <h3>4. Main types of AI technology</h3>
  <ul>
    <li><b>Machine Learning:</b> Systems learn patterns from data.</li>
    <li><b>Deep Learning:</b> Machine learning using multi-layer neural networks.</li>
    <li><b>Generative AI:</b> Systems that can create text, images, audio or code.</li>
    <li><b>Natural Language Processing:</b> Technology for working with human language.</li>
    <li><b>Computer Vision:</b> Technology for interpreting images and video.</li>
    <li><b>Robotics:</b> Systems that connect software intelligence with physical machines.</li>
  </ul>

  <h3>5. Examples of AI in everyday life</h3>
  <ul>
    <li>Voice assistants and chatbots.</li>
    <li>Recommendations for videos, music and products.</li>
    <li>Translation and speech recognition.</li>
    <li>Photo enhancement and image recognition.</li>
    <li>Tools that help people write, code and study.</li>
  </ul>

  <h3>6. Benefits of learning AI</h3>
  <ul>
    <li>Understand modern technology and solve problems.</li>
    <li>Build useful projects and improve digital skills.</li>
    <li>Explore future study and career opportunities.</li>
    <li>Use AI tools to support creativity and learning.</li>
  </ul>
  <p><b>Important:</b> AI can make mistakes and produce biased or outdated
  answers. Check important information and protect personal data.</p>
</section>

<section id="roadmap">
  <h2>AI Learning Roadmap: Beginner to Advanced</h2>
  <div class="grid">
    <div class="card"><h3>Level 1: Foundations</h3>
      <p>Learn what AI is, its history, uses, limitations and responsible use.</p></div>
    <div class="card"><h3>Level 2: Digital Skills</h3>
      <p>Practise file management, spreadsheets, logical thinking and problem solving.</p></div>
    <div class="card"><h3>Level 3: Python</h3>
      <p>Learn variables, conditions, loops, functions, lists and dictionaries.</p></div>
    <div class="card"><h3>Level 4: Mathematics</h3>
      <p>Build foundations in algebra, graphs, probability and basic statistics.</p></div>
    <div class="card"><h3>Level 5: Machine Learning</h3>
      <p>Explore datasets, features, training, testing and model evaluation.</p></div>
    <div class="card"><h3>Level 6: Deep Learning</h3>
      <p>Study neural networks and how modern deep-learning systems work.</p></div>
    <div class="card"><h3>Level 7: Generative AI</h3>
      <p>Learn about language models, image generation, prompting and AI limitations.</p></div>
    <div class="card"><h3>Level 8: Build Projects</h3>
      <p>Create a study helper, FAQ chatbot or simple data-analysis project.</p></div>
  </div>
</section>

<section>
  <h2>Beginner Project Ideas</h2>
  <div class="grid">
    <div class="card"><h3>AI Study Assistant</h3>
      <p>Design a tool that explains school topics and generates practice questions.</p></div>
    <div class="card"><h3>FAQ Chatbot</h3>
      <p>Create a chatbot that answers questions from a small set of approved information.</p></div>
    <div class="card"><h3>Data Explorer</h3>
      <p>Use a sample dataset to create charts and explain patterns.</p></div>
  </div>
</section>

<section id="quiz">
  <h2>Lesson 1 Quiz</h2>
  <p>Test what you have learned.</p>
  <form id="quizForm">
    <p><b>1. What does AI stand for?</b></p>
    <label><input type="radio" name="q1" value="a"> Automated Internet</label><br>
    <label><input type="radio" name="q1" value="b"> Artificial Intelligence</label><br>
    <label><input type="radio" name="q1" value="c"> Advanced Information</label>

    <p><b>2. What is Machine Learning?</b></p>
    <label><input type="radio" name="q2" value="a"> A computer screen</label><br>
    <label><input type="radio" name="q2" value="b"> A type of battery</label><br>
    <label><input type="radio" name="q2" value="c"> A method for learning patterns from data</label>

    <p><b>3. Can AI make mistakes?</b></p>
    <label><input type="radio" name="q3" value="a"> Yes</label><br>
    <label><input type="radio" name="q3" value="b"> No, never</label>

    <p><b>4. Which language is commonly used in AI development?</b></p>
    <label><input type="radio" name="q4" value="a"> HTML only</label><br>
    <label><input type="radio" name="q4" value="b"> Python</label><br>
    <label><input type="radio" name="q4" value="c"> CSS only</label>

    <p><b>5. What should you do with an important AI answer?</b></p>
    <label><input type="radio" name="q5" value="a"> Always believe it without checking</label><br>
    <label><input type="radio" name="q5" value="b"> Share private information</label><br>
    <label><input type="radio" name="q5" value="c"> Verify it using reliable sources</label>
    <p><button class="btn" type="submit">Check My Answers</button></p>
  </form>
  <div id="quizResult" aria-live="polite"></div>
</section>

<section>
  <h2>Continue Your Journey</h2>
  <p>Finish Lesson 1, review your quiz answers and practise explaining
  AI in your own words before moving to Lesson 2: How to Start Using AI Tools.</p>
</section>
</main>

<footer>
  <p>© 2026 Moon AI Academy</p>
  <p>Learn responsibly. Build creatively. Keep exploring.</p>
</footer>

<script>
function markLesson(){
  document.getElementById("bar").style.width="100%";
  document.getElementById("progressText").textContent="Lesson progress: 100% (saved for this page session only)";
}
document.getElementById("quizForm").addEventListener("submit",function(e){
  e.preventDefault();
  const answers={q1:"b",q2:"c",q3:"a",q4:"b",q5:"c"};
  let score=0;
  for(const q in answers){
    const chosen=this.querySelector('input[name="'+q+'"]:checked');
    if(chosen && chosen.value===answers[q])score++;
  }
  document.getElementById("quizResult").innerHTML=
    "<h3>Your Score: "+score+" / 5</h3><p>"+
    (score===5?"Excellent work! You understand the basics of AI.":
    "Good effort! Review Lesson 1 and try again.")+"</p>";
});
</script>
</body>
</html>
