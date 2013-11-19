Print 202
=====

Usage
----

To print local files just give the name, for arXiv files link to the pdf

Example:
	$ ./printfile foo.pdf http://arxiv.org/pdf/XXXX.XXXX.vX.pdf bar.pdf

Authenitcation
-------------

In order not to have to enter a password every time do as follows,

1. Generate an ssh key if you don't already have one:
	$ ssh-keygen

2. Copy the key to the server:
	$ ssh ssh-copy-id atom@143.239.221.57

Bam, the server will no longer ask you for the password for ssh.

TODO
----

[ ] Stop hardcoding the server and login
[ ] Check multiple files work
[ ] Make only one ssh connection per session
[ ] Have the script read and summarise the paper in an understandable manner
[x] At least print single things
