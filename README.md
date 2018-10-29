# A Shell in C

A simple UNIX shell written in C with basic functionality. It demonstrates the basics of how a shell works. That is: read, parse, fork, exec, and wait. Since its purpose is demonstration (not feature completeness or even fitness for casual use), it has many limitations, including:

* Commands must be on a single line.
* Arguments must be separated by whitespace.
* No quoting arguments or escaping whitespace.
* No piping or redirection.
* Only builtins are: cd, help, exit.


## Running the Shell
To run the shell simply go to the native terminal and run the following code
```
$ gcc -g shell.c -lreadline
```
## Resources to read
* https://brennan.io/2015/01/16/write-a-shell-in-c/
* https://indradhanush.github.io/blog/writing-a-unix-shell-part-1/
