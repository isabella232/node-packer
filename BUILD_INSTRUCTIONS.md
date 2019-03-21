# How to build a binary `nodec` (macOS)

## Download `rubyc`

GitHub: https://github.com/pmq20/ruby-packer

```bash
curl -L http://enclose.io/rubyc/rubyc-darwin-x64.gz | gunzip > rubyc
chmod +x rubyc
./rubyc --help
```

## Build `nodec`

In the `node-packer` checkout dir:

```bash
rubyc bin/nodec
mv a.out nodec
```