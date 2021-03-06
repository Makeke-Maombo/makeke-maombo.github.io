-------

Title: Test

-------



Hello World

JavaScript Program statements
The previous handout introduced various language elements and described the way in which code should be written. It mostly focussed on expressions – small fragments of code (such as 'x < y', or 'a == 1') that can be evaluated to produce a result; the result typically being 'true' or 'false'. Some of the examples showed expressions in the context of a larger program, but in general we have not considered how we actually make the program do something. In order to get the program to carry out some action, we need to use statements, and this page introduces some basic statements. All programs consist of a series of statements that are carried out in order.
Simple and compound statements
We have already seen some statements in the examples shown so far. Our first code showed a very simple program that consisted of one line of JavaScript, embedded within an HTML page; that JavaScript program consisted of the single statement 'alert()', with a text string containing a message included as a parameter to the statement. In this case, 'alert()' is a function call: we are causing the program to carry out a (pre-defined) function. Other single-line statements include variable declaration statements using 'var' as we saw on the previous page.
On other occasions we need to carry more complicated actions that can be expressed in a single statement, and for these we need to use compound statements. Compound statements are treated within the wider structure of the program as a single statement, but they consist internally of a number of sub-statements. The sub-statements are grouped together within curly brackets '{}'. We've already seen this in some of the examples shown so far, but it is illustrated below. The code shows the generic structure of an 'if' statement. If a certain condition is met (the supplied expression is evaluated and the result is 'true') then the associated statement is carried out; if the result of the expression is 'false', then the statement is ignored, and we continue on to the next statement in the program.
