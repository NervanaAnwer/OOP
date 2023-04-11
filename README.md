# OOP
<div>
  
## Assignment 1 (Colored Box)
Declare and implement a class ColoredBox which stores a box of characters (Dynamic 2D array). <br />
The class has private member variables that are attributes of the box like the box itself(which is a dynamic 2D array of characters), a character that forms the box, dimensions of the box (length and width) and color of the box (integer).<br />
The class also has a static member variable that stores the biggest area among the boxes objects of the class.<br />

### The member functions that needs to be implemented:
1- A constructor or constructors that takes length and width of the box (mandatory), the character that constructs the box (optional and if not provided the character is ‘#’), the color of the box (optional and if not provided the color is white).<br />
2- Getters and setters for the building block character and color of the box.<br />
3- A display function that prints the box.<br />
4- A function displayTransposed that displays the box transposed.<br />
5- A function displayWider that displays the box on a wider scale.<br />
6- A function that takes a color as a parameter and displays the box as a chess board where a character is displayed with the original color of the object, and the next character is displayed with the parameter color. For example let’s say we have a box object (boxObj) with dimensions 4 and 7, the character ‘&’, and the color 14 (yellow).<br />
7- A function getArea that returns the calculated area of the box (if for ex. Length = 10 and width = 3, then area = 30).<br />
8- A static member function getMaxArea that returns the value of the static member variable.<br />
9- A destructor that frees dynamic memory.<br />
#### Test case:
<img src=https://user-images.githubusercontent.com/105722419/231208516-5f2fac5e-1bfe-4cb6-b2c2-e522f12cf128.jpg width="600" height="600">
  
</div>
 
<div>
  
 ## Assignment 2 
in this program we are trying to facilitate online shopping so we have infromation about the seller such as his name, email and the maximum number of items he can stor we can create more than one seller and store (name ,email & items of seller with max capacity ) & what he have items (id ,name ,price,quantity) can create more than item and then we allow the user to enter some details about any product he wants to buy or sell such as name, price, quantity if this product is already found within the seller so we increment it's quantity if not and there is a space for it we add it with a new id if we want to sell an item we just enter it's name and the quantity we want and if it's not available we will have a message with the amount left from this item if we want to access a certain item and know if it's available or not we enter it's id and all details will appear such as quantity, name, id and price we can also print the seller's info and the products he have in store 
 
</div>

<div>
  
  ## Assignment 3
  Declare and implement 5 classes: FloatArray, SortedArray, FrontArray, PositiveArray & NegativeArray.<br />
 1- The FloatArray class stores a dynamic array of floats and its size. It has:<br />
 -A parameterized constructor that takes the array size.<br />
 -An add method that adds a float at the end of the array.<br />
 -Overloading for the insertion operator << to write the array to a file (ofstream)<br />
 -Overloading for the extraction operator >> to read the array elements from the file (ifstream) and add them to the array.<br />
 -A destructor to deallocate the array<br />
2- The SortedArray inherits from FloatArray. It has:<br />
 -A parameterized constructor that takes the array size.<br />
 -An add method that adds a float at the right place in the array such that the array remains sorted with every add. Don’t add to the array then sort but rather add in the right place.<br />
3- The FrontArray inherits from FloatArray. It has :<br />
 -A parameterized constructor that takes the array size.<br />
 -An add method that adds a float at the front of the array.<br />
4- The PositiveArray that inherits from SortedArray. It has:<br />
 -A parameterized constructor that takes the array size.<br />
 -An add method that adds a float to the array only if it’s a positive number. It then uses the add method of SortedArray.<br />
5- The NegativeArray that inherits from SortedArray. It has:<br />
 -A parameterized constructor that takes the array size.<br />
 -An add method that adds a float to the array only if it’s a negative number. It then uses the add method of SortedArray.<br />
  ### Test Case:
  #### Input File: 
  <img src=https://user-images.githubusercontent.com/105722419/231214715-d336829f-7553-4336-9eef-eaef795d22c2.png  ><br />
  ####  Output file:
  <img src= https://user-images.githubusercontent.com/105722419/231215234-b62998f8-81fc-44b1-ab63-4a68ebd66be9.png  >
 
  </div>
