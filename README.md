<h1>Color Picker.js</h1>
	<h2>color picker uses only javascript</h2>
	Before using the color picker component referring to add to the project file (<b>colorPicker.js</b>)
	<br>
	<div class="code">
		&lt;script type="text/javascript" src="<b>colorPicker.js</b>"&gt;&lt;/script&gt;
	</div>


	very easy to convert any element of a web page in the button to select the color for this you need only add that element class (<b>colorPicker</b>)

	<div class="code">
		&lt;div class="<b>colorPicker</b>"&gt;select color&lt;/div&gt;
	</div>

	<hr>
	<h3>attributes:</h3>
	<ul>
		<li><b>value</b> - initializes the color picker color also keeps the color result</li>
		<li><b>cpWidth</b> - sets the width of the color picker</li>
		<li><b>cpHeight</b> - sets the height of the color picker</li>
		<li><b>bgColor</b> - dynamically changes the color of the call button color picker</li>
	</ul>
	<div class="btn colorPicker" value="#ffffff" cpWidth="160" cpHeight="160" bgColor>select color</div><br><br><hr>
	<h3>attributes:</h3>
	<ul>
		<li><b>hsvText</b> - displays the color code in the HSV</li>
	</ul>
	<div class="btn colorPicker" value="#e5ff00" cpWidth="160" cpHeight="160" bgColor hsvText>select color</div><br><br><hr>

	<h3>attributes:</h3>
	<ul>
		<li><b>cpXOff</b> - X sets the offset relative to the call button color picker</li>
		<li><b>cpYOff</b> - Y sets the offset relative to the call button color picker</li>
	</ul>
	<div class="btn colorPicker" value="#007eff" cpXOff="10" cpYOff="10" bgColor>select color</div><br><br><hr>

	<h3>attributes:</h3>
	<ul>
		<li><b>cpX</b> - establishes a fixed position for the X color picker</li>
		<li><b>cpY</b> - establishes a fixed position for the Y color picker</li>
	</ul>
	<div class="btn colorPicker" value="#e40000" cpX="300" cpY="500" bgColor>select color</div><br><br><hr>

	tested only on chrome and firefox!
