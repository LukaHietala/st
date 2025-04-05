### Installation

Requires `xlib` development headers. Default installation path: `/usr/local`.

#### Dependencies

On Debian/Ubuntu:

```bash
sudo apt install libx11-dev libxft-dev
```

Arch people can figure it out themselves.

#### Building

```bash
git clone https://github.com/lukahietala/st
cd st
sudo make clean install
```

You can customize the installation path by editing the `config.mk` file.
