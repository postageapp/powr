# powr

Simple Pow process manager.

## Usage

To stamp out a `tmp/restart.txt` file that will cause the Ruby Rack processes
to restart on the next load:

    powr

To show all Ruby Rack processes for the current application that are running:

    powr -s

To kill off all Ruby Rack processes for the current application:

    powr -k

## Notes

The location of the Rails root is determined based on the presence of a
`config/database.yml` file.

## Copyright

Copyright (c) 2014 Scott Tadman. See LICENSE.txt for
further details.

