<p align="center">
  <img src="https://i.imgur.com/C0Wcdr5.png" />
</p>


### Project Elixir [![Download Project Elixir](https://img.shields.io/sourceforge/dt/project-elixir.svg)](https://projectelixiros.com/download)

Project Elixir is another aftermarket AOSP ROM which basically offers minimal UI enhancement & close to Stock Android ROM with great performance, security and stability. Most of the OEMs' these days will provide slow and untimely updates, but we don't do that here. We closely follow Google to bring the latest updates to our users, and even prolong support for devices that have been declared obsolete by OEMs. Our ROMs' source code is open-source, secure, stable, and outstanding. Your experience while using Project Elixir will be butter smooth without compromising the quality of the Android experience. In short, it's perfectly balanced between Great Performance, Security, stability, minimal UI & awesome features including pixel goodies. So do not hesitate anymore, join us now and start enjoying the beauty of stock Android. Build and enjoy Project Elixir on your respective devices!

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

### Create a directory for the source files

* You can name this directory however you want, just remember to replace
* WORKSPACE with your directory for the rest of this guide.
* This can be located anywhere (as long as the fs is case-sensitive)

```bash
mkdir WORKSPACE
cd WORKSPACE
```

### Install Repo in the created directory

>> [Hint: This might take a long time]

```bash
repo init -u https://github.com/Project-Elixir/manifest -b Tiramisu
```

>> [Hint: Want to save some space ? Then use this]

```bash
repo init --depth=1 -u https://github.com/Project-Elixir/manifest -b Tiramisu
```

### Download the source
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build

```bash
# Set up environment
. build/envsetup.sh
# Choose a target
lunch aosp_$device-userdebug
# Build the code
mka bacon -jX
```

### Credits

 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**ArrowOS**](https://github.com/ArrowOS)

### Adding Support

- For adding your device to the list of OFFICIALLY supported devices, you need to [**Fill the form & Apply for Maintainership**](https://projectelixiros.com/documentation) and fulfil the [**Maintainership requirement**](https://projectelixiros.com/documentation). Also you can contact us on Telegram profiles below.

### Follow  us for more

 * [**Telegram Announcements Channel**](https://t.me/Elixir_Updates)
 * [**Our OFFICIAL Website**](https://projectelixiros.com/)
 * [**Our Team**](https://projectelixiros.com/team)
 * [**Currently supported devices**](https://projectelixiros.com/download)
 * [**Changelog**](https://projectelixiros.com/changelog)
 * [**Telegram Discussion Group**](https://t.me/Elixir_Discussion)


### Do consider donating or buying me a coffee on Paypal if you want to appreciate our work or join us on Patreon for sustainable support and early build access.

```bash
Patreon : https://www.patreon.com/join/uglykid24
```
```bash
GPAY UPI ID: dwarmachine24@oksbi
```
```bash
PAYPAL: https://www.paypal.me/uglykid24
```

# Happy Building :)
