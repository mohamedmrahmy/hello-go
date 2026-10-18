# hello-go
It prints a title "My first Go project", then it calculates the multiplication of 2 given int 6 & 7, and last line prints the author's name.

## How to run
The command to run it
```
go run .
```
The command to build .exe
```
go build
```
## Example output
```
My first Go project
42
Built by Mohamed Rahmy
```
## What I learned
- `go mod init` - creates the module go.mod file & turns the current folder into Go project
- After any changes inside main.go, .exe file needs to be updated with the changes using go build command
- hello.exe didn't run because we didn't add `.\` right before the file .exe name which tells to run a program fron the current folder so it should be `.\hello.exe` as a command
- hello.exe didn't get uploaded because of `.gitignore` file and inside we mentioned which files to ignore as *.exe
