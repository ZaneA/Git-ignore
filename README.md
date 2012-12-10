Git-ignore
===

A quick script for downloading .gitignore templates from the official GitHub .gitignore repository, using the API.

License
---

Public domain.

Installation
---

Run `bundle install` inside the repo to grab the `rainbow` gem, used for coloring the output.

Symlink the `git-ignore` file into your `~/bin`.

Usage
---

Usage is simple, you can either list the available templates:

    # git ignore
    Usage: git-ignore <template> [template ...]
    Where <template> is one of:
    Actionscript, Android, AppceleratorTitanium, Autotools, Bancha, C, C++, CFWheels, CMake, CSharp, CakePHP, Clojure, CodeIgniter, ... etc

Or download one or more templates into a `.gitignore` in the current directory:

    # git ignore C++ Android
    Fetching C++ .gitignore template..
    Fetching Android .gitignore template..
    Done.
