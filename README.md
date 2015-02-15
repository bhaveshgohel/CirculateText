# CirculateText
CirculateText JQuery plugin to bend any text on circular shape of desired radius.

# Dependency:
Since CirculateText is a Jquery plugin so Jquery is an obvious dependency you must include. Additionally the plugin also uses the jqueryrotate to rotate the text so make sure to include that as well! You can find jqueryrotate here:
https://code.google.com/p/jqueryrotate

# Usage
Simply include the jquryrotate and then include the circulatetext scripts in your html document:

<script src="js/jquery.js"></script>
<script src="js/jQueryRotateCompressed.js"></script>
<script src="js/circulateText.js"></script>

Now you can initialize the plugin on any desired text you want. Eg :

<!-- The text you want to ciculate -->
<div id="circulateThis">
  Ciculate Me
</div>

<!-- Incude the scripts : Jquery,Jqueryrotate,Circulate -->
<script src="js/jquery.js"></script>
<script src="js/jQueryRotateCompressed.js"></script>
<script src="js/circulateText.js"></script>

<!-- Initialize the plugin -->
<script>
	$(".circulateText").circulateText(200);
</script>

# Options
CiculateText provides two options to rotate your text:
radius: radius of the circle the text sits on
space: this is optional, if provided it will determine the spaces between the characters

$(".circulateText").circulateText(radius,space);
