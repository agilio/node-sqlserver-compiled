# Compiled SQL Server driver #

This is a convenience package providing simplified access to **msnodesql-0.2.1-v0.6-ia32.msi** obtainable from [MS Downloads](http://www.microsoft.com/en-us/download/details.aspx?id=29995). This means:

- It works with **0.6.x** version of Node.js.
- Node.js has to be **32bit (x86)**.
- The bitness of the OS doesn't matter - this package will work on both Windows x86 and x64.

## Background info ##

This is a helper package that provides compiled version of the standard
[msnodesql package](https://github.com/WindowsAzure/node-sqlserver). The original package is meant to be compiled locally using Python, Visual C++ etc. This package provides compiled binaries that can be referenced from `package.json` directly.

Only the necessary files are kept so folders like `src` and `test` are not included.

## Usage ##

Use it in a Node.js project by including this in the dependies section of `package.json`:

    "dependencies" : {
        // ...
        "node-sqlserver": "https://github.com/agilio/node-sqlserver-compiled/tarball/master",
        // ...
    }
