# legacyplano
A parser project


As of 1.8, 'go tool yacc' is no longer included. Instead, obtain 'goyacc' with the following:
go get -u golang.org/x/tools/cmd/goyacc

example https://github.com/cdstelly/goyacc-sample
https://github.com/golang-samples/yacc/tree/master/simple

Followed by:
goyacc -o calc.go -p Calc calc.y