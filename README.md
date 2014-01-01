ca-jquery-board
===============

A jQuery board widget

The [http://jquery.com/ jQuery] board widget use [http://jqueryui.com/ jQuery-ui] draggable, resizable and selectable widgets to create an editable view of objects. Objects can be yellow notes on a notes board, windows on a windows manager screen or images on a drawing board. 

<wiki:video url="http://www.youtube.com/watch?v=0P6tHmwV2Qk"/>

----
<wiki:toc max_depth="2" />
----

*Example 1:* Board with elements, how to create a board with elements, [http://ca-jquery-board.googlecode.com/hg/example1.html example1].

*Example 2:* Simple tasks like copy, paste, delete and show-grid, [http://ca-jquery-board.googlecode.com/hg/example2.html example2].

*Example 3:* Customizing the board, creating flower and tree custom elements using hooks, [http://ca-jquery-board.googlecode.com/hg/example3.html example3].

*Example 4:* Customizing the board, using the example flower widget plug-in, [http://ca-jquery-board.googlecode.com/hg/example4.html example4].

*Example 5:* Customizing the board, using the dialog forms plug-in, [http://ca-jquery-board.googlecode.com/hg/example5.html example5].

----
==Built in Functionality== 

===Edit mode===

In edit mode, objects are interactive. jQuery ui board objects can be selected, dragged and re-sized using the mouse. Objects can be re-sized and dragged together, change their visibility order and view parameters.

===View mode===

In view mode, jQuery ui board objects are not interactive. Objects can change their view in view mode using the widget API.

===Load and Save===

jQuery ui board objects can be serialized into JSON strings. jQuery ui board objects can be loaded from JSON strings or data objects.

----
==Extentions==

===Edit===
Enables copy, paste, paste style and paste size functionality. 

===Order===
Enables raise, down, bottom and top ordering of objects.

===Arrange===
Enables snap to grid, align horizontally, align vertically and distribute objects evenly.

===Dialogs===

Enables adjustable dialogs for editing elements data.

----
==Customization==

===Hooks===

jQuery ui board use hooks on the widget set-data and set-value to customize the view mode and edit mode widget behavior.

===Plug-ins===

jQuery ui board use plug-ins to create new widget types, and customize the view mode and edit mode behavior of the plugged in widget.

----
==Images==

*Example 2:* Simple tasks like copy, paste, delete and show-grid, [http://ca-jquery-board.googlecode.com/hg/example2.html example2]

<img src="http://ca-jquery-board.googlecode.com/hg/example-img/edit-mode.png" width="400" />


*Example 3:* Customizing the board, creating flower and tree custom elements, [http://ca-jquery-board.googlecode.com/hg/example3.html example3]

<img src="http://ca-jquery-board.googlecode.com/hg/example-img/view-mode.png" width="400" />

