# Bootleggers for Titan (Pasta) #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/BootleggersROM/manifest.git -b pasta

# Clone my local repo
git clone https://github.com/linusdan/bootleg_titan_manifests.git -b master .repo/local_manifests

# Sync
repo sync -c --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ source build/envsetup.sh

# Choose a target
$ lunch bootleg_titan-userdebug

# Build the code
$ mka bacon
```
