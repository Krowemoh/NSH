# NovasShell
A Fancier Shell for Universe

**Installation**
Pull the file and then simply compile it.

In Linux:
```
$ wget https://raw.githubusercontent.com/Krowemoh/NovasShell/main/NSH -O /path/to/BP/NSH
```

In Universe
```
> BASIC BP NSH
> CATALOG BP NSH
> NSH
```

If everything went well, you should now see a brand new prompt!
```
user:13@ACCOUNT>
```

**Requirements**
This application currently assumes that the system is UniVerse on Linux. 

**Features**

- Custom Prompt: Prompt displays username, port and account
- Tab for Suggestions: Allows for commands, files and items inside files to be suggested when you hit tab 
  - If you type LIS at the prompt and then tab, you’ll get a list of all the verbs that start with LIS
  - If you do LIST INVENTORY and then hit tab, you’ll get all the files that start with INVENTORY
  - If you do LIST INVENTORY-FILE AZ12, you’ll get all the items start with AZ12
- Permanent Command History: Save commands to /tmp/.nsh, this can be changed for a more permanent location.
- Up/Down: Allows navigation of the entire command history
- Left/right to edit commands - Edit commands and move the cursor around in a line.
- Man Pages: Displays the help pages in a slightly more straightforward format. 
  - MAN LIST
- Man Basic: Help pages for basic can be found by doing MAN BASIC {ITEM} 
  - MAN BASIC MATREAD
- Linux access: Shortcut to get to Linux and added ability to execute shell commands quickly (Same thing as doing sh in tcl)
  - !curl google.ca 

**Hacking**
Feel free to open up the file and make any changes you like, please submit them if you think others might get something out of it as well!
