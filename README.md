# Raw CFX Server
A very basic [cfx server](https://docs.fivem.net/docs/server-manual/setting-up-a-server-vanilla/#windows) with no resources except [sessionmanager](https://github.com/citizenfx/cfx-server-data/tree/master/resources/%5Bsystem%5D/sessionmanager) as it's required.

## Launch
- Download the artifacts for [windows](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/)/[linux](https://runtime.fivem.net/artifacts/fivem/build_proot_linux/master/) in any path, for example `C:\FXServer\Artifacts`/`~/FXServer/Artifacts`.
- Clone this repository to any path in the machine, for example `C:\FXServer\NewServer`/`~/FXServer/NewServer`.
- Execute the following command line:
### Windows
```cmd
CD /D "C:\FXServer\NewServer"
"C:\FXServer\Artifacts\FXServer.exe" +exec server.cfg
```
### Linux
```sh
cd ~/FXServer/NewServer && bash ~/FXServer/Artifacts/run.sh +exec server.cfg
```
