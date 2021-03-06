# BQ Aquaris E5 aka Vegeta / Aquaris E5 HD aka Vegetahd

The family of Aquaris E5 devices by BQ are all called vegeta +  a special suffix (there is an E5 HD so it's vegetahd for example). **HOWEVER**, the hardware is "the same" only in the versions E5 (vegeta) and E5 HD (vegetahd). The newer [**E5 4G (vegetalte)**](devices/vegetalte.md) which has an LOS 14.1 image is a **completely different** System and does not share the same hardware. **BUT** the [**BQ Aquaris E4.5 (krillin)**](devices/krillin.md) is **basically the same** and maybe it's images will work with minor changes.

## Status

### Halium

There has been no effort to get Halium onto this device so far.

### Distributions

The following entries are just a placeholder, exactly as this sentence.

|               Distribution               | Device Specific Files | Kernel | What works | What doesn't work |
| :--------------------------------------: | :-------------------: | :----: | :--------: | :---------------: |
| Ubports 15.04 (Android 5.1 base) [device page](https://devices.ubports.com/#/vegetahd) |           ?           |   ?    |     ?      |         ?         |


### Kernel & Hardware
#### Mainline (4.13rc4 as of writing)
There is a very rudimentary device tree source file inside kernel 4.13rc4 [here](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/arch/arm/boot/dts/mt6589-aquaris5.dts?h=v4.13-rc4). This still needs a lot of work.

#### Canonical's Ubuntu Touch kernel (3.4.67 based)
This kernel can be found [here](https://github.com/bq/aquaris-E5/tree/aquaris-E5-ubuntu-master)

## Device Specifics

### Guides

#### Entering Fastboot & Recovery Mode
For [BQ Aquaris E4, E4.5, E5 and E6](http://www.mibqyyo.com/en-articles/2016/01/20/recovery-menu-bq-phones/), assuming *device is off*:

> Hold *Power* button + *Volume Up* button until menu pops up
>
> Boot Mode Selection:
> Navigate with *Volume Up*  and select with *Volume Down*
>
> Entering Recovery:
> Press *Volume Up* to access menu
> Navigate with *Volume* buttons and select with *Power* button.



### Developer Info

Some devices show strange behaviour of some kind, try to find this (for example in the xda-developers forum) and document it

### Usefull Ressources
If anything might be usefull but didn't fit above you can just throw in some links here.