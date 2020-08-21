# VossReleases
Rolling release repository for VossII

To install a binary version of VossII simply issue the command: 
tar xfj voss.tar.gz2


Voss II
=======

Voss II is a software suite for describing and reasoning about circuits.
Circuits, and properties about them, are described in a functional language
called *fl*.

Fl is a statically typed language with call-by-need semantics (also known as
*lazy evaluation*) and binary decision diagrams built right into the language
itself.

Voss II has been tested and found to work on Debian, Ubuntu, Fedora, Red Hat
and OpenSUSE. If you're using it on another distribution, we'd love to hear
from you!


Introduction to VossII
----------------------
There is a
["Getting Started with VossII and fl"](https://teamvoss.github.io/tutorial)
tutorial in the doc/fl_tutorial directory (you can do firefox doc/fl_tutorial/fl_tutorial.html or your choice of browser to see it)

There is also a more extensive
[User's Guide](https://github.com/TeamVoss/VossII/blob/master/doc/fl_guide.pdf)



Installation
------------

Download our
[pre-built binaries](https://github.com/TeamVoss/VossII/releases/latest)
and unpack them to your directory of choice, then put <installation-directory>/bin in your search path and you will be able to run the fl interpreter by simply invokng fl. Note that you need the <voss dir>/bin in your search path for the Verilog reader to work, and it must be earlier than any paths containing other versions of yosys!


Voss II depends on Tk for its graphical bits. If the fl interpreter dies with
an angry message about not being able to find `wish`, you need to install it:

* **On Ubuntu/other Debian-based**
  ```shell
  sudo apt install tk
  ```
* **On Fedora/Red Hat**
  ```shell
  sudo yum install tk
  ```
* **On SUSE**
  ```shell
  sudo zypper install tk
  ```


