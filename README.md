Displays the CPU usage with a small graph like so

```bash
⣾⣄ 2.13%
```

## Usage

Just put the following block to your `~/.i3/i3blocks.conf`

```bash
[cpu_usage]
interval=1
command=<path to this repo>/cpu.sh
min_width=⣾⣄ 100.00%
```
