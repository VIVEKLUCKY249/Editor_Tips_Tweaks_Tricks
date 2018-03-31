# Editor_Tips_Tweaks_Tricks

## All the available and suggestable tips, tweaks, tricks and plugins for famous code editors like Sublime Text 3, Geany, VSCode, Komodo Edit 11, PhpStorm etc. ##

### Sublime Text 3 Recommended Plugins and their optimal settings ###

#### Links: ####
http://www.sublimelinter.com/en/stable/  
https://github.com/SublimeLinter/SublimeLinter  
https://github.com/SublimeLinter/SublimeLinter-php  
https://github.com/SublimeLinter/SublimeLinter-jsl  

#### Settings: ####

```sublime-settings
// %AppData%\..\Roaming\Sublime Text 3\Packages\User\SublimeLinter.sublime-settings
{
    "linters": {
        "php": {
            "cmd": "C:\\Webroot\\php5633\\php.exe",
            "cmd": "C:/Webroot/php5633/php.exe"
        }
    },
    "paths": {
        "windows":[
            "C:\\Webroot\\Jsl030\\jsl.exe"
        ],
        "windows":[
            "C:/Webroot/Jsl030/jsl.exe"
        ]
    }
}
```

### Sublime Text 3 User Specific Settings ###
```sublime-settings
// User specific settings for ST3 Editor
{
	"bold_folder_labels": true,
	"detect_indentation": true,
	"font_size": 12,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_to_bracket": true,
	"tab_size": 4,
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true,
	"use_tab_stops": true,
	"word_wrap": true
}
```
