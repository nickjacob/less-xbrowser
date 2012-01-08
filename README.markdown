# X-Browser LESS
## README

Simple set of parametric mixin classes to be used to provide cross-browser compatibility to CSS3 styles. Used with the LESS CSS compiler. 

### Usage
1. create a new .less file for your own code
2. add @import 'myfile.less'; to x-browser.less, or @import x-browser.less into your file
3. compile your less!

	#my-div{
		.border-radius(3px);
		.box-shadow(#33ccff);
	}
	
	#awesome-div{
		.box(@faveColor);
	}

### More Info:

* To use less, check out the docs: [lesscss.org](http://lesscss.org/)
* Also check out Bryan Jones' awesome mac LESS app, [codekit](http://incident57.com/codekit/)

