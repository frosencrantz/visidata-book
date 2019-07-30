The VisiData class is a singleton, containing all of the 'global' state for the current session. Currently, it must be available in the `vd` global. Eventually, it might be substitutable for perhaps multiple shared sessions.

`from visidata import vd`, then the global API would be everything on the VisiData object.
