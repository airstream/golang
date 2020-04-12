    $ go version
go version go1.14.2 linux/amd64

    $ go
Go is a tool for managing Go source code.
Usage:
    go <command> [arguments]


    $ go help doc
usage: go doc [-u] [-c] [package|[package.]symbol[.methodOrField]]

    $ go help fmt
    
--- 

    $ go mod init github.com/airstream/service
    $ vi main.go 
    package main

    import "fmt"

    func main() {
        fmt.Println("Hello, GO!")
    }

    $ go run github.com/airstream/service
    Hello, GO
