# DslReports-CLI

DslReports.com's commandline speed testing utility.





### How do I use this?

First, get the required dependencies:

1. `go get github.com/codegangsta/cli`
2. `go get github.com/BrendanMcCallum/DslReports`
3. `go get github.com/antonholmquist/jason`

Then simply run : `go run main.go`

### Additional Flags

#### -d --debug

Use this to have useful debugging information output to the screen as well as saved in a folder called dslreports.com in the current working directory.


#### -o --output json|csv

Saves the speed test results in the format specified as the first argument


#### --down number


Specify the number of streams to be used for the download test.

#### --up number

Specify the number of streams to be used for the upload test.


