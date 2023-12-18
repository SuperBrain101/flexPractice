# flexPractice
Practices of using `display:flex;` (all ideas are created by another on from Youtube)
## Flex-wrap
### Use `flex-wrap:wrap;` 
- for responsiveness and...
- to ensure that the items move to a new line if the size can't fit webpage(so it doesn't make the size smaller instead)
## Order
### use `order:#;`
- When you want to switch items...
- it's kinda like picking the item like :nth-of-type(#) and then that number becomes whatever has the order feautre in the items
  ### for example:
  - /* First elemnt of class .items using :nth-of-type()*/
-  ` .item:nth-of-type(1){
  /*Now we want the first item to become the third item, so pretty much the first item will have a blue background and will become the third item (use with a FLEX ITEM ONLY)/*
  order:3;
  }`

-  `.item:nth-of-type(3){
  background-color:blue;
  }`
