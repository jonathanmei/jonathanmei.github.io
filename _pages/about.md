---
layout: about
permalink: /
title: Jonathan <strong>Mei</strong>
description: >
  Sr. Research Engineer @ <a href="http://luminous.com">Luminous Computing</a> &ensp; | &ensp;
  Santa Clara, CA &ensp; | &ensp;
  first [dot] last [at] lmns [dot] com

profile:
  align: right
  image: prof_pic.jpg
  address: >
    <p>&emsp;Me in the &quot;wild&quot;</p>

news: false
social: false
---

<script>
var kindergarten = false;
var prof25 = document.getElementById("profile_pic").src;
function fade() {
  pp = document.getElementById("profile_pic");
  pp.style.transition = 0.2;
  a25 = document.getElementById("age25");
  a5 = document.getElementById("age5");
  ad = document.getElementById("address");
  E5 = document.getElementById("ELI5");


  if (!kindergarten) {
    a5.style.position = "relative";
    $("#age5").fadeToggle();
    $("#age25").fadeToggle();
    a5.style.display = "inline";
    a25.style.position = "absolute";

    $("#profile_pic").fadeToggle(200);
    setTimeout(function() {pp.src = "assets/img/prof_age5.jpg";}, 200);
    E5.innerHTML = "Explain Like I'm 25";
    ad.innerHTML = "&emsp;Me being wild";
    $("#profile_pic").fadeToggle(200);
  }
  else {
    a25.style.position = "relative";
    $("#age25").fadeToggle();
    $("#age5").fadeToggle();
    a25.style.display = "inline";
    a5.style.position = "absolute";

    $("#profile_pic").fadeToggle(200);
    setTimeout(function() {pp.src = prof25;}, 200);
    E5.innerHTML = "Explain Like I'm 5";
    ad.innerHTML = "&emsp;Me in the &quot;wild&quot;";
    $("#profile_pic").fadeToggle(200);
  }

  kindergarten = !kindergarten;
}
</script>
Hi there! Welcome to my little bubble on the net. Here's a bit about me. [<a href="#" id="ELI5" onclick="fade(); return false">Explain Like I'm 5</a>]

<div id="fader" style="position:relative">
  <div id="age25">
    <p>
      I develop large machine learning models and algorithms, studying their scaling behavior, especially for implementation on a novel supercomputer architecture that uses silicon photonics for communication to avoid bottlenecks found in current hardware.
      In my previous lives, among <a href="https://scholar.google.com/citations?user=bm4orewAAAAJ">other things</a>, I've worked on:
      <ul>
       <li> making photorealistic holograms from light fields using a combination of geometric computer vision, deep learning, and classical image processing</li>
       <li> <a href="https://ieeexplore.ieee.org/abstract/document/8320856">interpretable</a> machine learning via sparse <a href="https://ieeexplore.ieee.org/abstract/document/7763882">graph signal processing</a></li>
       <li> virtual reality controllers for standalone headsets using low-cost, low-power sensors</li>
       <li> computational 3D imaging based on <a href="https://ieeexplore.ieee.org/abstract/document/6738075/">time-of-flight</a> of light</li>
      </ul>
    </p>
    <p>
      I received my <a href="https://kilthub.cmu.edu/ndownloader/files/12255548">Ph.D.</a> from <a href="http://cmu.edu/">Carnegie Mellon University</a> in the Electrical & Computer Engineering department in 2018.
      I was advised by Prof. <a href="http://users.ece.cmu.edu/~moura/">José M.F. Moura</a>.
      I received my B.S. and <a href="https://dspace.mit.edu/bitstream/handle/1721.1/85609/870686410-MIT.pdf?sequence=2">M.Eng.</a> degrees in Electrical Science and Engineering from <a href="http://mit.edu/">Massachusetts Institute of Technology</a> in 2013.
      I was advised by <a href="https://www.rle.mit.edu/stir/">Vivek K. Goyal</a>.
    </p>
  </div>

  <div id="age5" style="position:absolute;display:none">
    <p>
      I make and study artificial intelligence on a new type of supercomputer that uses lasers to communicate way faster than electricity.
      I also used to work on <a href="https://scholar.google.com/citations?user=bm4orewAAAAJ">other things</a> like:
      <ul>
       <li> creating beautiful 3D videos and pictures by describing how cameras capture light, a sprinkle of black magic, and instagram filters</li>
       <li> <a href="https://ieeexplore.ieee.org/abstract/document/7763882">crazy connected computer models</a> that can be <a href="https://ieeexplore.ieee.org/abstract/document/8320856">easily explained</a> to people</li>
       <li> 3D video game controllers for virtual reality that were cheap but good</li>
       <li> measuring how far away things are using the <a href="https://ieeexplore.ieee.org/abstract/document/6738075/">time it takes for light</a> to hit things and bounce back to the camera</li>
      </ul>
    </p>
    <p>
      I got a <a href="https://kilthub.cmu.edu/ndownloader/files/12255548">fancy piece of paper</a> saying I did a lot of hard math and science from <a href="http://cmu.edu/">a good school</a> in 2018.
      I was helped along by Prof. <a href="http://users.ece.cmu.edu/~moura/">José M.F. Moura</a>.
      Before that, I got some other <a href="https://dspace.mit.edu/bitstream/handle/1721.1/85609/870686410-MIT.pdf?sequence=2">fancy pieces of paper</a> saying I was ready to get a job doing hard math and that I had started to do some science, this time from a different <a href="http://mit.edu/">good school</a> in 2013.
      There, I was helped along by <a href="https://www.rle.mit.edu/stir/">Vivek K. Goyal</a>.
    </p>
  </div>
</div>
I like to [jump](projects/3_trick), [rock climb](http://hangar18.com), fold (not jiggle jiggle) [origami](projects/1_paper), and dabble in other miscellaneous [artsy](projects/6_misc) media.
I also occasionally enjoy playing tennis, [violin](http://www.youtube.com/user/changethewhirled/), [chess](https://lichess.org/@/meihem), and other [board](http://catanuniverse.com/en/game/) [games](http://dominion.games) at an amateur level, and frolicking [on top of](http://cal-sailing.org/) and [underneath](https://www.tdisdi.com/) water.
