# Node.js Import Example

## In `package.json`

    "type": "module",
    "imports": {
        "#local/*": "./some/deeply/nested/*"
    },

## In index.js

    import importedHi from '#local/file.js';
    importedHi(2);
