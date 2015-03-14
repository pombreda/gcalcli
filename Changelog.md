# Project moved to: https://github.com/insanum/gcalcli #


### gcalcli-2.1 ###

  * Enhancements
    1. new import command for importing ics/vcal files to a calendar
    1. add events to any calendar instead of just the default
    1. ability to override the color for a specific calendar
    1. added ability to specify calendars and colors in the config file
    1. new --https option to force using SSL
    1. new --mon option to display calw and calm weeks starting with Monday
    1. new --24hr option for displaying timestamps in 24 hour format
    1. all day events are no longer shown with a timestamp
    1. interactively prompt for a password if none is found
    1. calendar data gathering is now multi-threaded for performance
  * Fixes
    1. all unicode problems should now be fixed
    1. calw and calm displays can now handle wide east asian unicode characters
    1. use only ANSI C strftime formats for cross platform compatibility
    1. --ignore-events now works for the agenda and search commands
    1. all day events on Sunday no longer show again on the next week
    1. fixed calw and calm layout issues with events that have no titles
    1. dump events that are beyond year 2038 (really?)

### gcalcli-1.4 ###

  * colors are now supported in the 'calw' and 'calm' displays
  * new --border-color switch

### gcalcli-1.3 ###

  * new '--cal' switch used to specify a single calendar or multiple using a regex
  * config file support (~/.gcalclirc or override on command line)
  * new 'calm' and 'calw' command that displays a nice graphical representation of your calendar
  * new '--ignore-started' switch
  * fixed time display (am/pm) for Mac OSX
  * the 'remind' command now works against all specified calendars
  * support for 'editor' calendars

### gcalcli-1.2 ###

  * support unicode input and output

### gcalcli-1.1 ###

  * initial release