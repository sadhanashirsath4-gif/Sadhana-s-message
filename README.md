<!DOCTYPE html>
<html>
<head>
    <title>Secret Message 🎁</title>
</head>

<body style="background:black; color:white; text-align:center;">

<h2>👀 Click below</h2>

<button onclick="playMusic()">Open 🎁</button>

<p id="msg" style="display:none;">
first press 2 time ❤️ Thank you so much for your wishes ani yevde efforts majha sathi khup mothi goshtye and jhop thodi thambun majha sathi jagun 😅 birthday wish krlya bdl khup khup dhanyavad
</p>

<audio id="bgmusic">
  <source src="music.mp3" type="audio/mpeg">
</audio>

<script>
function playMusic() {
  document.getElementById("bgmusic").play();
  document.getElementById("msg").style.display = "block";
}
</script>

</body>
</html>hamari aur aapki yesi hi nok jhok chlti rhe aur nazar na lage 
aakhiri message samapt hoke me end krti hu🫣😜🤣🤣🫡
</div>

<audio id="bgmusic" autoplay loop muted>
  <source src="music.mp3" type="audio/mpeg">
</audio>

<script>
function showMessage() {
    document.getElementById("message").style.display = "block";
}

window.addEventListener("click", function() {
  let music = document.getElementById("bgmusic");
  music.muted = false;
  music.play();
});
</script>

</body>
</html>
