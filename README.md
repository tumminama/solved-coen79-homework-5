Download Link: https://assignmentchef.com/product/solved-coen79-homework-5
<br>
<table width="653">

 <tbody>

  <tr>

   <td width="27">1.</td>

   <td width="626">  1. Please complete the following implementation:  template &lt; <strong>class</strong> Item &gt;</td>

  </tr>

  <tr>

   <td width="27">2.</td>

   <td width="626">binary_tree_node &lt;Item&gt;* tree_copy (<strong>const</strong> binary_tree_node &lt;Item&gt;* root_ptr)</td>

  </tr>

  <tr>

   <td width="27"> </td>

   <td width="626">          • Using the previous implementation, complete the following function for the bag class given in Appendix 1: </td>

  </tr>

  <tr>

   <td width="27">1.</td>

   <td width="626"> template &lt; <strong>class</strong> Item &gt;</td>

  </tr>

  <tr>

   <td width="27">2.</td>

   <td width="626"><strong>void</strong> bag &lt;Item&gt;::operator = (<strong>const</strong> bag&lt;Item&gt;&amp; source)</td>

  </tr>

  <tr>

   <td width="27">3.</td>

   <td width="626">// Header file used: bintree.h</td>

  </tr>

 </tbody>

</table>




<ol start="2">

 <li>For the bag class defined in Appendix 1, please complete the following function:</li>

</ol>




<ol>

 <li>template &lt; <strong>class</strong> Item &gt;</li>

 <li><strong>void</strong> bag&lt;Item&gt;::insert(<strong>const</strong> Item&amp; entry)</li>

 <li>// Postcondition: A new copy of entry has been inserted into the bag.</li>

 <li>// Header file used: bintree.h</li>

</ol>























































<strong> </strong>







<ol start="3">

 <li>Write a function to perform <em>left-right</em> rotation on the following AVL tree. The figure shows the steps. (Note: Please implement the function in two steps: (1) left rotation, (2) right rotation.)</li>

</ol>




parent







<ol>

 <li>template &lt; <strong>class</strong> Item &gt;</li>

 <li>binary_tree_node &lt;Item&gt;* left_right_rotation (binary_tree_node &lt;Item&gt;*&amp; parent) {</li>

 <li>binary_tree_node &lt;Item&gt;* temp;</li>

</ol>











































<ol start="4">

 <li>Add the following numbers to an AVL tree. Please draw the final tree. 2, 4, 6, 8, 10, 12, 20, 18, 16, 14</li>

</ol>










<ol start="5">

 <li>The following functions are available:</li>

</ol>







Also assume the following functions are available:




<ul>

 <li>binary_tree_node&lt;Item&gt;* left_rotation (binary_tree_node&lt;Item&gt;*&amp; parent)</li>

 <li>binary_tree_node&lt;Item&gt;* right_rotation (binary_tree_node&lt;Item&gt;*&amp; parent)</li>

 <li>binary_tree_node&lt;Item&gt;* left_right_rotation (binary_tree_node&lt;Item&gt;*&amp; parent)</li>

 <li>binary_tree_node&lt;Item&gt;* right_left_rotation (binary_tree_node&lt;Item&gt;*&amp; parent)</li>

</ul>




Complete the following function, which balances a tree rooted at temp.




<ol>

 <li>template &lt; <strong>class</strong> Item &gt;</li>

 <li>binary_tree_node&lt;Item&gt;* balance(binary_tree_node &lt;Item&gt;*&amp; temp)</li>

</ol>











































<ol start="6">

 <li>Please implement the following function (<em>recursively</em>).</li>

</ol>




<ol>

 <li>template &lt; <strong>class</strong> Item &gt;</li>

 <li><strong>void</strong> flip(binary_tree_node &lt; Item &gt; * root_ptr)</li>

 <li>// <strong>Precondition</strong>: root_ptr is the root pointer of a non-empty binary tree. // <strong>Postcondition</strong>: The tree is now the mirror image of its original value.</li>

</ol>




Example:




//          1                                 1

//         /                                / 

//        2   3                             3   2

//       /                                    / 

//      4   5                                 5   4










<ol>

 <li>template &lt; <strong>class</strong> Item &gt;</li>

 <li><strong>void</strong> flip (binary_tree_node &lt;Item&gt;* root_ptr)</li>

</ol>




<strong>      </strong><strong> </strong>




<strong>Appendix 1: </strong>Bag class with binary search tree.





