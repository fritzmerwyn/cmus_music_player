# CMUS Music Player - UPdate library

create file with:

#!/bin/bash
cmus-remote -C clear
cmus-remote -C "add ~/Music"
cmus-remote -C "update-cache -f"

and save somewhere handy (eg ~/)

open cmus and directly type:
:bind -f common u shell ~/update_cmus_library.sh
Press Enter
Press "u" to update library.
