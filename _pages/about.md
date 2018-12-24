---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
    


<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
  *{
  box-sizing: border-box;
}
/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

.left {
  width: 75%;
}

.right {
  width: 25%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h2>Two Unequal Columns</h2>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Some text..</p>
    <p>I am currently working on restless bandits and reinforcement learning with <a href = "https://www.irit.fr/~Urtzi.Ayesta/" target="_blank">Prof. Urtzi Ayesta</a> and <a href = "http://verloop.perso.enseeiht.fr/" target="_blank">Prof. Maaike Verloop</a> at <a href = "https://www.irit.fr/?lang=en" target="_blank">IRIT</a>. </p>

<p>Before transitioning to Toulouse, I was working on game theoretic approaches for health-care operations with <a href = "https://esd.sutd.edu.sg/people/faculty/shrutivandana-sharma" target="_blank"> Prof. Shruti </a> and <a href = "https://esd.sutd.edu.sg/people/faculty/ying-xu" target="_blank">Prof. Ying</a> at <a href = "https://esd.sutd.edu.sg/" target="_blank"> ESD</a>. 
I graduated from the <a href = "http://www.ieor.iitb.ac.in/" target="_blank">IEOR@IITB</a> 
with my Ph.D. studying stochastic systems. </p>

<p>On these pages you will be able to find a lot about my technical interests. I hope you enjoy them and find them helpful to what interests you. </p>

<p>I am in the <b>job market</b>. Interested employers can <a href="mailto:manu-kumar.gupta@irit.fr">email</a> me for any queries and informal discussion.</p>
    
  </div>
  <div class="column right" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>
