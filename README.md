# ScriptForAnki
This Bash script is for preparing an Anki import with | (pipe) as a delimitor. You are to manually edit in the answers from the resulting file OR Modify the script.

Usage is stated in the script file.

This will only work for questions that are stated in this order:

QUESTION

OPTION

OPTION

OPTION

[...]

OPTION

if it's like this: 

QUESTION


OPTION

OPTION

then you will be getting a newline and a pipe which you have to remove.
