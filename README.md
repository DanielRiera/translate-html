# System of translate string HTML

Using jQuery for replace string depending the languaje selected or defined in a variable

# Dependencies

- jQuery

# Installation


1.- Copy lang.min.js in a folder
2.- Reference in index with script tag
3.- Create "lang" variable for control the languaje selected, using 1,2,3,4... for diferent languajes for example:

	
	lang = 1;

	/******
		1 = Spanish
		2 = English
		3 = French
		4 = Italian
	******/

4.- En your HTML include lg tag for translate string, example

Before
```HTML
<div>Hello</div>
```
After
```HTML
<div><lg>Hello</lg></div>
```