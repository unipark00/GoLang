## GoLang Start ~
### [ Setup ]
1) Download path  
https://dl.google.com/go/go1.10.windows-amd64.msi

2) Environment Variables
* User variables  : ```GOROOT = C:\Go```
* System variables: add ```%GOROOT%\bin``` to ```Path```

### [ Tools ]
Go includes the same sort of debugging, testing, and code-vetting tools as many language distributions. The Go distribution includes, among other tools,  

* ```go build```, which builds Go binaries using only information in the source files themselves, no separate makefiles
* ```go test```, for unit testing and microbenchmarks
* ```go fmt```, for formatting code
* ```go get```, for retrieving and installing remote packages
* ```go vet```, a static analyzer looking for potential errors in code
* ```go run```, a shortcut for building and executing code
* ```godoc```, for displaying documentation or serving it via HTTP
* ```gorename```, for renaming variables, functions, and so on in a type-safe way
* ```go generate```, a standard way to invoke code generators

It also includes profiling and debugging support, runtime instrumentation (to, for example, track garbage collection pauses), and a race condition tester.

There is an ecosystem of third-party tools that add to the standard distribution, such as **```gocode```**, which enables code autocompletion in many text editors, **```goimports```** (by a Go team member), which automatically adds/removes package imports as needed, **```errcheck```**, which detects code that might unintentionally ignore errors, and more. Plugins exist for adding language support to several widely used text editors. Additionally, several IDEs are available. For instance, **```LiteIDE```**, which is branded as "a simple, open source, cross-platform Go IDE", and **```GoLand```**, which claims to be "capable and ergonomic."

### [ Keyword ]
```
break        default      func         interface    select
case         defer        go           map          struct
chan         else         goto         package      switch
const        fallthrough  if           range        type
continue     for          import       return       var
```
### [ Link ]
https://github.com/arahansa/golkorea
가장 빨리 만나는 Go 언어: https://github.com/pyrasis/golangbook
