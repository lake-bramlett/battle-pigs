
| Behavior | Input | Output |
| ------------- |:-------------:| -----:|
| Click button and display two random numbers | Click | 2, 100 |
| Click button and display two random numbers <= 6 | Click | 2, 6 |
| Add those numbers together and display | 2, 6 | 8 |
| Add total of two numbers to "score" | 8 | Round Score: 8 |
| Add logic that sets round score to zero if one or more numbers === 1 | numbers: 4, 1 | Set round score to 0 |
| Adds logic to add round score to Total Score | (old) Total Score: 4, Round Score: 8 | (new) Total Score: 12 |
| Add win condition when total score >= 100 | total score = 104 | "Winner winner pork dinner!" |  
| create Player Object | | new Player [name, myTurn, round score, total score] |
| Add logic to track total score in player object | | Player [name, true, 8, 12] |
| Add logic to switch turns based on "true" myTurn property | true/false | Player [name, true, 8, 12] Player [name, false, 0, 6] |
| Add logic to "End Turn" when either random === 1 or "hold" is used | 1, "hold" | endTurn( ); |
