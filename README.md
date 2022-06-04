# CrystalOS

 Getting Started
---------------
To get started with the CrystalOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/CrystalOS-Temp/manifest.git -b A12.1
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

To lunch your device and start building

```bash
Crystalize crystal_devicecodename-buildtype
```
