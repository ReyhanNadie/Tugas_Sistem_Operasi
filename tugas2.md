# <p style="text-align: center;"> **1** <br> **INTRODUCTION** </p>

A modern computer consists of one or more processors, some main memory,
disks, printers, a keyboard, a mouse, a display, network interfaces, and various
other input/output devices. All in all, a complex system.oo If every application programmer had to understand how all these things work in detail, no code would ever
get written. Furthermore, managing all these components and using them optimally
is an exceedingly challenging job. For this reason, computers are equipped with a
layer of software called the **operating system**, whose job is to provide user programs with a better, simpler, cleaner, model of the computer and to handle managing all the resources just mentioned. Operating systems are the subject of this
book.

Most readers will have had some experience with an operating system such as
Windows, Linux, FreeBSD, or OS X, but appearances can be deceiving. The program that users interact with, usually called the **shell** when it is text based and the
**GUI (Graphical User Interface)**—which is pronounced ‘‘gooey’’—when it uses
icons, is actually not part of the operating system, although it uses the operating
system to get its work done.

A simple overview of the main components under discussion here is given in
Fig. 1-1. Here we see the hardware at the bottom. The hardware consists of chips,
boards, disks, a keyboard, a monitor, and similar physical objects. On top of the
hardware is the software. Most computers have two modes of operation: kernel
mode and user mode. The operating system, the most fundamental piece of software, runs in **kernel mode** (also called **supervisor mode**).

### <p style="text-align: center;">INTRODUCTION</p>

In this mode it has complete access to all the hardware and can execute any instruction the machine is
capable of executing. The rest of the software runs in **user mode**, in which only a
subset of the machine instructions is available. In particular, those instructions that
affect control of the machine or do I/O )Input/Output" are forbidden to user-mode
programs. We will come back to the difference between kernel mode and user
mode repeatedly throughout this book. It plays a crucial role in how operating systems work.
