Download Link: https://assignmentchef.com/product/solved-solved-mydeque-class
<br>
1.Create a MyDeque class based on the discussion of deques (p. 143) in this chapter. It should include the following methods: insertFront() insertRear() removeFront() removeRear() peekFront() peekRear() isEmpty() isFull() toString() Peek means retrieve the value without remove it. •You may create the class by updating the existing class Queue.java in page 138 of the textbook. Delete display () method from the class. •The data type of the elements in MyDeque is DataRecord. DataRecord class contains: o Instance vars: id (String: any numeric chars) and data (String: any string). o Set/get methods, toString() o Use default constructor when create the object (you don’t need to write the constructor) •It needs to handle wrap-around of the array, as a circular queue does. •Refer the given methods in the example class to define the signature (method head) of each above method. 2.The toString() in MyDeque should always display the data stored in the deque in the sequence from ‘front’ to ‘rear’, not the data sequence from index 0 to the end in the array. 3.Write an application class to test all methods defined in MyDeque class. The application should allow the user to decide the length of the deque and operate on the queue as many times as he/she wants till choosing ‘Quit’. The selections for users are: • Insert to front • Insert to rear • Remove from front • Remove from rear • Peek front • Peek rear • Display queue • Quit You should test the functions as thoroughly as you can. Test the deque with the size of 5. Make the cases to allow the front and rear crossing the array boundaries in both ends. You have to record your testing sample and submit it with all classes. In the record, show me how you test the front/rear crossing low index boundary and high index boundary. (Display your deque frequently during the debugging to check the correctness of the functions) 4.Write a program to implement a stack class which is based on the Deque class you have implemented. It should include the following methods: push() pop() peek() isEmpty() isFull() To avoid the name conflict with the Stack class defined in Java library, please pick any name other than Stack for your class. [Note: This technique is called delegation. Define a deque object in this stack class, and then use any existing methods of the deque to implement the functions of the stack. If you still have problems, do self-study for class delegation in OO design.] 5.For all methods and applications you write, give comments (top doc before each method, not only // comments by the side of the sentences) to explain your strategy.