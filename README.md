# Go Map Access Panic

This repository demonstrates a common error in Go: accessing a map element without first checking if the map is nil.  This can lead to a runtime panic, crashing your program.

## Bug

The `bug.go` file contains code that attempts to access an element of a map that hasn't been initialized. This results in a panic.

## Solution

The `bugSolution.go` file provides a corrected version that checks if the map is nil before accessing its elements, preventing the panic.

## How to reproduce

1. Clone the repository.
2. Navigate to the repository directory.
3. Run `go run bug.go` to see the panic.
4. Run `go run bugSolution.go` to see the corrected code in action.