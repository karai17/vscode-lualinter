# vscode-lualinter

A simple [Visual Studio Code](https://code.visualstudio.com/) extension to lint Lua scripts with [luac -p](https://www.lua.org/manual/5.1/luac.html).

![Example screenshot](http://i.imgur.com/hm3dSEC.png)

![Example animation](https://thumbs.gfycat.com/BoringThinCockerspaniel-size_restricted.gif)

## Requirements
1. Ensure that `luac` is installed in your system.
2. Run [`Install Extension`](https://code.visualstudio.com/docs/editor/extension-gallery#_install-an-extension) command from [Command Palette](https://code.visualstudio.com/Docs/editor/codebasics#_command-palette).
3. Search and choose `lualinter`.

## Options
`"lualinter.enable"` - enable Lua linter

`"lualinter.warnOnSave"` - show warning message if there is an error when saving a file

Default options values are:
```json
{
    "lualinter.enable": true,
    "lualinter.warnOnSave": false
}        
```

**Enjoy!**