# Variables  

We are going to practice using built-in and user created variables today! Variables are containers for information that can change.

Some variables are system variables like `mouseX`, `mouseY`, `height`, and `width`. These are variables tha are built into the system and can be accessed by the user when writing our programs. For example, to plot a shape at the middle of the screen we could say:

```javascript
// Plots a circle at half the width of the canvas and half the height of the canvas. This corresponds to the center of the canvas.
ellipse(width/2, height/2, 60);
```

We may also want to declare our own variable that can be used in the program. We use this using the keyword `var` and giving the variable a unique name. The example below plots 4 circles using a user create `yPos` variable:

```javascript
// Declare a variable ouside the function
var y = 70;

function draw() {
	// Use the variable inside the draw function
	ellipse(50, y, 25);
	ellipse(100, y, 25);
	ellipse(150, y, 25);
	ellipse(200, y, 25);
}
```

## Task: Do You Want to Build a Snowman?
![](https://media.giphy.com/media/WFJAqzg0hZ6dq/giphy.gif)
**GOAL**: Draw a snowman using your knowledge of p5 and variables!.

**REQUIREMENTS**: You should:
- At least 3 ellipse(), correctly layered so that it looks like one is resting on top of the other.
- At least two line() for the arms
- Use created variables (e.g. x and y) and built-in variables (mouseX, width, heigth, etc.) to place shapes on the page. 
- What shape do you think I used to make the nose? Use [p5✱ Reference](https://p5js.org/reference/) to figure out how to make this shape.
