# GC_Graffiti
<!DOCTYPE html>
<html>
<head>
<link href="https://fonts.googleapis.com/css?family=Oswald|PT+Sans" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Catamaran|Fjalla+One" rel="stylesheet">
<title>24 Sustainable Restaurants</title>
<link rel="stylesheet" type="text/css" href="GC_Graffiti.css">
</head>
<!-- item 26-->
        <link rel="icon"
          type="image/png"
          href=""
          />
<!--slide area-->

  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="Graffiti+Earth.jpg" style="width:100%">
    <div class="text">Graffiti Earth</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="Graffiti+Earth+Dining+Room.jpg" style="width:100%">
    <div class="text">Graffiti Earth</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    <img src="GEfood.jpg" style="width:100%">
    <div class="text">Food</div>
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

<h1>Graffiti Earth Tribeca NYC</h1>

<body>
    <p>Even outside the kitchen, Graffiti Earth is focused on sustainability from furniture, made from renewable materials, down to the napkins. The dining room of Graffiti Earth has the same intimate feeling as the original with a bit more elegance. A large feature wall displays dishes as a nod to the restaurant’s rural, farmhouse kitchen atmosphere, while warm metals and weathered woods are paired with soft metallic elements for an urban space befitting the restaurant’s Tribeca location.</p>

<P>Who knew that furniture could be sustainable?</p>
    
    
<p>For more information<a href="https://ecocult.com/the-24-best-sustainable-and-eco-friendly-restaurants-in-nyc/">Visit Graffiti Earth</a></p>
    <p>&copy; Graffiti Earth</p>
</body>
</html>
