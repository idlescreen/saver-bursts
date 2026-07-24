# saver-bursts

Official **bursts** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idle-core).

## Build

Requires a sibling checkout of the core daemon for `idle-api`:

```bash
git clone https://github.com/idlescreen/idle-core.git
git clone https://github.com/idlescreen/saver-bursts.git
cd saver-bursts
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install idle-saver-bursts
# or: sudo dnf install idle-saver-bursts
```

See [idlescreen.github.io/packages](https://idlescreen.github.io/packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
