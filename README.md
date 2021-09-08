# CS50

## [Ref](https://video.cs50.io/zYierUhIFNQ?screen=VmZ-cWfb2QM)

## Week 0

### Scratch

## Week 1

### C language
* step to install cs50 lib
    1. Download the latest release from https://github.com/cs50/libcs50/releases
    1. Extract libcs50-*.*
    1. cd libcs50-*
    1. sudo make install

By default, we install to /usr/local. If you'd like to change the installation location, run sudo DESTDIR=/path/to/install make install as desired.

- compiler C in cli
  `make <filename>`

- execute program after complie
  `./hello`

### Types

- String is text, it word

### Process

arguments --> functions --> output

## Issue
(cs50 library wont link to file in cs50 appliance)[https://stackoverflow.com/questions/23749103/cs50-library-wont-link-to-file-in-cs50-appliance]

* You got to tell the compiler to link in the library by running either
    `clang -lcs50 -o hello hello.c`
