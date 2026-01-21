<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Brody's Games</title>
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
}
body.dark header { background:#000; }

#logo { width:70px; }

nav { display:flex; gap:10px; position:relative; align-items:center; }

.tab {
  padding:10px 15px;
  cursor:pointer;
  font-weight:700;
}
.tab:hover { opacity:0.7; }

.underline {
  position:absolute;
  height:3px;
  background:#ff3333;
  bottom:0;
  left:0;
  transition:0.3s;
}

main {
  padding:20px;
  height:calc(100vh - 60px);
  display:flex;
  flex-direction:column;
}

iframe {
  width:100%;
  height:100%;
  border:none;
  border-radius:6px;
}

#fullscreenBtn {
  padding:8px 12px;
  background:#444;
  color:#fff;
  border:none;
  border-radius:6px;
  cursor:pointer;
  margin-bottom:10px;
}
</style>
</head>

<body class="light">

<header>
  <div style="display:flex; align-items:center; gap:15px;">
    <img id="logo" src="https://i.postimg.cc/tYfvHKd2/GOON-GAMES-removebg-preview.png">
    <nav id="topNav">
      <div class="tab active" onclick="switchTab('youtube', this)">YouTube</div>
      <div class="tab" onclick="switchTab('games1', this)">GN Math</div>
      <div class="tab" onclick="switchTab('games2', this)">Geometry Dash</div>
      <div class="tab" onclick="switchTab('games3', this)">200+ Games</div>
      <div class="tab" onclick="switchTab('soundboard', this)">Soundboard</div>
      <div class="underline" id="tabUnderline"></div>
    </nav>
  </div>
  <div id="moonIcon" onclick="toggleDarkMode()">🌙</div>
</header>

<main id="mainContent"></main>

<script>
function toggleDarkMode() {
  document.body.classList.toggle('dark');
  document.body.classList.toggle('light');
}

function switchTab(tab, el) {
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  el.classList.add('active');

  const u = document.getElementById('tabUnderline');
  u.style.width = el.offsetWidth + "px";
  u.style.left = el.offsetLeft + "px";

  const main = document.getElementById('mainContent');

  if(tab === 'youtube') {
    main.innerHTML = `
      <button id="fullscreenBtn" onclick="goFullscreen('ytIframe')">Fullscreen</button>
      <iframe id="ytIframe" src="https://www.watchkin.com/" allowfullscreen></iframe>`;
  }

  if(tab === 'games1') {
    main.innerHTML = `
      <button id="fullscreenBtn" onclick="goFullscreen('g1')">Fullscreen</button>
      <iframe id="g1" src="https://deltamath.climaref.cl/" allowfullscreen></iframe>`;
  }

  if(tab === 'games2') {
    main.innerHTML = `
      <button id="fullscreenBtn" onclick="goFullscreen('g2')">Fullscreen</button>
      <iframe id="g2" src="https://scratch.mit.edu/projects/860151753/" allowfullscreen></iframe>`;
  }

  if(tab === 'games3') {
    main.innerHTML = `
      <button id="fullscreenBtn" onclick="goFullscreen('g3')">Fullscreen</button>
      <iframe id="g3" src="https://mathlessons.b-cdn.net/" allowfullscreen></iframe>`;
  }

  if(tab === 'soundboard') {
    main.innerHTML = `
      <button id="fullscreenBtn" onclick="goFullscreen('sb')">Fullscreen</button>
      <iframe id="sb" src="https://tuna.voicemod.net/" allowfullscreen></iframe>`;
  }
}

function goFullscreen(id) {
  const el = document.getElementById(id);
  if(el.requestFullscreen) el.requestFullscreen();
}

window.onload = () => {
  switchTab('youtube', document.querySelector('.tab.active'));
};
</script>

</body>
</html>
