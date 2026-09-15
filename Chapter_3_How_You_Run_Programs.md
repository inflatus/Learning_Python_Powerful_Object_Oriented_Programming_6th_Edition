# Chapter 3

## How You Run Programs

### Notes

>Now it is time for code. To run Python scripts and applications, Python must be installed. The official website for downloading the language is [Python.org](https://www.python.org/downloads/).
>This site offers source code for multiple operating systems. At the time of this note, the version shown is 3.14.7 (stable). Even though this is not the bleeding edge of the language, it is the recommended version. From this site, you can also find installation instructions.
>Interactive code: once it is installed, you can run code in the REPL (read, evaluate, print, loop). This is Python's interactive mode.
>Where to run: in code folders.
>Deciding where to store working code or scripts is worth considering. Code that depends on other code should go into the same folder. Separating code is useful when trying to differentiate between thought processes. For example, all math scripts could go in a math folder, and the script that checks the weather could be in its own folder. The structure is personal.
>When to use the prompt: use it during learning and testing. It can be used to execute code quickly to verify syntax and understanding. This helps prevent many micro-scripts that may not necessarily be saved. Again, this is personal. In this case, documentation is key for me, and I want to be able to show something I coded.
>Created the first script. Ran it through the REPL as well. I was able to see the output. I did not see anything when running the script in the terminal. Make sure you are running in the directory of the script. I was not able to see the output of the script because, in VS Code, there is a section in the top-right to run and debug your code. I tried to run the code from the terminal window within VS Code, and it did not display.
>There are many other IDLEs available to run code, including web-based options, applications, and even smartphones.
>Running code within code: importing modules means using .py files. There is nothing that makes a file a module other than the fact that it has a .py extension. Where to run imports is within a folder. Ensure that all files needed for import are within that folder.
>Reloading modules is used when you need to import more than once in a session. This seems especially useful while using the REPL. Reload requires parentheses, and import does not. Reload is object-based, and import is a statement.
>The exec builtin is used when not using modules to import. The function runs it as if it were a string.
>Command-line launchers can run the code as if it were using the terminal. The os module provides this ability.
---
---

### Synopsis
>Deciding on a version of Python should at least be the stable version. I can see a time when needing to use an older or newer version would be helpful for testing code. The REPL choice does not seem to be much of one. The built-in REPL should suffice for learning the language and getting a grasp on functionality.
>The first script is in a separate folder within the repository. Now that this has started, I will see how well my thought process is at keeping things organized.