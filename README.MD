# Grade Calculator

This Go project calculates a student's final grade. Assignments are worth 50%,
exams are worth 35%, and essays are worth 15%.

## Files

- `grade_calculator.go` has the calculator code.
- `grade_calculator_test.go` has the tests.
- `go.mod` has the Go module information.

## Example

```go
calculator := NewGradeCalculator()
calculator.AddGrade("assignment 1", 92, Assignment)
calculator.AddGrade("exam 1", 88, Exam)
calculator.AddGrade("essay 1", 95, Essay)

finalGrade := calculator.GetFinalGrade()
```

## Run the tests

You need Go 1.24 or newer. From the repository folder, run:

```sh
cd grade-calculator
go test
```

To check test coverage, run:

```sh
go test -cover
```
