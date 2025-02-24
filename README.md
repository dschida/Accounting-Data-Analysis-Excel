Generate a ranked set of improv games from drop-down list of dates depending on the preferences of actors on stage. Consolidate 2 sets of data. Weight attendance (maybe vs. yes) and preference (like vs. neutral vs. dislike).

Highlight: Apply SUM of dynamic array column-by-column with embedded LAMBDA.

BYCOL(NumericalRatings, LAMBDA(Array, SUM(Array))
