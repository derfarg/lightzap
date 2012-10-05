LightZAP
by Szalai Mihaly ( origional by Lokesh Dhakar [ Lightbox ] )

SETUP
	1. Upload js, css, icons folder to FTP, and paste the next three line to HTML header region.
		<script src="js/jquery-1.7.2.min.js"></script>
		<script src="js/lightzap.js"></script>
		<link href="css/lightzap.css" rel="stylesheet"/>
	2. Add a rel="lightzap" attribute to any link tag to activate LightZAP.
		<a href="images/image-1.jpg" rel="lightzap[group_name]" title="my caption" desc="description" by=”author” by-href=”www.byauthor.org><img src=”images/image-1_thumb.jpg></a>
	href = the fullsize image path
	rel = lightzap[group_name] or whitout [...]
	src = thumbnail image path
	title = the image caption ( optional )
	desc = description ( optional )
	by = the link text ( eg.: author ) ( optional )
	by-url = the link url ( eg.: author webpage ) ( optional )

SETTINGS
	In js/lightzap.js
