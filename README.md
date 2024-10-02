ref: https://www.youtube.com/watch?v=jpKysZwllVw&ab_channel=ThatDevOpsGuy

```
# Download https://go.dev/

GOROOT=/c/Go
mkdir -p $GOROOT
# Install the go
# export the path 
export PATH=$PATH:$GOROOT/bin

# set up the workspace 
GOPATH=/c/my-go-ws/

mkdir -p $GOPATH/k8s-operator-example/app
cd $GOPATH/k8s-operator-example
go mod init github.com/naren4b/k8s-operator-example/app
 
 
 
 
 
# Packages https://pkg.go.dev/


```
