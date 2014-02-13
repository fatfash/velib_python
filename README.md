velib_python
============
This is the general Victron Energy python library. Today it only contains code
that is related to dbus and the Color Control GX. Note that busitem.py,
dbusitem.py and tracing.py are deprecated. See vedbus.py instead.

Also note that finishing up vedbus.py is still in
the works.


Code style
==========

Comply with PEP8, except:
- use tabs instead of spaces, since we use tabs for all projects within Victron.
- max line length = 110

pep8 --max-line-length=110 --ignore=W191 *.py
