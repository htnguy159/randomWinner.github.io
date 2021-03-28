<!DOCTYPE html>
<html>

<head>
  <title>Random Winner</title>
  <link href="styles/styles.css" rel="stylesheet">
</head>

<body>

  <h1>Random Winner Selector</h1>
  <p>Enter Participants</p>

  <form>
    <input type="text" id="input" />  

     <button id="addName">
      Submit Name
    </button>
  </form>


  <p> </p>


  <!-- Banner -->
  <div class="banner">
    <img src="banner.png" id="banners" alt="Banner" style="width:50%;">
    <div class="centered text-white bold large-text">
      <p id="before">Winner is...</p>
      <p id="answer"></p>
    </div>
  </div>

  <div class="container">
    <button id="button">
      Select Winner
    </button>
  </div>

  <!--Show given list here -->
  <p class="text-green"> Winner selected from this list of: </p>
  <p id="pplList">Loading...</p>

  <!-- Scripts -->
  <script src="scripts/script.js"></script>




</body>
</html>