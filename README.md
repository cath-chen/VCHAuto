# VCHAuto
Automating selecting candidates for VCH health site


## Logic

1. if speaks viet
    1. check hypertension trained
        1. if no — take but find another person hypertension trained
        2. at least 3
2. if not speak viet
    1. checked hypertension trained
        1. if no — don’t choose
    2. at least 3

combine both lists into 1 list
choose random people to fill entire list — if already in list choose again

check home from list of above
	if from home — check if 5 (if more than 5 then reject)
	if from ucla — check if 10 (if more than 10 then reject)

if num people sign up < max  —> output everyone is accepted (manual check pls)
check length of list — if not long enough loop the whole thing
