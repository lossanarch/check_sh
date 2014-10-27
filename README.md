check_sh
========
Small Python script to pull check_mk livestatus data and display it in the terminal curses-style.

TODO:
Move WARN status alerts to under CRIT (i.e. move CRIT to top)
Output to PAD so that arrow keys can be used to scroll up and down the alert list
Make left/right arrow keys scroll columns left/right (maybe through +/- of string slicing?)
