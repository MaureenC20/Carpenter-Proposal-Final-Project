<html lang="en">
    <head>
        <meta http-equiv='cache-control' content='no-cache'> 
<meta http-equiv='expires' content='0'> 
<meta http-equiv='pragma' content='no-cache'>
<div class="navbar">
  <a href="#home" class="w3-bar-item w3-button">Home</a>
  <a href="#news" class="w3-bar-item w3-button">Contact Us</a>
  <div class="dropdown">
  <button class="dropbtn" onclick="myFunction()">Genres
    <i class="fa fa-caret-down"></i>
  </button>
  <div class="dropdown-content" class="w3-bar-item w3-button" id="myDropdown">
    <a href="./code.html" class="w3-bar-item w3-button">Disney</a>
    <a href="#" class="w3-bar-item w3-button">Classical</a>
    <a href="#" class="w3-bar-item w3-button">Rock and Roll</a>
  </div>
  </div> 
</div>
<script>
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}
window.onclick = function(e) {
  if (!e.target.matches('.dropbtn')) {
  var myDropdown = document.getElementById("myDropdown");
    if (myDropdown.classList.contains('show')) {
      myDropdown.classList.remove('show');
    }
  }
}
</script>
    <link rel="stylesheet" type="text/css" href="https://MaureenC20.github.io/style.css"> 
    </head>
    <body style="background-image: url('cellist.webp');background-size: cover;
  height: 50px;
  position: relative;>
        <h1 class="title orange"> Welcome to the Musical Findings! </h1>
        <h2 class="green"> Different genres of music</h2>
        <p> -Hip Hop
            -Rap
            -Classical
            -R & B
            -Rock and Roll
            -Musicals
            -Religious </p>
        <p> Hip hop is a genre enjoyed by many. Some of the best performers of all time include Rihanna and Drake.
            However their work is not as well known.</p>
        <p> If you prefer 80s music visit <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ>80s"> music</a>
        <h3 class="blue"> Explore pop music  Explore </h3>
