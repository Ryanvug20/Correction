# Correction
A small correction on a program

I was using a different version of python, resulting in a error upon reading the code in the linux terminal. Changed from python 2.7 to python 3.0

#!/usr/bin/python3
import sys

if len(sys.argv)==2:
    print("Knock, Knock, {0}".format(sys.argv[1]))
else:
    sys.stderr.write("Usage: {0} <name>\n".format(sys.argv[0]))
