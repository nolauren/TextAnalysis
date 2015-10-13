
# Count2Text

```
ls -ltrh 
```
(long, time, reverse order, human readable)
```
mv count2txt Desktop/
```

```
chmod 755 count2txt
```
 Change permissions,make this file executable, 755 make this executable for everybody.

Download code to proper folder 
```
curl -O URL (git hub url of the code) https://raw.githubusercontent.com/agoldst/dfr-analysis/master/count2txt
```

```perl
 ./count2txt ~/Desktop/2015.10.3.kg2GhvJn/wordcounts/*.txt > NameOfFile
 ./count2txt ~/Desktop/2015.10.3.XxVvKVDq/wordcounts/*.txt > NameOfFile
```

# Not Enough Memory

Outside of terminal: 
Go to mallet2.0.7/bin/
Dragg mallet into text editor. 
Change MEMORY=1g 
Say computer has 8g hten change it to 4g.

OR

With the terminal:
Go to mallet2.0.7/bin/
type pico mallet
Change MEMORY=1g . Suggestion is 4g.
Control X to save and exit.

