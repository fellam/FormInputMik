The FormInputMik extension enables the edit or generation of a page using 
one Semantic Form Input.

For details see https://www.mediawiki.org/Extension:FormInputMik

Please help me improving this project making a donation:
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="UBX4YGMGGWHEN">
<input type="image" src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal – The safer, easier way to pay online.">
<img alt="" border="0" src="https://www.paypalobjects.com/en_GB/i/scr/pixel.gif" width="1" height="1">
</form>

== Dependencies ==

This extension was developed for MediaWiki 1.17 with at least Semantic
MediaWiki 1.5.3 and Semantic Forms 2.4 installed. Other version might work, but
are not tested.

== Installation ==

1. Download the package. Unpack the folder inside /extensions (so that the files
   are in /extensions/FormInputMik, rename the folder if necessary).

2. In your LocalSettings.php, add the following line to the end of the file:

   require_once("$IP/extensions/FormInputMik/FormInputMik.php");

