---
title: gotoDate
type: method
---

Moves the calendar to an arbitrary year/month/date.

<div class='spec' markdown='1'>
.fullCalendar( 'gotoDate', *year* [, *month*, [ *date* ]] )
</div>

**IMPORTANT**: `month` is 0-based, meaning January=`0`, February=`1`, etc.

This method can also be called with a single argument, a Date object
(only works in versions >= 1.3.2).
