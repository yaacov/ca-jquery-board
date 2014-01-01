ca-jquery-board
===============

A jQuery board widget

The [jQuery](http://jquery.com/) board widget use [jQuery-ui](http://jqueryui.com/) draggable, resizable and selectable widgets to create an editable view of objects. Objects can be yellow notes on a notes board, windows on a windows manager screen or images on a drawing board. 

<wiki:video url="http://www.youtube.com/watch?v=0P6tHmwV2Qk"/>

*Example 1:* Board with elements, how to create a board with elements, [example1](http://ca-jquery-board.googlecode.com/hg/example1.html).

*Example 2:* Simple tasks like copy, paste, delete and show-grid, [example2](http://ca-jquery-board.googlecode.com/hg/example2.html).

*Example 3:* Customizing the board, creating flower and tree custom elements using hooks, [example3](http://ca-jquery-board.googlecode.com/hg/example3.html).

*Example 4:* Customizing the board, using the example flower widget plug-in, [example4](http://ca-jquery-board.googlecode.com/hg/example4.html).

*Example 5:* Customizing the board, using the dialog forms plug-in, [example5](http://ca-jquery-board.googlecode.com/hg/example5.html).

Built in Functionality
======================

Edit mode
---------

In edit mode, objects are interactive. jQuery ui board objects can be selected, dragged and re-sized using the mouse. Objects can be re-sized and dragged together, change their visibility order and view parameters.

View mode
---------

In view mode, jQuery ui board objects are not interactive. Objects can change their view in view mode using the widget API.

Load and Save
-------------

jQuery ui board objects can be serialized into JSON strings. jQuery ui board objects can be loaded from JSON strings or data objects.

Extentions
==========

Edit
----
Enables copy, paste, paste style and paste size functionality. 

Order
-----
Enables raise, down, bottom and top ordering of objects.

Arrange
-------
Enables snap to grid, align horizontally, align vertically and distribute objects evenly.

Dialogs
=======
Enables adjustable dialogs for editing elements data.

Customization
=============

Hooks
-----

jQuery ui board use hooks on the widget set-data and set-value to customize the view mode and edit mode widget behavior.

Plug-ins
--------

jQuery ui board use plug-ins to create new widget types, and customize the view mode and edit mode behavior of the plugged in widget.

Images
======

*Example 2:* Simple tasks like copy, paste, delete and show-grid, [example2](http://ca-jquery-board.googlecode.com/hg/example2.html)

<img src="http://ca-jquery-board.googlecode.com/hg/example-img/edit-mode.png" width="400" />


*Example 3:* Customizing the board, creating flower and tree custom elements, [example3](http://ca-jquery-board.googlecode.com/hg/example3.html)

<img src="http://ca-jquery-board.googlecode.com/hg/example-img/view-mode.png" width="400" />

