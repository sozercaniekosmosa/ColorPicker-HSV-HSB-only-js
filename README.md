Color Picker.js HSV / HSB
	
color picker uses only javascript
	
Before using the color picker component referring to add to the project file (colorPicker.js)
	
		<script type="text/javascript" src="colorPicker.js"></script>


very easy to convert any element of a web page in the button to select the color for this you need only add that element class (colorPicker)

		<div class="colorPicker">select color</div>


	
attributes:

value - initializes the color picker color also keeps the color result
cpWidth - sets the width of the color picker
cpHeight - sets the height of the color picker
bgColor - dynamically changes the color of the call button color picker
	
	<div class="btn colorPicker" value="#ffffff" cpWidth="160" cpHeight="160" bgColor>select color</div>
	
attributes:

hsvText - displays the color code in the HSV
	
	<div class="btn colorPicker" value="#e5ff00" cpWidth="160" cpHeight="160" bgColor hsvText>select color</div>

attributes:

cpXOff - X sets the offset relative to the call button color picker
cpYOff - Y sets the offset relative to the call button color picker
	
	<div class="btn colorPicker" value="#007eff" cpXOff="10" cpYOff="10" bgColor>select color</div>

attributes:

cpX - establishes a fixed position for the X color picker
cpY - establishes a fixed position for the Y color picker
	
	<div class="btn colorPicker" value="#e40000" cpX="300" cpY="500" bgColor>select color</div>

tested only on chrome and firefox!
