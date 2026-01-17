#### goal
This codebase represents a webapp designed to allow users to emulate playing the viola on a phone. the home page has options for selecting which phone the user has. For now, the only option should be a samsung 24 ultra. clicking on that phone will launch the viola experience. 

### Digital viola interface
The page will display viola frets spaced out as a whole note, whole note, half note, whole note. The spacing will be calibrated to realistically match the spacing of a viola on the selected phone screen. 

There will also be 4 vertical lines indicating which string of the viola is being played. The top 80 of the lines will be in light grey, while the bottom 20% are black.  

When the user touches one of the 4 vertical lines in the bottom 20% area, indicated by the black color, the phone will play the correct sound that a viola would. app will check for any presses on the upper 80% where the frets are and take the furthest down to indicate which fret is pressed.

Wherever the user presses should be mapped to the closest string location at half note intervals. Don't bother trying to implement tremelo, but conceivably, if the user wiggles their finger, the frequency can oscillate emulating tremelo as well.

### Misc
Make sure to look up the correct spacings for a viola so the digital interface is correct. 

The entire interface should be controlled by a single html file
