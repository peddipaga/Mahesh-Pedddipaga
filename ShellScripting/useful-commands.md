## I found these commands are useful 

**To remove end of line in a file**

`perl -pi -e 'chomp if eof' filename`

**The** `ack` **command**

 Ack is designed as an alternative to grep for programmers

  if you are using mac, do below
 
    1) brew install ack
    2) `man ack` for more details.
----
==== Wrapper around a program ====
<code bash>
myprog=/bin/ls
echo "This is the wrapper script, it will exec $myprog"

# do some vodoo here, probably change the arguments etc.
# well, stuff a wrapper is there for

exec "$myprog" "$@"
</code>
