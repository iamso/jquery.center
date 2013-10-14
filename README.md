jQuery Center Plugin
====================
Simple jQuery Plugin to center an element. 

Found this plugin on the internet some time ago. I don't know who wrote it, but I wanted to make it available for others.

Setup
-----
Setup with default options.
```javascript
$(function(){
    $('#centered_object').center({
		inside:window, // element, center into window
		transition: 0, // millisecond, transition time
		minX:0, // pixel, minimum left element value
		minY:0, // pixel, minimum top element value
		vertical:true, // booleen, center vertical
		withScrolling:true, // booleen, take care of element 
inside scrollTop when minX < 0 and window is small or when 
window is big
		horizontal:true // booleen, center horizontal
	});
});
```

License
-------
Don't know, I suppose MIT.