# what-i-learned-week-4

##  `Strings`

A JavaScript `string` stores a series of characters like "Patrick Navarre". 

A `string `can be any text inside double or single quotes: 

let carName1 = "Subaru Outback"; 
let carName2 = 'Jeep Wrangler'; 

`String indexes` are zero-based: 

The first character is in position 0, the second in 1, and so on.


## `String Methods `

* String Length: 
The length property returns the length of a `string`.

str.`length`;

* `indexOf`:
Finding a `string` in a `string`.

str.`indexOf`();

---------

* `lastIndexOf`:
The `lastIndexOf` method returns the index of the **last** occurrence of a specified text in a string.

str.`lastIndexOf`();

----------

* `slice`

The `slice` methode extracts a part of a string and returns the extracted part in a new string.  The method takes 2 parameters: the start position, and the end position (end not included).

str.`slice`();

`let` str = "Apple, Banana, Kiwi";

`let` res = str.`slice`(7, 13);

The result of res will be:

Banana

----------

* `toUpperCase` and `toLowerCase`

A string is converted to either *uppercase* or *lowercase*.

str.`toUpperCase`

str.`toLowerCase`

----------


* `charAt`

The `charAt` method returns the character at a specified index (position) in a string.

*Example*:

`let` str = "HELLO WORLD";

str.`charAt`(0);            returns H


--------

## `Arrays`

An array is a special variable, which can hold more than one value at a time.

If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

`let` car1 = "Jeep";

`let` car2 = "Ford";

`let` car3 = "Chevrolet";

Creating an Array
Using an array literal is the easiest way to create a JavaScript Array.

Syntax:

`let` array_name = [item1, item2, ...];    


**Example**:

`let` cars = [ 'Jeep' ,  'Ford' , 'Chevrolet' ];


### Access the Elements in an Array

You can access an array element by referring to the **index number**[0].

* `math.abs` - the `math.abs` method returns the absolute value of a number.  


When using an array you typically use `const` instead of `let`.

* `.push`

The `.push` method adds new items to the end of an array, and returns the new length.

* `.pop`

The `.pop` method removes the last element of an array, and returns that element.  

* `.splice`

The `.splice` method adds/removes items to/from an array, and returns the removed item(s).

The `.splice` method DOES change the original array.  

* `.concat` 

The `.concat` method is used to join two or more arrays.  This method does NOT change the existing arrays, but returns a NEW array, containing the values of the joined arrays.






 


 

 

