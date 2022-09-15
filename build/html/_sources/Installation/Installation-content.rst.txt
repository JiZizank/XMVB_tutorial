For Module Distribution
========================
After obtaining the compiled object xmvb.o of XMVB program, one will need to modify::

	set XMVB=false

to::

	set XMVB=true

in the *lked* script in GAMESS-US package. Then run the lked script to get GAMESS executable
with the whole capability of XMVB.

For Stand-Alone Distribution
=============================
The stand-alone distribution is released as a package of compiled executable files. To install the stand-alone distribution, the users should:
A	Unpack the compressed tar file by using the following command::

	tar xvfz xmvb.tar.gz

Once the file is unpacked successfully, a new directory **xmvb/** will be created.

B	Set the VBDIR environment variable to the location of XMVB package and append **xmvb/**
to your $PATH. The variable VBDIR is essential for PPD algorithm and utility PREINT(see
Section 6.2).
