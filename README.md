![PixelPlusUI](https://i.imgur.com/TIgKV2M.png "PixelPlusUI")

PixelPlusUI
===========

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

```bash
# Create a directory for the source files
# You can name this directory however you want, just remember to replace
# WORKSPACE with your directory for the rest of this guide.
# This can be located anywhere (as long as the fs is case-sensitive)
$ mkdir WORKSPACE
$ cd WORKSPACE
# Install Repo in the created directory
$ repo init --depth=1 -u https://github.com/PixelPlusUI-Elle/manifest -b eleven
# Download the source
$ repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
# Set up environment
$ . build/envsetup.sh
# Choose a target
$ lunch aosp_$device-userdebug
# Build the code
$ mka bacon -jX
```
