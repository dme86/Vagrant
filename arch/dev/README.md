### Common commands

|Command| Description |
|--|--|
| pacman -Syu 'pkg' |Install (and update package list)  |
|pacman -S 'pkg |Install only |
|pacman -Rsc 'pkg' |Uninstall |
|pacman -Ss 'keywords' |Search |
|pacman -Syu |Upgrade everything |

### Query

|Command| Description |
|--|--|
|pacman -Qe |List explictly-installed packages |
|pacman -Ql 'pkg' |What files does this package have? |
|pacman -Qii 'pkg' |List information on package |
|pacman -Qo 'file' |Who owns this file? |
|pacman -Qs 'query |Search installed packages for keywords |

### Other

|Command| Description |
|--|--|
|pactree 'pkg' |What does _pkg_ depend on? |
|pactree -r 'pkg' |What depends on _pkg_? |
