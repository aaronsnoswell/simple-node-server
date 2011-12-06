# simple-node-server - A minimalist node.js web server

Serves any files in or below the current directory. Supports file extension
based mime-type detection and simple routes like

    "user/add" : function(file, request, result, contentType) {
        // etc...
    }

## Requires

Requires node (*nix, OSX) or node.exe (windows) to be on your path.
