+++
title = "pages"
subtitle = "Test"
+++

![TextTableImage](/images/Overview.png "{width='200'}")
## Motivation

Since the information technology industry left the aera of single programs the integration between components became the heartbeat of information systems. There are different ways to implement integration. Although there are modern and spohisticated approaches to do that, text files still play an important role in integration by data exchange.
TextTable is designed to support and analyze text files especially with plain fixed length file formats.
TextTable allowes to create file definitions to parse and render the flat files and implements a simple selection and manipulation sql-like language and editing the data in table view.
 
## Interface definition

The query language allows to define the text file specification which is used to parse the input text file into the table structure and to render the table back to the output file. Please read the documentation for the [interface definition](/page/interface_def)

## Query Language

The query language can be used to analyze the table data information based on the input text. It can also be used to perform some modifications to the table data. Once the table data was modified it can be rerenderd into the input file utilizing the interface definition. It's also possible to edit the data directly at the output table. Please find the [query language definition here.](/page/query)

## User Interface
The user interface is grouped in to three areas:
- The interface file input and output pane
- The file interface definition pane and
- The query and data edititing pane

The input and output pane allows load and store the interface files in different codes pages. At the file interface definition you can edit the file definition which supports the user with syntax highlighting and returning errors of the interface definition. Once the interface is specified you can parse the data into the data table of the query and editing pane. With the query and data edititing pane you can perform the query language statement with support of syntax highlighting and error messages. You can also edit the parsed data in the data table. After that you can then render the table data back into the file. Please find the detailed [description of the ui here](/page/ui)