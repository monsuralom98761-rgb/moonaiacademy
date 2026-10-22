
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
/*
  Moon AI Academy video library.
  Before use: fill in firebaseConfig below, enable Email/Password Auth,
  create Firestore + Storage, and deploy the security rules in README.md.
*/
import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.0/firebase-app.js";
import {
  getAuth, onAuthStateChanged, signInWithEmailAndPassword, signOut
} from "https://www.gstatic.com/firebasejs/11.6.0/firebase-auth.js";
import {
  getFirestore, collection, addDoc, getDocs, query, orderBy, serverTimestamp, deleteDoc, doc
} from "https://www.gstatic.com/firebasejs/11.6.0/firebase-firestore.js";
import {
  getStorage, ref, uploadBytesResumable, getDownloadURL, deleteObject
} from "https://www.gstatic.com/firebasejs/11.6.0/firebase-storage.js";

// Firebase Console > Project settings > Your apps > SDK setup and configuration
const firebaseConfig = {
  apiKey: "PASTE_YOUR_FIREBASE_API_KEY",
  authDomain: "PASTE_YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "PASTE_YOUR_PROJECT_ID",
  storageBucket: "PASTE_YOUR_STORAGE_BUCKET",
  messagingSenderId: "PASTE_YOUR_MESSAGING_SENDER_ID",
  appId: "PASTE_YOUR_FIREBASE_APP_ID"
};

const $ = (id) => document.getElementById(id);
const videoGrid = $("videoGrid");
const pageMessage = $("pageMessage");
let auth, db, storage, currentUser = null, approved = false;
let firebaseReady = false;

function showPageMessage(message) { pageMessage.textContent = message; }
function setUploadStatus(message) { $("uploadStatus").textContent = message; }
function escapeText(value="") {
  return String(value).replace(/[&<>"']/g, c => ({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
}
function configIsSet() {
  return firebaseConfig.apiKey.startsWith("AIza") &&
    !firebaseConfig.projectId.startsWith("PASTE_") &&
    !firebaseConfig.appId.startsWith("PASTE_");
}
function showSetupNotice() {
  videoGrid.innerHTML = '<div class="empty-state">Firebase setup is not finished yet.<br>Follow the setup steps in <b>README.md</b>, then refresh this page.</div>';
  $("videoCount").textContent = "Setup required";
  $("signInButton").disabled = true;
  $("signInButton").title = "Add your Firebase config in app.js first";
}
function makeVideoCard(video) {
  const card = document.createElement("article");
  card.className = "video-card";
  const player = document.createElement("video");
  player.controls = true;
  player.preload = "metadata";
  player.playsInline = true;
  player.src = video.url;
  player.setAttribute("aria-label", video.title || "Video lesson");
  const info = document.createElement("div");
  info.className = "video-info";
  const title = document.createElement("h3");
  title.textContent = video.title || "Untitled video";
  const desc = document.createElement("p");
  desc.textContent = video.description || "No description added.";
  const meta = document.createElement("div");
  meta.className = "video-meta";
  meta.textContent = "MOON AI ACADEMY";
  info.append(title, desc, meta);
  if (approved && currentUser && video.ownerUid === currentUser.uid) {
    const del = document.createElement("button");
    del.className = "btn btn-outline";
    del.type = "button";
    del.textContent = "Delete video";
    del.style.marginTop = "14px";
    del.addEventListener("click", () => removeVideo(video, card, del));
    info.appendChild(del);
  }
  card.append(player, info);
  return card;
}
async function loadVideos() {
  videoGrid.replaceChildren();
  const loading = document.createElement("div");
  loading.className = "empty-state";
  loading.textContent = "Loading video library…";
  videoGrid.appendChild(loading);
  try {
    const snapshot = await getDocs(query(collection(db, "videos"), orderBy("createdAt", "desc")));
    videoGrid.replaceChildren();
    let count = 0;
    snapshot.forEach(item => {
      const v = item.data();
      if (typeof v.url !== "string" || !v.url.startsWith("https://")) return;
      videoGrid.appendChild(makeVideoCard({ id: item.id, ...v }));
      count++;
    });
    $("videoCount").textContent = `${count} video${count === 1 ? "" : "s"}`;
    if (!count) {
      const empty = document.createElement("div");
      empty.className = "empty-state";
      empty.textContent = "No videos yet. Approved creators can sign in and upload the first lesson.";
      videoGrid.appendChild(empty);
    }
  } catch (error) {
    console.error(error);
    videoGrid.innerHTML = '<div class="empty-state">Could not load videos. Check Firestore rules and setup in README.md.</div>';
  }
}
async function checkPermission(user) {
  if (!user) return false;
  try {
    // The trusted permission is stored in a Firestore document whose ID is the user's UID.
    const { getDoc } = await import("https://www.gstatic.com/firebasejs/11.6.0/firebase-firestore.js");
    const snap = await getDoc(doc(db, "uploaders", user.uid));
    return snap.exists() && snap.data().canUpload === true;
  } catch (e) {
    console.error("Could not check upload permission", e);
    return false;
  }
}
function refreshCreatorUI() {
  $("signInButton").hidden = !!currentUser;
  $("signOutButton").hidden = !currentUser;
  $("uploadNav").hidden = !approved;
  $("upload").hidden = !approved;
  if (approved) showPageMessage("Signed in: video upload is enabled for this approved account.");
  else if (currentUser) showPageMessage("This account is signed in but is not approved to upload videos.");
  else showPageMessage("");
}
async function removeVideo(video, card, button) {
  if (!approved || !currentUser || video.ownerUid !== currentUser.uid) return;
  if (!confirm(`Delete "${video.title}"? This cannot be undone.`)) return;
  button.disabled = true;
  try {
    await deleteDoc(doc(db, "videos", video.id));
    if (video.storagePath) await deleteObject(ref(storage, video.storagePath));
    card.remove();
    showPageMessage("Video deleted.");
    await loadVideos();
  } catch (e) {
    console.error(e);
    showPageMessage("Could not delete video. Check permissions and try again.");
    button.disabled = false;
  }
}

$("signInButton").addEventListener("click", () => {
  $("authError").textContent = "";
  $("authDialog").showModal();
});
$("closeDialog").addEventListener("click", () => $("authDialog").close());
$("authForm").addEventListener("submit", async (event) => {
  event.preventDefault();
  $("authError").textContent = "";
  try {
    await signInWithEmailAndPassword(auth, $("email").value.trim(), $("password").value);
    $("authDialog").close();
    $("authForm").reset();
  } catch (error) {
    console.error(error);
    $("authError").textContent = "Sign-in failed. Check your email/password and try again.";
  }
});
$("signOutButton").addEventListener("click", async () => {
  try { await signOut(auth); }
  catch (e) { console.error(e); showPageMessage("Could not sign out. Please try again."); }
});
$("uploadForm").addEventListener("submit", async (event) => {
  event.preventDefault();
  if (!firebaseReady || !currentUser || !approved) {
    setUploadStatus("Only approved creator accounts can upload.");
    return;
  }
  const file = $("videoFile").files[0];
  const title = $("videoTitle").value.trim();
  const description = $("videoDescription").value.trim();
  if (!file || !title) { setUploadStatus("Enter a title and choose a video."); return; }
  const allowedTypes = ["video/mp4","video/webm","video/ogg","video/quicktime"];
  if (!allowedTypes.includes(file.type)) { setUploadStatus("Choose an MP4, WebM, OGG, or MOV video."); return; }
  const maxBytes = 500 * 1024 * 1024;
  if (file.size > maxBytes) { setUploadStatus("This demo allows videos up to 500 MB. Increase limits only after reviewing storage and cost."); return; }
  $("uploadButton").disabled = true;
  $("progressBar").style.width = "0%";
  setUploadStatus("Starting upload…");
  const safeName = file.name.replace(/[^a-zA-Z0-9._-]/g, "_").slice(-100);
  const storagePath = `videos/${currentUser.uid}/${Date.now()}-${safeName}`;
  const storageRef = ref(storage, storagePath);
  const task = uploadBytesResumable(storageRef, file, { contentType: file.type });
  task.on("state_changed",
    snapshot => {
      const percent = Math.round((snapshot.bytesTransferred / snapshot.totalBytes) * 100);
      $("progressBar").style.width = `${percent}%`;
      setUploadStatus(`Uploading… ${percent}%`);
    },
    error => {
      console.error(error);
      setUploadStatus("Upload failed. Check your Storage rules, billing/quota, and internet connection.");
      $("uploadButton").disabled = false;
    },
    async () => {
      try {
        const url = await getDownloadURL(task.snapshot.ref);
        await addDoc(collection(db, "videos"), {
          title, description, url, storagePath, ownerUid: currentUser.uid,
          createdAt: serverTimestamp(), fileSize: file.size, contentType: file.type
        });
        $("uploadForm").reset();
        $("progressBar").style.width = "100%";
        setUploadStatus("Upload complete! Your video is now in the library.");
        await loadVideos();
      } catch (error) {
        console.error(error);
        setUploadStatus("The file uploaded but saving its details failed. Ask the site owner to check Firestore rules.");
      } finally {
        $("uploadButton").disabled = false;
      }
    }
  );
});

if (!configIsSet()) {
  showSetupNotice();
} else {
  try {
    const app = initializeApp(firebaseConfig);
    auth = getAuth(app);
    db = getFirestore(app);
    storage = getStorage(app);
    firebaseReady = true;
    onAuthStateChanged(auth, async user => {
      currentUser = user;
      approved = await checkPermission(user);
      refreshCreatorUI();
      await loadVideos();
    });
  } catch (error) {
    console.error(error);
    showSetupNotice();
  }
}
