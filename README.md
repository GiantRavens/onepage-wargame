# onepage-wargame
Simple, easily modifiable hex boardgame in a webpage with only JS and CSS.

https://user-images.githubusercontent.com/914790/210110862-84a05608-912c-4555-bd0e-e566d75652d2.mov

## overview
One Page Wargame is an example of using easily modifiable, well understood HTML, CSS, and JS to instantly set up a wargame of your choice and design.

Compared to drawing hexes on a canvas element - individual hexes are far easier to address and add custom css and image backgrounds to.

Each hexagon is a div element, and each unit is a draggable div. Look at the CSS and JS examples to render your unit counters as you like.

After defining the rows and columns of your mapboard, the hexes are written in Javascript, and hex ID's are added as well.

## todo
  -TODO: show hex terrain example using the assets in /img
  -TODO: add more unit examples
  -TODO: clean up draggable JS to now show div artifacts underneath the dragged element
  -TODO: make dragged units snap to nearest hex center
  -TODO: add actions to 'flip' a unit
  -TODO: add actions to mark or flag a unit with a marker like 'fired'
