# FCC-JS-Challenge-3_Golf_Code

In the game of golf each hole has a par meaning the average number of strokes a golfer is expected to make in order to sink the ball in a hole to complete the play. Depending on how far above or below par your strokes are, there is a different nickname.

Your function will be passed par and strokes arguments. Return the correct string according to this table which lists the strokes in order of priority; top (highest) to bottom (lowest):

Strokes equals 1,	Return = "Hole-in-one!"
Strokes equals <= par - 2,	Return = "Eagle"
Strokes equals par - 1,	Return = "Birdie"
Strokes equals par,	Return = "Par"
Strokes equals par + 1,	Return = "Bogey"
Strokes equals par + 2,	Return = "Double Bogey"
Strokes equals >= par + 3,	Return = "Go Home!"

par and strokes will always be numeric and positive. We have added an array of all the names for your convenience.

