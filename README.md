# OpenWrt Node.js Packages (nodejs)

##Description

OpenWrt Node.js Packages : for trunk (Bleeding Edge) / LEDE

Note: Testing target only ar71xx.

## License

See:
- [OpenWrt license](http://wiki.openwrt.org/about/license)

## Usage

Add follow line to feeds.conf or feeds.conf.default
```
src-git node https://github.com/nxhack/openwrt-node-packages.git;v4.x
```

Run
```
./scripts/feeds update node
./scripts/feeds install -a -p node
```
