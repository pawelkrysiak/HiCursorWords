# HiCursorWords MOD #

----------

## About ##

This script highlights words under the cursor like many IDEs.

This doesn't provide scope-aware highlighting nor language specific one.
You can control highlighting by highlighting group names.

## Configuration ##

**default config:**

	let g:HiCursorWords_delay = 200
	let g:HiCursorWords_style = 'MatchParen'
	let g:HiCursorWords_hiGroupRegexp = ''
	let g:HiCursorWords_debugEchoHiName = 0

**Variables explanation:**

(A right hand side value is a default value.)

	g:HiCursorWords_delay = 200
A delay for highlighting in milliseconds.
Smaller value may cause your machine slow down.

    g:HiCursorWords_style = 'MatchParen'
Defines which highlight group should be used by the plugin.

 	g:HiCursorWords_hiGroupRegexp = ''
If empty, all words are highlighted.
If not empty, only the specified highlight group is highlighted.

To investigate highlight group name, the next variable may help you.

	g:HiCursorWords_debugEchoHiName = 0
If not 0, echoes the highlight group name under the cursor.

----------

