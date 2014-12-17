cmd_looper
==========

Utility for looping output of shell commands, with ability to specify filters, limits, and automatic refreshes.

	Usage: cmd_looper [cmd]
	  Loops a command, refreshing after key press.

	Arguments:
	 Filters:
	        --head=N                Fetch only N lines from the top
	        --tail=N                Fetch only N lines from the bottom.
	        --grep="expr"           Pass output through grep.

	 Other:
	        --refresh=N             Refresh automatically after N seconds.
	        --buffer                Collect all output before displaying. Default behaviour is to provide output as it comes.
	Filters are executed in order of apperance.

	Example: cmd_looper last --head=10 --grep=root




