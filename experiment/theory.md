The execution of programming language codes is done by a compiler. A compiler is given a set of codes or rather a sequence of codes that perform a desired task. The task may or may not be repetitive but the compiler is smart enough to process it. Such repetitive code is known as a 'loop'.<br>

Loop is a sequential set of instructions which gets executed multiple times to reduce minimize the repetition of code.<br>
In Python, we have two types of loops :<br>
i. for loop<br>
ii. while loop<br>

To understand the functioning and flow of a loop, you must get familiar with the term 'block'. A block is the smallest unit in a loop which performs one particular task.<br><br>
<b>'For' loop :</b><br><br>
Syntax : <br><br>for object in range(initialization, limit, update ):<br>
statements<br><br>
The above given syntax is of for loop where we put the object name after 'for' and the limit inside 'range( )'.<br><br>
Program:<br>
<img src="images/img3.PNG"><br><br>
Output : <br>
0<br>
1<br>
2<br>
3<br><br>
<b>'While' loop :</b><br><br>
Syntax : <br><br>while expression:<br>
statements<br><br>
The above statement is for while loop, where the testing condition is placed after while and it is followed by the statements placed in the loop body.<br>
Program:<br><br>
<img src="images/img1.PNG"><br><br>
Output:<br><br>
Hello people<br>
Hello people<br>
Hello people<br><br>
Program:<br><br>
<img src="images/img2.PNG"><br><br>
Output:<br><br>
hello geek<br>
hello geek<br>
..........<br><br>
Nested loops :<br><br>
A nested loop is an inner loop in the loop body of the outer loop. The inner or outer loop can be any type, such as a while loop or for loop. For example, the outer for loop can contain a while loop and vice versa<br><br>
Program:<br><br>
<img src="images/img4.PNG"><br><br>
Output:<br><br>
1 <br>
2 2<br>
3 3 3<br>
4 4 4 4<br><br>
Program:<br><br>
<img src="images/img5.PNG"><br><br>
Output:<br><br>
1 Outer loop is executed only once<br>
1 Inner loop is executed until to completion<br>
2 Inner loop is executed until to completion<br>
2 Outer loop is executed only once<br>
1 Inner loop is executed until to completion<br>
2 Inner loop is executed until to completion

