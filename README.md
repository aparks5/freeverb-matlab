# freeverb-matlab
jezar at dreampoint's freeverb implemented in MATLAB

had to dig around to find the original source code, which unsurprisingly is a whole lot easier to grok than any of the other impelmentations i've read!

this script performans batch reverb. change the file to whatever you want. 

yes it is very, very slow. no pointers in matlab, and matrices are getting passed in and out like crazy, performance is not the point (of this particular exercise)! 

i wanted to see how the thing works. and now it does. it is slow but does the freeverb. 

for one channel. will update to add the stereospread and do the other channel.
