Download Link: https://assignmentchef.com/product/solved-csci1112-homework-6
<br>
<h1>1      Introduction</h1>

This homework is intended to reinforce your understanding of Big-O and run-times for algorithms. It is comprised of various different exercises that will ask you to find the run-times of loops, explain the run-times of algorithms you have seem in class, and improve algorithms.

<strong>1.2     Submission</strong>

You must turn in a pdf file with your answers on it.

<h2>1.3      Grading Rubric</h2>

Grading will be based off of both correct answers as well as answer completion. Be sure to show all over your work and explain things thoroughly. Incomplete answers will not receive full credit.

<h2>1.4     Plagarism</h2>

We will use a set of automated tools specifically designed to analyze solutions for plagarism. If you copy code from another source, classmate or website, there is a very high probability that these tools will flag your work as plagarized. You are permitted to discuss the problems at a high level; however, you must write your own solution. If you do not share answers or outright borrow answers from a website, you will have no problem with the plagarism filter.

<h1>2         Run-time and Big-O Exercises</h1>

<h2>2.1         Calculate the Big-0 run time of these loops</h2>

<h3>2.1.1</h3>

i=0;

While i &lt; n {

For (j=0;j&lt;n;j++){

Print(this is a loop)

}

i = i*2;

}

<h3>2.1.2</h3>

Array x = new array[n]

Count = 0;

For (i=0;i&lt;n;i++){

Array[Count] = I;

Count


If ( i%3 =0) {

While (Count ! =0) {

Count —

Array[Count] = 0

}

}

}

<h2>2.2        Algorithm run-time (Big-O) questions</h2>

<strong>2.2.1</strong>

What is the run-time of bubble sort? Explain why in detail.

<strong>2.2.2</strong>

What is the run-time of running binary search on a sorted array? Explain why in detail.

<strong>2.2.3</strong>

What is the Worst case run-time of Quicksort? Why? What is the average case run-time of Quicksort? Why?

<h2>2.3      Fibonacci Sequence</h2>

<h3>2.3.1</h3>

Find the Big-O run-time of this program

Public int Fibb ( int x ){

If(x==1) return 1;

If (x==0) return 0;

Return Fibb(x-1)+Fibb(x-2); }

<h3>2.3.2</h3>

Rewrite this program so that it has a much smaller run-time.

Hint: use an array to store information. O(n) is the optimal solution

<h3>2.3.3</h3>

Explain the run time of your program.