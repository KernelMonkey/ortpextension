# ortpextension - Library
### Copyright (C) 2011  Orazio Briante orazio.briante@hotmail.it
### Laboratory A.R.T.S. - University Mediterranea of Reggio Calabria - Faculty of Engineering

### The ortpextension library implement RTP extension (Realtime Transport Protocol - RFC 3550)

## Prerequisites:

* autotools and libtools (to compile the library)
* oRTP version 0.17.0 or later

* doxygen (optional, to make documentation)

## How to Generate Makefile
	    $ sh autogen.sh

## Compile - Makefile
    $ ./configure --prefix=/usr
    $ make
    $ su
    # make install

## Unistalling - Makefile
    $ su
    # make uninstall

## To clean directory
 
 run "make clean" from the test source tree.


## Test Files:
(you may install ortpextension library first and run it with superuser privileges)

* rtpextsend: to send a file stream with a static rtp extension for all packet
* rtpextrecv: to show the receved rtp extension and store a rtp stream

