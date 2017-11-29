# Elevator
Creates and runs an elevator simulator, with multiple elevators and different passangers, each elevator cannot open if they are not at a floor, and they cannot move before the elevator doors are closed this requires complex mutex locks to be used without causing the threads to slow down

## Build

`make test`

The above make will build and run a few test to demonstrait the program
