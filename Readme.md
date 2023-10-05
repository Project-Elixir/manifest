<p align="center">
  <img src="https://imgur.com/6nrBzqm.png" />
</p>

# Welcome to the Project 𝓔𝓵𝓲𝔁𝓲𝓻 /////////////// 

Project Elixir basically is yet another AOSP ROM in the market. Redefining your android experience with our new update which offers minimal UI enhancement and close to Stock android experience with customization So do not hesitate anymore, join us now and start enjoying the beauty of stock Android. 

[![Download Project Elixir [Custom ROM]](https://img.shields.io/sourceforge/dm/project-elixir.svg)](https://projectelixiros.com/download) <img src="https://komarev.com/ghpvc/?username=Project-Elixir&style=flat-square" alt="Project-Elixir" />  [![Download Project Elixir [Custom ROM]](https://img.shields.io/sourceforge/dt/project-elixir.svg)](https://projectelixiros.com/download) 

To get started, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

### Create a directory for the source files

* You can name this directory however you want, just remember to replace
* WORKSPACE with your directory for the rest of this guide.
* This can be located anywhere (as long as the fs is case-sensitive)

```
mkdir WORKSPACE
```
```
cd WORKSPACE
```

### Install Repo in the created directory
```bash
repo init --depth=1 -u https://github.com/Project-Elixir/manifest -b UNO
```

### Download the source
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Set up environment for Build
```
. build/envsetup.sh
```
### Choose a target
```
lunch aosp_$device-userdebug
```
### Build the code
```
mka bacon -jX
```

### Credits

 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**xdroidOSS**](https://github.com/xdroid-oss)
 * [**ParanoidAndroid**](https://github.com/AOSPA)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * And some other ROMs not mentioned above
   
### Adding Support

- For adding your device to the list of OFFICIALLY supported devices, you need to [**Fill the form & Apply for Maintainership**](https://docs.google.com/forms/d/1eme8i0nXFNpv2fEfbskoANIwLUGy4KcYXssluWv6obE) and fulfil the [**Maintainership requirement**](https://projectelixiros.com/documentation). Also you can contact us on Telegram profiles below.

<br>

<p align="center">
  <img src="https://i.imgur.com/9wgrVmV.png" />
</p>
