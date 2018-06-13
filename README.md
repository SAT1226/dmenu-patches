# dmenu4.8 patches

## dmenu-migemo.patch
Add migemo matching to dmenu.     
Using migemo matching:   

    $ dmenu -migemo

Default migemo dictionary: '/usr/share/migemo/utf-8/migemo-dict'   

#### Dependencies:
* [C/Migemo](https://github.com/koron/cmigemo)
* [PCRE](https://www.pcre.org/)

## dmenu-keybinds.patch
Change keybinds.

|Keys|Description|
| ---- | ---- |
|Tab|Up|
|Shift + Tab|Down|
|Shift + Insert|Paste from primary X selection|
|Ctrl  + Space|Copy the selected item to the input|field.
|Ctrl  + v|Paste from X clipboard|
|Ctrl  + V|Paste from primary X selection|
|Ctrl  + BackSpace|Delete word left|

## License
MIT License

