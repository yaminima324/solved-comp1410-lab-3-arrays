Download Link: https://assignmentchef.com/product/solved-comp1410-lab-3-arrays
<br>
Practice dealing with 2D arrays.

<strong>Pre-requisite(s): </strong>– Read and review chapter 6.

<strong>Manipulating a 2D array: </strong>

<ol>

 <li>Create a two dimensional array (e.g. <strong>int A2D [ M ][ N ] ;</strong>) of size <strong>M x N </strong>to store integer values. Use <strong>#define M 6 </strong>and <strong>N 5 </strong>to start. (Using symbolic constants instead of hard coding the array sizes improves scalability).</li>

 <li>Populate the array pseudo-randomly, with integer numbers between 1 and <strong>M x N</strong>, inclusive, so that every array element is unique (no duplicates).</li>

 <li>Print the array in a table format (use formatting codes to achieve this).</li>

 <li>Use Linear Search to find if a number <strong><em>n </em></strong>is found in the array, where <strong><em>n </em></strong>is an integer between 1 and <strong>M x N</strong> (inclusive) entered by the user.</li>

 <li>Apply a single LEFT shift operation to the array. LEFT shift means move every element one position to the LEFT; the first element becomes the last one, and the first element in each row moves up to become the last element in the previous row.</li>

</ol>




Example: Left shift of a 2 x 4 array:                      becomes:

<ul>

 <li>8 3 2                                               8 3 2 5</li>

 <li>6 1 7                                               6 1 7 4</li>

</ul>

<ol start="6">

 <li>Print the shifted array.</li>

</ol>




<strong>Summary of the lab requirements:</strong> You must create an interactive menu within <strong>main()</strong> for this program (call it <strong>Lab3.c</strong>) with choices to fill the array with random numbers, search the array, left shift the array, print the array and either repeat a menu item or quit.

<strong> </strong>

<strong>Design and document the following functions (REQUIRED): </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="240">– <strong>PrintArray2D()            </strong></td>

   <td width="387"><strong>— </strong>to print the array.</td>

  </tr>

  <tr>

   <td width="240">– <strong>PopulateRandom2D()  </strong></td>

   <td width="387"><strong>— </strong>to populate the array with pseudo-random numbers.</td>

  </tr>

  <tr>

   <td width="240">– <strong>LinearSearch2D()      </strong></td>

   <td width="387"><strong>— </strong>to search the array for a value, return true if found.</td>

  </tr>

  <tr>

   <td width="240">– <strong>LeftShift2D()               </strong></td>

   <td width="387"><strong>— </strong>to left shift the array.</td>

  </tr>

 </tbody>

</table>




Each one of the functions above accepts a 2D array as a parameter, along with any additional parameters that you may find necessary. The return types of the functions are also your choice. <u>Do NOT use global (i.e. file scope) variables</u> in this program.

Important Note: When passing 2D arrays as parameters to functions, it is necessary to specify the number of columns explicitly.  Hence:  <strong>int foo( int A[][N] );</strong> is valid and permits references to all elements within <strong>A</strong>, such as <strong>A[i][j] for 0&lt;=i and 0&lt;=j&lt;N</strong>.

<strong>EVALUATION OF WORK AND ATTENDANCE: Total 5 marks</strong>.

You need to show to your lab instructor the work you have completed for this lab assignment, generally in the form of a working program. The marks you will receive for the lab are made of two parts, the programming part and lab attendance. Do not email your work to the Instructor or to any teaching assistant.

<strong>Lab Work Mark</strong>: You will be evaluated based on your solution for the problem assigned, using the following scheme:  You must attend the lab and show your work in order to earn any of the following marks.

<ul>

 <li>mark = No appreciable and relevant work done.</li>

 <li>marks = Incomplete code / does not compile, with no, little or invalid documentation.</li>

 <li>marks = Complete running program with no, little or invalid documentation.</li>

 <li>marks = Incomplete code / does not compile, with suitable documentation.</li>

 <li>marks = Complete running program with suitable documentation (minor errors may be accepted).</li>

</ul>


