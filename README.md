# local-sundial-time-eqt-app-widget
A local sundial time equation of time clock App Widget for mobile devices.

Display a clock with 3 times with a widget on the home screen in mobile devices.

Display:
First time in digits: clock with the device time (HH:MM:SS)
First time in digits: clock with the UTC time (HH:MM:SS)
Second time in digits: clock with the calculated local sundial time (HH:MM:SS)

Calculating:
- get the device time.
- get the timestamp (UTC).
- get the longitude from GPS.
- calculate the equation of time with the timestamp. (formular available).
- calculate the difference to UTC with the longitude (1 hour = 15°).
- calculate the local sundial time with the calculated values.

Help needed. I can not program apps widgets.
