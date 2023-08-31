# openresty-slackware

## Install dependence packages

```bash
slackpkg -batch=on -default_answer=y install zlib \
gd libxslt fontconfig libxcb libX11 libXau libXdmcp libXpm
```
## and then build openresty package

```bash
git clone https://github.com/zonshy/openresty-slackware.git
cd openresty-slackware/
./openresty.SlackBuild
```
