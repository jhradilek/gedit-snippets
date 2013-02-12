# gedit Snippets

## Description

The **gedit-snippets** repository provides a collection of code snippets for **gedit**, the official text editor of the GNOME desktop environment. In particular, it provides snippets for the following file types:

* **docbook.xml** — Snippets for the DocBook XML language according to the [DocBook: The Definitive Guide, version 2.0.17](http://www.docbook.org/tdg/).

* **mallard.xml** — Snippets for the Mallard XML language according to [Mallard 1.0 DRAFT (as of 2013-02-11)](http://projectmallard.org/1.0/index.html).

## Installation

### Installing the Snippets in the Graphical User Interface

To install snippets for a particular file type in the graphical user interface, take the following steps:

1. From the main menu of the **gedit** text editor, select *Tools* → *Manage Snippets…* to open a dialog box titled **Manage Snippets**.

2. At the bottom-left corner of the dialog box, click the **Import Snippets** button. Another dialog box titled **Import Snippets** appears.

3. Navigate to the directory with your local copy of this repository, select an appropriate **.xml** file (for example, to install the snippets for the DocBook XML language, select the file named **docbook.xml**), and click **Open** to confirm your choice.

The snippets are automatically loaded when you close the **Manage Snippets** dialog box.

### Installing the Snippets on the Command Line

To install snippets for a particular file type on the command line, change to the directory with your local copy of this repository, and run the following command:

    cp <filetype>.xml ~/.config/gedit/snippets/

For example, to install the snippets for the DocBook XML language, type:

    cp docbook.xml ~/.config/gedit/snippets/

The snippets are loaded the next time you start the editor.

## Uninstallation

### Uninstalling the Snippets in the Graphical User Interface

The current version of the **gedit** text editor does not provide an easy way to uninstall all snippets at the same time.

### Uninstalling the Snippets on the Command Line

To uninstall snippets for a particular file type on the command line, run the following command:

    rm ~/.config/gedit/snippets/<filetype>.xml

For example, to uninstall the snippets for the DocBook XML language, type:

    rm ~/.config/gedit/snippets/docbook.xml

The snippets are unloaded the next time you start the editor.

## Copyright

Copyright © 2012, 2013 Jaromir Hradilek

This program is free software; see the source for copying conditions. It is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
