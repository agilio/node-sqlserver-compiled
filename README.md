# Compiled Node.js driver for SQL Server

This package contains the result of compilation of the [node-sqlserver package](https://github.com/WindowsAzure/node-sqlserver) - technically, it is the result of `npm install node-sqlserver` on Windows x64.

It is a convenience package as it doesn't require developer to have Python, Visual C++ and other dependencies installed.

Use it in a Node.js project by including this in the dependies section of `package.json`:

    "dependencies" : {
        // ...
        "node-sqlserver": <git URL here (TODO)>,
        // ...
    }