Git-ignore
===

A quick script for downloading .gitignore templates from the official GitHub .gitignore repository, using the API.

License
---

Public domain.

Installation
---

Run `bundle install` inside the repo to grab the `rainbow` gem, used for coloring the output.

Symlink/copy the `git-ignore` file to somewhere in your `$PATH`.

Usage
---

Usage is simple, you can either list the available templates:

    # git ignore
    Output .gitignore templates to STDOUT.
    Usage: git-ignore <template> [template ...]
    Where <template> is one of:
    Actionscript, Android, AppceleratorTitanium, Autotools, Bancha, C, C++, CFWheels, CMake, CSharp, CakePHP, Clojure, CodeIgniter, ... etc

Or print one or more templates to STDOUT (so it can be quickly output or redirected into .gitignore):

    # git ignore C++ Android > .gitignore
    Fetching C++ .gitignore template..
    Fetching Android .gitignore template..
    Done.
