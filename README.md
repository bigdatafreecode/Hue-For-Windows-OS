# Hue-For-Windows-OS
Big Thanks to Hue Teams &amp; Big Data Community in the Worlds :D 

Download the CygWin file from "http://bit.ly/2NpbSfO". In the file "CygWin" in it already exists:
(Ref. Http://gethue.com/ and https://www.youtube.com/watch?v=SPCJA3Cs1Kg)
1. Hue (version 3.11), on CygWin try running "# pip install python-pam"
2. Pluggable Authentication Modules (OpenPAM) that have been compiled (create *.dll file in cygwin64\usr\local\bin\cygpam-2.dll), with the following steps for solution error "import pam AttributeError: function 'calloc' not found AttributeError: function 'strdup' not found AttributeError: function 'pam_start' not found and others":
     # ./configure --with-pam-unix --with-su
     # make
     # make install

May be useful. :D

![Install Hue on Windows OS](https://github.com/bigdatafreecode/Hue-For-Windows-OS/blob/master/Install%20Hue%20on%20Windows%20OS.png)
