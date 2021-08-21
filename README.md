# org.bzdev.CVRDecode

By using org.bzdev.CVRDecode, you can store data from  multiple California
digital vaccine records in file or print the data on standard output.
Normally the data printed is restricted to show names, birth dates,
the last vaccination date, whether fully vaccinatated, whether the
record's digital signature is valid, and the location of a record
(typically a file name).  The records are sorted by name and
date of birth.

When run as a desktop application or from the command line with no
arguments, a GUI will appear showing a table of buttons. The first
two set an input directory and and output file. Each button will
change color to a pale yellow when the directory or file name has
been entered.  Once both are entered, the Run button must be pressed
to generate the output.  Two other buttons, one name Table and the
other named Console can be used.  The Table button will display the
table saved in the output file, and the Console button will show
any error messages that might have been generated. The Exit
button terminates the program.  The ouput file will be in
CSV (Comma Separate Value) format, so it can be easily imported
into a spreadsheet.

Running the command

```
flatpak run org.bzdev.CVRDecode --help
```

from a terminal window will display a Linux man page documenting
the command-line options.

A typical use case is one in which someone running a private event
asks attendees to email vaccination records in advance, and will
have a list - e.g., a paper copy - of those who sent the records
at the entrance.  
