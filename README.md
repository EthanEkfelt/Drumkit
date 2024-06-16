# Drumkit
 Siste innlevering - IT prosjekt VG 2 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drumkit</title>
    <link rel="stylesheet" href="drumkit.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap" rel="stylesheet">
  </head>
    <script src="drumkit.js"></script>
</head>

<body>

<main>
  <header>
    <div>
    <a class="main-title" href="drumkit.html">TrommeSpill</a>

    </div>
    <div>
    <nav class="navbar">
      <ul class="nav-list">
        <li class="nav-item"><a href="hjem.html">Hjem</a></li>
        <li class="nav-item"><a href="Guide.html">Guide</a></li>
        <li class="nav-item"><a href="drumkit.html">Trommesett</a></li>
        <li class="nav-item"><a href="#footer">Kontakt</a></li>
      </ul>
    </nav>
    </div>
  </header>
  


    <section class="main-wrapper">
      <div class="key-map-wrapper">
        <h2>Spill-knapper</h2>
        <ul class="key-map-list">
          <li>
            <kbd class="key-code">E</kbd>
            <span class="key-sound">Crash</span>
          </li>
          <li>
            <kbd class="key-code">R</kbd>
            <span class="key-sound">Ride</span>
          </li>
          <li>
            <kbd class="key-code">F</kbd>
            <span class="key-sound">Floor tom</span>
          </li>
          <li>
            <kbd class="key-code">G</kbd>
            <span class="key-sound">Mid tom</span>
          </li>
          <li>
            <kbd class="key-code">H</kbd>
            <span class="key-sound">High tom</span>
          </li>
          <li>
            <kbd class="key-code">V</kbd>
            <kbd class="key-code">B</kbd>
            <span class="key-sound">Kick</span>
          </li>
          <li>
            <kbd class="key-code">J</kbd>
            <span class="key-sound">Snare</span>
          </li>
          <li>
            <kbd class="key-code">I</kbd>
            <span class="key-sound">Hi-Hat Open</span>
          </li>
          <li>
            <kbd class="key-code">K</kbd>
            <span class="key-sound">Hi-Hat Closed</span>
          </li>
        </ul>
      </div>
  

      <div class="drum-kit-wrapper">
        <img id="crash-ride" class="crash-cymbal" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/img/crash.png" alt="Crash cymbal">
        <img id="hihat-top" class="hihat-top-cymbal" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/img/hihat-top.png" alt="Hi Hat cymbal">
        <div data-key="74" class="key snare">
          <kbd>J</kbd>
        </div>
        <div data-key="66" class="key kick">
          <kbd>B</kbd>
        </div>
        <div data-key="86" class="key kick2">
          <kbd>V</kbd>
        </div>
        <div data-key="72" class="key tom-high">
          <kbd>H</kbd>
        </div>
        <div data-key="71" class="key tom-mid">
          <kbd>G</kbd>
        </div>
        <div data-key="70" class="key tom-low">
          <kbd>F</kbd>
        </div>
        <div data-key="69" class="key crash">
          <kbd>E</kbd>
        </div>
        <div data-key="82" class="key ride">
          <kbd>R</kbd>
        </div>
        <div data-key="73" class="key hihat-open">
          <kbd>I</kbd>
        </div>
        <div data-key="75" class="key hihat-close">
          <kbd>K</kbd>
        </div>
        <img class="drum-kit" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/img/drum-kit.png" alt="Drum Kit" />
      </div>
    </section>
  </main>

  <footer id="footer">
    <div class="footer-content">
      <div class="footer-section about">
        <h2>Om Oss</h2>
        <p>Vi, hos Erasmusmontanus, er lidenskapelige trommeslagere som elsker å dele vår kunnskap og lidenskap for trommespill med andre. Besøk oss for å lære mer om trommesett og trommespilling.</p>
      </div>
      <div class="footer-section contact">
        <h2>Kontakt Oss</h2>
        <p>E-post: Erasmusmontanus@trommekit.no</p>
        <p>Telefon: +47 123 45 678</p>
        <p>Adresse: Erasmusmontanusveien 12, 0450 Oslo, Norge</p>
      </div>
      <div class="footer-section social">
        <h2>Følg Oss</h2>
        <a href="https://facebook.com" target="_blank">Facebook <label><i class="fa-brands fa-snapchat icon"></i></label></a>
        <a href="https://twitter.com" target="_blank">Twitter<label><i class="fa-solid fa-mobile-button fa-shake icon"></i></label></a>
        <a href="https://instagram.com" target="_blank">Instagram<label><i class="fa-brands fa-instagram icon"></i></label></a>

       
        

      </div>
    </div>
    <div class="footer-bottom">
      <p>&copy; 2024 Trommekit. Alle rettigheter forbeholdt.</p>
    </div>
  </footer>
  

  <audio data-key="74" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/snare.wav"></audio>
  <audio data-key="66" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/kick.wav"></audio>
  <audio data-key="86" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/kick.wav"></audio>
  <audio data-key="72" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/tom-high.wav"></audio>
  <audio data-key="71" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/tom-mid.wav"></audio>
  <audio data-key="70" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/tom-low.wav"></audio>
  <audio data-key="69" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/crash.wav"></audio>
  <audio data-key="82" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/ride.wav"></audio>
  <audio data-key="73" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/hihat-open.wav"></audio>
  <audio data-key="75" src="https://raw.githubusercontent.com/ArunMichaelDsouza/javascript-30-course/master/src/01-javascript-drum-kit/sounds/hihat-close.wav"></audio>

  </body>
</html>