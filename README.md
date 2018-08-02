To run this script, you need to copy "easy-lock.php" in your php directory...
-----------------------------------------
To run this you need to include this file and call the lock() function, at the beggining of the file, with a string parameter representing the password...
-----------------------------------------
For higher functional demands, check the documentation, or send a support ticket here: http://support.artur99.net
-----------------------------------------

Example:

<?php
include 'easy-lock.php';
lock("1234");
?>
<!-- Your Page Content -->

-----------------------------------------

Inline example:

<?php include 'easy-lock.php';lock("1234");?>
<!-- Your Page Content -->

-----------------------------------------

If you want to keep this file in the root, just change the "include" to 
include '/easy-lock.php';
or inside a folder:
include '/inc/easy-lock.php';
