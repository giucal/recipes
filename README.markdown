macOS recipes
=============

These 'recipes' are meant to be installed as they are or put somewhere
and executed through something like my [`recipe` script][recipe.sh].

[recipe.sh]: https://github.com/giucal/scripts/blob/master/recipe.sh

Summary
-------

Here's a brief explanation for each of them.

    hidden-files (show|hide)

Tells the Finder to show or hide dot-files and files with the hidden
flag set. By default, Finder doesn't show these files.
**Will restart the Finder process.**

    reset-launchpad

Resets the Lauchpad, which will then re-sort apps.
**Will restart the Dock process.**

    spotlight-indexing (on|off)

Activates or deactivates Spotlight's file indexing. When indexing
is off, some apps's functionalities will stop working.
