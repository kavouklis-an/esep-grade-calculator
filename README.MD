# ESEP Grade Calculator

This library is a simple utility to calculate your grades. The program calculates grades of assignments, exams and essays. First it 
calculates the average of each category, then it multiplies the value by its' assigned weight and converts the numerical grade to a letter grade.

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```

The `grade_calculator.go` file contains the calculator code, and `grade_calculator_test.go` contains the unit tests. 