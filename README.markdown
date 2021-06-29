macOS recipes
=============

These 'recipes' are meant to be installed as they are or
executed through something like my [`recipe` script][recipe.sh].

[recipe.sh]: https://github.com/giucal/scripts/blob/master/recipe.sh

Summary
-------

Here's a brief explanation for each of them.

    hidden-files (show|hide)

Tells the Finder to show or hide dot-files and files with the hidden
flag set. **Will restart the Finder process.**

    reset-launchpad

Resets the Lauchpad, forcing it to re-sort apps.
**Will restart the Dock process.**

    spotlight-indexing (on|off)

Activates or deactivates Spotlight's file indexing. When indexing
is off, some apps' functionalities will stop working.

    create-desktop (on|off)

Re-enables or disables the desktop.

    itunes-backup (status|on|off)

Turns pre-sync backups for iDevices on or off.

    caffeiname <process-name>

`caffainate`s a process by name.

    ytdl <URL>

Downloads a video and extracts its audio. Requires [youtube-dl].

[youtube-dl]: https://youtube-dl.org/
