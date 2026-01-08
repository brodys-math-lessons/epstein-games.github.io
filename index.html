<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Epsteins Nutsack</title>
<link href="https://fonts.googleapis.com/css2?family=Oxygen:wght@400;700&display=swap" rel="stylesheet">
<style>
  * { margin:0; padding:0; box-sizing:border-box; font-family:'Oxygen', sans-serif; transition: all 0.25s; }

  body.light { background: #f0f0f0; color:#000; }
  body.dark { background: #0d0d0d; color:#fff; }

  header {
    display:flex;
    justify-content: space-between;
    align-items: center;
    padding:10px 20px;
    background:#d3d3d3;
    color:#000;
  }
  body.dark header { background:#000; color:#fff; }

  #logo { width:70px; height:auto; margin-right:15px; }

  nav { display:flex; gap:10px; position:relative; align-items:center; }
  .tab {
    padding:10px 15px;
    cursor:pointer;
    font-weight:700;
    color:#000;
    position: relative;
    z-index:1;
    display:flex;
    align-items:center;
  }
  body.dark .tab { color:#fff; }
  .tab:hover { opacity:0.7; }

  .underline {
    position:absolute;
    height:3px;
    background:#ff3333;
    bottom:0;
    left:0;
    transition: all 0.3s ease;
    border-radius:2px;
    z-index:0;
  }

  #moonIcon { cursor:pointer; font-size:1.5rem; }

  main {
    padding:20px;
    display:flex;
    justify-content:center;
    align-items:flex-start;
    height:calc(100vh - 60px);
    position: relative;
    flex-direction:column;
  }

  #fullscreenBtn {
    padding:8px 12px;
    background:#444;
    color:white;
    border:none;
    border-radius:6px;
    cursor:pointer;
    margin-top:10px;
  }

  #fullscreenBtn:hover { opacity:0.8; }

  #youtubeSection iframe { width:100%; max-width:800px; height:450px; margin-top:20px; border:none; border-radius:5px; }

  #gamesIframe, #soundboardIframe { width:100%; height:100%; border:none; border-radius:5px; }
</style>
</head>
<body class="light">

<header>
  <div style="display:flex; align-items:center; gap:15px;">
    <img id="logo" src="https://i.postimg.cc/tYfvHKd2/GOON-GAMES-removebg-preview.png" alt="Goon Games Logo">
    <nav id="topNav">
      <div class="tab active" onclick="switchTab('youtube', this)">YouTube</div>
      <div class="tab" onclick="switchTab('games', this)">Games</div>
      <div class="tab" onclick="switchTab('soundboard', this)">Soundboard</div>
      <div class="tab" onclick="redirectClassroom(this)">
        <img src="https://i.ibb.co/7Jr9rJfz/classroom-icon.png" alt="Classroom" style="width:24px; height:24px;">
      </div>
      <div class="underline" id="tabUnderline"></div>
    </nav>
  </div>
  <div>
    <div id="moonIcon" onclick="toggleDarkMode()">🌙</div>
  </div>
</header>

<main id="mainContent">
  <div id="youtubeSection">
    <input id="urlInput" placeholder="Paste YouTube URL here">
    <button onclick="loadVideo()">Watch</button>
    <button id="fullscreenBtn" onclick="goFullscreen('videoContainer')">Fullscreen</button>
    <div id="videoContainer"></div>
  </div>
</main>

<script>
function toggleDarkMode() {
  document.body.classList.toggle('dark');
  document.body.classList.toggle('light');
}

function switchTab(tab, element) {
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  element.classList.add('active');

  const underline = document.getElementById('tabUnderline');
  underline.style.width = element.offsetWidth + "px";
  underline.style.left = element.offsetLeft + "px";

  const main = document.getElementById('mainContent');

  if(tab === 'youtube') {
    main.innerHTML = `
      <div id="youtubeSection">
        <input id="urlInput" placeholder="Paste YouTube URL here">
        <button onclick="loadVideo()">Watch</button>
        <button id="fullscreenBtn" onclick="goFullscreen('videoContainer')">Fullscreen</button>
        <div id="videoContainer"></div>
      </div>`;
  } 
  else if(tab === 'games') {
    main.innerHTML = `
      <button id="fullscreenBtn" onclick="goFullscreen('gamesIframe')">Fullscreen</button>
      <iframe id="gamesIframe" src="
https://172.96.141.252doge.quipasur.cl/" allowfullscreen></iframe>`;
  } 
  else if(tab === 'soundboard') {
    main.innerHTML = `
      <button id="fullscreenBtn" onclick="goFullscreen('soundboardIframe')">Fullscreen</button>
      <iframe id="soundboardIframe" src="https://tuna.voicemod.net/" allowfullscreen></iframe>`;
  }
}

window.addEventListener('load', () => {
  const activeTab = document.querySelector('.tab.active');
  const underline = document.getElementById('tabUnderline');
  underline.style.width = activeTab.offsetWidth + "px";
  underline.style.left = activeTab.offsetLeft + "px";
});

function loadVideo() {
  const url = document.getElementById("urlInput").value;
  const videoId = url.match(/(?:youtube\.com.*v=|youtu\.be\/)([^&\n?#]+)/);
  if(!videoId){ alert("Invalid YouTube URL"); return; }
  document.getElementById("videoContainer").innerHTML = `<iframe id="ytFrame" src="https://www.youtube.com/embed/${videoId[1]}" allowfullscreen></iframe>`;
}

// Fullscreen function
function goFullscreen(elementId) {
  const elem = document.getElementById(elementId);
  if(elem.requestFullscreen) elem.requestFullscreen();
  else if(elem.webkitRequestFullscreen) elem.webkitRequestFullscreen();
  else if(elem.msRequestFullscreen) elem.msRequestFullscreen();
}

function redirectClassroom(element) {
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  element.classList.add('active');
  window.open('https://classroom.google.com/', '_blank');
}
</script>

</body>
</html>
