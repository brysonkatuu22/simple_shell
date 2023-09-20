.SH NAME
.B simple_shell \- simple UNIX command interpreter made in C



BY BRYSON KATUU AND FAVOUR NKANDA



.SH SYNOPSIS
$ /hsh [options] [file]

.SH DESCRIPTION
Simple_Shell is a command language interpreter that executes commands read from the standard input.
Clone of sh

.SH Return Value

Always returns the status of the previously executed command ( 0 if no command was executed) , number means exit fail codes

.SH PATH

looks in PATH env variable for executable program file location.

.SH

.B Invocation
.in +2n
simple_shell can be invoked both interactively and non-interactively.
If invoked with standard input not connected to a terminal, it reads and executes received commands in order.

If simple_shell is invoked with standard input connected to a terminal, an interactive shell is opened.
When executing interactively, the simpl_shell displays the prompt \"($) "\ when it is ready to read a command.

.SH OPTIONS
.B simple_shell
Command options will be typed after the main command followed by a space and a
 '-' symbol.

.SH EXAMPLE

./hsh [command] [options]
$ ls -l




.SH BUGS
not many found.






.SH AUTHOR
BRYSON KATUU
FAVOUR NKANDA
