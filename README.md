# UC Santa Cruz Language, Systems, and Data Seminar demo 2024

## Setup

```
cargo install --git https://github.com/esoterra/wow wow

vim ~/.bashrc # add `$HOME/.wow/bin` to path

wow init
```

## Examples

```
cowsay
cat2 wow.kdl
claw ./examples/test.claw ./test.wasm
templatec ./examples/website-template.html ./website-template.wasm
```

## Wave-Tank

```
cargo install --git https://github.com/lann/wave-tank
```

```
wave-tank website-template.wasm 'apply({title:"A", content:"B", include-footer:false})'
```
