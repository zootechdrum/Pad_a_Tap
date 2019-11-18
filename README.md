# Pad-a-Tap project
This project is inspired by Colt Steele's course on Udemy.com

![](images/drum.gif)

## Technologies Used

1. HTML5
2. paper-full.js
3. CSS
4. Javascript 


##Snippet of Code
The below code will rotate and and adjust the color of the square on the Canvas.


```Javascript

	function onFrame(event) {
		for(var i = 0; i < rect.length; i++){
			rect[i].rotate(3);
			rect[i].scale(.9);
			rect[i].strokeColor.hue += 6;
			rect[i].position.y += -6
		}
	}
```