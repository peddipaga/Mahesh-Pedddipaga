## I found these commands are useful 

**To remove end of line in a file**

`perl -pi -e 'chomp if eof' filename`

**The** `ack` **command**

 Ack is designed as an alternative to grep for programmers

  if you are using mac, do below
 
    1) brew install ack
    2) `man ack` for more details.
----------

**The**  `exec` **command**

   Use exec to redirect output of each and every commnad of a shell script to a log file helpful. 
   This is super useful to keep your script clean
   
     exec > file                                                      
     exec 2>&1
