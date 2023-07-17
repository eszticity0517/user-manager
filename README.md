# README #

Setup, guideline, deployment ...

Author: Eszter Weiszné Szabó

# Some docs about setting up the project #
(skip this if you wish, this part contains my steps before creating the repo)

download Golang from https://go.dev/dl/

for version check type in the terminal: go version

you might need to set goroot and gopath variables, also adding Go to Path variable:

https://stackoverflow.com/questions/7970390/what-should-be-the-values-of-gopath-and-goroot

An autocompletion daemon for the Go programming language
go install https://github.com/nsf/gocode@latest

install gopls for your IDE:
https://pkg.go.dev/golang.org/x/tools/gopls

to restore packages, run:
go mod tidy
