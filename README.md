Wormhole
========

Unix file system shortcut utility based on [a blog post](http://jeroenjanssens.com/2013/08/16/quickly-navigate-your-filesystem-from-the-command-line.html) by Jeroen Janssens. His shell shortcut functions are practical but I vastly prefer one command with different flags as opposed to different commands for the same utility. Because of this I put together Wormhole.

Wormhole lets you create shortcuts in your file tree to quickly navigate from one remote directory to another.

![screenshot](http://cl.ly/image/2m2x1y1f1y0w/Screen%20Shot%202013-08-27%20at%204.22.56%20PM.png)

Commands
---------------------

* ` whole <name> ::> Jump through wormhole `
* ` whole -a <name> ::> Add working directory to wormholes `
* ` whole -r <name> ::> Remove <name> from wormholes `
* ` whole -l ::> Lists all current wormholes `
* ` whole -h ::> Display this message `

Installation
---------------------

Just add the script to your `.bashrc` or `.bash_profile` and you'll be good to go after you refresh your configuration. 

Installation on OS X:

1. Open the Terminal.
2. Navigate to your home directory: `cd`
3. Create a .bash_profile: `touch .bash_profile`
4. Copy the function to your clipboard and edit the newly created profile: `pico .bash_profile`
5. Paste the function into your profile and save: <kbd>Ctrl</kbd>+<kbd>X</kbd>. Confirm by typing `y` and return.
6. Refresh your bash configuration: `. .bash_profile`

That would be the *whole* shebang.

License
---------------------

Wormhole is licensed under [COPYPASTE](http://cp.kuri.mu/).
