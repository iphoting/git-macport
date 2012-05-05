# Git DVCS for MacPorts

From the [git website][site]:

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

> Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

[site]: http://git-scm.com/

## About

The port came about as the official git port on MacPorts repository is unmaintained.

## Installation

1. Clone this repo to a permanent path.
2. Add this cloned path to `/opt/local/etc/macports/sources.conf` *before* the default rsync line:

	`file:///path/to/git-macport`

3. `port -v sync`.
4. `port -v <install|upgrade> git-core`.

## Credits
Software written by respective owners.