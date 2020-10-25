---
layout: page
title: Advocacy
permalink: /advocacy
---
# making a box


<div class="row">
  <div class="column">
    <img src="img/caregiver-feelings-10-24.png">
    <img src="img/caregiver-feelings.png">
    <img src="img/caregiver-jobs.png">
    <img src="img/caregiver-map-10-24.png">
  </div>
  <div class="column">
    <img src="img/caregiver-feelings-10-24.png">
    <img src="img/caregiver-feelings.png">
    <img src="img/caregiver-jobs.png">
    <img src="img/caregiver-map-10-24.png">
  </div>
  <div class="column">
    <img src="img/caregiver-feelings-10-24.png">
    <img src="img/caregiver-feelings.png">
    <img src="img/caregiver-jobs.png">
    <img src="img/caregiver-map-10-24.png">
  </div>
  <div class="column">
    <img src="img/caregiver-feelings-10-24.png">
    <img src="img/caregiver-feelings.png">
    <img src="img/caregiver-jobs.png">
    <img src="img/caregiver-map-10-24.png">
  </div>
</div>


<h2>Opacity with Box</h2>
<p>Hover over the image to see the effect.</p>

<div class="container">
  <img src="img/caregiver-whofor.png" alt="Avatar" class="image" style="width:100%">
  <div class="middle">
    <div class="text">John Doe</div>
  </div>
</div>


<!-- JAVASCRIPT?
 -->
<button onclick="one()">1</button>
<button onclick="two()">2</button>
<button onclick="four()">4</button>

<script>
// Get the elements with class="column"
var elements = document.getElementsByClassName("column");

// Declare a "loop" variable
var i;

// Full-width images
function one() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.flex = "100%";
  }
}

// Two images side by side
function two() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.flex = "50%";
  }
}

// Four images side by side
function four() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.flex = "25%";
  }
}
</script>