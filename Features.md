## vstr enhancements ##

_if_ - use if statements

_strcmp_ - compare two strings

_math_ - use math functions with vstr

`---------------------------------------------------`

## Reduced map change spam ##

Moved debug text into developer print

`---------------------------------------------------`

## Console appearance controls ##

_scr\_conUseShader_ - 0/1 | Enable/Disable the use of console shader

_scr\_conColorAlpha_ - 0-1 | Scale of how much alpha layer is shown

_scr\_conColorRed_ - 0-1 | Scale of how much red layer is shown

_scr\_conColorBlue_ - 0-1 | Scale of how much blue layer is shown

_scr\_conColorGreen_ - 0-1 | Scale of how much green layer is shown

#### Console bar color/height ####

_scr\_conBarColorRed_  - 0-1 | Scale of how much red layer is shown

_scr\_conBarColorBlue_ - 0-1 | Scale of how much blue layer is shown

_scr\_conBarColorGreen_ - 0-1 | Scale of how much green layer is shown

_scr\_conBarHeight_ - 0-1 | Scale of how much big the console bar is

`---------------------------------------------------`

## Bloom ##

_r\_bloom_ - 0/1 | Enable/Disable bloom

_r\_bloom\_alpha_ - 0-1 | Scale of how much alpha layer is shown

_r\_bloom\_diamond\_size_ - Size of the diamonds

_r\_bloom\_intensity_ - Intensity of bloom

_r\_bloom\_darken_ - How much to darken bloom

_r\_bloom\_sample\_size_ - Number of samples

`---------------------------------------------------`

## Delay ##

Similar to wait, but allows for other functions to be used while delay is being used.

`---------------------------------------------------`

## Aliases ##

_alias_ - Set an alias for a command

_unalias_ - Remove an alias for a command

_aliaslist_ - List all current aliases

_clearaliases_ - Removes all aliases

`---------------------------------------------------`

## Cvar parsing ##

Allows for the usage of \$cvar\ be to replace by the value of the cvar. Use \$$cvar\ to retain \$cvar\ when restarting tremulous.

Example: "echo \$name\" will result in "Tachyon"