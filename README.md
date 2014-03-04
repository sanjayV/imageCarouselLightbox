ImageCarouselLightbox
=====================

Display image large view in lightbox with carousel.


Structure :-

Include "lightbox-carousel.js" and "lightbox-carousel.css" in header.

<pre>
<link href="css/lightbox-carousel.css" type="text/css" rel="stylesheet">
<script type="text/javascript" src="js/lightbox-carousel.js"></script>

<!-- HTML -->
<div class="mainClass">
	<div class="innerClass">
		<img title="Image one" src="image1.jpg" />
	</div>
	<div class="innerClass">
		<img title="Image two" src="image2.jpg" />
	</div>
	<div class="innerClass">
		<img title="Image three" src="image3.jpg" />
	</div>
</div>


<!-- Javascript -->
<script type="text/javascript">
	$(function(){
		$(".mainClass").lightboxCarousel();
	})
</script>
</pre>

Image title will display in popup header.
