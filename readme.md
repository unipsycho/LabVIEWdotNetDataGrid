#LabVIEW dot Net DataGrid Overview
A very useful and easy to use data grid to replace LabVIEW's tables and multicolumn listboxes.  This datagrid supports more of the standard expected table/grid functions for sorting, filters and auto fitting content, and best of all, it supports some extended datatypes embedded within the grid.

Basically, this grid allows better table support, with more built in features that you can use standard LabVIEW data with and basic properties to your own string data into a more friendly grid and content display.

![Front Panel](https://raw.githubusercontent.com/unipsycho/LabVIEWdotNetDataGrid/v0.1/documentation/img/Frontpanel.png)

#Features
* Auto drawing and formatting of content
* Auto Column width sizing (auto, cell, fill, none, etc)
* Inline objects for combobox, buttons, checks and images
* Clickable Columns to sort (Asc/Dsc)
* Dragable columns to reorder them
* Minimum column widths
* Basic Events integration with LabVIEW Event structure for integration into your app

#Easy to Use
![Block Diagram](https://raw.githubusercontent.com/unipsycho/LabVIEWdotNetDataGrid/v0.1/documentation/img/BlockDiagram.jpg)

# Dependencies
OpenG is used for several variant data inspectors

#Usage
See the example code. Four simple steps to use it:

####1.Place a .NET DataGrid control on the front panel

![Insert .NET Control](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/v0.1/documentation/img/Insert%20.NET%20Control.jpg)

####2.Initialize the DataGrid Class using the .net control reference

![Choose DataGridView](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/v0.1/documentation/img/Select%20DataGridView.jpg)

####3.Define the column parameters
![Define Columns](https://raw.githubusercontent.com/unipsycho/LabVIEWdotNetDataGrid/v0.1/documentation/img/defineColumns.PNG)

####4.Add data
![Add String Table Data](https://raw.githubusercontent.com/unipsycho/LabVIEWdotNetDataGrid/v0.1/documentation/img/StringData.png)

#Data Types
Currently, there are several datatypes supported:
* Strings
* Booleans
* Numbers
* Timestamps
* Images
* Buttons
* Combobox (selection lists)

#Events
* Cell Edit Ended - This single event is used currently as a sample for callback events.
* Cell Value Changed - Works but errors currently on custom datatypes. Need to handle errors and extend this event

# Contributing

This repository is written and maintained in LabVIEW 2014.
