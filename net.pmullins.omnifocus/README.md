# OmniFocus

[OmniFocus](https://www.omnigroup.com/omnifocus) is an [Alfred](http://www.alfredapp.com/) workflow for [OS X](https://www.apple.com/osx/)
that makes creating new OmniFocus tasks easy. This is a modified version of the [workflow](http://www.alfredforum.com/topic/1041-create-new-task-in-omnifocus-inbox/?hl=omnifocus) 
originally found on the Afred forums. Thank you CapnAverage, Ryan M, and Orky for getting things started!

## Requirements

- [Alfred](http://www.alfredapp.com/)
- Alfred [Powerpack](http://www.alfredapp.com/powerpack/)
- [net.pmullins.omnifocus.alfred](https://github.com/phmullins/alfred-workflows/tree/master/net.pmullins.omnifocus) workflow

## Usage

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

## Author
Created by Patrick H. Mullins [@phmullins ](https://twitter.com/phmullins).

## License

Copyright [2015] [Patrick H. Mullins]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
