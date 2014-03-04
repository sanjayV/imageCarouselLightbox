ImageCarouselLightbox
=====================

Display image large view in lightbox with carousel.


Structure :-

Include "lightbox-carousel.js" and "lightbox-carousel.css" in header.

<pre>
&lt;link href="css/lightbox-carousel.css" type="text/css" rel="stylesheet"&gt;
&lt;script type="text/javascript" src="js/lightbox-carousel.js"&gt;&lt;/script&gt;

&lt;!-- HTML --&gt;
&lt;div class="mainClass"&gt;
	&lt;div class="innerClass"&gt;
		&lt;img title="Image one" src="image1.jpg" /&gt;
	&lt;/div&gt;
	&lt;div class="innerClass"&gt;
		&lt;img title="Image two" src="image2.jpg" /&gt;
	&lt;/div&gt;
	&lt;div class="innerClass"&gt;
		&lt;img title="Image three" src="image3.jpg" /&gt;
	&lt;/div&gt;
&lt;/div&gt;


&lt;!-- Javascript --&gt;
&lt;script type="text/javascript"&gt;
	$(function(){
		$(".mainClass").lightboxCarousel();
	})
&lt;/script&gt;
</pre>

Image title will display in popup header.
