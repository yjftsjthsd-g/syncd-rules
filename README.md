# syncd-rules
python3 utils for manipulating syncd rules

## syncd-add
Adds a new src -> [dest] rule
Example use:
```syncd-add fs:///home/brian/Documents dropbox:///Documents```
or
```syncd-add --rules ~/tmp/rules.json fs:///home/brian/Documents dropbox:///Documents```

By default this will add rules for bidirectional sync; if you only want to sync in one direction, use the ```--monodirectional``` flag.
