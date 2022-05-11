
## MOnSieurFPGA Package Files

- [**MiSTer-devel**](https://github.com/MiSTer-devel), [**JTFPGA**](https://github.com/jotego), and other distribution packages for **MOnSieurFPGA** images running ArchLinux and MiSTerFPGA userspace binaries.

## Package List

- MOnSieurFPGA packages are fully automated. Every four hours, the most current binaries are pulled and new packages are pushed to [**Releases**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages). For detailed information on packages click the **source links** below.

- After initial installation, run **`sudo pacman -Sy "pkgname" --overwrite "*"`** to install/update individual packages listed below. 

- Use the following command **`sudo pacman -Syuu --overwrite "*"`** to update **all installed** packages.

| PKG Name| Source | Maintainer |Package Information | Default Installation |
|---------|--------|------------|--------------------|----------------------|
[**MiSTer-Devel-Bin**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Main_MiSTer**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Devel-Bin/PKGBUILD) | MOnSieurFPGA | Userspace binary that manages MiSTer on the ARM side, prebuilt. | **Yes** |
[**MiSTer-Linux-Addons**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Linux_Image_creator_MiSTer**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Linux-Addons/PKGBUILD) | MOnSieurFPGA | MiSTerFPGA Linux Addon Utilities. | **Yes** |
[**MiSTer-Devel-Menu**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Distribution_MiSTer**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Devel-Menu/PKGBUILD) | [**theypsilon**](https://github.com/theypsilon) | MiSTerFPGA distribution package. | **Yes** |
[**MiSTer-Devel-Support**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Distribution_MiSTer**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Devel-Support/PKGBUILD) | [**theypsilon**](https://github.com/theypsilon) | MiSTerFPGA distribution package. | **Yes** |
[**MiSTer-Devel-Cheats**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Distribution_MiSTer/Cheats**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Devel-Cheats/PKGBUILD) | [**theypsilon**](https://github.com/theypsilon) | MiSTerFPGA distribution package. | No |
[**MiSTer-Devel-Arcade**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Distribution_MiSTer/_Arcade**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Devel-Arcade/PKGBUILD) | [**theypsilon**](https://github.com/theypsilon) | MiSTerFPGA distribution package. | No |
[**MiSTer-Devel-Computer**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Distribution_MiSTer/_Computer**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Devel-Computer/PKGBUILD) | [**theypsilon**](https://github.com/theypsilon) | MiSTerFPGA distribution package. | No |
[**MiSTer-Devel-Console**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MiSTer-devel/Distribution_MiSTer/_Console**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MiSTer-Devel-Console/PKGBUILD) | [**theypsilon**](https://github.com/theypsilon) | MiSTerFPGA distribution package. | No |
[**MOnSieur-NeoGeoMVS**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MOnSieur-NeoGeoMVS**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MOnSieur-NeoGeoMVS/PKGBUILD) | MOnSieurFPGA | Most recent core build of **NeoGeo MVS** by [**blackwine**](https://github.com/blackwine)/[**furrtek**](https://github.com/furrtek). | No |
[**MOnSieur-ToaplanV1**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MOnSieur-ToaplanV1**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MOnSieur-ToaplanV1/PKGBUILD) | MOnSieurFPGA | Most recent core build of **ToaplanV1** by [**va7deo**](https://github.com/va7deo/zerowing). | No |
[**MOnSieur-Nichibutsu-68000**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**MOnSieur-Nichibutsu-68000**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/MOnSieur-Nichibutsu-68000/PKGBUILD) | MOnSieurFPGA | Most recent core build of **Nichibutsu 68000 (Terra Cresta Based)** by [**va7deo**](https://github.com/va7deo/terracresta). | No |
[**JTFPGA-MiSTer**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/releases/tag/Packages) | [**jotego/jtpremium**](https://github.com/MOnSieurFPGA/MOnSieurFPGA-Packages/blob/main/armv7h/JTFPGA-MiSTer/PKGBUILD) | [**theypsilon**](https://github.com/theypsilon) | Most recent **JTFPGA** cores for MiSTerFPGA by [**jotego**](https://github.com/jotego). | No |

## Licensing

Follow the GPLv3 license attached.
