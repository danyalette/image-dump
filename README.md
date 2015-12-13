# image-dump

Easily display all the images in a directory. 

[DEMO](http://danya.ca/image-dump)

This script generates a thumbnail for each image, and displays the thumbnails in a grid. 
Clicking on thumbnails opens a lightbox. 

There are two settings: 

$dir = "images"; //directory containing images
$max_page = 12; //pics per page

Notes:
- requires the PHP GD library 
- you will probably have to change some permissions in order to allow index.php to create the thumbnail directory and save images to that directory 
