#LabVIEW dot Net DataGrid Overview
A very useful and easy to use data grid to replace LabVIEW's tables and multicolumn listboxes.  This datagrid supports more of the standard expected table/grid functions for sorting, filters and auto fitting content, and best of all, it supports some extended datatypes embedded within the grid.

Basically, this grid allows better table support, with more built in features that you can use standard LabVIEW data with and basic properties to your own string data into a more friendly grid and content display.

![Front Panel](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/master/documentation/img/Frontpanel.png)


#Features
* Auto drawing and formatting of content
* Auto Column width sizing (auto, cell, fill, none, etc)
* Inline objects for combobox, buttons, checks and images
* Clickable Columns to sort (Asc/Dsc)
* Dragable columns to reorder them
* Minimum column widths
* Basic Events integration with LabVIEW Event structure for integration into your app

#Easy to Use
![Block Diagram](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/master/documentation/img/BlockDiagram.jpg)

# Dependencies
OpenG is used for several variant data inspectors

#Usage
See the example code. Four simple steps to use it:

####1.Place a .NET DataGrid control on the front panel

![Insert .NET Control](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/master/documentation/img/Insert%20.NET%20Control.jpg)

####2.Initialize the DataGrid Class using the .net control reference

![Choose DataGridView](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/master/documentation/img/Select%20DataGridView.jpg)

####3.Define the column parameters
![Define Columns](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/master/documentation/img/defineColumns.PNG)

####4.Add data
![Add String Table Data](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/master/documentation/img/StringData.png)

#Data Types
Currently, there are several datatypes supported:
* Strings
* Booleans
* Numbers
* Timestamps
* Images
* Buttons
* Combobox (selection lists)
* Links

#Events
* Cell Edit Ended - This single event is used currently as a sample for callback events.
* Cell Value Changed - 
* Cell Validating - This is an automatic callback event, that cancels any edits when the cell value doesn't validate.  No LabVIEW events are currently generated from this.
* DataError - when formattting fails on the data for a cell on change
* UserAddedRow - returns the row
* UserDeletedRow - returns the row

# Releases
Grab the latest releases to use this project [here from github](https://github.com/unipsycho/LabVIEWdotNetDataGrid/releases).
# Contributing

This repository is written and maintained in LabVIEW 2014 SP1.
See the [Todo.md](https://github.com/unipsycho/LabVIEWdotNetDataGrid/blob/v0.1/todo.md) for areas you can contribute.
