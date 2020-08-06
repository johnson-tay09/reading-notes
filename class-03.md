# Class 3 Reading Notes
## <i>HTML & CSS</i>
## Chapter 3: “Lists” (pp.62-73)
- **List types:** There are ordered lists for making lists with a numerical hierarchy and Unorded lists for arbitrary bulleted lists. Both of these lists use li for list item. Definition lists for terms followed by their definition and use dt for term and dd for definition.
- **Nested lists:** When you add a new list inside an li tag creating a new sub list. These items will be displayed indented farther than the parent list.

## Chapter 13: “Boxes” (pp.300-329)
- **Box settings** You can set the dimensions of your box length, width, and height with %, px or ems. Percentages and ems are more flexible as they are relative and will work on more devices. Max width and min width let you put limits on how wide your box can get. This is helpful to keep text from stretching across big displays or becoming too compact on small ones. The same applies to min height and max height.
- **Overflow** Tells the browser what to do when the content is too big for its box. Hidden will hide any excess content. Scroll adds a scroll bar to allow the reader to see all the content even if the box is too small!
- **Border properties** Can be given in 'thin', 'medium' & 'thick' or you can specify pixels. The style of the border can be set to solid, dotted, dashed, doubled, groove, ridge, insert, outset and can be separated by each (side border-style-left...). Border colors can be set all at once or individually like border stlye and you can short hand it by border-color; color1, color2, color3, color4.
- **Centering** To center a box you must set a width so it doenst take up the whole page and then you can set the left and right margins to auto. Block level and inline are translatable between each type.
## <i>JavaScript & jQuery</i>
## Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)
- **Arrays** Arrays can store more than one value. They can store numeric, boolean or string values. Arrays have no set length which is an advantage over lists. You can call an item in an array by invoking the variable name with the desired index position. Variable-Name.length represents the number of items in an array. You can overwrite an index in an array like you would any other variable.

## Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)
- **If else statements:** Is an if statement that lets you run one set of code when its true or a different set if its false.
- **Switch statements** Switch statements start with a variable called switch value. Each case following indicates a possible value for the switch and the code it should run if it matches the switch.
- **Loops** Check for a true condition like an if statement but repeatedly. If it is true the code will run. It then check if the condition is still true and will run again until the condition becomes false. For loops let you run code a specific number of times. While loops are for when you dont know how many times you need to run the code and will only exit when the loop condition returns false or a break is hit. Do while loops are just while loops that will always run the code at least once even if the condition is false. For loops are usually used to go through the items in an array.