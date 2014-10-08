parallax-plugin
===============

Plugin to create parallax pages easily

<b><u>HTML</u></b>

	<div id="parallax-1" parallax-enabled="true" parallax-direction="-" parallax-speed="5" parallax-xpos="left"></div>
	<div id="parallax-2" parallax-enabled="true" parallax-direction="+" parallax-speed="10"></div>
	<div id="parallax-3" parallax-enabled="true" parallax-direction="-" parallax-speed="7" parallax-xpos="50%"></div>

<b><u>CSS</u></b>

Following is the sample css. Change your own css as per the requirement. With help of this plugin you can create different layers of elemets giving it absolute position to get a 3D like parallax effect. e.g Diamonds are moving up and down on the window scroll.

	#parallax-1 {
	  width: 100%;
	  min-height: 1000px;
	  height: 1000px;
	  position: relative;
	  background: url("file-path") no-repeat 0% 0% fixed;
	  background-size: cover;
	}

<b><u>JS</u></b>

Include the <b>"ezplex"</b> reference

	<script src="js/ezplex.js"></script>
	<script>
		$(document).ready(function(){
			$('body').ezplex();
		});
	</script>

It will take all the elements with defined attributes

That's it!! you have parallax page.. You can create it in whatever manner you like. I am just trying to provide a little help.

-------------------------------------------------------------------------------------------------------------------------------

<b><u>Options/How to</u></b>

All the Attributes are optional but one attribute is required

<b><u>Required</u></b>

parallax-enabled="true" OR parallax-enabled="false"

<b><u>Optional</u></b>

(1) parallax-direction="-" // By default it's set to minus. minus = y-position downwards and plus = y-position upwards <br />
(2) parallax-speed="10" // By default it's set to 10. <br />
(3) parallax-xpos="left" // By default it will take current x-position of background. parallax-xpos takes values in persantage, pixels and string. eg. "50%", "200px" OR "center". <br />


Any suggestions or comments are highly appreciated

- Bhaumik Mehta
