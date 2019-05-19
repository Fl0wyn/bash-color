## Download
`curl -sL git.io/bashcolor > ~/.bashcolor`
## Import into a script
`source ~/.bashcolor`
## Use
`echo -e "$Gbu Hello $NC"`

***

# Foreground

### Color
* ` R=$(echo -e "\e[31m") # Red`
* ` G=$(echo -e "\e[32m") # Green`
* ` Y=$(echo -e "\e[33m") # Yellow`
* ` B=$(echo -e "\e[34m") # Blue`
* ` M=$(echo -e "\e[35m") # Magenta`
* ` C=$(echo -e "\e[36m") # Cyan`

### Color + Light
* `Rl=$(echo -e "\e[91m")                  # Red + Light`
* `Gl=$(echo -e "\e[92m")                  # Green + Light`
* `Yl=$(echo -e "\e[93m")                  # Yellow + Light`
* `Bl=$(echo -e "\e[94m")                  # Blue + Light`
* `Ml=$(echo -e "\e[95m")                  # Magenta + Light`
* `Cl=$(echo -e "\e[96m")                  # Cyan + Light`

### Color + Bold
* `Rb=$(echo -e "\e[31m\e[1m")             # Red + Bold`
* `Gb=$(echo -e "\e[32m\e[1m")             # Green + Bold`
* `Yb=$(echo -e "\e[33m\e[1m")             # Yellow + Bold`
* `Bb=$(echo -e "\e[34m\e[1m")             # Blue + Bold`
* `Mb=$(echo -e "\e[35m\e[1m")             # Magenta + Bold`
* `Cb=$(echo -e "\e[36m\e[1m")             # Cyan + Bold`

### Color + Underline
* `Ru=$(echo -e "\e[31m\e[4m")             # Red + Underline`
* `Gu=$(echo -e "\e[32m\e[4m")             # Green + Underline`
* `Yu=$(echo -e "\e[33m\e[4m")             # Yellow + Underline`
* `Bu=$(echo -e "\e[34m\e[4m")             # Blue + Underline`
* `Mu=$(echo -e "\e[35m\e[4m")             # Magenta + Underline`
* `Cu=$(echo -e "\e[36m\e[4m")             # Cyan + Underline`

### Color + Light + Underline
* `Rlu=$(echo -e "\e[91m\e[4m")            # Red + Light + Underline`
* `Glu=$(echo -e "\e[92m\e[4m")            # Green + Light + Underline`
* `Ylu=$(echo -e "\e[93m\e[4m")            # Yellow + Light + Underline`
* `Blu=$(echo -e "\e[94m\e[4m")            # Blue + Light + Underline`
* `Mlu=$(echo -e "\e[95m\e[4m")            # Magenta + Light + Underline`
* `Clu=$(echo -e "\e[96m\e[4m")            # Cyan + Light + Underline`

### Color + Bold + Underline
* `Rbu=$(echo -e "\e[31m\e[1m\e[4m")       # Red + Bold + Underline`
* `Gbu=$(echo -e "\e[32m\e[1m\e[4m")       # Green + Bold + Underline`
* `Ybu=$(echo -e "\e[33m\e[1m\e[4m")       # Yellow + Bold + Underline`
* `Bbu=$(echo -e "\e[34m\e[1m\e[4m")       # Blue + Bold + Underline`
* `Mbu=$(echo -e "\e[35m\e[1m\e[4m")       # Magenta + Bold + Underline`
* `Cbu=$(echo -e "\e[36m\e[1m\e[4m")       # Cyan + Bold + Underline`

***

# Background

### Background Color
* `RB=$(echo -e "\e[41m")                  # Background Color Red`
* `GB=$(echo -e "\e[42m")                  # Background Color Green`
* `YB=$(echo -e "\e[43m")                  # Background Color Yellow`
* `BB=$(echo -e "\e[44m")                  # Background Color Blue`
* `MB=$(echo -e "\e[45m")                  # Background Color Magenta`
* `CB=$(echo -e "\e[46m")                  # Background Color Cyan`

### Background Color + Light
* `RlB=$(echo -e "\e[101m")                # Background Color Red + Light`
* `GlB=$(echo -e "\e[102m")                # Background Color Green + Light`
* `YlB=$(echo -e "\e[103m")                # Background Color Yellow + Light`
* `BlB=$(echo -e "\e[104m")                # Background Color Blue + Light`
* `MlB=$(echo -e "\e[105m")                # Background Color Magenta + Light`
* `ClB=$(echo -e "\e[106m")                # Background Color Cyan + Light`
`
### Background Color + Bold
* `RBb=$(echo -e "\e[41m\e[1m")            # Background Color Red + Bold`
* `GBb=$(echo -e "\e[42m\e[1m")            # Background Color Green + Bold`
* `YBb=$(echo -e "\e[43m\e[1m")            # Background Color Yellow + Bold`
* `BBb=$(echo -e "\e[44m\e[1m")            # Background Color Blue + Bold`
* `MBb=$(echo -e "\e[45m\e[1m")            # Background Color Magenta + Bold`
* `CBb=$(echo -e "\e[46m\e[1m")            # Background Color Cyan + Bold`

### Background Color + Light + Bold
* `RlBb=$(echo -e "\e[101m\e[1m")          # Background Color Red + Light + Bold`
* `GlBb=$(echo -e "\e[102m\e[1m")          # Background Color Green + Light + Bold`
* `YlBb=$(echo -e "\e[103m\e[1m")          # Background Color Yellow + Light + Bold`
* `BlBb=$(echo -e "\e[104m\e[1m")          # Background Color Blue + Light + Bold`
* `MlBb=$(echo -e "\e[105m\e[1m")          # Background Color Magenta + Light + Bold`
* `ClBb=$(echo -e "\e[106m\e[1m")          # Background Color Cyan + Light + Bold`

### Background Color + Underline
* `RBu=$(echo -e "\e[41m\e[4m")            # Background Color Red + Underline`
* `GBu=$(echo -e "\e[42m\e[4m")            # Background Color Green + Underline`
* `YBu=$(echo -e "\e[43m\e[4m")            # Background Color Yellow + Underline`
* `BBu=$(echo -e "\e[44m\e[4m")            # Background Color Blue + Underline`
* `MBu=$(echo -e "\e[45m\e[4m")            # Background Color Magenta + Underline`
* `CBu=$(echo -e "\e[46m\e[4m")            # Background Color Cyan + Underline`

### Background Color + Light + Underline
* `RlBu=$(echo -e "\e[101m\e[4m")          # Background Color Red + Light + Underline`
* `GlBu=$(echo -e "\e[102m\e[4m")          # Background Color Green + Light + Underline`
* `YlBu=$(echo -e "\e[103m\e[4m")          # Background Color Yellow + Light + Underline`
* `BlBu=$(echo -e "\e[104m\e[4m")          # Background Color Blue + Light + Underline`
* `MlBu=$(echo -e "\e[105m\e[4m")          # Background Color Magenta + Light + Underline`
* `ClBu=$(echo -e "\e[106m\e[4m")          # Background Color Cyan + Light + Underline`

### Background Color + Bold + Underline
* `RBbu=$(echo -e "\e[41m\e[1m\e[4m")      # Background Color Red + Bold + Underline`
* `GBbu=$(echo -e "\e[42m\e[1m\e[4m")      # Background Color Green + Bold + Underline`
* `YBbu=$(echo -e "\e[43m\e[1m\e[4m")      # Background Color Yellow + Bold + Underline`
* `BBbu=$(echo -e "\e[44m\e[1m\e[4m")      # Background Color Blue + Bold + Underline`
* `MBbu=$(echo -e "\e[45m\e[1m\e[4m")      # Background Color Magenta + Bold + Underline`
* `CBbu=$(echo -e "\e[46m\e[1m\e[4m")      # Background Color Cyan + Bold + Underline`

### Background Color + Light + Bold + Underline
* `RlBbu=$(echo -e "\e[101m\e[1m\e[4m")    # Background Color Red + Light + Bold + Underline`
* `GlBbu=$(echo -e "\e[102m\e[1m\e[4m")    # Background Color Green + Light + Bold + Underline`
* `YlBbu=$(echo -e "\e[103m\e[1m\e[4m")    # Background Color Yellow + Light + Bold + Underline`
* `BlBbu=$(echo -e "\e[104m\e[1m\e[4m")    # Background Color Blue + Light + Bold + Underline`
* `MlBbu=$(echo -e "\e[105m\e[1m\e[4m")    # Background Color Magenta + Light + Bold + Underline`
* `ClBbu=$(echo -e "\e[106m\e[1m\e[4m")    # Background Color Cyan + Light + Bold + Underline`
***
* `bC=$(echo -e "\e[1m")           # Bold`
* `uC=$(echo -e "\e[4m")           # Underlined`
* `NC=$(echo -e "\e[0m")           # No Color`
