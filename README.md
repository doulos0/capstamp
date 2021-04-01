# capstamp
Simple bash script to add a time stamp for screen shots

This is perfect for penetration testers who collect screen shots for evidence. The date stamped is not the current date, but the last modify date, so many screen captures can be collected and stamped later to provide a timeline. 


This particular method doesn't delete the old image, just creates a new one with "s_" at the beginning of the file name.

Requires convert, a linux tool. Part of Imagemagick

sudo apt install imagemagick

INSTALLATION

chmod +x and copy to a directory in your path (e.g., /usr/bin) 

USAGE

capstamp image.png
  
  works with jpg,png,etc. 
  
Added RFC3339 UTC version "ucapstamp" 
  
  
