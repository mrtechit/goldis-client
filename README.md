# goldis-client
A client application which connects to goldis server

### Install Go
This project is implemented using Go. If Go is not yet installed, please download and install from [here](https://golang.org/doc/install)

### Build
```bash
go build 
```
### Run client
```bash
./mockredis-cli
```
### Commands
Allowed commands are `DUMP`, `SET`, `RENAME`, `QUIT`, `HELP` and used in following manner :
```bash
DUMP <key>
SET <key> <value>
RENAME <key> <key>
QUIT
HELP
```