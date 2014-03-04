ImageCarouselLightbox
=====================

Display image large view in lightbox with carousel.


Structure :-

Include "lightbox-carousel.js" and "lightbox-carousel.css" in header.

<link href="css/lightbox-carousel.css" type="text/css" rel="stylesheet">
<script type="text/javascript" src="js/lightbox-carousel.js"></script>


<!-- HTML -->
<div class="mainClass">
	<div class="innerClass">
		<img title="Image one" src="img/carousel/Pleiades_large.jpg" />
	</div>
	<div class="innerClass">
		<img title="Image two" src="img/carousel/_n02o5mji9.jpg" />
	</div>
	<div class="innerClass">
		<img title="Image three" src="img/carousel/_g6nnejt4o.jpg" />
	</div>
</div>

<!-- Javascript -->
<script type="text/javascript">
	$(function(){
		$(".mainClass").lightboxCarousel();
	})
</script>

Image title will display in popup header.
