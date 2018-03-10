
# Install LinkerD

## Find the latest release and download it - e.g. we're using v1.3.6

```
LINKERD_VERSION=1.3.6
mkdir ~/tools/linkerd/downloads
cd ~/tools/linkerd
curl -L https://github.com/linkerd/linkerd/releases/download/$LINKERD_VERSION/linkerd-$LINKERD_VERSION.tgz \
     -o ~/tools/linkerd/downloads/linkerd-$LINKERD_VERSION.tgz
tar -xf downloads/linkerd-$LINKERD_VERSION.tgz -C .
ln -s linkerd-1.3.6 current
```
