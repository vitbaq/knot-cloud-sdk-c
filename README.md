# knot-cloud-sdk-c

KNoT Cloud SDK in C is part of the KNoT project.
It is a client-side library that provides an AMQP abstraction to the KNoT Cloud
for C applications.


## Compilation and installation

In order to compiler the source code you need following software packages:
 - GCC compiler
 - GNU C library

and dependencies:
 - automake
 - autoconf
 - libtool

### How to install dependencies:

1. `$ sudo apt-get install automake autoconf libtool`

### How to build:

1. `$ ./bootstrap-configure`
2. `$ make`

### How to install:

1. `$ make install`


## License

All KNoT Cloud SDK in C files are under LGPL v2.1 license, you can check
`COPYING` file for details.
