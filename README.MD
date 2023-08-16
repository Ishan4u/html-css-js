# Relative and Absolute Positioning
### Relative
- Relative positioning is
  essentially a way to take an element without removing it from the natural flow of the page and just push or pull
  it a bit to the top the bottom on the left or the right and it doesn't affect the rest of the elements on the page.  

### Absolute
  - position:absolute is radically different from position relative position absolute aligns the element in relation to its parent element  

  - absolute positioned element to honor the positioning of its parent the parent element must have position relative  
  ![html-position](https://github.com/Ishan4u/clean-blog/assets/111623376/396168d5-c7a8-42f3-9475-782f2c04c95f)

  # ::after / ::before  / ::hover

  # CSS Display Property  
  ## 1. inline
  - width and height values were ignored
  - vertical margin and padding values be ignored
  - horizontal margin and padding is observed  

 > ### default element apply inline
 > - span
 > - image  


  ## 2. block
  - width and height values were observed
  - vertical margin and padding values be observed
  - horizontal margin and padding is observed

   > ### default element apply inline
   > - div
   > - heading tags  

## 3. inline-block
- custom width possibly a custom height or we want it to have padding so in our CSS will say display:inline-block

## 4. flex
- The flex box is CSS Layout Design build using display:flex property Flexbox is used to build one-dimensional layout in css. One dimensional means flexbox can build layout in one dimension ( either row or column ) at one time. For two-dimensional layouts, use CSS Grids that can handle both row and column.  
- learn more flex properties [Flex property](https://tutorial.techaltum.com/css-flexbox.html#:~:text=Flex%20is%20the%20value%20of,auto%20width%20and%20auto%20height.)

# Flexbox and Grid


`display: grid;`  

`grid-template-columns: 300px 200px ` = first item 300px width, 2nd item 200px width  
`grid-template-columns: 25% 75% ` = first column 25% width, 2nd column 25% width  
`grid-template-columns: 1fr 1fr 1fr ` = three colulmn divide equal part in available space  
`grid-template-columns: repeat(3,25%) ` = three times 25% width  
`grid-template-columns: repeat(auto-fit,minmax(300px, 1fr)) ` = columns automatically adjust to fit a minimum width of 300 pixels while evenly distributing the available space.  

``

# Float
- The CSS float property is used to place an element to the left or right side of its container, allowing other elements to wrap around it. 
The syntax is as follows:
```css
element {
  float: none | left | right | inherit;
}
```
> none: The element does not float. This is the default value.  
> left: The element floats to the left of its container.  
> right: The element floats to the right of its container.  
> inherit: The element inherits the float value from its parent element.  

- Here's an example of using the float property:
```css
img {
  float: right;
}
```
> - In this example, the image will float to the right of its container, and any text in the container will wrap around the image.

- **Modern Alternatives: Flexbox and Grid**


