
<!--#echo json="package.json" key="name" underline="=" -->
read-data-directory-hierarchy-pmb
=================================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Read a all data files into an object that mimics the directory hierarchy.
<!--/#echo -->



API
---

This module exports one function:

### read-data-directory-hierarchy-pmb(how)

`how` is an optional options object that supports these keys:

*

:TODO:


Usage
-----

:TODO:



<!--#toc stop="scan" -->



Security considerations
-----------------------

* Weird stuff™ can happen if the directories or files to be read change while
  they're being compiled.
* All symlinks are trusted, so all your symlink tricks are on the menu.



Known issues
------------

* Needs more/better tests and docs.




&nbsp;


License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->
