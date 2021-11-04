go mod init github.com/xcheng85/golang-module-test

go list -m -versions rsc.io/sampler

go mod tidy
go list -m all

go test ./...

git tag v0.1.0

 git remote add origin https://github.com/xcheng85/golang-module-test

 git tag v0.1.0

 git push origin v0.1.0

 go list -m github.com/xcheng85/golang-module-test@v0.1.0