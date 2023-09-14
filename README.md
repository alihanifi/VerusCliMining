
```bash
lscpu
```
If the output doesn't show `Architecture: aarch64` or `CPU op-mode(s): 32-bit, 64-bit`, then do not bother to continue. Your phone is not running a 64-bit OS.

```bash
curl -o- -k https://raw.githubusercontent.com/alihanifi/VerusCliMining/main/install.sh | bash
```
exit with `<CTRL>-X` followed by `y` and an `<ENTER>`
```bash
nano config.json
```

## Usage:

```bash
cd ccminer
```
start mining with `~/ccminer/start.sh`
```bash
./start.sh
```
