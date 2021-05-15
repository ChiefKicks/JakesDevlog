START
RT 90 Degrees

FD 1 Block

LT 90 Degrees

FD 1 Block

LT 90 Degrees

FD 1 Block

Approach Intersection 1

Random Direction (LT/RT/FD)

BASED ON NUMBER OF CARS SEEN

(0-3)LT (4-6)FD (7-9)RT


IF CHOOSE LT

LT 90 Degrees

FD 2 Blocks

LT 90 Degrees

FD 1 Block (Circle)

DEAD END 

SETPOS Intersection 1


IF CHOOSE FD

FD 3 Blocks

RT 45 Degrees

FD 1 Block

DEAD END 

SETPOS Intersection 1



IF CHOOSE RT

RT 90 Degrees

FD 1 Block

Approach Intersection 2

Random Direction (LT/RT)

Coin Flip, Heads is RT and Tails is LT


IF CHOOSE LT

LT 90 Degrees

FD 3 Blocks (Curve up hill)

Approach Main Road

SETPOS Intersection 2

SETPOS Intersection 1

SETPOS Home

END


IF CHOOSE RT

RT 90 Degrees

FD 2 Blocks

Approach Main Road

SETPOS Intersection 2

SETPOS Intersection 1

SETPOS Home

END


I just did a standard walk around my neighborhood. I live surrounded by houses on a close street in the suburbs. 
I see cars and houses, birds chirping my neighbor washing his car. The randomness made it more interesting and “interactive”. 
I would only add more possibilities or places to go, say to the school or the deli. I think this code would work well in my neighborhood and give a good exercise. 
