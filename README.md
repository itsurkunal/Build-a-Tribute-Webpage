# Build-a-Tribute-Webpage
Tribute Page in Web
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Tribute Page
  </title>
  <link rel="stylesheet" href="css/styles.css">
  <style>
  .row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}

#tribute-link {
  color: #CC0000;
  font-weight: bold;
}

#image {
  max-width: 500px;
  display: block;
}

#img-caption {
  font-size: 30px;
}

.center {
  margin: auto;
  width: 50%;
  padding: 10px;
  text-align: center;
}
</style>
</head>

<body>
  <main id="main">

    <h1 id="title" class="center">Mahatma Gandhi</h1>

    <div id="img-div">
      <div class="row">
        <div class="column"></div>
        <div class="column">
          <img src="MahatmaGandhi.jpg" alt="Mahatma Gandhi at Home" id="image">
          <img src="m1.jpg" alt="Mahatma Gandhi In Samaj" id="image">
          <img src="m2.jpg" alt="Mahatma Gandhi Black and White" id="image">
          <img src="m3.jpg" alt="Mahatma Gandhi Vivid Colors Portrait" id="image">
        </div>
        <div class="column">
          <img src="m4.jpg" alt="Mahatma Gandhi BnW Portrait" id="image">
          <img src="m5.jpg" alt="Mahatma Gandhi Cool" id="image">
          <img src="m6.jpg" alt="Mahatma Gandhi Points at You" id="image">
          <img src="m7.jpg" alt="Mahatma Gandhi Portrait" id="image">
          <img src="m8.jpg" alt="Mahatma Gandhi Freedom" id="image">
        </div>
        <div class="column"></div>
      </div>
      <p id="img-caption" class="center"><em>One of the Greatest Freedom Fighter</em></p>
    </div>

    <div id="tribute-info" class="center">
      <p>down the street you can hear her scream</p>
      <p>"you're a disgrace"</p>
      <p>as she slams the door in his drunken face</p>
      <p>and now he stands outside</p>
      <p>and all the neighbours start to gossip and drool</p>
      <p>he cries "oh girl, you must be mad</p>
      <p>what happened to the seet love you and me had"</p>
      <p>against the door he leans and starts a scene</p>
      <p>and his tears fall and burn the garden green</p>
      <p>and so castles made of sand,</p>
      <p>fall in the sea eventually</p>
      <p>a little indian brave who before he was ten</p>
      <p>played war games in the woods with his indian friends</p>
      <p>and he built a dream that when he grew up</p>
      <p>he would be a fearless warrior indian chief</p>
      <p>many moons passed and the dream grew strong until tomorrow</p>
      <p>he would sing his first war song</p>
      <p>and fight his first battle but something went wrong</p>
      <p>surprise attack killed him in his sleep that night</p>
      <p>and so castles made of sand</p>
      <p>melts into the sea eventually</p>
      <p>there was a young girl whose heart was a frown</p>
      <p>because she was crippled for life and couldn't speak a sound</p>
      <p>and she wished and prayed she would stop living</p>
      <p>so she decided to die</p>
      <p>she drew her wheel chair to the edge of the shore</p>
      <p>and to her legs she smiled</p>
      <p>"you won't hurt me no more"</p>
      <p>but then a sight she'd never seen made her jump and say</p>
      <p>"look a golden winged ship is passing my way"</p>
      <p>and it really didn't have to stop</p>
      <p>it just kept on going</p>
      <p>and so castles made of sand</p>
      <p>slips into the sea eventually</p>
    </div>
    <div class="center">
      <a href="https://en.wikipedia.org/wiki/Mahatma_Gandhi" target="_blank" id="tribute-link">
        Learn more about Mahatma Gandhi.
      </a>
    </div>
  </main>
</body>
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>

</html>
