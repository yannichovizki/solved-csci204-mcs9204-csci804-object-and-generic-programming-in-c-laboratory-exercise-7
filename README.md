Download Link: https://assignmentchef.com/product/solved-csci204-mcs9204-csci804-object-and-generic-programming-in-c-laboratory-exercise-7
<br>
Task: A template class – Bag (1.0)




Define a template class <strong>Bag </strong>in a file<strong> Bag.h. </strong>A <strong>Bag </strong>is a collection of zero or more elements, in no particular order that may have duplicates. The public interface consists of methods to:

<ul>

 <li>Create a template class</li>

 <li>A function <strong>add()</strong> which can add an element to a <strong>Bag</strong>.</li>

 <li>A function <strong>remove()</strong> which can remove a given element from a <strong>Bag</strong>. If the element is duplicated, only remove the first one.</li>

 <li>Implement the union of two <strong>Bag </strong>objects in an overloaded <strong>+ operator</strong>. The union of two <strong>Bag </strong>objects, b1 and b2, should be a <strong>Bag </strong>object containing elements that belong to b1 or b2. Remember that duplication is fine.</li>

 <li>An insertion operator (&lt;&lt;) that print all the elements in the <strong>Bag</strong>.</li>

</ul>

Implement member functions and insertion operator for the <strong>Bag</strong> in a file <strong>Bag.cpp</strong>. Download the file <strong>testBag.cpp</strong> in which instantiates and initialize two <strong>integer</strong> <strong>Bag </strong>objects and two <strong>double Bag </strong>objects to test your <strong>Bag </strong>class.  Compile the program like g++ testBag.cpp

Run the program like.

./a.out

Number of integers for an integer bag 1: 5

Input an integer: 1 Input an integer: 3

Input an integer: 4

Input an integer: 6

Input an integer: 9

The first integer bag contains:  1 3 4 6 9




Number of integers for an integer bag 2: 3

Input an integer: 1 Input an integer: 6

Input an integer: 8

The second integer bag contains:  1 6 8




Combine two integer bags:  1 3 4 6 9 1 6 8




Input the element that needs to be removed: 1

After the element 1 has been removed, the bag contains 3 4 6 9 1 6 8




Input the element that needs to be removed: 6

After the element 6 has been removed, the bag contains 3 4 9 1 6 8




Number of doubles for a double bag 1: 6

Input a double: 1.5

Input a double: 2.2

Input a double: 3.2

Input a double: 1.5

Input a double: 2.4

Input a double: 2.2

The first double bag contains:  1.5 2.2 3.2 1.5 2.4 2.2




Number of doubles for a double bag 2: 4

Input a double: 2.2

Input a double: 3.3

Input a double: 4.1

Input a double: 3.2

The second double bag contains:  2.2 3.3 4.1 3.2




Combine two double bags:  1.5 2.2 3.2 1.5 2.4 2.2 2.2 3.3 4.1 3.2




Input the element that needs to be removed: 1.5

After the element 1.5 has been removed, the bag contains 2.2 3.2 1.5 2.4 2.2 2.2 3.3 4.1 3.2




Input the element that needs to be removed: 4.1

After the element 4.1 has been removed, the bag contains 2.2 3.2 1.5 2.4 2.2 2.2 3.3 3.2




You can download <strong>input_bag.txt</strong> to test your program by

./a.out  &lt; input_bag.txt





