# Bash Support for BBEdit

A port of [Bash Support for Vim](https://github.com/vim-scripts/bash-support.vim)

Utilizing Clippings in BBEdit we can achieve roughly the same behavior. I've been an
avid Bash Support user in Vim but have since moved 100% to BBEdit. Included are my
most used features. Mainly for generating a file header, comments and auto-completion
of common shell statements.

## Installation

Copy the Bash Support folder to your `~/Library/Application Support/BBEdit/Clippings` directory.

When working with a shell file, you can begin typing `File Header` or selecting from Menu > Clippings > Bash Support > Comments and it will generate the following:

```
#!/bin/bash -
#===============================================================================
#
#          FILE: my_script.sh
#
#         USAGE: ./my_script.sh
#
#   DESCRIPTION:
#
#       OPTIONS: ---
#  REQUIREMENTS: ---
#          BUGS: ---
#         NOTES: ---
#        AUTHOR: Andrew Diver
#  ORGANIZATION:
#       CREATED: 04/27/2020 11:29:52
#      REVISION: ---
#===============================================================================

set -o nounset                              # Treat unset variables as an error

```

You can view the other Clippings examples via this repo or install and play.

## To-do

Add common Tests
