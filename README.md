# IEEE Stock Car Race – Game Rules

## The Setup
The field is a 4x8 foot board divided into two sections: the racecourse and the pit area. The racecourse is an oval with two lanes divided by a white center line. The pit area sits at the bottom of the field and has three 12x12 inch parking spots. Before the match starts, two obstacle cars are randomly placed on the course, one in each lane on the long straightaways. A die is rolled to determine which pit spot your robot is assigned to.

## Starting
Your robot starts completely inside the 12x12x12 inch start box. The match begins when the referee raises the green start flag, which your robot should detect automatically. You can also use a manual start button as a backup. Starting before the flag drops you from 10 points to zero for that bonus, so make sure your sensing is dialed in.

## The Race
Your robot runs three laps around the oval course fully autonomously. The whole thing must be completed in 3 minutes or less to earn the base 100 point completion bonus. Finishing early gets you 1 bonus point for every full 10 seconds under 3 minutes.

## The Pit Stop
Sometime after lap 1 or lap 2, your robot must enter the pit area and stop in its assigned spot. A few things have to happen here. Your robot needs to stop for a minimum of 2 seconds, drop off the tire it carried from the start, and pick up a fresh tire from the pit area (it cannot reuse the one it dropped). Leaving before 2 seconds knocks your pit stop points from 15 down to 10. Hitting the correct assigned spot earns additional points on top of that.

## Scoring Points

| Achievement | Points |
|---|---|
| Entering the course | 25 |
| Finishing in under 3 minutes | 100 |
| Speed bonus (per full 10 seconds under 3 min) | 1 |
| Starting from the green flag | 10 |
| Making a pit stop | 15 (10 if you leave early) |
| Stopping in the correct pit spot | 15 |
| Dropping your tire in the pit | 25 |
| Picking up a fresh tire | 40 |
| Ending the race in your assigned pit spot | 15 |
| Clean lap without touching walls | 10 |
| Clean lap without hitting an obstacle | 15 |
| Raising your school flag on the final lap | 25 |
| Entering the publicity contest | 10 |

## Ending the Match
After 3 minutes the technician must stop the robot without disturbing any game elements. It is strongly recommended to build an automatic shutoff into your robot rather than trying to stop it manually, since anything that happens after time expires does not count toward your score.
