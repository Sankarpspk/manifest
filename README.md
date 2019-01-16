# Future-OS #

### Sync ###

```bash
# Initialize local repository
repo init -u https://github.com/future-os/manifest -b pie
```

```bash
# Sync
repo sync --force-sync --no-clone-bundle
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh
```
```bash
# Choose a target
$ lunch future_$device-userdebug
```
```bash
# Build the code
$ mka bacon -jX
```
