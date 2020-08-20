# Class 12 Reading Notes

## Charts.js API
An HTML5 plug in that uses canvas elements to draw graphs onto the page. You can use different techniques to create animated bar, line and pie graphs. 
## Canvas APIs 
Canvas elements only have width and height. Always supply an ID attribute to your canvas elements. You can change the margins and padding like a normal img element. Canvas is easy to display fallback content for older browsers. Just put the fallback ontent between the canvas tags and it will be displayed if the browser doesnt support canvas. This is why canvas requires a closing tag. Use getContext('2d') to set the canvas up. Canvas works with a grid system and coordinates. fillRect strokeRect clearRect draw repsective recangles at fillRect(x,y, width, height). X Y specify position on the canvas relative to the origin in the top left corner. 
Create a path. Draw a path. Fill or stroke it to render. The moveTo function acts like picking up the pen when drawing. You can draw straihgt lines with the lineTo metho (x,y). Similar to arc or arcTo. fillStyles and fillStroke let us add color. We  can set transparentcy with the globalAlpha setting. We can change to many different line styles including width and cap. CanvasGradient lets you set graidients and apply fillstyles for colors. We can make patterns with createPattern(image,type). Canvas lets us add shadows too. You can use fillText or strokeText to render text. We can change the font, align and direction of the text.

