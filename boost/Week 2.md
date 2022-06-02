# Beginner Boost 2022

## Week 2

Apparently there is a way to get around using Windows Terminal from the Windows Store page, but I think we went on a tangent path and have yet to open Windows Terminal.
Perhaps we'll cross that bridge in week 4.

Learned difference between Terminal, CLI, and Shell. (See vocab below)

Learned the dire importance of `sudo` and `apt`. On a related note, we also learned how to install software from the CLI 

Bash commands learned so far:

* `apt` - Advanced Packaging Tool; essentially used to install and remove software. Use interactively only (use `apt-get` in scripts). Typically used with `sudo`.
* `cd` - Change Directory.
* `hostname` - Display host name of computer.
* `ls` - List files in *current* directory.
* `man` - Manual. VERY IMPORTANT! Append this with any other command to read the manual entry about that command, for example, `man cd`.
* `pwd` - Print Working Directory; tells you where you are.
* `sudo` - Essentially "run this command as root" (superuser). For example, `sudo apt upgrade`.

**CLI (Command Line Interface)** - Anything that takes input on a single line and then does REPL (Read, Evaluate, Print, Loop). Can technically be done without a terminal.

**grep** - A command for searching through text files "and stuff".

**inode** - An entry in a table. (A commmon thing to hear in UNIX is that *everything is just a file*)

**shell** - In the hierarchy of Hardware < Kernel < Shell < FTP, the shell (named for enveloping the Kernel and Hardware) is the level at which the user is able to 
interface with the computer with *shell languages* like bash and such can even be done remotely with SSH. Literally an interactive program providing access to another,
deeper system.

**terminal** - Derives from a literal, physical terminal which would allow direct interface with a given system. Presents a cel-based text screen. Historically, based
on the standard VT100 terminal invented to use a digital method to replace Teletype machines.
