headeradder
===========

Adds optional headers to source files (currently only C-style comments supported)

To remove headers:
../headeradder/headers.py -e ../tinia-license.txt -k "Copyright STIFTELSEN SINTEF 2012"  -x -r .

Then add them with new year:
../headeradder/headers.py -e ../tinia-license.txt -k "Copyright STIFTELSEN SINTEF 2014" -r .


