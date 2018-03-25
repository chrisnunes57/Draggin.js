# Draggin.js
A fully multi-platform Javascript library for easily and quickly creating interactive user interfaces.
## [DEMO](https://draggin.surge.sh)
## Inspiration
This project was created with simplicity and abstraction in mind. Draggin.js is the first complete drag and drop library that you can use without writing a single line of Javascript. I wanted a library that I could use with ease, instead of spending extra time configuring a heavy library.
## Features
- *SERIOUSLY* Lightweight (3kb when compressed!)
- **Fully** touch compatible
- No need to write Javascript code
- Once included, is **instantly** usable
- Editable text!
- Leverages GPU for increased performance
- ***ZERO DEPENDENCIES***
     - Written in vanilla Javascript
     - No extraneous CSS or JS needed
## Get Started
To use the script, simply include it in your webpage in a ```<script>``` tag:
```
<script type="text/javascript" src="https://chrisnunes.net/draggin.js"></script>
```
### OR

Download the draggin.min.js file above and include it in your webpage:
```
<script type="text/javascript" src="draggin.min.js"></script>
```
#### NOTE
Don't include this script in the ```<head>``` of your page. Draggin.js must run after your whole page has rendered for it to work, so include it at the very end of your ```<body>``` tag. This is better practice than including scripts in the ```<head>```.
## Usage
Draggin.js is designed with simplicity in mind. Once you have included the script in your page, all you have to do is render an element and give it a class of "draggable."
```
<h1 class="draggable">Hello, World!</h1>
```
To use the editable text that is part of Draggin.js, use any text element and give it a class of "text.
```
<h1 class="text">Hello, World!</h1>
<p class="text">Hello, World!</p>
<a href="#" class="text">Hello, World!</a>
<div class="text">Hello, World!</div>
```
All of the above are valid examples of editable text. You can also combine both classes for the intended experience. 
Simply click once to drag elements, and double click to edit text.
```
<h1 class="draggable text">Both tags work at the same time!</h1>
```
## Future Developments
- React.js Port 
- Resizable Elements
