# syncd-rules
python3 utils for manipulating syncd rules

## syncd-add
Adds a new src -> [dest] rule
Example use:
```
syncd-add fs:///home/brian/Documents dropbox:///Documents
syncd-add --rules ~/tmp/rules.json fs:///home/brian/Documents dropbox:///Documents
```
Note that as implemented, this currently is only one-directional
