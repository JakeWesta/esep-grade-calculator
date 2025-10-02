# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

The library is broken up into three main files:

1. Go.mod – Lists the Go version and defines module path.
2. Grade_calculator.go – This is where all the functionality is defined. The GradeCalculator struct and GradeType type are defined. Multiple functions are made according to the specification, such as calculating a new grade, adding a grade, and calculating final grade. 
3. Grade_calculator_test.go – Imports the testing package to make functions that call the functions defined in grade_calculator.go and makes sure there output values are expected. 

To add further test cases, follow the current instantiations and declare a function with certain added grades with an expected output.


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