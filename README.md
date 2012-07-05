# Compiled SQL Server driver for 32-bit Node.js

Important: **this will only work with 32-bit version of Node.js**.

This package contains the compiled [node-sqlserver package](https://github.com/WindowsAzure/node-sqlserver). Technically, it is a result of `npm install node-sqlserver` on Windows.

It is a convenience package as it doesn't require a developer's PC to have Python, Visual C++ etc. installed.

Use it in a Node.js project by including this in the dependies section of `package.json`:

    "dependencies" : {
        // ...
        "node-sqlserver": "https://github.com/agilio/node-sqlserver-compiled/tarball/master",
        // ...
    }
