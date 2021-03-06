# Game of life

## Rules

- Underpopulation: An alive cell with 0-1 live neighbors will die
- Right conditions: An alive cell with 2-3 live neighbors will be kept alive
- Overpopulation: An alive cell with more than 3 live neighbots will die
- Regeneration: A dead cell with exactly 3 live neighbors will live

# App
## Run

Run the game of life directly with go

`go run main.go`

## Tests

Execute all the test cases

`go test`

# Remaining tasks

- [ ] run it forever and update results in console
- [ ] connect edges so every cell will have 8 neighbors
- [ ] refactor

# References

[Programming Projects for Advanced Beginners #2: Game of Life](https://robertheaton.com/2018/07/20/project-2-game-of-life/)