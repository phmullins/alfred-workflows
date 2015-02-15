# OmniFocus

[OmniFocus](https://www.omnigroup.com/omnifocus) is an [Alfred](http://www.alfredapp.com/) workflow for [OS X](https://www.apple.com/osx/)
that makes creating new OmniFocus tasks easy.

Example:

!["OmniFocus Workflow"](https://github.com/phmullins/IBM-Search/blob/master/assets/alfred_bluepages_ss.png)

## Requirements

- [Alfred](http://www.alfredapp.com/)
- Alfred [Powerpack](http://www.alfredapp.com/powerpack/)
- net.pmullins.omnifocus.alfred Workflow

## Usage

Type `of` in Alfred followed by the task you would like to create. You can specify a due date by using the `#` modifier. 

Example:

`of Call Alfred #tomorrow at 12pm`

A few clarifications/changes. 
 
The "!" syntax is actually used for Flagging an Action.
So if you just enter text as in "todo myaction" it will NOT be flagged
But if you enter "todo myaction!" it will be flagged.
 
Also, using one instance of # will create a DUE date, while two instances will create a START DATE and then a DUE Date
So "myaction #today" creates a due date of today
But "myaction #today #tomorrow" creates a start date of today and a due date of tomorrow.
 
For clarity, I changed my subtext to:
Flag! @Context ::Project #Due (#Start #Due) $Duration //Note

## Author
Created by Patrick H. Mullins [@phmullins ](https://twitter.com/phmullins)

## License

(The MIT License)

Copyright (c) 2015 Patrick H. Mullins

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.