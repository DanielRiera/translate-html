# System of translate string HTML

Using jQuery for replace string, option of ```<select>``` tag, placeholder of ```<inputs>``` or ```<textarea>``` depending the languaje selected or defined in a variable

Note: I´m using this system for Phonegap Apps

### Dependencies

- jQuery

### Installation


- Copy lang.min.js in a folder.
- Reference in index with script tag.
- Create "lang" variable for control the languaje selected, using 1,2,3,4... for diferent languajes for example:
	```	
	lang = 1;

	/******
		1 = Spanish
		2 = English
		3 = French
		4 = Italian
	******/
	```
- En your HTML include lg tag for translate string, example.

Before
```HTML
<div>Hello</div>
```
After
```HTML
<div><lg>Hello</lg></div>
```

- Create a JSON archive contain the translate string, using 'demo.json' as a guide.

- Now every time change the DOM, the strings be translated.

### Changelog

1. 2016/08/19 - Is created repository