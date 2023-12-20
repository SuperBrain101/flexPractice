# flexPractice
### flex Basis
- esentially is the width; you can even use it instead of `width:#;`
- flex basis is , however,, used for  the basis(or starting point) of the width for other flex properties
- You can add flex basis anywhere that a width would be(essentially at any point of an element(for a flex so item or container)
- use by writing for ex: `flex-basis:300px;`
### flex grow 
- by using `flex-grow:#;` (where # is 0/DEFAULT,1,2,3)
- we can have a rate of growth by '#'
- so when we have a flex-basis(or starting width) it grows by '#' responsively...specifically minimized screen is flex-basis and the window getting bigger means  flex-growth/ elment grows
  ### flex shrink
  - similar to flex growth but shrinks instead of grows
  - ( `flex-shrink:#;` )
  -  ex: `flex-shrink:2;`
### flex property / putting it all together...
- the flex property allows you to adjust the growth rate,shrink rate and the flex basis all on one line (much like the border property)
-  *Remember that 0 is the default/nothing happens with flex-growth and flex-shrink
- The flex property looks like this: `flex: grow# shrink# basis#
- For an example this flex property is telling the element to have a growth rate of 1 no shrink and a flex basis of 25px:
- `flex: 1 0 25px;`
