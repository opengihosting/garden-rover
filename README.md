# Garden Rover

## Robotic Lawn Mower

A squad of robotic lawn mowers are to be used to cut the grass of homes in the local area. These gardens, which are curiously rectangular and all the same size, must be navigated by the lawn mowers so that every bit of grass is cut.

A mower's position is represented by a combination of x and y coordinates and a letter representing one of the four cardinal compass points. The garden is divided up into a grid to simplify navigation. An example position might be `0 0 N` which means the mower is in the bottom left corner and facing North.

Each mower will explore sequentially, which means that the second mower won't start to move until the first one has finished moving.

In order to control a mower, the gardener sends a simple string of letters. The possible letters are 'L', 'R' and 'M'. 'L' and 'R' make the mower spin 90 degrees left or right respectively, without moving from its current spot. 'M' means move forward one grid point, and maintain the same heading.

Assume that the square directly North from (x, y) is (x, y+1).

## Usage
`> dotnet build` will restore packages and build the application

`> dotnet test` will run the tests
