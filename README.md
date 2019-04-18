# Goofing off with BASIC

## Overview

No, I don't mean VBScript.  I don't mean VBA.  I sure as puck don't mean VB.NET.  No, I mean BASIC - the ridiculously old-school scripting language of the 1980s!  Right now I just have one script, written for the Commodore 64, that puts my blog's name and main themes on the screen.

Down the road, I might play with it some more, but if I do I think I might switch to Assembly - one step closer to learning to code for the (S)NES! :)

## The code

```
10 POKE 53280,0
20 POKE 53281,0
30 FOR i=0 to 40: PRINT "": NEXT i
40 POKE 646,7
50 PRINT "           THE GEEK ON SKATES           "
60 POKE 646,3
70 PRINT ""
80 PRINT "   Tech, Hockey, and all things Geeky   "
90 POKE 646,14
100 PRINT ""
110 PRINT "       http://www.geekonskates.com"
120 FOR i=0 to 10: PRINT "": NEXT i
130 POKE 198,0: WAIT 198,1 
140 POKE 53280,14
150 POKE 53281,6
```

## To run it:

1. Type in the code above on your C64 emulator (or actual C64 if you have one, lol).  If your emulator supports pasting, that's cheating. :)
2. Type the command "RUN" and press Enter
3. My code will do its thing and wait for you to press a key.  When you do, the colors will reset to the defaults.

## License

The Do What You Want License:

## You are allowed to:

* Fork it
* Clone it
* Change it
* Sell it
* Do whatever else you like with it.

## You are NOT allowed to:

* Blame me in any way if it doesn't work
* Sue me if it breaks something or causes other problems

## I would appreciate, but don't require, that you:

* Mention me someplace noticeable if you use my code in your project:
* Subscribe to my blog

NOTE: If you wonder what I mean by "it", "code", or "this" I mean the contents of the Git repository this license is part of.  I understand the Legalese language evolved from English because people needed definitions of the obvious, so I figured it just had to be said. :)