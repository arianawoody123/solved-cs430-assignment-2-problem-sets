Download Link: https://assignmentchef.com/product/solved-cs430-assignment-2-problem-sets
<br>
<strong>Problem 1</strong>

Do problem 13-4 (a) and (b) on page 333 in CLRS. Justify your answer.

Problem 2

Consider the code for Randomized-Selection on page 216 in CLRS. Support someone carelessly implemented the code, but omitted the “-1” on line 8, that it typing q instead of q – 1.

Does the corrupted code still work (that is, correctly find the <em>i</em><sup>th </sup>smallest element) always, some-times, or never? Explain your answer.

Problem 3 (25pts)

Coins of various values are placed on the cells of an <em>n</em>×<em>m </em>chess board. Let the upper left corner cell be (1<em>,</em>1) and the lower right cell be (<em>n,m</em>); cell (<em>i,j</em>) has coins valued at <em>c<sub>ij </sub></em>. A robot starts at cell (1<em>,</em>1) and can move only to the right or down on the board.

<ol>

 <li>Give a dynamic programming algorithm expressed recursively without memoization to determine the path the robot should follow to maximize the total value of the coins collected as the robot wanders on the board from cell (1<em>,</em>1) to cell (<em>n,m</em>). Analyze the time required and give corresponding pseudocode.</li>

 <li>Give the algorithm iteratively with memoization. Analyze the time required and give corresponding pseudocode</li>

</ol>

<h2>Problem 4</h2>

We are given a sequence of <em>n </em>numbers, <em>a</em><sub>1</sub><em>,a</em><sub>2</sub><em>,</em>··· <em>,a<sub>n </sub></em>and want to find the <em>longest increasing subsequence </em>(LIS); that is, we want to find indices <em>i</em><sub>1 </sub><em>&lt; i</em><sub>2 </sub><em>&lt; </em>··· <em>&lt; i<sub>m </sub></em>such that <em>a<sub>i</sub></em><em><sub>j </sub>&lt; a<sub>i</sub></em><em><sub>j</sub></em><sub>+1 </sub>and <em>m </em>is as large as possible. For example, given the sequence 5, 2, 8, 6, 3, 6, 9, 7 we have an increasing subsequence 2, 3, 6, 9 and there is no longer increasing subsequence.

<ol>

 <li>Give a recursive dynamic programming recurrence (just give the function) for the LIS of a sequence <em>a</em><sub>1</sub><em>,a</em><sub>2</sub><em>,</em>·· <em>,a<sub>n</sub></em>. (Hint : Let <em>L<sub>i </sub></em>be the length of the LIS in <em>a</em><sub>1</sub><em>,a</em><sub>2</sub><em>,</em>··· <em>,a<sub>i </sub></em>, let <em>A<sub>i </sub></em>be index of the smallest possible largest element in that increasing subsequence, and let <em>B<sub>i </sub></em>be index of the second-largest element in that increasing subsequence.</li>

</ol>

Express <em>L<sub>i </sub></em>recursively. You may assume a dummy element <em>a</em><sub>0 </sub>= −∞)

<ol start="2">

 <li>Give the algorithm iteratively with memoization. Analyze the time required and give corresponding pseudocode.</li>

</ol>