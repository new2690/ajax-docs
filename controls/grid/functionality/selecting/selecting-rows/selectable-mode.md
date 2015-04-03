---
title: Selectable Mode
page_title: Selectable Mode | UI for ASP.NET AJAX Documentation
description: Selectable Mode
slug: grid/functionality/selecting/selecting-rows/selectable-mode
tags: selectable,mode
published: True
position: 5
---

# Selectable Mode



## RadGrid Selectable Mode

There are three selectable modes in __RadGrid__ control. These modes could be manipulated using the __SelectableMode__ property. SelectableMode is a GridItem enum property which determines if the item could be selected on the server, the client or both. Here is description of the possible modes:

* __SelectableMode.ServerAndClientSide__: This is the default value and it represents the current selection behavior depending on the prefered selecting mechanism.

* __SelectableMode.ServerSide__:This value allows the developer to select items on the server which could not be changed by the end user.

* __SelectableMode.None__: The item could not be selected on the client or the server. If the GridItem.Selected value have been true it is automatically deselected when SelectableMode is set to None.