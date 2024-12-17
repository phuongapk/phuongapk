<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Heart 02</title>
    <link rel="stylesheet" href="./style.css" />
  </head>

  <body id="playButton">
    <h3 data-text="Em giữ trái tim này nhé">Em giữ trái tim này nhé</h3>
    <audio id="audioPlayer" src="./mt.mp3"></audio> 
    <script src="./js/three.min.js"></script>
    <script src="./js/MeshSurfaceSampler.js"></script>
    <script src="./js/TrackballControls.js"></script>
    <script src="./js/simplex-noise.js"></script>
    <script src="./js/OBJLoader.js"></script>
    <script src="./js/gsap.min.js"></script>
    <script src="./js/script.js"></script>
    <script>
      const playButton = document.getElementById("playButton");
      const audioPlayer = document.getElementById("audioPlayer");
  
      playButton.addEventListener("click", function() {
          audioPlayer.play();
      });
  </script>

  </body>
</html>
