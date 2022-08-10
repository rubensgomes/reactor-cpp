# misc-cpp-projs/reactor

NOTE:  This code is not fully tested, and should be considered under  development code.

This project contains the C++ source code of an implemenation of the reactor/acceptor
design pattern. The reactor/acceptor design pattern is commonly used for network
communication applications that rely on sockets.  I wrote the initial reactor/acceptor
management design in Java back 1999.  The link to that source code can be found below at:

[Java Reactor Source Code] ( https://github.com/rubensgomes/reactor )

## Environment

The development environment consists of Linux (or Linux-Like) environment with C++ (2011-C++11) GNU compiler, and the Boost C++ source libraries.

## Build and Run 

A Makefile is provided in each folder to build a test application.  The user should review the Makefile to ensure that its settings (like INCLUDE and LIB paths) are appropriately set for the environment.

To run a build at the Linux shell type:

    make clean; make

