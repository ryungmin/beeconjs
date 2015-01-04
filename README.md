beeconjs
=========
BeeconJS - remote control javascript library

 BeeconJS Java Library v0.0.1
 http://beeconjs.com/
 
 Copyright 2015, Dayyoung You
 Dual licensed under the MIT or GPL Version 2 licenses.
 Visit http://beeconjs.com/license 
 
This is  BeeconJS Javascript Library for web. 

## Installation

Include Script on your site.

src="http://code.jquery.com/jquery-1.11.1.min.js"
src="http://beeconjs.com/socket.io/socket.io.js"
src="http://beeconjs.com/js/beecon-0.1.1.js"

src="http://asia.beeconjs.com/js/beecon-0.1.0.js?region=asia"
//this is strict option to asia region. 
script src="http://beeconjs.com/js/beecon-0.1.0.js?badge=true"
//this is badge option to display icon. 

## Usage
		

var BeeconBee = new Bee('BeeconJS.com',1);
//inflate Bee.

var BEEIMG = $('#beeImg');
//select image object. 

BeeconBee.addButton(1,"B",function(){  
  BEEIMG.attr('src', "/img/bee1.png");
});
//add button1 to change image. 

BeeconBee.addButton(2,"E",function(){  
  BEEIMG.attr('src', "/img/bee2.png");
});
//add button1 to change image.

BeeconBee.addButton(3,"E",function(){  
  BEEIMG.attr('src', "/img/bee3.png");
});
//add button1 to change image.
	
		
## Features

http://www.beeconjs.com/api

## License

Dual licensed under the MIT or GPL Version 2 licenses.
 
