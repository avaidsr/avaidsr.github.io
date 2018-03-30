A Pen created at CodePen.io. You can find this one at https://codepen.io/simonswiss/pen/zrQNmK.

 A simple experiment to transition a sticky navbar from a `Start` color / size into another color / size.

The navbar has some data attributes in HTML. These are used to add / remove CSS classes to create the CSS transition on scroll.

The scroll event listener is only firing every 100ms (via a setInterval) and only triggers the classes toggle if it actually needs to.

I am pretty sure there are more performant ways of doing this - but as a proof of concept for a modular approach, this is pretty neat! :)