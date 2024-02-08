# PyCharm CLI Config Guide

This guide is to help you setup the PyCharm terminal command. This will let you open any code file or directory in PyCharm via the command line. This is similar to VSCode’s `code [name of file or directory]` .

1. Navigate to `/usr/local/bin` using your terminal.

2. Run `touch pycharm` from the location you navigated to in the previous step. This will create an empty file named ‘pycharm.’

3. Open the new ‘pycharm’ file in a code editor.

4. Add the following code block to the empty ‘pycharm’ file: 
```
#!/bin/sh

open -na "PyCharm CE.app" --args "$@"
```
5. Navigate back to `/usr/local/bin`. Run the following command to make the ‘pycharm’ file executable `chmod +x pycharm`

6. Now you can open the PyCharm from anywhere on your computer using the following commands: 
```
pycharm [name of file or directory]

---or---

pycharm .
```

This guide is based on PyCharm’s official [documentation](https://www.jetbrains.com/help/pycharm/working-with-the-ide-features-from-command-line.html#45050b20).
