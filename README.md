# NBA_Playoffs
## Directories:
Directories should be named as follows:
`first_round`, `second_round`, `third_round`, `finals`. 
For each round, each participant has a .txt file with his message for the respective round, while the names of the files do not matter.
Examples of messages per round are given below.
The name of the participant should be written consistently in each file.

Names of teams should be 3 letters. Names of players should be 4 letters (first two of first and last names was found to be good, robust and simple enough for most people).

## Running the notebook:
1. Provide the path for the relevand directories and the name of the odds file.
2. Type the results in the cell which requires it.
3. Call the function `calc_total` by giving it as an input the round you are calculating (int). It will calculate all the previous rounds as well.

### Example for pre-round 1 message (not case-sensitive):

`YOUR_NAME`

`champ,XXX`

`Second,XXX`

`MIA_ATL,XXX_9`

`BOS_BKN,XXX_9`

`MIL_CHI,XXX_9`

`PHI_TOR,XXX_9`

`PHX_NOP,XXX_9`

`MEM_MIN,XXX_9`

`GSW_DEN,XXX_9`

`DAL_UTA,XXX_9`

### Example for pre-round 2 message (not case-sensitive):

`Your_Name`

`PHX_LAC,XXX_9`

`GSW_DEN,XXX_9`

`DAL_UTA,XXX_9`

`MIL_CHI,XXX_9`

`SCORERS:XXXX,XXXX,XXXX,XXXX`

### Example for pre-round 3 message (not case-sensitive):

`Your_Name`

`MIL_CHI,XXX_9`

`PHI_TOR,XXX_9`

`SCORERS:XXXX,XXXX`

`ASSISTERS:XXXX,XXXX`

`REBOUNDERS:XXXX,XXXX`

### Example for pre-round 4 message (not case-sensitive):

`Your_Name`

`MIL_CHI,XXX_9`

`SCORERS:XXXX`

`ASSISTERS:XXXX`

`REBOUNDERS:XXXX`


