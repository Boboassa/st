# Boboassa's build of st

st is a simple terminal emulator for X which sucks less.


## Requirements

In order to build st you need the Xlib header files.


## Installation

Edit config.mk to match your local setup (st is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```
make clean install
```


## Running st

If you did not install st with `make clean install`, you must compile
the st terminfo entry with the following command:

```
tic -sx st.info
```

See the man page for additional details.


## Applied patches

Patches are a way of adding functionality to the minimal standard build of st

- Selection colors


## Acknowledgments

Visit [suckless.org](https://st.suckless.org/) for more information on st
and other suckless programs.
