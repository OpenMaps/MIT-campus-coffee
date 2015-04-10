## Tutorial of MIT Campus Map and Surrounding Coffee Shops

This is an excellent beginning web application for anyone new to JavaScript and/or [LeafletJS](http://leafletjs.com/).  The tutorial was developed by MIT and is easy to understand.  I have included additional information below about publishing your application via [GitHub Pages](https://pages.github.com/) as well as [Bower](http://bower.io/), a package manager that makes including frameworks, libraries, and utilities in your projects more convenient for developers.  I feel as though all of this information together is an excellent start to learning about and creating web maps.


The full MIT tutorial can be found [here](http://duspviz.mit.edu/leaflet-js/).

Application can be found [here](http://tannerkj.github.io/MIT-campus-coffee/).

######Adjustments I made when running through this tutorial:
######Step 1.b

I did not serve locally using Python.  I created a [GitHub repo](https://github.com/tannerkj/MIT-campus-coffee) and viewed changes locally using *http://localhost/~username/projectname/* before pushing to GitHub.  It is a good standard practice to follow.  Also, you then have the ability to publish your webpages using GitHub Pages.  

###### Step 1.d

I used [Bower](http://bower.io/), as mentioned above, to add Leaflet to my project.  It would be prudent to become familiar with Bower and its dependencies since many common packages can be easily installed with its use.  Dependencies for Bower include [Node and npm](https://nodejs.org/) and [Git](http://git-scm.com/).  

Using command line, inside my working directory, I entered the following:

	bower install leaflet
		
You will notice a new folder in your working directory called *bower_components* that contains the necessary Leaflet files for your project.  Therefore, the Leaflet CSS link in the *head* section of your index.html would be referenced as:
	
	<link rel="stylesheet" href="./bower_components/leaflet/dist/leaflet.css" />

and the Leaflet JavaScript link at the bottom of the *body* section would be referenced as: 
	
	<script src="./bower_components/leaflet/dist/leaflet.js"></script>


![MIT-campus-coffee](/images/MIT_campus_coffee.png)		

	

	
