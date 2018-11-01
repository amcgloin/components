# components

This repository is to add any components or code I have worked on for web design. Feel free to use anything I have made.

<h1>Index</h1>
<h3>Interactive Illustrator Java Script</h3> <p>A style guide to make illustrator svgs interactive with dimmable columns and fade in/fade out numbers
<br><br>
To use, create a graph in Illustrator and save as an SVG. Copy the code from the SVG file into a prettifier, then copy it into Brackets.<br><br>Copy the Interactive Illustrator Java Script above the code. Use Command+f to find the 'rect' elements. This are the columns in the graph.
<br><br> 
The code will look like this: 
  
  ```
  <rect x="187" y="283"...
  ```
  
 Add ids counting up so the code will look like this: 
 
 ```
 <rect id="column1" x="187" y="283"..., the next one will be 
 <rect id="column2" x="187" y="283"..., and the next will be 
 <rect id="column3" x="187" y="283"...' and so on.
 ```

<h4>To fade in and fade out text boxes and connecting lines</h4>

Click on the live preview button on the top right of Brackets, and click inspect. A window will open up. Click the top-left button which looks like an arrow on a screen. Click on the text box or line you want to fade in and out. The code where that element is will be shown on the right, in the new window. Find that same code in Brackets, using Command+f will help, and assign the element the desired id: 

```
<g id="numbers1">
<g id="line1">
```
  
  <br><br>
  Make sure paired lines and textboxes have a paired number in their id. In the example code, there is a paired line and textbox above columns two and four. Move the commands relating to the line and textbox to whichever column the box and line are above. Make sure to move  the commands in both mouseenter and mouseout.
  <h4>To add a color change</h4>
    To add color changes, alter the hex codes on the backgroundColor command under mouseenter to whatever you want to color to change to on mouseover. It is currently set to Mustang News green, which is the default color for our graphs. The hexcode in mouseout reverts the color back to Mustang News green, if the color is changed. </p>
<h3>State Funding Test</h3> Application of the interactive illustrator script on a graphic. Open in illustrator and live preview to see how it looks.
<h3>audiotext.html</h3> Audio plays when text is clicked, instead of soundcloud embeds or audio players
<h3>performance.mp3</h3> Sample audio
<h3>Cards</h3> A simple card code to be used for online news content with digestable bits
