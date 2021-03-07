![PixelPlusUI](https://i.imgur.com/foReqPr.png "PixelPlusUI")


PixelPlusUI is a Pixel Experience based ROM with some more friendly user experience. What differentiates us from the rest, you ask? Well that's why you're here. LET'S FIND OUT. It has additional localised and personalized functionality while preserving the stock Android look by adhering to Material Design guidelines. Unlike OEMs' slow and untimely updates, we closely follow Google to bring the latest updates to our users, and even prolonging support to devices that have been declared obsolete by OEMs. Our ROMs' source code is open source, secure, stable and outstanding. Your experience using PixelPlusUI will be butter smooth with added convenience and features. So do not hesitate anymore, join us now and start enjoying the beauty of stock Android or even be one of our developers. Let's bring this project to greater heights! PixelPlusUI is a minimal and close to stock Android ROM which offers great performance and stability with many awesome features. The main aim of this rom is to give user a better experience without compromising quality of Android experience so that no one struggles in any kind of difficulties while using their device. PixelPlusUI brings a better UI/UX to Android with a seamless experience coupled with customisations and user security. But this doesn't mean our aim is to provide all the customisation available on the planet. We are focused on a cleaner, more Material design approach with Pixel Goodies. So sit back and enjoy PixelPlusUI on your device!

===========

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

## Create a directory for the source files

* You can name this directory however you want, just remember to replace
* WORKSPACE with your directory for the rest of this guide.
* This can be located anywhere (as long as the fs is case-sensitive)

```bash
$ mkdir WORKSPACE
$ cd WORKSPACE
```

### Install Repo in the created directory

>> [Hint: This might take a long time]

```bash
repo init -u https://github.com/PixelPlusUI-Elle/manifest -b eleven
```

>> [Hint: Want to save some space ? Then use this]

```bash
$ repo init --depth=1 -u https://github.com/PixelPlusUI-Elle/manifest -b eleven
```

### Download the source
```bash
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

![Credit](https://i.imgur.com/a6njYr9.png "Credit")


 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**BlissROMs**](https://github.com/BlissRoms)
 * [**Syberia Project**](https://github.com/syberia-project)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**Octavi-OS**](https://github.com/Octavi-OS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**StatiXOS**](https://github.com/StatiXOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**AOSAP**](https://github.com/AOSAP)
 * [**ShapeShiftOS**](https://github.com/ShapeShiftOS)
 * [**PixelExtended**](https://github.com/PixelExtended)
 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
 * [**Wave-Project**](https://github.com/Wave-Project)
 * [**Project-404**](https://github.com/P-404)




![Support and Donation](https://i.imgur.com/aNanj7v.png "Support and Donation")

### Adding Support
 - For adding your device to the list of supported devices, please fill the maintainers form [**Form**](https://docs.google.com/forms/d/e/1FAIpQLScA5G_AUKiJlDWCM4Beaf_059dVZiClHv_rwZsklcXcGq0tzQ/viewform?vc=0&c=0&w=1) with your device tree and previous experience in building roms. Or you can contact us on Telegram Profiles below for faster response.
 * [**Kostya-Maslennikov**](https://t.me/kostyajrz)
 * [**Saurav**](https://t.me/ugly_kid_af)

### Follow  us for more
 * [**Telegram Group**](https://t.me/ppuichat)
 * [**Telegram Channel**](https://t.me/ppuich)
 * [**Telegram Announcements**](https://t.me/ppuinews)

### DONATION LINKS ------------------

If you have liked our work and want to support us please consider donating for servers

```bash
PAYTM UPI ID : dwarmachine24@paytm
GPAY UPI ID: dwarmachine24@oksbi
PAYPAL: https://www.paypal.me/uglykid24
```

# Happy Building :)
