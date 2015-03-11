# cscope
Cscope is a developer'.s tool for browsing C programming code.

init version cscope-15.8a release, you can also find here:
http://cscope.sourceforge.net/
http://sourceforge.net/projects/cscope/files/

Usage:
	cscope commands:
	add  : Add a new database             (Usage: add file|dir [pre-path] [flags])
	find : Query for a pattern            (Usage: find c|d|e|f|g|i|s|t name)
	       c: Find functions calling this function
	       d: Find functions called by this function
	       e: Find this egrep pattern
	       f: Find this file
	       g: Find this definition
	       i: Find files #including this file
	       s: Find this C symbol
	       t: Find assignments to
	help : Show this message              (Usage: help)
	kill : Kill a connection              (Usage: kill #)
	reset: Reinit all connections         (Usage: reset)
	show : Show connections               (Usage: show)
