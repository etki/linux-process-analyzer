# Standard Draft Warning

Hey there! This project is just an idea yet, don't take it too 
seriously. Nothing working has been already done.

# Linux Process Analyzer

While there are lots of tool to monitor process activity, i haven't 
seen one that would emit *totals* of process - how many forks did it 
spawn? How many threads? How much time each thread spent in running 
state? What was max ram consumption for specific thread? You can
get answers from /proc, but not after process has been stopped.

There's `time` utility to measure execution time and some other 
information, but no tool to gather it all. Linux Process Analyzer 
acts pretty much as `time`, wrapping provided command and gathering 
information.

Please be advised that 'gathering information' is an action too and 
will spend some CPU to maintain itself, thus making metrics less 
accurate.
