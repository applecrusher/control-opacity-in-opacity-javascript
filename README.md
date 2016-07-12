# control-opacity-in-opacity-javascript

In CSS, you cannot control an element's opacity within an element that has opacity already defined. An example can be found here:

https://jsfiddle.net/bwwd0oao/

You have the element with the white background you want to show clearly with 1.0 opacity given it's parent already has .7. It just doesn't work. This library aims to fix that issue by using javascript to render the elements in their absolute positions outside of the div. 

Proposed Solution:

Use Javascript to make a duplicate of element outside of it's parent element, and then setting the absolute position of it's 
