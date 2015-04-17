#all
allow different old/new rules files?

need to pull out util functions:
	pick rules file
	load/save rules file
	restart daemon
	start syncd if no default rules file

#syncd-add
handle new dest on existing src
handle raw file:// portably (ex. "syncd-add C:\Docs D:\bak\docs")

#syncd-remove
handle bidirectional rules
add start-syncd-if-no-default-rules-file, although it really should be in util

#syncd-restart
rewrite in portable python
