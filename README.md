# Like 007, but different

A set of Node.js tools and utilities for creating CLIs.

* zx
* Automatic / easy to include tty/pty.
* Automatic / easy to get results of running external command.
* ARGV
* CONFIG / XDG
* sg-file
* cli-shezargs reboot

## ZX-like Magic

* But do not _need_ to put no-more-no-less than each ARG in one ${} construct.
* Easy to use a non-async version (if possible)?

## TTY / PTY

* Easy to make launched executable think it is on a TERM.

## Get Results from Launched Executable

* Assumes launched executable was launched for a result on its STDOUT.
* But still easy if not.

## ARGV

* Has command-line parsing utility.

## CONFIG / XDG

* Read settings from config file(s).
* Config files in correct dirs (according to XDG_ ...)

## SG-FILE

* Knows a lot about where things go on the file system
 * Like what goes into /bin, /usr/bin, etc. vs. /etc and /var and /home

## cli-shezargs Reboot

* MVP -- parsing args only





