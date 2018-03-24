

# Install Node

## Find the latest release and download it - e.g. we're using v1.3.6

```
NODE_BASE_DIR=~/tools/node
NODE_VERSION=9.9.0
mkdir -p $NODE_BASE_DIR/downloads

curl -L https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz \
     -o $NODE_BASE_DIR/downloads/node-$NODE_VERSION
tar -xf $NODE_BASE_DIR/downloads/node-$NODE_VERSION -C $NODE_BASE_DIR

rm $NODE_BASE_DIR/current || echo "" >> /dev/null
ln -s $NODE_BASE_DIR/node-v$NODE_VERSION-linux-x64 $NODE_BASE_DIR/current

```
