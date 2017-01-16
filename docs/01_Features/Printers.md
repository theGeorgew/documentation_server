
## printers

Table o’ Printers
-------------

IP |  Name  | Location
——-|:———————:|———————:
10.1.8.1  | PRTED01 | ED Department
10.1.8.2  | PRTLABLB01 |  Lab Label Printer 1
10.1.8.3  | PRTLABLBL02 | Lab Label Printer 2			
10.1.8.4 | PRTRAD01 | RAD printer 			
10.1.8.5 | PRTADMIT01	| Admitting room
10.1.8.6 | PRTEDADMIT01 | ED admit	 			
10.1.8.7 | PRTLAB01 | Laboratory print
10.1.8.19 |PRT7SCHED01 | Scheduling Office


## Sorting
To sort your files and folders in a specific way, you can prefix them with a number and underscore, e.g. `/docs/01_Hello_World.md` and `/docs/05_Features.md` This will list *Hello World* before *Features*, overriding the default alpha-numeric sorting. The numbers will be stripped out of the navigation and urls. For the file `6 Ways to Get Rich`, you can use `/docs/_6_Ways_to_Get_Rich.md`

You might also wish to stick certain links to the bottom of a page. You can do so by appending a '-' to the start of the filename, e.g. a new file `/docs/-Contact_Us.md` will always appear at the bottom of the current list. Weights can also be added to further sort the bottom entries. e.g. `/docs/-01_Coming.md` will appear before `/docs/-02_Soon.md` but both will only appear after all positive or non-weighted files. 
