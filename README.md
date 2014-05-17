## progfun-setup

The script `setup.sh` will, on a 64 bit Ubuntu Linux machine, install some of the software
required for the Coursera course called *Functional Programming Principles in Scala*,
by Martin Odersky.

Here is what will be installed:

1.  git         git-core, main components of Git version control system
2.  java        openjdk-7-jdk, unless a suitable JRE is already present
3.  sbt         sbt-0.13.2, version of the Scala build tool
4.  eclipse     scala-SDK-3.0.3-2.10-linux.gtk.x86_64, Eclipse IDE with Scala plugins

To run the script from a network connected Ubuntu 14.04 instance, invoke the following
three commands in a terminal window:

    wget https://raw.githubusercontent.com/williamdemeo/progfun-setup/master/setup.sh
	chmod a+x setup.sh
	./setup.sh

(This assumes wget is already installed, which is typically true of a standard Ubuntu distribution.)
