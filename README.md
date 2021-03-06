ffmpeg-windows-build-helpers
============================

This helper script lets you cross compile a windows 32 or 64 bit version of ffmpeg.exe,
including many dependency libraries.

To run the script:

In a Linux box (VM or native):

download the script (git clone the repo, run it, or do the following in a bash window) $

```bash
wget https://raw.github.com/rdp/ffmpeg-windows-build-helpers/master/cross_compile_ffmpeg.sh -O cross_compile_ffmpeg.sh
chmod u+x cross_compile_ffmpeg.sh
./cross_compile_ffmpeg.sh
```

And follow the prompts.
It works with 32 or 64 bit Linux, and can produce  both 32 and 64 bit windows ffmpeg.exe's

See also 
http://github.com/rdp/ffmpeg-windows-build-helpers/wiki for more tips, including being able to build it more quickly!

OS X users, this may help: https://github.com/rdp/ffmpeg-windows-build-helpers/wiki/OS-X

Feedback welcome roger-projects@googlegroups.com
