# tools
Little tools for development

###xsearch
Search the key word you want to find in any txt files, like function name, or where the function is called. It is just like `cat xxx | grep "function_name"`. But it can highlight the key word.
***
**usage:** 
``` shell
*xsearch* DIRECTORY KEYWORDS -i IGNORE -t FILETYPE
```
**example:**
``` shell
./xsearch . 653377 -i .svn -t cpp
```
