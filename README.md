# nvflip
Reverse or set the state of "flipping" on an Nvidia graphics card. This is handy when using screen recorders for screencasting. Simple Screen Recorder does this check, but some other recorders do not.

# Syntax
    nvflip [off|on]
Reverse flipping state: `nvflip`

Turn flipping off     : `nvflip off`

Turn flipping on      : `nvflip on`

# Notes
This little script illustrates writing the result of one command to a temporary file, then reading the results of that file to make a decision. This script does require Nvidia hardware drivers in Linux (BSD?). 
