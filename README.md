# xml2object
require "Xml2Object.php";

$xml = '<?xml version="1.0" encoding="UTF-8" ?>
<export>
	<data>
		<data1>Telephone</data1>
		<data2>220</data2>
	</data>
	<data>
		<data1>Tele</data1>
		<data2>20</data2>
	</data>
	<data>
		<data1>Yep</data1>
		<data2>120</data2>
	</data>
	<data>
		<data1>Frigo</data1>
		<data2>20</data2>
	</data>
	<data>
		<data1>DVD</data1>
		<data2>89</data2>
	</data>
	<data>
		<data1>Camescope</data1>
		<data2>35</data2>
	</data>
</export>';

//parse xml 2 object
$object= \Xml2Object\Xml2Object::getObjectXml($xml);