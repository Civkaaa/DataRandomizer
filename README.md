# DataRandomizer
## Description
App that generates random data files of different format. Used to generate data for debugging programs. Programm currently supports 2 types of patterns for generation. All generation patterns support various tweaking and customization. 
All generated data is stored in a plain txt file and is placed in a current program folder by default.

![изображение](https://github.com/sv022/DataRandomizer/assets/83920644/1daf41bc-293d-46da-90e7-0b2a0ae5693b)


## Installation
>Installation from the source code guide

	Install pyinstaller (`pip install -U pyinstaller`)
	
	Open cmd in your final program folder
	
	`pyinstaller -F -w -i "icon.ico" DataGenerator.py`
	
	!logo.gif, icon.ico and .py file must be in the same folder, otherwise use absolute path!

> installation from the .zip archive

	unextract the archive
	
	!logo.gif, icon.ico and the executable must always be in one folder!
