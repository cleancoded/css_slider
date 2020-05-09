Cleancoded CSS Slider
==========

Cleancoded Pure CSS, simple slider.


## Supported browsers

- Chrome `(tested only on 30)`
- Firefox `(tested only on 24)`
- IE
	- `9`   No transitions
	- `10+` Works perfect
- Opera `(tested only on 12)`


## Installation

- Include the CSS stylesheet at the end of `<head>` element:

	```html
	<link rel="stylesheet" href="/path/to/csslider.css" />
	```            
- Put code into webpage:
	
	```html
	<div class="csslider">
	    <input type="radio" name="slides" id="slides_1" checked />
	    <input type="radio" name="slides" id="slides_2" />
	    <input type="radio" name="slides" id="slides_3" />
	    <input type="radio" name="slides" id="slides_4" />
	    <input type="radio" name="slides" id="slides_N" />
	    <ul>
	        <li>Content of slide 1</li>
	        <li>Content of slide 2</li>
	        <li>Content of slide 3</li>
	        <li>Content of slide 4</li>
	        <li>Content of slide N</li>
	    </ul>
	    <div class="arrows">
	        <label for="slides_1"></label>
	        <label for="slides_2"></label>
	        <label for="slides_3"></label>
	        <label for="slides_4"></label>
	        <label for="slides_N"></label>
	        <label for="slides_1" class="goto-first"></label>
	        <label for="slides_N" class="goto-last"></label>
	    </div>
	    <div class="navigation">
		    <div>
	        	<label for="slides_1"></label>
	        	<label for="slides_2"></label>
	        	<label for="slides_3"></label>
	        	<label for="slides_4"></label>
	        	<label for="slides_N"></label>
		    </div>
	    </div>
	</div>	
## Local configuration
If you want to change configuration for specific element you must override default config. 
For instance if you have an element with id `#my-slider` and you want to change:
- arrows color

```css
#my-slider .arrows label {
   border-left-color: red;
   border-right-color: red;
}
```
- inside navigation border

```css
#my-slider.inside .navigation label {
    border: 1px solid red;
}
```
