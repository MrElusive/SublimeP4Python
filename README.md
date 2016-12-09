# SublimeP4Python

P4Python API packaged for use as a Package Control 3 dependency.

This dependency was created by extracting the Python wheels hosted on the [P4Python](https://pypi.python.org/pypi/P4Python) package index.
All credit for the P4Python API itself goes to Perforce Software Inc.

## Installation

You should not need to install this dependency yourself. Package Control 3 will install it automatically if you
install a plugin that requires it (such as [Subforce](https://github.com/MrElusive/Subforce)).

However, if you need to install this dependency manually for development reasons:

1. Clone this repository to your Sublime Text Packages directory.

        $ cd path/to/Packages
        $ git clone https://github.com/MrElusive/SublimeP4Python.git

2. Add a .sublime-dependency file to the root directory of SublimeP4Python with the following text:

        50

3. Run "Package Control: Install Local Dependency" in Sublime.
