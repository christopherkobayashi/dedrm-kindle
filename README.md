# dedrm-kindle
DeDRM command-line tools for Kindle

You'll need:

* pycryptodome

Usage:

k4mobidedrm.py -s $(cat ~/kindle-serial | tr $'\n' ,$) ${PATH_TO_INPUT} ${PATH_TO_OUTPUT}/
