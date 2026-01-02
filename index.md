---
title:
layout: home
---

<!-- Welcome to the **Bartosz Błasiak Project Page**.  -->


# Welcome to the Blasiak Project Page

-------

<img width="120" src="/assets/photo_lindau.png" alt="Welcome!" align="left" hspace="9" vspace="10"> 
<p align="justify">
My research interests focus on the large-scale Quantum Chemistry &mdash; investigating
complex condensed-phase systems from the perspective of Quantum Mechanics. 
I am currently a research associate in Goethe University Frankfurt, in the 
<cite>
<a target="_blank" rel="noopener noreferrer" href="https://www.theochem.uni-frankfurt.de/teaching.php">Theoretical Chemistry of Complex Systems group</a></cite>.
</p>

Read recent
posts to get to know more about my research and collaborations.

-------

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

/* === Uniform slide layout === */
.mySlides {
  height: 620px;            /* uniform slide height */
  position: relative;
}

/* Inner layout container */
.slide-inner {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  padding-top: 30px;
  padding-bottom: 20px;
}

/* Image control */
.slide-inner img {
  max-height: 450px;        /* same image footprint */
  width: auto;
  object-fit: contain;
}

/* Caption control */
.slide-caption {
  max-width: 720px;
  font-size: 0.95rem;
  text-align: justify;
}

/* --- */

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 7</div>
  <div class="slide-inner">

     <img width="600" src="/assets/2RDM_iBT_TFD_2025.png" alt="iBT TFD RDMs" >
     <div class="slide-caption">
     <cite>
     <a target="_blank" rel="noopener noreferrer" href="https://arxiv.org/abs/2505.21302">Inverse Bogoliubov Transformation</a>
     </cite>
     in Thermofield Dynamics of open quantum systems 
     is convenient for propagating correlated wavepackets 
     from computational cost perspective, but also highly <em>non-trivial for phase space analysis</em>.
     Here we demonstrate new methods how to efficiently analyse the time evolution
     of the physical system in terms of the auxiliary 2-particle reduced density matrix.
     This approach, once combined with electronic structure fragmentation methods,
     is a powerful way to include thermal ensemble in open quantum systems 
     such as electronic
     chromophores with disorder. It is relevant for studying energy and charge transfer processes
     in organic photovoltaic materials.
     </div>

  </div>
</div>



<div class="mySlides fade">
  <div class="numbertext">2 / 7</div>

     <div class="slide-inner">
     <img width="600" src="/assets/BioSolEFP.png" alt="Bio-SolEFP" >
     <div class="slide-caption">
     <cite>
     <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.1039/C6CP01578F">Bio-SolEFP</a>
     </cite>
     method enables calculations of IR spectra of selected vibrational chromophores
     in very complex molecular environments like proteins, taking into account intricate interplay
     of various quantum mechanical effects on intermolecular interactions.
     </div>

  </div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 7</div>

     <div class="slide-inner">
     <img width="600" src="/assets/JCC_2021.jpg" alt="JCC Cover 2021" >
     <div class="slide-caption">
     <cite>
     <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.1002/jcc.26462">EOP</a>
     </cite>
     method enables encapsulations of electron repulsion integrals in fragment-based approaches
     to Quantum Chemistry, making them many orders of magnitude faster and turning them into effective
     fragment potentials.
     </div>

  </div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 7</div>
     <div class="slide-inner">
     <img width="600" src="/assets/Example_1_EET.png" alt="EOPs for EET" >
     <div class="slide-caption">
     <cite>
     <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.1039/D0CP04636A">EOP</a>
     </cite>
     method enables effective fragment parameterization of excitonic energy transfer couplings (EET).
     This is the first step to generate complex excitonic Hamiltonians for arbitrary arangement of 
     chromophores with disorder. It is relevant for studying energy and charge transfer processes
     in organic photovoltaic materials.
     </div>

  </div>
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 7</div>
     <div class="slide-inner">
     <img width="600" src="/assets/Calmodulin_SolEFP_2018.jpeg" alt="Bio-SolEFP calmodulin" >
     <div class="slide-caption">
     <cite>
     In collaboration with the 
     <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.1021/acs.jpclett.8b00969">Casey Londergan group</a>, 
     we applied the
     <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.1039/C6CP01578F">Bio-SolEFP</a>
     fragmentation method to establish quantitative connection between the FTIR line shape
     and the structural and dynamical charactristics of SCN-labeled calmodulin in its native form in water.
     </cite>
     </div>

  </div>
</div>


<div class="mySlides fade">
  <div class="numbertext">6 / 7</div>
     <div class="slide-inner">
     <img width="600" src="/assets/Example_2_CT.png" alt="EOPs for EET" >
     <div class="slide-caption">
     <cite>
     <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.1002/jcc.26462">EOP</a>
     </cite>
     method makes the transfer (CT) term of the state-of-the-art charge EFP2 method
     less time-consuming by more than one order of magnitude.
     </div>

  </div>
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 7</div>
     <div class="slide-inner">
     <img width="600" src="/assets/Workshop.png" alt="Quantum Chemistry Workshop" >
     <div class="slide-caption">
     Visit our
     <cite>
     <a target="_blank" rel="noopener noreferrer" href="https://github.com/globulion/qc-workshop#quantum-chemistry-workshop">Quantum Chemistry Workshop</a>
     </cite>
     to learn more about how to materialize your scientific ideas for implementing your computational methods into action.
     </div>

  </div>
</div>



<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
  <span class="dot" onclick="currentSlide(7)"></span>
</div>

<script>
let slideIndex = 1;
let slideTimer = null;
const slideInterval = 5000;  // 5 seconds

showSlides(slideIndex);
startAutoSlides();

function plusSlides(n) {
  stopAutoSlides();          // pause auto on manual click
  showSlides(slideIndex += n);
  startAutoSlides();         // restart timer
}

function currentSlide(n) {
  stopAutoSlides();          // pause auto on manual click
  showSlides(slideIndex = n);
  startAutoSlides();         // restart timer
}

function startAutoSlides() { 
  slideTimer = setInterval(() => {
    showSlides(slideIndex += 1);
  }, slideInterval);
}

function stopAutoSlides() {  
  clearInterval(slideTimer);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
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
</body>


-------

<!-- {% include collections-overview.html %} -->

