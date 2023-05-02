Download Link: https://assignmentchef.com/product/solved-coptimzation-problem-set-1
<br>



<strong>Convex Optimization</strong>




<table width="380">

 <tbody>

  <tr>

   <td width="43">Ref.</td>

   <td width="337">Exercises</td>

  </tr>

  <tr>

   <td width="43">[1]</td>

   <td width="337">2.2, 2.12 (d)(e)(g), 2.18, 2.24, 3.3, 3.18, 3.19(a)</td>

  </tr>

 </tbody>

</table>

<h1>Matlab Assignment</h1>

<strong>Problem 1. </strong>Let the set S be described by,

<em>.</em>

<ul>

 <li>Use Matlab to draw the set S and investigate its convexity.</li>

 <li>Show your conclusion in part (a) theoretically.</li>

</ul>

<strong>Problem 2. </strong>Let <em>Q</em><sub>1 </sub>and <em>Q</em><sub>2 </sub>be arbitrary <em>n </em>× <em>n </em>symmetric matrices (<em>n &gt; </em>2).

<ul>

 <li>Use Matlab to draw the set and investigate its convexity.</li>

 <li><strong>Extra point: </strong>Can you show your conclusion in part (a) theoretically?</li>

</ul>

<strong>Problem 3. </strong>Let <em>A </em>be a real <em>m</em>×<em>n </em>matrix with a singular value decomposition given by <em>A </em>= <em>U</em>Σ<em>V <sup>T </sup></em>(as discussed in class). For a positive integer <em>k </em>≤ min{<em>m,n</em>}, we let <em>A<sub>k </sub></em>denote an <em>m </em>× <em>n </em>matrix which is an

“approximation” of the matrix <em>A </em>obtained from its top <em>k </em>singular values and singular vectors, i.e.,

<em>A</em><em>k </em>= <em>U</em><em>k</em>Σ<em>kV</em><em>kT,</em>

where <em>U<sub>k </sub></em>has the first <em>k </em>columns of <em>U</em>, <em>V<sub>k </sub></em>has the first <em>k </em>columns of <em>V </em>, and Σ<em><sub>k </sub></em>is the upper left <em>k </em>× <em>k </em>block of Σ.

<ul>

 <li>To provide a good approximation for <em>A</em>, consider the cost function k<em>A </em>− <em>X</em>k<sub>2 </sub>where <em>X </em>is restricted to be an <em>m </em>× <em>n </em>matrix with rank(<em>X</em>) ≤ <em>k</em>. It can be shown that <em>A<sub>k </sub></em>is the minimizer of the cost function k<em>A </em>− <em>X</em>k<sub>2</sub>. Download the file HajiFirouz.jpg. Read this file in Matlab by typing:</li>

</ul>

A=imread(’HajiFirouz.jpg’)<em>; </em>A=im2double(A) <em>;</em>

A=rgb2gray(A) <em>;</em>

Figure 1: Haji Firouz in Problem 8

The result is a 395 × 665 matrix <em>A</em>, with each entry representing a single pixel in the picture with a number between 0 and 1.

For different values of <em>k</em>, use Matlab to compute <em>A<sub>k</sub></em>, construct a compressed image with <em>A<sub>k </sub></em>(You can used the command imwrite<em>), </em>and report the value of k<em>A </em>− <em>A<sub>k</sub></em>k<sub>2</sub>.

<ul>

 <li>Based on your experiments in part (a), provide a good compressed image for HajiFirouz and explain your interpretations.</li>

</ul>

<h1>References</h1>

[1] Boyd, Stephen, Stephen P. Boyd, and Lieven Vandenberghe. Convex optimization. Cambridge university press, 2004.

2