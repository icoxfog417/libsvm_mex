libsvm_mex
==========

mex files to use libsvm on Windows.

The process to use [libsvm](http://www.csie.ntu.edu.tw/~cjlin/libsvm/) on Windows Octave is described at  [here](http://flyingpies.wordpress.com/2012/11/20/getting-libsvm-to-work-with-octave-on-windows/).  
In short, you have to compile libsvm (it needs Visual Studio install!), and it is too hard.  

So I prepared mex files. It's confirmed on Windows 8.1 64bit. Octave version is 3.6.4.


## How to use
copy all mex files in `win64` to `<octave_home>lib/octave/<octave_version>/site/oct/i686-pc-mingw32`.
(It may works on 32bit (because compiler in Visual Studio works on x86), but I don't confirm).

Type `svmtrain` command on Octave, it may works.

