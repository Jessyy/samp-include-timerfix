[SA-MP Include - TIMERFIX][github]
====================

This include will make your timers accurate by ~5ms.

Limitations
-----------
You can, by default, have only 128 timers running at the same time. If you feel the need to increase this, define TIMER_FIX_TIMER_SLOTS before you include the script.
Something to keep in mind is this include causes PAWN to work harder. Therefore, you shouldn't have loads of timers running at the same time as it will require higher CPU usage.

Compatibility
-------------
It works for SetTimer and SetTimerEx, though not with strings and arrays.
It works very well with y_timers.

Credits
-------
- Slice for creating this include

[github]: https://github.com/Jessyy/samp-include-timerfix
