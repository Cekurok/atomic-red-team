## File and Directory Discovery

MITRE ATT&CK Technique: [T1083](https://attack.mitre.org/wiki/Technique/T1083)


### File and Directory Discovery

Input:

    ls -a > allcontents.txt

Input:

    ls -la /Library/Preferences/ > detailedprefsinfo.txt

Input:

    file */* *>> ../files.txt

Input:

    find . -type f

Input:

    ls -R | grep ":$" | sed -e 's/:$//' -e 's/[^-][^\/]*\//--/g' -e 's/^/ /' -e 's/-/|/'



References:

http://osxdaily.com/2013/01/29/list-all-files-subdirectory-contents-recursively/

https://perishablepress.com/list-files-folders-recursively-terminal/
