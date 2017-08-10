# sublime-keymap


[
    // Movement
    { "keys": ["ctrl+b"], "command": "move", "args": {"by": "characters", "forward": false} },
    { "keys": ["ctrl+f"], "command": "move", "args": {"by": "characters", "forward": true} },
    { "keys": ["ctrl+p"], "command": "move", "args": {"by": "lines", "forward": false} },
    { "keys": ["ctrl+n"], "command": "move", "args": {"by": "lines", "forward": true} },

    { "keys": ["ctrl+a"], "command": "move_to", "args": {"to": "bol", "extend": false} },
    { "keys": ["ctrl+e"], "command": "move_to", "args": {"to": "eol", "extend": false} },

    // Find
    { "keys": ["ctrl+shift+f"], "command": "show_panel", "args": {"panel": "find", "reverse": false} },

    // Add folder to project
    { "keys": ["ctrl+shift+o"], "command": "prompt_add_folder" },

    // Refresh File Tree
    { "keys": ["f5"], "command": "refresh_folder_list" }
]
