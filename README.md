
<html lang="en">
    <style>
    <head{
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 100% 100%;
}>
</style>
<div class="navbar">
  <a href="#home">Home</a>
  <a href="#news">News</a>
  <div class="dropdown">
  <button class="dropbtn" onclick="myFunction()">Dropdown
    <i class="fa fa-caret-down"></i>
  </button>
  <div class="dropdown-content" id="myDropdown">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
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
    <body>
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
        <h3 class="blue"> Explore pop music            ___ Explore Rap</h3>
