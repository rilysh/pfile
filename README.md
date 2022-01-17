# pfile
A small permission setting utility for linux

# Usage
pfile [FILE] [PERMSSIONS]

Note: Permissions are calculated by bits, before you can give perms would recommended to use permissions aliases for example r (read), w (write), x (execute), u (user), g (group), o (others) etc. So if you've give `pfile test.txt rw` it means generated / existed `test.txt` by any program you can able to read and write it, rwx for read, write and execute, only r or w refers it will only able to read either write.

# Ex. Image
<a href="https://imgur.com/Ro9GqkL.png">
  <img src="https://imgur.com/Ro9GqkL.png" />
</a>

This `rwx` and others are permissions.
