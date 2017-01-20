# glamptromp
ME
===

function setup() {
  createCanvas(600,600);
   background(255);
}

function draw() {

  noStroke()
  fill(random(130,200), random(80,120), random(30,80), random(50,100))
  ellipse(mouseX -random(-width/8, width/8), mouseY -random(-height/8, height/8), random(1, 5), random(1,5));

  //left eye
  //white
  beginShape
  noStroke();
  fill(255);
  vertex(258, 300);
  bezierVertex(239, 280, 220, 280, 208, 295);
  bezierVertex(210, 295, 231, 307, 246, 300);
  //endShape();
    //blue
   fill(141, 182, 205)
   ellipse(233, 293, 24, 24)
   //iris
    fill(0)
    ellipse(233, 293, 8, 8)
  //shine
  //fill(255)
  //quad(222, 293, 229, 292, 231, 296, 224, 298)
  //fill(255)
  //ellipse(239, 290, 3, 3)
  //ellipse(235, 295, 2, 3)
  //lash
  stroke(0);
  strokeWeight(2)
  noFill();
  beginShape();
  curveVertex(258,  297);
  curveVertex(250,  288);
  curveVertex(236,  283);
  curveVertex(219,  288);
  curveVertex(203,  299);
  curveVertex(197,  302);
  endShape();

  //right eye
    //blue
    noStroke();
    fill(159, 182, 205)
    ellipse(359, 298, 24, 24)
    //black
    fill(0)
    ellipse(359, 298, 8, 8)
  //shine
  //fill(255)
  //rect(353, 299, 4, 4)
  //fill(255)
  //ellipse(366, 296, 3, 3)
  //ellipse(366, 296, 3, 3)
  //lash
  stroke(0);
  strokeWeight(2)
  noFill();
  beginShape();
  curveVertex(337,  300);
  curveVertex(340,  296);
  curveVertex(354,  287);
  curveVertex(372,  292);
  curveVertex(390,  307);
  curveVertex(397,  312);
  endShape();
  strokeWeight(1)
  //bottom lash
 // curve(198, 282, 209, 296, 244, 305, 258, 298);

  //brows
  //left
  fill(35, 30, 30);
  noStroke();
  beginShape();
  vertex(185, 265);
  bezierVertex(214, 255, 259, 251, 268, 273);
  bezierVertex(258, 275, 246, 269, 219, 267, 185, 265);
  endShape();
  //right
  beginShape();
  vertex(417, 289);
  bezierVertex(392, 260, 372, 261, 333, 264, 300, 286);
  bezierVertex(336, 282, 385, 266, 408, 287);
  endShape();

  //nose
  //leftarc
    stroke(0);
  strokeWeight(1)
  noFill();
  beginShape();
  curveVertex(269,  355);
  curveVertex(269,  355);
  curveVertex(266,  360);
  curveVertex(260,  365);
  curveVertex(255, 382);
  curveVertex(264, 388);
  curveVertex(267, 391);
  endShape();
   //leftbridgearc
  beginShape();
  curveVertex(282,  385);
  curveVertex(280,  385);
  curveVertex(274,  384);
  curveVertex(269,  385);
  curveVertex(272, 380);
  curveVertex(280, 380);
  curveVertex(292, 391);
  curveVertex(300, 394);
  endShape();
   //leftbridgearc
  beginShape();
  curveVertex(290, 394);
  curveVertex(297, 393);
  curveVertex(309, 383);
  curveVertex(319, 380);
  curveVertex(322, 384);
  curveVertex(316, 386);
  curveVertex(310, 385);
  curveVertex(307, 383);
  endShape();
  // rightarc
  beginShape();
  curveVertex(322,  355);
  curveVertex(330,  365);
  curveVertex(333, 386);
  curveVertex(316, 391);
  curveVertex(314, 388);
  endShape();

  //LEar
  stroke(0);
  beginShape();
  curveVertex(162, 297);
  curveVertex(157,  292);
  curveVertex(144,  289);
  curveVertex(140, 303);
  curveVertex(139, 315);
  curveVertex(149, 339);
  curveVertex(155, 362);
  curveVertex(154, 375);
  curveVertex(165, 378);
  curveVertex(171, 378);
  endShape();
  //REar
  stroke(0);
  beginShape();
  curveVertex(427, 311);
  curveVertex(430,  304);
  curveVertex(444,  297);
  curveVertex(448, 303);
  curveVertex(443, 311);
  curveVertex(443, 330);
  curveVertex(439, 342);
  curveVertex(436, 355);
  curveVertex(429, 371);
  curveVertex(429, 381);
  curveVertex(422, 386);
  curveVertex(416, 383);
  endShape();


  // mouth
  // lips
  noStroke();
  fill(255,192,203);
  beginShape();
  vertex(240, 442);
  bezierVertex(266, 457, 314, 458, 340, 446, 350, 338);
  bezierVertex(352, 430, 318, 428, 273, 432, 240, 442);
  endShape();
  // line
  stroke(0);
  beginShape();
  curveVertex(236,  443);
  curveVertex(241,  442);
  curveVertex(243,  442);
  curveVertex(262, 436);
  curveVertex(283, 439);
  curveVertex(294, 442);
  curveVertex(318, 436);
  curveVertex(347, 438);
  curveVertex(350, 440);
  endShape();

  // beard
  noStroke();
  fill(139,70,40);
    beginShape();
  vertex(158, 344);
  vertex(169, 393);
  vertex(185, 418);
  vertex(206, 439);
  vertex(210, 468);
  vertex(218, 476);
  vertex(220, 447);
  vertex(229, 447);
  vertex(235, 471);
  vertex(248, 488);
  vertex(265, 492);
  vertex(280, 483);
  //vertex(280, 475);
  vertex(270, 473);
  vertex(270, 466);
  vertex(296, 462);
  vertex(321, 464);
  vertex(316, 482);
  vertex(323, 488);
  vertex(355, 471);
  vertex(355, 445);
  vertex(370, 443);
  vertex(373, 461);
  vertex(380, 460);
  vertex(384, 435);
  vertex(400, 410);
  vertex(420, 382);
  vertex(427, 349);
  vertex(417, 422);
  vertex(393, 488);
  vertex(342, 541);
  vertex(264, 546);
  vertex(210, 503);
  vertex(172, 441);
  vertex(162, 390);
  endShape(CLOSE);
  // mustache left
  fill(150,80,30);
  beginShape();
  vertex(283, 396);
  vertex(266, 400);
  vertex(259, 410);
  vertex(235, 415);
  vertex(218, 440);
  vertex(222, 450);
  vertex(245, 437);
  vertex(266, 433);
  vertex(289, 428);
  vertex(289, 404);
  endShape(CLOSE);
  // mustache right
   beginShape();
  vertex(296, 407);
  vertex(295, 422);
  vertex(304, 431);
  vertex(324, 429);
  vertex(348, 436);
  vertex(357, 448);
  vertex(373, 443);
  vertex(370, 428);
  vertex(360, 413);
  vertex(342, 411);
  vertex(322, 396);
  endShape(CLOSE);

  //hair
   fill(35, 30, 30);
   beginShape();
  vertex(159, 347);
  vertex(157, 319);
  vertex(167, 274);
  vertex(168, 248);
  vertex(171, 242);
  vertex(174, 199);
  vertex(200, 150);
  vertex(305, 160);
  vertex(394, 159);
  vertex(420, 211);
  vertex(420, 266);
  vertex(428, 332);
  vertex(428, 350);
  vertex(434, 326);
  vertex(432, 302);
  vertex(438, 300);
  vertex(450, 203);
  vertex(430, 144);
  vertex(389, 105);
  vertex(339, 80);
  vertex(297, 67);
  vertex(252, 83);
  vertex(215, 68);
  vertex(184, 95);
  vertex(184, 130);
  vertex(166, 136);
  vertex(149, 146);
  vertex(144, 221);
  vertex(147, 263);
  vertex(156, 291);
  vertex(151, 305);
  endShape(CLOSE);



  if (isMousePressed)
    background(255);


  }
```

Things I do
-------------
+    [architecture](https://issuu.com/cfboyd/docs/1607_boyd_worksamples)
+ [visual art](http://cfbcfbcfb.tumblr.com)
+ [music](https://soundcloud.com/cfboyd)
+ [homemade t-shirts and poetry zines](https://www.etsy.com/shop/sharpieshirts)


Things that Inspire Me
----------------------

+ Artist and maker of oddities [Johanna Schmeer](http://johannaschmeer.com/) in particular this [project of futuristic edible organic art](https://vimeo.com/98281097)
+ Architect and Artist [Lebbeus Woods](http://www.lebbeuswoods.net/)
+ Artist [Olafur Eliasson](http://www.olafureliasson.net/)
+ Land Artist [Michael Heizer](http://doublenegative.tarasen.net/city/)
+ Architet [Andres](https://vimeo.com/28586784) [Jacqe](http://andresjaque.net/material_proyectosrealizados/imagenes/proyecto31/images/foto1.jpg)
+ [Anything](http://68.media.tumblr.com/10fb8bedf9783edb630786c7209a2758/tumblr_o1mejgmIbz1rqiykjo1_1280.jpg) [NASA](http://68.media.tumblr.com/6f8af5abab3e75b102dee3eb17e5e204/tumblr_obm4c7w0SX1rqiykjo1_1280.jpg) [does](http://68.media.tumblr.com/505870327a4513c0f1068b38c4347b4a/tumblr_nyc4ltoFwS1rqiykjo1_1280.jpg)
+ [Plants](http://68.media.tumblr.com/8581f1a7fa1c7c66ff24527501887cb6/tumblr_mjrin9SKYa1qzt6vjo1_500.gif) and [paintings](http://hashknife.tumblr.com/post/133544333713/russian-style-stanislav-zhukovsky-spring) of [plants](http://68.media.tumblr.com/7c57e18b5eb0d5239ed1e0ea8c365c63/tumblr_ny4orcnXHY1qd1iyxo1_1280.jpg)

What I'd like to Do in CCI
--------------------------
Create a command center where a user can interact physically with parameters of an immersive multimedia installation.

I don't have a strong concept yet but I'd like to explore anxiety vs. spectacle through empowering users to tune the artificial environment and the level and pace of stimulation to their comfort level.


kbye
! [alt text](http://68.media.tumblr.com/b876f0255dd33ce56f9623762d079551/tumblr_o6zwbfxHEH1ry46hlo1_400.gif "Crunz4Corn")
