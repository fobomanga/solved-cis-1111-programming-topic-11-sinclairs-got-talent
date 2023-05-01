Download Link: https://assignmentchef.com/product/solved-cis-1111-programming-topic-11-sinclairs-got-talent
<br>
Write a C++ program to determine the winner of the “Sinclair’s Got Talent” contest. The contest has five judges, each of whom awards a score between 1 and 10 for each of the performers. Fractional scores are not allowed. A contestant’s final score is determined by dropping the highest and lowest scores received, then averaging the three remaining scores (the average should be rounded to two decimal places). The winner is the contestant with the highest average score. If there is a tie, the winner will be the first contestant judged.

<strong>Requirements</strong>:

<ol>

 <li>Input the contestant’s first name followed by the 5 judges’ scores. You do not know how many contestants there are. Design the loop so the loop terminates when you are finished entering contestants.</li>

 <li>Input validation: Do not accept a judge’s score that is less than 1 or greater than 10.  As each score is entered send the score to a function to test the score’s validity.</li>

 <li>Use function calcAvgScore that has the contestant’s 5 scores as input parameters

  <ol>

   <li>returns the average score for that contestant.</li>

   <li>Calls two functions, findLowest and findHighest which both accept the 5 scores as input parameters and return the lowest and highest scores, respectively.</li>

  </ol></li>

 <li>Do not use global variables. All variables used in the functions must be passed as parameters or declared locally.</li>

 <li>At the end of the program, display the winner and winning score (rounded to 2 decimal places).</li>

</ol>

<strong>Sample Output:</strong>

<strong> <img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/04/473.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/04/473.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></strong>

<strong> </strong>

<strong>Submit:</strong>

Zipped folder named LastNameFirstNameCIS1111NameOfAssignment which contains:

<ol>

 <li>Your .cpp file</li>

 <li>Screen shots of your code and output</li>

</ol>


