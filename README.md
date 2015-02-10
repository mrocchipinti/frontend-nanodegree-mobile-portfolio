frontend-nanodegree-website_optimization
===============================

Requirements
- Web browser support for Javascript
- Keyboard & mouse

Installation
- Expand and copy all files.  Directory tree must be maintained.
- Open index.html in web browser.

Controls
- Keyboard & mouse 

Optimizations
- Images
	Images were re-sized to fit the specific dimensions required by the layout.
	An images shrinking program was used on all images to ensure the smallest possible size.
- Minification
	Both JavaScript and CSS files were minified to reduce whitespace characters.
- External Refernces
	External references to CSS and JS were moved in-line to remove the need for secondary request waiting.
- Media tags
	Media tags were added to reduce the about of CSS imported for a specific media type.
- Viewport
	Added viewport meta tag.
- JavaScript optimization
	changePizzaSizes() was modified to get the list of elements and calculate the the new width only once rather than for each element.
	updatePositions() was modified to calculate the new scroll positon once rather than for each element.