# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

You can test three different grade categories:

Assignments - Weighted at 50%
Exams - Weighted at 35%
Essays - Weighted at 15%

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test
```

Expected output "go test" is:
PASS
ok esep/grade-calculator  (time elapsed in s)

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
Expected output is:
ok esep/grade-calculator coverage: 100.0% of statements

The grading scale is as follows:

A >= 90
B >= 80
C >= 70
D >= 60
F <  60