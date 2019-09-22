# gomod-tutorial
 belajar Go Mod (MVN nya Golang)
Adalah Dependency buatan dari team Go 

Pre
versi go 1.12*

step by step
1. mkdir gomod-tutorial
2. masuk ke folder gomod-tutorial
3. inisial project
``` 
go mod init github.com/srigalamilitan/gomod
```
result 
```
go: creating new go.mod: module github.com/srigalamilitan/gomod
```

4. go mod tidy digunakan untuk membersihkan depedency yang tidak digunakan (unused dependency)
5. go mod help -->
```
λ go mod help
Go mod provides access to operations on modules.

Note that support for modules is built into all the go commands,
not just 'go mod'. For example, day-to-day adding, removing, upgrading,
and downgrading of dependencies should be done using 'go get'.
See 'go help modules' for an overview of module functionality.

Usage:

        go mod <command> [arguments]

The commands are:

        download    download modules to local cache
        edit        edit go.mod from tools or scripts
        graph       print module requirement graph
        init        initialize new module in current directory
        tidy        add missing and remove unused modules
        vendor      make vendored copy of dependencies
        verify      verify dependencies have expected content
        why         explain why packages or modules are needed

Use "go help mod <command>" for more information about a command.


```

 

Pro
1. tidak perlu lagi buat project didalam GOPATH
