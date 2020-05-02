## Flex container properties


- display
- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items
- align-content

### display property

This property defines the flex container and its mandatory to work with flexbox.

Possible values are:
- flex 
- inline-flex

display: flex  -----> it cretaes the block flex container means the items are placed from left to right in a block container.

dispaly: inline-flex  -----> it creates a inline flex container means the container takes enough width to only accomdate its childrens.


### flex-direction property


This property defines the direction in which the flex items are placed in the container.

Possible values are:
- row
- row reverse
- column
- coulmn- reverse

flex-direction: row -----> it's default value for flex-dirction and places items form left to right that start from main-start.

flex-direction: row-reverse -----> it places the items from right to left that start from main-end.

flex-direction: column -----> it places the items from top to bottom.

flex-direction: column-reverse -----> it places the items from bottom to top.


### flex-wrap property

It is used to control the wrapping of items within the container.

Possible values are:
- no-wrap
- wrap
- reverse-wrap

By default all the flex items in the container are try to fit into a single line, if there is no space the items simply overflows. So if reduces the width of the browser the items begins to shrink but at a moments they are no- longer to view.

flex-wrap: no-wrap -----> by deault flex-wrap set to no-wrap.

flex-wrap: wrap ----->  wrapping takes place automaticlly when requried, items moves to the next row within the container.

flex-direction ----> here the items moves to the top row instead of next row within the container.


here we can wrap the items vertically also but for we need items flex-direction property set to column and container have height.


### flex-flow property

It is a shorthand property of combination of flex-direction and flex-wrap.


### justify content property

It defines the alignment of the flex-items along the main-axis.

Possible values are:
- flex-start
- flex-end
- center
it has some additonal values for space distribution:
- space-between
- space-around
- space-evenly

justify-content: flex-start -----> this is the default value for justify-content. In that flex items are align to the left-end of the container(main-start).

justify-content: flex-end -----> In that flex-items are align to the right end of the container(main-end).items 

justify-content: center -----> In that flex-items are placed in the center of the container.

justify-content: space-between -----> It splict the extra spaces into and added in between of flex-items.

justify-content: space-around -----> It splits the spaces and added around the all the flex-items.

justify-content: space-evenly -----> It splits the space into equal width.


### align-items property

It defines the alignment of the flex-items along the cross-axis. for this we need height of the container.

Possible values are:
- stretch
- flex-start
- flex-end
- center
- baseline

align-items: stretch -----> By default the value is strech, it means the flex-items stretches the entire length of the container.

align-items: flex-start -----> All the items are pushed to the start of the container along the cross-axis.

align-items: flex-end -----> All the items are pushed to the end of the container along the cross-axis.

align-items: center -----> All the items are align to the center of the container along the cross-axis.

align-items: baseline -----> It defines each item text is allign on the same base line in the container,


### align-content property

This property is used to define the alignment of the flex-items during wrapping inside the container along the cross-axis.

Similar to justify-content but it's along with cross-axis.

Possible values are:
- stretch
- flex-start
- flex-end
- space-between
- space-around
- space-evenly

item-content: stretch -----> This is the default value.

item-content: flex-start -----> This aligns the content to the cross-start.

item-content: flex-end -----> This aligns the content to the cross-end.

item-content: center -----> This aligns the content to the cross-start.

item-content: space-between | space-around |space-evenly work similar to justify-content but along with cross-axis.

---