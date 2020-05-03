### Flex-item properties

- order
- flex-grow
- felx-shrink
- flex-basis
- flex
- alig-self

---

#### order property

The flex items are placed in the container in the same order they apper in the code.

By default the value of order property is set to zero for all items, we can change to 1,2,3..so on.


#### flex-grow property

This property defines what amount of space inside flex container the items should take up, by defaulut the items takes spacethat is required to fit the content of the item.

so default value of flex-grow property for all flex-item is set to zero.


#### flex-shrink property

This property defines the amount of shrink-size accepted by flex-item when we reduce the width of the browser.
The defalut value of flex-shrink: 1;


#### flex-basis property

This property specifies the intial space taken by flex-item, the defalut value is set to order that means flex-items takes only that much space that is suffecient to accomdate its content.

We can set the value in px,rem and % also.


#### flex property

This property is a shorthand for the combination of flex-grow, flex-shrink and flex-basis.

#### flex-self property

This property specifies the aligment of individual flex-item along the cross-axis.
By default value set to auto, it means the item follows the alignment according to the parent container align-items property.

Possible-values are:

- auto
- flex-start
- flex-end
- center
---
