## NixTools
Hand Picked Command Line Tools From Cygwin to be used globally in modern windows without the need to install Cygwin.

These binaries are taken from recently updated Cygwin64 environment.

These tools all work without any issues in windows command prompt (cmd) and powershell.

Tools Included:
Tool | Notes
---|---
cat | Prints out contents of text files
find | For finding files and folders with recursive support
grep | Filtering data
head | Reading first lines in a file
ls | Get file system listings
nc | For scanning ports. eg nc -zv 127.0.0.1 80 will show if port 80 is open on the server
sed | Handy tools for replacing strings 
tail | For reading end and following text files (eg logs)
touch | Create or alter timestamp of a  file
wc | Get word or line count of a file

### Installation
```
cd <where_to_install>
git clone git@github.com:JavaScriptDude/nixtools.git
```

Then add your new path to your PATH Environment variables and presto, you now have tail available from commandline :)

For each release, I will upload the zip's to VirusTotal for scanning and validation. Please always confirm files before running with Virus Total or other virus checking tools.
