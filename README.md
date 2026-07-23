# saver-bursts

Official **bursts** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idle-core).

## Build

Requires a sibling checkout of the core daemon for `trance-api`:

```bash
git clone https://github.com/idlescreen/idle-core.git
git clone https://github.com/idlescreen/saver-bursts.git
cd saver-bursts
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install trance-saver-bursts
# or: sudo dnf install trance-saver-bursts
```

See [idlescreen.github.io/idle-packages](https://idlescreen.github.io/idle-packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
