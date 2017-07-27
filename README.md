veloeclipse
===========

Veloeclipse is a HTML/XML/JSP/Velocity Editor for Eclipse (Angularjs Support)

[Site](http://masrawi.github.io/veloeclipse/)

### Features:
- Smart indentation of velocity directives ( on pressing return or when using tabs)
- XML support
- Angularjs support
- Jtidy integration
- code folding
- code Formatting for single file or directory
- Smart indentation of html tags( on pressing return or when using tabs)
- Syntax highlighting for both html and velocity
- Autocompletion and Content assist for tags,directives and references (Ctrl + space in html attribute values or when opening or closing tags)
- jumping to statring tag/directive when hovering on the closing tag/directive and then pressing Ctrl+Alt+ mouseclick
- opening html definitions on tags when pressing Ctrl+Alt+ mouseclick
- Tested on Eclipse 4.4, 4.6, 4.7

### Install: 
- Open Eclipse
- Go to: Help -> Install New Software...
- Select: "Eclipse Project Updates - http://download.eclipse.org/eclipse/updates/4.x"
- Open Category: "Eclipse Tests, Examples, and Extras"
- Select and Install: "Eclipse 2.0 Style Plugin Support"
- Restart Eclipse
- Go to: Help -> Install New Software...
- Add new Eclipse Update Site:
```
Name: Veloeclipse
Location: https://raw.githubusercontent.com/masrawi/veloeclipse/master/site.xml
```
- Install Plugin

#### If the standard way to install plugin does not work
For Eclipse Mars/NEON (I've just verified that) you to do this (assuming that C:\eclipseMarsEE is root folder of your Eclipse):

Add plugins folder to C:\eclipseMarsEE\dropins so that it looks like: C:\eclipseMarsEE\dropins\plugins
Then add plugin you want to install into that folder: C:\eclipseMarsEE\dropins\plugins\someplugin.jar
Start Eclipse with clean option.
If you are using shortcut on desktop then just right click on Eclipse icon > Properties and in Target field add: -clean like this: C:\eclipseMarsEE\eclipse.exe -clean
enter image description here

Start Eclipse and verify that your plugin works.
Remove -clean option from Target field.

Credit to Nenad Bulatovic on Stack Overflow for the install instructions.
