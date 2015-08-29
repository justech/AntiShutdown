# AntiShutdown
## Prerequisite
- ProxyCap ([Get the trial version](http://www.proxycap.com/download.html))
- Plink (master.zip includes it)

## Installation
0. Install ProxyCap
1. Download master.zip
2. Unzip it
3. Setup start.bat
4. Load the rule files on ProxyCap

### How to setup start.bat
`plink [options] [user@]host [command]`
#### Options for AntiShutdown
- -P port : connect to specified port
- -pw passw : login with specified password
- -D [listen-IP:]listen-port : Dynamic SOCKS-based port forwarding

#### Examples of start.bat
```
plink -P 2222 -pw 1234 -D 127.0.0.1:5111 test@test.com
```
(-D option is compulsory.)

## Running
0. Run ProxyCap (It is running when startup by default)
1. Execute start.bat
2. Enable ProxyCap
3. Enjoy the game in 2:00~7:00
