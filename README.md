# dedrm-kindle
DeDRM command-line tools for Kindle.

Extracted from Apprentice Alf's DeDRM_tools, release v7.2.1.

## Why?

Because the official DeDRM_tools dropped command-line support in favor of Calibre-only plugin.

Calibre is bloated, and the creator is egomaniacal and untrustworthy.  All I need is a way to remove DRM from my Kindle books -- no conversion, no categorization, no tracking by the Calibre creator.

You'll need:

* pycryptodome

Usage:

k4mobidedrm.py -s $(cat ~/kindle-serial | tr $'\n' ,$) ${PATH_TO_INPUT} ${PATH_TO_OUTPUT}/
