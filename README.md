# Boboassa's build of st

st - simple terminal emulator for X

## Requirements

In order to build st you need the `Xlib` header files.

## Installation

Edit config.mk to match your local setup (st is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```
make clean install
```


## Running `st`

Set st as your default terminal emulator program and then run it as normal

Otherwise you can run it with the command: `st`.

See the man page for additional details.

## Configuration

The configuration of st is done by creating a custom `config.h`
and (re)compiling the source code.

## Applied patches

Patches are a way of adding functionality to the minimal standard build of st

- Selection colors

## Acknowledgments

Visit [suckless.org](https://st.suckless.org/) for more information on st
and other suckless programs.
