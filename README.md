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

#### Note on `nc.exe`:
`nc.exe` may show up in some virus scanners but I have confirmed that this is the proper executable from Cygwin. Its likely showing up because its a handy tool for hackers to drop on servers to poke around and thus shows up in some virus redlists. Again, please confirm the files yourself.


### Checksums at 20220416
cfbc5c568c62a9155d4de0ad1d10b4a7dc8f278b  cat.exe
1fe1eb8104773c41ece210dc9604e3193b6f3893  cygiconv-2.dll
ecbae6bdf43ace13a779f45377bd2e445d61f616  cygintl-8.dll
9d163effd19695d30d92358217ea25d217d343c4  cygncursesw-10.dll
0885e0c99f75f33d7516b3afd8ef670dbba77974  cygpcre-1.dll
231711acd4573a7b1e96c633a81319dc47c8db28  cygpcre2-8-0.dll
35fdd7e3ab7b4b36e874fc4e0df22d4feaa33500  cygwin1.dll
217ff5629c797068a19829b3ce9a21a8ab5601ba  find.exe
618a5a8f3d98098e0ba350460895aa3b3db33af8  grep.exe
216f6ffdfe4b76e89efa1d84111aa823307aea8c  head.exe
bfd378fc36908cbac83124cee661c67003a13e07  ls.exe
ba6f26d71e4e87b0a3a013c7aa295ba8a705e332  nc.exe
7dfcf619adef092cc25d892d8f6552189026990c  sed.exe
5f93550a82daeaa07346f113b8a7bbba0a54d343  tail.exe
10bcba5d34a285f71daf1048f04a4833e90edc7a  touch.exe
21c96fb9310b311acfa3a9e006e474e9cb6bdc49  wc.exe
