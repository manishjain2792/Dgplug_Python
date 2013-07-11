======
Mount
======

Problem:
--------
Write a python program which gives the same output as while typing "mount" command in the terminal.

Code Snippet
------------

::

  1. #!/usr/bin/env python
  2. file=open("/proc/mounts") # open file named "/proc/mounts
  3. print file.read() # read that file and print it
  4. file.close() # it closes that file after reading it

Explanation
-----------
At first open the file **.proc/mounts** using "open" command. Then i used "file.read()" command to read the file and use **print** to print the content of that file. At last i closed that file using "file.close()" command.

The code is `here <https://github.com/manishjain2792/dgplug_python/mount/mount.py>`

How to execute:
---------------
::
    $ python mount.py

or

::
    $ chmod +x mount.py
    $ ./mount.py



