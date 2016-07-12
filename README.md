# Jot

Jot appends a timestamped entry to a daily journal file.


```
Usage of bin/jot:
  -datefmt string
    	Date Format (see golang time package) (default "Jan-02-2006")
  -dir string
    	Notes Directory (default "/home/user/Dropbox/Notes")
  -note string
    	Note content (default "Tick..")
  -pre string
    	Note filename prefix (default "jot-")
  -timefmt string
    	Timestamp Format (see golang time package) (default "15:04:05")
```

By default creates or appends to `$HOME/Dropbox/Notes/jot-Jan-02-2006.txt`,
substituting in today's date.
