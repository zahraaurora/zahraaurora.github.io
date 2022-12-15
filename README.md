<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
</head>
<body>
  <h1>Sushi Dushi</h1>
 <!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>

<div class="w3-sidebar w3-bar-block w3-collapse w3-card w3-animate-right" style="width:200px;right:0;" id="mySidebar">
  <button class="w3-bar-item w3-button w3-large w3-hide-large" onclick="w3_close()">Close &times;</button>
  <a href="#" class="w3-bar-item w3-button">Link 1</a>
  <a href="#" class="w3-bar-item w3-button">Link 2</a>
  <a href="#" class="w3-bar-item w3-button">Link 3</a>
</div>

<div class="w3-main" style="margin-right:200px">
<div class="w3-salmon">
  <button class="w3-button w3-teal w3-xlarge w3-right w3-hide-large" onclick="w3_open()">&#9776;</button>
  <div class="w3-container">
    <h1>over ons</h1>
  </div>
</div>

<div class="w3-container">
  <p>Welkom bij ons sushi restaurant. Wij bieden een uitgebreid assortiment aan heerlijke sushi en andere Japanse gerechten. Onze sushi wordt gemaakt met de beste en verse ingredienten en zijn met veel zorg en liefde bereid. We hopen je snel te zien in ons restaurant!.</p>
  <p><b>Resize the browser window to understand how it works.</b></p>
</div>

</div>

<script>
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
}

function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>
     
</body>
</html>
