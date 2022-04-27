# How-to-create-and-access-integer-arrays-in-PHP.
How to create and access integer arrays in PHP.
<html>
  <body>
 
  <?php
  /* The first method to create an array in PHP. */
  $numbers = array( 1, 2, 3, 4, 5);
 
  foreach( $numbers as $value )
  {
  echo "Array element value is $value <br />";
  }
 
  /* Second method to create array in PHP. */
  $numbers[0] = "one";
  $numbers[1] = "two";
  $numbers[2] = "three";
  $numbers[3] = "four";
  $numbers[4] = "five";
 
  foreach( $numbers as $value )
  {
  echo "Array element value is $value <br />";
  }
  ?>
 
  </body>
</html>
