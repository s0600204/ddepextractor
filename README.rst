
Debian Package Build Dependency Extractor
"""""""""""""""""""""""""""""""""""""""""

Reads a ``debian/control`` file and exports a list of build dependencies in a
format that can be piped to ``apt-get install``.

.. Note: Due to ``apt``/``apt-get``'s inability to support ``lt``, ``le``,
         ``ge``, or ``gt`` versioning when specifying packages, this context is
         removed.

Usage
'''''

1. Navigate to the root directory of a package being packaged (the folder above
   ``debian``.

2. Run ``ddepextract``.
