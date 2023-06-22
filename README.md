### Go

**Go Download,** https://go.dev/doc/install

`anup@ubuntu-22042-08:~$ wget https://go.dev/dl/go1.20.5.linux-amd64.tar.gz`

<br>

### Go installation,

**Remove any previous Go installation,**

`anup@ubuntu-22042-08:~$ sudo mkdir /home/anup/go`

`anup@ubuntu-22042-08:~$ rm -rf /home/anup/go && tar -C /home/anup -xzf go1.20.5.linux-amd64.tar.gz`

<br>

**Add /usr/local/go/bin to the PATH environment variable,**

`anup@ubuntu-22042-08:~$ export PATH=$PATH:/home/anup/go/bin`

`anup@ubuntu-22042-08:~$ echo $PATH`

<br>

**Verify installation,**

`anup@ubuntu-22042-08:~$ go version`

<br>
