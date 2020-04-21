# beegfs-7.1.4+kernel-5.6.4
Patch so that beegfs 7.1.4 compiles and runs on kernel 5.6.4. It's possible that this will work
on later kernel-ml releases. It's unlikely it's work for other versions of beegfs.

Absolutely no warranty of any kind. By using this patch, you accept all responsibilty for anything 
that may happen to your beegfs cluster and the data it holds.
I have no idea what the implications of these changes on the behaviour of the resulting code are.

```patch -N -p0 -d /opt/beegfs/src/client <beegfs-7.1.4.patch.txt```


