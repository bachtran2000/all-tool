# Install golang
~~~
mkdir temp
cd temp 
wget https://dl.google.com/go/go1.20.linux-amd64.tar.gz
sudo tar -xvf go1.20.linux-amd64.tar.gz
sudo mv go /usr/local
export GOROOT=/usr/local/go
export GOPATH=$HOME/go
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
source ~/.profile
~~~

# all-tool
get tool and install

```
go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
go install -v github.com/projectdiscovery/naabu/v2/cmd/naabu@latest
go install github.com/lc/gau/v2/cmd/gau@latest
go install github.com/tomnomnom/gf@latest
go install github.com/tomnomnom/waybackurls@latest
go install -v github.com/projectdiscovery/uncover/cmd/uncover@latest
go install github.com/Emoe/kxss@latest
go install github.com/hahwul/dalfox/v2@latest

nuclei
subfinder
httpx
```
# Install GCC for Win
https://udomain.dl.sourceforge.net/project/mingw-w64/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/8.1.0/threads-win32/sjlj/x86_64-8.1.0-release-win32-sjlj-rt_v6-rev0.7z
