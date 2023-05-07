Download Link: https://assignmentchef.com/product/solved-math-233-scientific-computing-assignment-1-hello-world
<br>
<ol>

 <li>What is your experience with C++ (before doing the homework) ?</li>

 <li>Read the introduction of ”C++ for Scientific Computing ”, write, compile and run your own ”Hello World” code.</li>

 <li>Read sections 2 to 8. Suggestion: run and modify the example codes.

  <ul>

   <li>Give one reason to use C++ over Matlab.</li>

   <li>What are the pros and cons of using the double type to represent real numbers ?</li>

   <li>How would you decide to use int versus long ?</li>

   <li>What does the &amp; operators does ? What about the * ?</li>

   <li>How would you declare a 3×4×5 array of real numbers, assuming that we want double precision ? How would you do it if at the time of compilation the array size <em>N </em>×<em>M </em>×<em>L </em>was not known ?</li>

   <li>If A is an array of double of size N, how do you access its first and last element ?</li>

  </ul></li>

 <li>(a) Imagine you want to implement a function Legendre(double x, int n) which return the value of the <em>n<sup>th </sup></em>Legendre Polynomial evaluated at x for 0 <em>&lt; n &lt; </em> Which control structure would you use ? why ?

  <ul>

   <li>Implement the Legendre(double x, int n) Your function should return an error message if <em>n &gt; </em>6 or <em>n &lt; </em>0.</li>

   <li>Implement a function sampledLegendre(double a, double b, int N, int n) which return the vector of size N containing the values of the <em>n<sup>th </sup></em>Legendre Polynomial at the uniformly distributed points <em>x</em><sub>0 </sub>= <em>a,…,x<sub>N</sub></em><sub>−1 </sub>= <em>b</em>.</li>

   <li>How can you verify your code ?</li>

   <li>If we call <em>A<sup>n</sup><sub>N </sub></em>the output of sampledLegendre(-1,1, int N, int n), what is the limit as <em>N </em>→ ∞ of the scalar product ? (You might wanna use what you just implemented to get some intuition…)</li>

  </ul></li>

</ol>