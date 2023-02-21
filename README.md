
cd ~/gospace
mkdir go-workspaces
cd go-workspaces
mkdir hello
cd hello
go mod init coderprabhu.com/hello
go: creating new go.mod: module coderprabhu.com/hello
go get golang.org/x/example
go run coderprabhu.com/hello

cd ~/gospace/go-workspaces
go work init ./hello
go run coderprabhu.com/hello

