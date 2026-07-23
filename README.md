# plugin-bursts

Official **bursts** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idlescreen) (Trance daemon).

## Build

Requires a sibling checkout of the daemon for `trance-api`:

```bash
git clone https://github.com/idlescreen/idlescreen.git
git clone https://github.com/idlescreen/plugin-bursts.git
cd plugin-bursts
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install trance-plugin-bursts
# or: sudo dnf install trance-plugin-bursts
```

See [idlescreen.github.io/packages](https://idlescreen.github.io/packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
