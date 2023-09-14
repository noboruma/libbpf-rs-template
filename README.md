# Prerequisites

Install the following tool for cargo:
```
cargo install cargo-generate
```

# Usage

Simply run the following:
```
cargo generate --git https://github.com/noboruma/libbpf-rs-template
```

# Usage example

```
└$ cargo generate --git https://github.com/noboruma/libbpf-rs-template
🤷   Project Name: MyXdp
⚠️   Renaming project called `MyXdp` to `my-xdp`...
🔧   Destination: /workspace/my-xdp ...
🔧   project-name: my-xdp ...
🔧   Generating template ...
🔧   Moving generated files into: `/workspace/my-xdp`...
🔧   Initializing a fresh Git repository
✨   Done! New project created /workspace/my-xdp
```

Then simply compile by doing:
```
cd /workspace/my-xdp
cargo build
```

And run the binary:
```
./target/debug/my-xdp
```
