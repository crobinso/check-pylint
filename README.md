### check-pylint

Simple helper script that scoops up all python modules and scripts beneath
the current directory, and passes them through pylint and pycodestyle. Has
a bit of smarts to ignore .git directory, and handle files that don't end
in .py

The point is that you can just fire off 'check-pylint' in any directory
containing python code and get a quick report.

To install, just symlink 'check-pylint' somewhere into your $PATH

To change the pep8/pylint config, put a config file in a standard
location for each tool, for example

* pycodestyle: ~/.config/pycodestyle
* pylint: ~/.config/pylintrc
