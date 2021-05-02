# keylogger_minor1

A Key-Logger will be coded using C Library’s.

Firstly, we will check for the current day by using our function day() and will use an inbuilt structure defined in time.h that returns a pointer with time info filled in and then will save it to our log file.

Now we will examine the current state of our caps lock and num lock and will put that state in the log file as On or Off.

After that, our save function will be initiated where we will save all our keystroke by specifying their key code values by using virtual key codes and getAsyncKeyState.

To have time stamp for Key-Strokes World Clock is used using Coordinated Universal Time (UTC), India Standard Time which is 5 hours and 30 minutes ahead of GMT.

Our ti() function will be called when a keystroke occurs and will note the exact time of pressing which will be logged in the log file.

The Log file generated will be analysed for frequency count and most frequent key pressed.

speed(), which will be a user defined function will be used for calculating typing speed.


