# Perl6 - WiringPI [![Build Status](https://travis-ci.org/Sufrostico/perl6-wiringpi.svg?branch=master)](https://travis-ci.org/Sufrostico/perl6-wiringpi)

Perl6 Wrapper for the WiringPi C library (to use with the raspberry pi).

From the [WiringPI site](http://wiringpi.com):
  > WiringPi is a GPIO access library written in C for the BCM2835 used in the
  > Raspberry Pi. It’s released under the GNU LGPLv3 license and is usable from C
  > and C++ and many other languages with suitable wrappers. It’s designed to be
  > familiar to people who have used the Arduino “wiring” system.

## Installation

 1. This module requires the wiringpi library to installed manually following
    [this guide](http://wiringpi.com/download-and-install/)

 1. Install this module by using panda

## Current status

 - Only the main functions of the library has been mapped using the NativeCall
   library.
 - The files needed for the other parts of the library are already created and
   present in the **next** branch but I'm unable to testit due to hardware/time
   constraints.

## Testing

To run tests:

```
    prove -e perl6
```

## Author

Aurelio Sanabria, sufrostico on #perl6 and github (https://github.com/sufrostico/)

## License

GPL - General Public License
