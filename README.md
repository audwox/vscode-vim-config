# vscode-vim-config

```json
{
    "vim.useSystemClipboard": true,
    "vim.hlsearch": true,
    "vim.handleKeys": {
       "<C-a>": false,
       "<C-c>": false,
       "<C-d>": false,
       "<C-k>": false,
       "<C-->": false,
    },
    "vim.normalModeKeyBindingsNonRecursive": [
        {
            "before": ["j"],
            "after": ["g", "j"]
        },
        {
            "before": ["k"],
            "after": ["g", "k"]
        },
        {
            "before": ["u"],
            "after": [],
            "commands": [
                {
                    "command": "undo",
                    "args": []
                }
            ]
        },
        {
            "before": ["<C-r>"],
            "after": [],
            "commands": [
                {
                    "command": "redo",
                    "args": []
                }
            ]
        }
    ]
}
```
