###PART ONE QUESTIONS
1. yes, it always moves forward unless there is something blocking its path like a rock or a wall.
2. the bug always moves forward into the next free space. If the space is not free, the bug turns.
3. if it does not move, it turns.
4. it leaves behind a flower!
5. when it is at the edge of a grid, it hits the wall and turns.
6. when there is a rock immediately in front of it, the bug turns.
7. No. flowers do not move.
8. a flower �dies�
9. NO. rock does not move. no other behavior.
10. No. actors are either replaced, removed, or do not move, but they cannot occupy the same space at the same time.

| Angle  | Direction  |
| ------ |:----------:|
| 0      | North      |
| 45     | North-East |
| 90     | East       |
| 135    | South-East |
| 180    | South      |
| 225    | South-West |
| 270    | West       |
| 315    | North-West |
| 360    | North      |

2. You can move it to any location on the grid. (ie. not outside the grid or on a rock). The bug maintains the original direction it was in before using moveTo. The program will error if you try to move it outside the grid.

3. setColor

4. The bug disappears. It is no longer there when the rock is removed.

##PART TWO:

1. The variable SideLength sets the length of the side (how far the bug should travel on each side of the shape)
2. The variable steps counts how many steps the bug has made and resets at a certain point
3. turn() is called twice because a turn is 45 deg and we want to rotate the bug 90 deg
4. The move() method can be called because it is inherited from another class
5. The size of a Box Bug's square will be as large as the parameter passed into it
6. The path can only change if the code is modified. Otherwise, it will always be a box.
7. The value of steps will be 0 when steps == sideLength


##PART THREE
section a.
1. loc1.getRow() 
2. false
3. 4,4
4. 135, SE
5. parameter in method says which direction to find. Method returns the closest one.
