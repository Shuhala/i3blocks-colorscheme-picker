# i3blocks-colorscheme-picker
Script to display a directory images name in a dropdown menu on click with _rufi_ to quickly change the desktop wallpaper and colorscheme with _pywal_.

## Requirements
- i3blocks
- pywal
- rofi
- FontAwesome (optional) for the icon

## Usage
Give execute permission to the script with `chmod +x colorscheme-picker` and add the `[colorscheme-picker]` block to your `.i3blocks.conf`.

```
colorscheme-picker [-h] [-d directory] [-p options (optional)] -- display a menu to change your wallpaper and colorscheme with pywal and rofi:
    -h  help
    -d  wallpapers directory
    -p  override pywal options
```

Example:
```
[colorscheme-picker]
command=$SCRIPT_PATH/colorscheme-picker -d $WALLPAPERS_DIRECTORY
full_text=
```

Enjoy!
