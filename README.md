<!-- Templates Screen -->
<div id="templatesScreen" class="templates" style="display:none;">
  <h1>Pick a Template</h1>
  <p>Each theme changes colors and stickers.</p>

  <div class="row">
    <div class="templateCard" onclick="chooseTemplate('pastel')">
      <div>🌸</div>
      <div class="title">Pastel</div>
    </div>

    <div class="templateCard" onclick="chooseTemplate('stars')">
      <div>⭐</div>
      <div class="title">Stars</div>
    </div>

    <div class="templateCard" onclick="chooseTemplate('fruit')">
      <div>🍓</div>
      <div class="title">Fruits</div>
    </div>

    <div class="templateCard" onclick="chooseTemplate('anime')">
      <div>🫶</div>
      <div class="title">Anime</div>
    </div>

    <div class="templateCard" onclick="chooseTemplate('cat')">
      <div>🐱</div>
      <div class="title">Cat</div>
    </div>

    <div class="templateCard" onclick="chooseTemplate('unicorn')">
      <div>🦄</div>
      <div class="title">Unicorn</div>
    </div>

    <div class="templateCard" onclick="chooseTemplate('nature')">
      <div>🌿</div>
      <div class="title">Nature</div>
    </div>

    <div class="templateCard" onclick="chooseTemplate('game')">
      <div>🎮</div>
      <div class="title">Game</div>
    </div>
  </div>

  <button onclick="backHome()">Back</button>
</div>

<!-- App Screen -->
<div id="appScreen" class="app" style="display:none;">
  <div class="sticker s1">🧸</div>
  <div class="sticker s2">🌸</div>
  <div class="sticker s3">⭐</div>
  <div class="sticker s4">🍓</div>

  <h2>🌈 My Cute To-Do</h2>

  <!-- NEW LABEL -->
  <div class="labelBox">
    <span>📝 Write your task here</span>
    <span class="arrow">⬇️</span>
  </div>

  <div class="inputRow">
    <input id="taskInput" type="text" placeholder="✨ Write something fun" />
    <button class="add" onclick="addTask()">➕</button>
  </div>

  <ul id="taskList"></ul>

  <div class="footer">💖 Click a task to finish it</div>
</div>
