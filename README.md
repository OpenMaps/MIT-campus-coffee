# MIT-campus-coffee

This is a great application for anyone new to JavaScript and/or [LeafletJS](http://leafletjs.com/).  It also introduces [Bower](http://bower.io/), a package manager that makes including frameworks, libraries, and utilities in your projects more convenient for developers.

The end result:  Map of the MIT campus, including coffee shops and cafes

The full tutorial can be found [here](http://duspviz.mit.edu/leaflet-js/).

A few adjustments I made when creating this tutorial:

- Step 1.d - I used Bower for installing Leaflet.  It's a package manager that makes including frameworks, libraries, and utilities in your projects more convenient for developers.  Using command line, inside my working folder, I entered the following:

		bower install leaflet
		
	You will notice a new folder in your working directory called *bower_components* that contains the necessary Leaflet files for your project.  Therefore, the Leaflet CSS link in the *head* section of your index.html would be referenced as:
	
		<link rel="stylesheet" href="./bower_components/leaflet/dist/leaflet.css" />

	and the Leaflet JavaScript link at the bottom of the *body* section would be referenced as: 
	
		<script src="./bower_components/leaflet/dist/leaflet.js"></script>
		

	

	
