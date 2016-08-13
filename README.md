# bloup
Simple, Fast, Handy and Very Small PHP Script Uploader.

How to use BLOUp:

1- Unzip the content of zip file and upload the file ( bloup.php ) to any directory in your website

2- Go to: www.yoursite.com/directory/bloup.php ( This action will create the uploads directory with index.html in it and an index.html

3- Login using the default password: 123456@

4- Change the password in the Change Password Section

Extra:

• You can change the files directory by edit the variable ( $path ) to any name with a slash ( / ):

$path = "e254bf3cbe39f19d0fa6aa3dd7855764/";

• You can edit the valid formats by editing the variable ( $valid_formats ) in this line ( read the comments ):

$valid_formats = array("jpg", "png", "gif", "zip");

• You can edit the maximum file size by editing the variable ( $max_file_size ):

$max_file_size = 1024*8800; // 8800 = 8800 Kb = 8.8 Mb

*** If you have some programming skills you can change the delete Hash ( e820903f412e8b033803a6d6ae381098 ) using a text editor by finding it and replace all with your new Hash or word.

Hint: There is only 3 of ( e820903f412e8b033803a6d6ae381098 ).
