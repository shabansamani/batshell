# BATSHELL
The shell that you deserve, but not the one you need.
Implement Unix shell (similar to bash) in C++. It will make use of low-level system calls (does NOT use *system*, *popen*, or *pclose* system calls or functions.

## Requirements
### Prompt
Should read input from the prompt and divide it into words and operators. Should employ quoting rules
Should include **"BATSHELL:"** followed by the present working directory, the **$** symbol.
...If present working directory is the home directory, a tilde (~) should replace the absolute path of the home directory