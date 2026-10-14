# ESEP Grade Calculator

A simple Go library designed to calculate course grades based on assignments, exams, and essays, and output a corresponding letter grade.

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
grade_calculator/
├── go.mod                  # Go module definition (esep/grade-calculator)
├── grade_calculator.go     # Core data structures and grading logic
├── grade_calculator_test.go# Unit tests for grade computation
README.MD                   # Project overview, setup, and instructions