Using Go workspaces

```
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

cd ~/gospace/go-workspaces
git clone https://go.googlesource.com/example
cd example 
rm -rf .git

cd ~/gospace/go-workspaces
go work use ./example

```

Git 
```
git init
git status
git checkout -b main
git add .
git commit -m "Using go workspaces"
git remote add origin https://github.com/CoderPraBhu/go-workspaces.git
git push -u origin main


```