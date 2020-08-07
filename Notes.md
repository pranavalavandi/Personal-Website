### Divs & Spans



- Block and inline elements. 
- Block elements take entire with of page. Inline elements take as much as needed. Can have 2 inline elements next to each other but not 2 blocks
- `<p> <text> </p>` . Paragraphs are block elements
- Spans: inline containers. Divs are block containers
- Span: `<span> </span>` 
- Div: `<div> </div>` 

### Meta Tags

- e.g. `<meta charset - “UTF-8”>` .
- Used to define data about data
- `<meta name = “description” content - “your description” >`
- `<meta name = “author" content = “Mike" >`
- `<meta name = “viewport” content = “width = device-width, initial-scale = 1.0”`



CSS Notes

/# = class

. = id

#### Flex-Box

- display: flex; in the parent 
- flex-direction: column / column-reverse / row / row-reverse
- flex-wrap: wrap / no-wrap; - wrap moves it to a new row if there is overflow
- justify-content: flex-start /flex-end/center;  where it starts. :space between even spaces in between. space-around: space in between containers and around them.
- align-items: flex-start /flex-end/center; where the containers start and doesn't stretch the entire way\
- The flex property can do the following in one line `flex: <grow> <shrink> <basis>` 
  - flex-basis: <>; = minimum width of an item
  - flex-grow: <>; amount of extra space that you want
  - flex-shrink:   <>; amount to shrink when we rescale the window. 0 is no shrink so the container stays the same 
- to align individual items `align-self: < flex-start /flex-end/center>` 

#### Grids

- Grid is focused on providing tools for both dimensions; width and height, whereas Flexbox is focused on width alone 
- `display: grid;` in the `.grid-container` (parent of each container which is .grid-item)
- `grid-template-columns: <>`; write the width of each column you want. `grid-template-rows: <>` same thing. set to `auto`, divides the space evenly 
-  `grid-column-gap/grid-row-gap: <>`  space between each row/column. done in `grid-gap: <row> <column>`
- `grid-column/grid-row: <start> /<end>` , start and end of the column. e.g. 1/3 would place the first container in 1 and end and at 3, if you align left then column 2 would be empty. `1/3` same as `1/ span 2`. Start point and how many rows/columns it spans
- `grid-area: 2/1/span 2/span 3 ` . `rowstart/columnstart/rowend/ columnend `

