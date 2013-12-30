# Equal Heights Responsive 

A simple jQuery plugin that allows you to set a group of elements height to that of the height of the tallest element amongst them.

*	Author: John Faldo johnfaldo@gmail.com

## Example 

You can view a working example at: http://optdesign.co.uk/equal-heights-responsive/

## Requirements 

*	jQuery http://jquery.com/download/
*	underscore.js http://underscorejs.org/ 

##Options 

*	responsive: true/false  - default is *false*, true enables responsive behavior
*	animate:  true/false  - default is *false*, true enables animations on resize 
*	animateSpeed: integer - default is *400*ms 

## Usage 

Default:

```

$('.elements').equalHeights();

```

With responsive behavior:

``` 

$('.elements').equalHeights({
	responsive:true
})

```

With animation, speed is default to 400ms:

```

$('.elements').equalHeights({
	animate:true
})

```

With responsive, animation and custom animation speed:

```

$('.elements').equalHeights({
	responsive:true,
	animate:true,
	animateSpeed:500
})

```

## File 

The plugin is located: js/equal-heights-responsive.js

Minified version:      js/equal-heights-responsive.min.js 


## Cross Browser Compatibility

Tested and working in *Chrome* Version 31.0.1650.63 m, *Firefox* 25.01, *Opera* 18.0, *IE* 7,8,9,10




