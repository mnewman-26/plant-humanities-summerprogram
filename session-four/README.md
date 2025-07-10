<a href="https://www.juncture-digital.org"><img src="https://juncture-digital.github.io/juncture/static/images/ve-button.png"></a>

<param ve-config 
title="Madder"    
source-image="https://upload.wikimedia.org/wikipedia/commons/0/07/SherardiaArv3.jpg"   
banner="https://upload.wikimedia.org/wikipedia/commons/0/07/SherardiaArv3.jpg" 
height=100
author="Emily Hughes, Moira Newman, Lois Nguyen"
layout="vertical">

### showing a map
blah blah blah
<param ve-map
	   center="38.91588,-77.06338"
	   zoom="18"
	   caption="This is the location of dumbarton oaks in Washington, DC">
	   
#### Or you can use the QUID from wikidata
This is dumbartoan oaks again 
<param ve-map
	   center="Q1264942"
	   zoom="18"
	   caption="This is dumbarton oaks from another website">
	   
### creating your own map using url coordinates and zoom level
bow bow bow bow
<param ve-map
	   center="40.28555,-76.65058"
	   zoom="13"
	   caption="This is the location of hershey Pensylvania">
	   
	   
### now create a layered map using geojason
these are the coordinates for a simple map: 32.38/34.89
<param ve-map prefer-geojson
	   center="32.38,34.89"
	   zoom="2.5"
	   caption="This is the location of the mediteranian?">  
	<param ve-map-layer geojson
	   url="https://raw.githubusercontent.com/mnewman-26/plant-humanities-summerprogram/main/session-four/madder%20fake%20map.json">


### now im adding a map marker 
filler filler filler blah blah blah
<param ve-map prefer-geojson
	   center="32.38,34.89"
	   zoom="2.5"
	   caption="This is the location of the mediteranian?">  
<param ve-map-layer geojson
	   url="https://raw.githubusercontent.com/mnewman-26/plant-humanities-summerprogram/main/session-four/madder%20fake%20map.json" >
<param ve-map-marker
	   url="wc:Madder_as_a_natural_dye.jpg"
	   coords="23.86,20.7"
	   circle="true"> 
