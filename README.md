# Xv6_systemcall

Xv6 is an operating system developed by MIT for the learning purpose. It is an implementation of the Unix version 6 using ANSI C language for x86 platforms. It is a great resource for learning operating systems and many universities all over the world have already used it in their courses. 

Here's how to run xv6 operating system on a QEMU virtual machine simply on top of a 64-bit Ubuntu 14.04 LTS machine.
First, You have to install some tools and packages on our Ubuntu Linux system as follows.
```
sudo apt-get update
sudo apt-get install build-essential
sudo apt-get install gcc-multilib
sudo apt-get install qemu
sudo apt-get install git
```
Then clone the git

`git clone https://github.com/C-Society/Xv6_systemcall.git`

`cd xv6`

As I have already done all the required things.Time to compile and run xv6 system on QEMU emulator.

`make`
`make qemu`

Now a new Qemu window will open. Type command

`ls`

It will list all the commands. So basically I have included 2 programs in it.

1. User defined program **first_program** whose output is

"Hello world this is our first program on Xv6"

2. System call **getyear** which displays the year in which the UNIX version of Xv6 is designed
