Download Link: https://assignmentchef.com/product/solved-ch08-320201-homework-7-stacks-queues-and-linked-lists-rooted-trees
<br>
<h2>Problem 1: Stacks &amp; Queues</h2>

<ul>

 <li>Implement in Python or C++ the data structure of a stack backed up by a linked list, that can workfor whatever type, and analyze the running time of each specific operation. In order to achieve this in C++, make use of <em>template &lt; classT &gt;</em>, on which you can find more information at</li>

</ul>

Implement the stack such that you have the possibility of setting a fixed size but not necessarily have to (size is -1 when unset). Check for the correctness of your functions and throw exceptions with suggestive messages in cases of underflow or overflow<a href="http://www.cplusplus.com/doc/tutorial/exceptions/">(C++,</a><a href="https://stackoverflow.com/questions/2052390/manually-raising-throwing-an-exception-in-python">Python)</a>. You can assume that if the size is passed, it always has a valid value.

<table width="599">

 <tbody>

  <tr>

   <td width="599">class         Stack [A ] ( ) :private :s t r u c t        StackNode ( ) { / / linked          l i s tA data ;StackNode ∗next ;};StackNode ∗top ; / / top of stack i n t size ; / /−1 i f not set , value otherwisei n t current size ; / / unused i f size = −1 public :fun push ( x :A) : void / / i f size set , check f o r overflow fun pop ( ) :A / / return element i f not in underflowfun isEmpty ( ) : bool / / 1 i s empty , 0 otherwise fun Stack ( i n t new size ) fun Stack ( )</td>

  </tr>

 </tbody>

</table>

5

10

15

Checking will be done by case-tests alone. The tests will cover overflow and underflow cases, as well as tests for different types of variables.

<ul>

 <li>Show how a queue can be implemented with two stacks.</li>

</ul>

<h2>Problem 2: Linked Lists &amp; Rooted Trees</h2>

<ul>

 <li>Program an in-situ algorithm that reverses a linked list of <em>n </em>elements in Θ(<em>n</em>). Add an explanation to why it is an in-situ algorithm in the code.</li>

 <li>Program an algorithm to convert a binary search tree to a sorted linked list and derive its asymptotictime complexity.</li>

 <li>Program an algorithm to convert a sorted linked list to a binary search tree and derive its asymptotictime complexity.</li>

</ul>