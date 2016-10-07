

# Open GIS and the geoeweb
<div align="right">by lassegs with reveal.js</div>

---

A presentation to the tune of the [Cantina theme](https://www.youtube.com/watch?v=kCGPt3XFxJk). 

This is the story of the state of web mapping from a free software and open source perspective. The story is rendered in typical Star Wars style. For the lulz.

+ 10:15 Story time
+ 11:00 Recess
+ 11:15 Story time
+ 11:35 Discussion
+ 12:00 Release

---

<!-- .slide: data-background-color="#000" data-background-transition="zoom" -->
<div style="font-weight: 800">
In a galaxy not so far away, neither in time nor space...
</div>


```

 I explore the origins of the hacker culture,including prehistory
 among the Real Programmers, the glory days of the MIT hackers,
 and how the early ARPAnet nurtured  the first network nation.

 I describe the early rise and eventual stagnation of Unix,
 the new hope from  Finland, and how *the last true hacker*
 became the next generation's patriarch. I sketch the way Linux
 and the mainstreaming of the Internet brought the hacker culture 
 from the fringes of public consciousness to its current prominence.


```

<div align="right">by ESR from [Cathedral and the Bazaar](http://www.catb.org/esr/writings/cathedral-bazaar/hacker-history/index.html#id2763962)</div>

---

<!-- .slide: data-background-color="#000" -->
A tour down the rabbit hole of [data science](https://www.coursera.org/specializations/jhu-data-science "Learn it at coursera")...
 
<iframe data-src="//giphy.com/embed/y55tOswHWvBxC" width="680" height="460" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

Note:


why should you go down this rabbit hole.
A history of digital mapping. One that tries to lay out a map of mapping, considering
our current situation. A given here is Bacon's statement that 'knowledge is power'.
When we create maps, make visualizations, or even just present, we are in fact creating new worlds. 

So be fully aware that while I try to offer you shoulders to stand on and see further,
you will also be subjected to my shortcomings, oversights and misunderstandings.


---

...and our complex webs and layers of [infrastructure](http://pubsonline.informs.org/doi/abs/10.1287/isre.7.1.111)...


<iframe data-src="https://map.norsecorp.com/" width="100%" height="768px" frameBorder="0" ></iframe>


---


<!-- .slide: data-background-color="#000" -->
###...where we'll briefly visit...




Note:
How long it will last, basic structure


---

### the resistance,
<iframe data-src="//giphy.com/embed/8jdQ5engCKyQM" width="680" height="460" frameBorder="0" class="giphy-embed" allowFullScreen></iframe

Note:
the resistance 

---


<!-- .slide: source data-background="https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/Jakarta_slumlife71.JPG/1280px-Jakarta_slumlife71.JPG" -->
###Empire <div style="font-size:0.5em">* Buy 1, get 1 free.</div>

---

### the GNU,
<!-- .slide: source data-background="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/Streifengnu_%28en._Wildebeest%29.JPG/1024px-Streifengnu_%28en._Wildebeest%29.JPG" -->

Note:
the wierd animal that turns out to be a powerful teacher.. RMS or the penguin? No, its obviously the GNU

Before next slide, remind about perspective, story telling and choice of technologies affects worldview. 

---

<!-- .slide: source data-background="http://bturn.com/wp-content/uploads/2011/11/darth-vader-face.jpeg" -->
##ESRI,

Note: 
the guards of the Empire

---


<!-- .slide: source data-background="http://img.lum.dolimg.com/v1/images/open-uri20150608-27674-13oku6w_bb2a0468.jpeg" -->

###Empire

Note: 
A great evil
---

###Empire
<!-- .slide: source data-background="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Rub_al_Khali_002.JPG/800px-Rub_al_Khali_002.JPG" -->


---
<!-- .slide: source data-background="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/2011_Horn_of_Africa_famine_Oxfam_01.jpg/800px-2011_Horn_of_Africa_famine_Oxfam_01.jpg" -->

### [Anthropocene](http://www.igbp.net/download/18.316f18321323470177580001401/1376383088452/NL41.pdf) / [Manthropocene](https://www.theguardian.com/commentisfree/2014/oct/20/anthropocene-working-group-science-gender-bias) / [Capitalocene](http://www.jasonwmoore.com/uploads/The_Capitalocene__Part_I__June_2014.pdf) / [Cthulucene](http://www.e-flux.com/journal/75/67125/tentacular-thinking-anthropocene-capitalocene-chthulucene/)
 

Note: 
A scenic perspective has taken hold of our social narrative. The discussion is which one? 

Anthropocene theorists (like chakrabarty 2009) contends that Humans now act with the power of geophysical forces, like tectonic plates or volcanoes, as the geological agent.
Manthropocene was originally a twitter complaint about the Anthropocene scientist working group consisted of "top scientists, climatologists, etc.", and all but one, Men. At the same time it grabs something deeper. Is anthropos really who created this mess, just a flat unqualified Human? Should we make the domination of men over women as Or should the Anthropos be gendered?

Hold on, says the capitalocene-people. The anthropos shouldnt only be qualified by gender, but also by class. Our current ecological crisis has been generated by the logic of capitalist society, where all is Human or Nature (with big H and N). Human here means those who have work, while Nature are both trees, waterfalls but also women, the "naturales", homeless, etc. All will be exploited in the process of capital accumulation, whereas only Humans (with a big H) are paid.   

Cthulucene is a another deep kind of ecological argument. All of these are links. Read them if you wanna be updated. 


---
<!-- .slide: source data-background="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/2011_Horn_of_Africa_famine_Oxfam_01.jpg/800px-2011_Horn_of_Africa_famine_Oxfam_01.jpg" -->

![Gnu Flute!](http://blog.larocadelconsejo.net/wp-content/uploads/2007/11/gnu_meditate_levitate.png)

---
# Free software

Note: 
There are many who don't see free software as a critique of the production process of what is. 
That is fine. This god has many faces, and fits into many narratives.


---


<!-- .slide: data-background-color="#000" -->

* 1960s - [CGIS](https://en.wikipedia.org/wiki/Canada_Geographic_Information_System). Rare computers.
* 1970s - Academics and pioneers. GRASS. Not so rare anymore. 
* 1980s - Spatial database breakthroughs and PCs. Diversification.
* 1990s - Mapinfo. Don't forget how you found this out - 1998 [google](https://scholar.google.com/scholar?q=history+of+gis+filetype%3Apdf&btnG=&hl=en&as_sdt=0%2C47).
* 2000s - ESRI, QGIS, Web 1.0 -> Web 2.0.
* 2010s - Web 2.0 maps.
* 2020s - 

Note:
Canadian grandmaster Roger Tomlinson / IBM --> geogratis
GRASS is freely available, and very usable together with QGIS.

1980s saw the breakthrough of 

Norge var tidlig på ARPAnet, da vi hadde seismiske stasjoner for måling av atombombesprenginger i Sovjet.
---

### Alternative view

A whole fucking bunch of map based software by the 2000s.

---

ArcGIS is just another GIS. 

---

Standardization takes work and time.
<iframe data-src="//giphy.com/embed/fmGzSnhk5IwX6" width="680" height="460" frameBorder="0" class="giphy-embed" allowFullScreen></iframe

---

What exactly is it ArcGIS does?

* What?
* How?
* Why?

---

<iframe data-src="//giphy.com/embed/Gt0zE0HOMkTCg" width="800" height="500" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

Note:
Let's just have look at it. What do we see when we use it?
Here I'm offering my shoulders to stand on and see further,
but you'll have to overcome my shortcomings.

---

Open, visualize, analyse and store

* ##~~What?~~
<small> * Big, bad question</small>
* Let's start with <big>How?</big>

---

 ##Opens a spatial database
  * Connects through storage or network
  * Recognizes and indexes information
  * Loads up relevant data from storage to RAM (working memory)
---
 ##Visualizes 
  * Coordinates and layers
  * Styles
  * Handles user interface
---
 ## Analyses
 * Measurements and overlays
 * Spatial correlation (Moran's I, etc.)
 * Spatial regression 
 * Network analysis
 * MANY MANY MORE
---

 ## Stores
 * To image
 * As file locally
 * To database remotely
 * As .pdf (to the printer)	

---
Ok, so it opens, visualizes, analyzes, stores what?
<h2>What are we mapping?</h2>
# Data?


---
<!-- .slide: source data-background="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/Battle_of_Bentonville_map.png/858px-Battle_of_Bentonville_map.png" -->
 
---

<!-- .slide: source data-background="https://upload.wikimedia.org/wikipedia/commons/0/05/Efecto_matrix.jpeg" -->
---

# Capta 
as opposed to
# data


--- 	


---
<!-- .slide: source data-background="http://img.lum.dolimg.com/v1/images/open-uri20150608-27674-13oku6w_bb2a0468.jpeg" -->

<iframe data-src="//giphy.com/embed/2JA0YPswSWXkI" width="900" height="660" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/blog-map-social-2JA0YPswSWXkI">via GIPHY</a></p>


---
The free as in freedom Geographical Information System
## QGIS

---
<!-- .slide: source data-background="https://qgis2015.files.wordpress.com/2015/02/1k0a4924.jpg" -->


#### Tool of the trade, basic and advanced
 

![Everyone loves QGIS](https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/QGis_Logo.png/436px-QGis_Logo.png)

[QGIS 2015 Nødebo](http://demo.qgis.org/demos/2015/index.html).
---

<section data-background="Wake_Pop_density_2.png"> </section>

---

Weakness

* Desktops, desktops everywhere.
* Stiff maps

* Strong user/developer divide

Note:
Omnious desktop fucking metaphor, the violent real abstraction of the desktop.

---

<!-- .slide: source data-background="http://i.giphy.com/j6iyD03LaUNuU.gif" data-background-transition="zoom" data-transition="zoom" -->
![websurfin](http://i.giphy.com/j6iyD03LaUNuU.gif)


### Speak Computer / 
### computer speaks back

```

lassegs@computer ~> echo "I'm not alone"
> I'm not alone
lassegs@computer -> :*(

```
---

There are many types of web maps and combinations of maps and other visualizations 

---

Recess

---

<!-- .slide: data-background="http://img.wallpaperfolder.com/f/6537179D1199/was-looking-mr-robot-and.jpg" -->
# Hacker culture / 
# Culture hacking



---

In the computer age, code is law.

---

---

![nope](http://www.reactiongifs.com/wp-content/gallery/no/john-cleese-no.gif)

A quick walk through of the **big 3** of **W3**

---
## HTML

Hypertext Markup Language is used to structure content for web browsers.

```
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1>Page Title</h1>
        <p>This is a really interesting paragraph.</p>
    </body>
</html>
```
---

## CSS

Cascading Style Sheets styles the visuals of HTML sites.
```
body {
    background-color: white;
    color: black;
}
```
---
## Javascript

Javascript allows us to control and change the web site after its loaded.


---

<!-- .slide: source data-background="https://www.gnu.org/graphics/listen-quarter.jpg" -->  

---

The **free** as in **freedom** geoweb stack

---

![anatomy2](http://maptime.io/anatomy-of-a-web-map/images/basemap-datalayers-05.png)

---
Tiles, tiles everywhere!



<iframe data-src="https://www.google.com/maps/embed/v1/place?q=oslo&key=AIzaSyAN0om9mFmy1QN6Wf54tXAowK4eT0ZUPrU" width="100%" height="630" frameBorder="0" allowFullScreen></iframe>

---

## Tile server

---

## Database

---

## [Leaflet](http://www.leafletjs.com)


## [Openlayers](http://www.openlayers.org)

Note: 
adsdklaslkdkas da.
This is a note
---

## ```<div id="map">```

Note:
Both leaflet and openlayers depend on this logic: A "map" div places a map element on the web page.
---

```
<html> <head> <title>Funky title</title> </head>
<body>
	<h1>Funky header</h1>
	<div id="map" style="width: 100%, height: 400px"></div>
		<script>
  		new ol.Map({
    			layers: [
      			new ol.layer.Tile({source: new ol.source.OSM()})
			 ],
   			 view: new ol.View({
     			 center: [0, 0],
    			  zoom: 2
 			   }),
  		  target: 'map'
 		 });
		</script>
</body> </html>
```
---

![anatomy](http://maptime.io/anatomy-of-a-web-map/images/anatomy-of-a-web-map.png)

---



<iframe data-src="https://kart.gulesider.no/" width="100%" height="700px" frameBorder="0" ></iframe>

Note:
Leaflet
---

<iframe data-src="https://www.1881.no/kart/" width="100%" height="700px" frameBorder="0" ></iframe>

Note:
Leaflet

---

<iframe data-src="https://darksky.net/25.7743,-80.1937" width="100%" height="700px" frameBorder="0" ></iframe>

Note:
Openlayers

---

https://codepen.io/lassegs/pen/yavPvXø

Note:
https://codepen.io/lassegs/pen/yavPvX
Make your own
---
Inspirational web maps
Check also 
https://cartahistorica.muhba.cat/index.html?lang=en


Note:
Openlayers
---
Distributed computing

---

The awesome powers of organization


---

2020s - IPFS and smart contracts

---


## credits, inspirations and resources
http://alignedleft.com/tutorials/d3/fundamentals
http://www.reactiongifs.com/wp-content/gallery/no/john-cleese-no.gif
http://boundlessgeo.com/wp-content/uploads/2016/04/Wake_Pop_density_2.png
http://i.giphy.com/j6iyD03LaUNuU.gif
https://upload.wikimedia.org/wikipedia/commons/e/ea/Battle_of_Bentonville_map.png
http://map.norsecorp.com/#/platform

Electronic Archeologist blog:
Programming Historian blog: 

