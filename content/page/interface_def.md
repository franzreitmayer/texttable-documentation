+++
title= "TextTable interface definition" 
subtitle= "define the structure of the file interface"
date= ""
draft = false
weight = 0
+++

## Quick overview
Currently the file definition only allows plain fixed length files. Supporting separated files is an open topic at the moment. You start the definition with the keyword **plain** followed by an **identifier** for the file definition. That is follow the column specification which is enclosed between the keywords **begin** and **end**, where **end** is stopped by a **; (Semicolon)**. But let's have a look at a simple example.

{{< figure src="/images/interface_example01.png" title="Example 01" caption="interface definition" alt="Alt text" width="200px">}}

The option **left** or **right** from the example above (the field id) is used when the table is rendered back to the file. This way you can define whether the field is left or right aligned at the file.

There are basically two different ways to define a column. You can do that eighter by defining a columns **length** or you can define where the column starts and ends in a single line with **from** and **to**. Using **from** and **to** there's no validation for gaps or intersections of the column definitions.
 
please find the [detailed language definition here](../TextTable.rrd.html).