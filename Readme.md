<!-- View this file with a Markdown editor (eg: http://markdownpad.com) -->
# Show Orienteering Results


## What it is
Web page to show orienteering results to the public.

The results are shown in a typical web page and then scrolled automatically until the end of the page. When the end of the page is reached the results are refreshed, and we start again at the top.

We will try to show two different columns with results. Like this we can cycle the results twice as fast. The idea would be to show for example Men on the left and women on the right.


## Usage
Just load the page in the browser. The page will do the rest of the work without any user intervention. It will only be necessary to keep refreshing the results from an external source (normally the event manager software). 

The names of the pages involved will be defined at a later stage.


## Problems
In a first approach the page uses IFrames to include the results page. This can cause security issues with some browsers.

In the first version it works fine in Internet Explorer 11 and Firefox 42. But it does not work in Chrome 46.


## Installation
No installation should be necessary.


## Configuration
Here are the things that need to be done once you have all the hardware setup. This is necessary since the resolution of the display will differ, and also their ability to display all the information.

### Font size
The font size must be defined by this page, since MT does not take it into account.

Go to the function `prepareIFrame` locate the lines that change the font and put there the values you want.

### MT results export
The size of the columns must be set on the MT software. Since that software does not take the font size into account when publishing results, we just have to keep trying until we get a good enough result.

### Page margin
Some TVs might cut a little of the page on the left and on the right. To account for this set the margin of the `body` tag on the CSS styles at the top of the page. 


## Dependencies
Uses JQuery 2.1.4.




## Authors
Developed by [Rui Botão][rui].


## Licensing
MIT.


## Bibliography
[JQuery][jquery].




<br><br><br>
Written by [Rui Botão][rui].<br>
Nov 2015


[rui]: mailto:rui@ruibotao.com "Rui"
[jquery]: http://jquery.com/  "JQuery"
