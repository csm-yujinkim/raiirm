# `raiirm`

## Description

Executes a script file called `.raiirm` upon deletion of a directory (if it exists) to handle resource management tied to the existence of said directory.

If the script does not exist, or if the script returns a non-zero exit code, `raiirm` stops and alerts the user.

