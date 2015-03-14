Context Menu
------------
_A simple Windows application that displays a ContextMenu for a given file._

This is ment as an extension to **[muCommander](http://www.mucommander.com/)** for use under Windows. It's based on the code from **[The Old New Thing](http://blogs.msdn.com/oldnewthing/archive/2004/09/20/231739.aspx)** blog.

The program, given a file name on the command line, displays the system context menu for it, then waits for the user to select an option (and sometimes close the "Properties" dialog) and ends.

The custom command for **muCommander** in the `HOME\.mucommander\commands.xml` file looks as follows:
```
<command alias="contextMenu" value="C:\\Path\\To\\ContextMenu.exe &quot;$f&quot;" /> 

```

---
_This project has been migrated from Google Code._
