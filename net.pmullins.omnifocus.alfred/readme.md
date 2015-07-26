### OmniFocus

[OmniFocus](https://www.omnigroup.com/omnifocus) is an [Alfred](http://www.alfredapp.com/) workflow for [OS X](https://www.apple.com/osx/)
that makes creating new OmniFocus tasks easy. This is a modified version of the [workflow](http://www.alfredforum.com/topic/1041-create-new-task-in-omnifocus-inbox/?hl=omnifocus) 
originally found on the Afred forums. Thank you CapnAverage, Ryan M, and Orky for getting things started!

### Requirements

- [Alfred](http://www.alfredapp.com/)
- Alfred [Powerpack](http://www.alfredapp.com/powerpack/)
- [net.pmullins.omnifocus.alfred](https://github.com/phmullins/alfred-workflows/tree/master/net.pmullins.omnifocus) workflow

### Usage

Type `of` in Alfred followed by the task you would like to create.

Example:

!["OmniFocus Workflow"](https://github.com/phmullins/alfred-workflows/blob/master/net.pmullins.omnifocus/assets/alfred_omnifocus_ss.png)

Modifiers:

- `#` = indicates the Due date. One instance of `#` indicates the creation date, while two will create a start date and a due date. 
- `!` = used for flagging an action. Make sure to place the `!` at the end of the item being flagged.
- `@` = the context of the item being added.
- `::` = the project the item should be associated with.
- `$` = the duration of the task
- `//` = a note to be added with the task

### Author
Created by Patrick H. Mullins [@phmullins ](http://www.pmullins.net/aboutme/). You can find me on Telegram as @pmullins.

### License
Source is released under the Apache License (Version 2.0) [license](license.md).