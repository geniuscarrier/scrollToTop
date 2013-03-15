scrollToTop
===========
A scrollToTop jQuery Plugin

How to use:
-------------------------

1. Include necessary JS files

	```
	<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
	<script src="js/jquery.scrollToTop.min.js"></script>
  	```

2. Add scrollToTop CSS file

	```
	<link rel="stylesheet" href="css/style.css" />
	```

3. Create a link element

	```
	<a href="#top" id="toTop"></a>
	```

4. Fire plugin using jQuery selector

	```
	$(function() {
		$("#toTop").scrollToTop();
	});
	```

5. Option: pass in a number to control scroll speed. Default: 800.

	```
	$(function() {
		$("#toTop").scrollToTop(1000);
	});
	```

Compatibility:
-------------------------

* IE7 and above, Firefox, Chrome, Safari and Opera
	
Live Demo:
-------------------------

* [Homepage](http://www.geniuscarrier.com)
* [Demo](http://www.geniuscarrier.com/demo/scrollToTop/scrollToTop.html)
