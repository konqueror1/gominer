# gominer

## Build
```
git clone https://github.com/AGPFMiner/gominer.git
cd gominer
go build
Or if you are crosscompiling, try this:
env CC=arm-linux-gnueabi-gcc CXX=arm-linux-gnueabi-g++ CGO_ENABLED=1 GOOS=linux GOARCH=arm GOARM=6 go build
```
