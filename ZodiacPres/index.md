---
title       : Intro to the Zodiac Application
subtitle    : Sun Signs for every birth date.
author      : Duff Bailey
job         : May 16, 2022
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- .class #id 
## Table of Contents
1. Application Description
2. Algorithms and Calculation
3. Usage and Disclaimers

--- .class #id 
## Application Description
For millenia, astrologists have linked people's personality and fates to their zodiac signs. 

This application returns the zodiac sign for any person based on the month and day of their birth.

Use the sliders to set the month number (1 for January, 2 for February, etc.) and the day of the month.  The appropriate sun sign will be displayed as output.

Birth dates are based on the Gregorian calendar.  Illogical month/day combinations such as 02/31 return the zodiac sign for their logical equivalent: (03/03).


--- .class #id 
## Algorithms and Calculation
Application input consists of the numeric equivalent of the birth month based on the Gregorian Calendar along with the birth day of the birth month as indicated by the two slider controls in the User Interface..  

The application used the birth month to obtain the "swing date" for that month.  The "swing date" is the date for that month when a new sun sign begins.  If the birth day is less than the swing date the original birth month value is used to select the sun sign. Otherwise, the sun sign for the following month is used.

The Alpha Numeric text for the sun sign is output to the user. 

--- .class #id 
## Usage and Disclaimers

To use the application, go to: https://duffbailey.shinyapps.io/Wk4Assign/

Disclaimer:
    
While there are many instances where this linkage between celestial events and the lives of ordinary persons appears valid, there has never been any scientific evidence supporting causality between astrology and real life events.  Consequently, this application should be used for entertainment purposes only and, under no circumstances, should it be used to assist with important life decisions.

Good luck!
