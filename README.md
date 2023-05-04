Download Link: https://assignmentchef.com/product/solved-csci-1302-assignment-1-two-dimensional-arrays-arraylists
<br>
<h2>Problem 1</h2>

Write an application that prompts the user to enter the values for two 3×3 matrices (i.e., two two-dimensional arrays with 3 rows and 3 columns) and then compute the sum of the first matrix + the transpose of the second.

Print both matrices, the transpose of the second, and the sum.

Note that the transpose of a matrix switches the rows and the columns, so a matrix

1        2                         1     3

would be

3        4                         2     4

To add two matrices together, you simply add their components

1        2     +     5     6     =        6       8

3        4            7     8            10     12

Test your application! Make sure the addition works properly.

<h2>Sample Run</h2>

Here’s a sample run (user input in <strong>bold</strong>, all numbers entered on a single line with a space between them, but you can have the user enter them on multiple lines if you like):

-1-

<h2>Problem 2</h2>

Write an application that prompts the user to enter the values for a list (store this is an ArrayList), or enter -1 to indicate they’re done entering numbers. Print out the numbers in the ArrayList and the sum of the numbers in the list that are odd with an even index or that are even but in an odd index.

For example if the user entered the numbers 1, 2, 3, and 4, then the sum would be 10.

index <strong><em>0 1 2 3</em></strong>

<table width="150">

 <tbody>

  <tr>

   <td width="51">value</td>

   <td width="25">1</td>

   <td width="25">2</td>

   <td width="25">3</td>

   <td width="25">4</td>

  </tr>

 </tbody>

</table>

1 and 3 are odd and they are located in even indices (0 and 2 are even, right?) and 2 and 4 are even and located at odd indices (1 and 3 are odd), so we add all the values together, 1 + 2 + 3 + 4 = 10.

<h2>Sample Run</h2>

Here are some more examples(user input in <strong>bold</strong>, all numbers entered on a single line with a space between them, but you can have the user enter them on multiple lines if you like). Note that the -1 isn’t used at all in the calculations:

-2-