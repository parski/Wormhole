Wormhole
========

Unix file system shortcut utility based on a blog post by Jeroen Janssens. His shell shortcut functions are brilliant in their simplicity but I vastly prefer one command with different flags as opposed to different commands for the same utility. Because of this I put together Wormhole.

` whole <name> ::> Jump through wormhole `
` whole -a <name> ::> Add working directory to wormholes `
` whole -r <name> ::> Remove <name> from wormholes `
` whole -l ::> Lists all current wormholes `
` whole -h ::> Display this message `

Just add the script to your `.bashrc` or `.bash_profile` and you'll be good to go after you refresh your configuration. Do so by `. .bash_profile`
