### Chaotic-AUR package list

This is the right place to submit package requests, bug reports, or outdated packages of [Chaotic-AUR](https://aur.chaotic.cx). Please feel free to use issues! 📜

![Chaotic-AUR](https://avatars.githubusercontent.com/u/66071775?s=400&u=99bc0536e7e77fe3e58839996600848f2d930ed5&v=4)

#### Examples of packages we have already built:

- [Linux-tkg kernels](https://github.com/Frogging-Family/linux-tkg) (BMQ, CFS,LTO, PDS, TT + their generic_v3 variations)
- Other popular kernel variations such as [Mainline](https://aur.archlinux.org/packages/linux-mainline)/-[anbox](https://aur.archlinux.org/packages/linux-mainline-anbox), [Xanmod-{tt,anbox,rt,lts}](https://aur.archlinux.org/packages?O=0&SeB=nd&K=xanmod), [Vfio](https://aur.archlinux.org/packages/linux-vfio)/-[lts](https://aur.archlinux.org/packages/linux-vfio-lts), [Next-git](https://aur.archlinux.org/packages/linux-next-git), [Cachyos-BORE](https://aur.archlinux.org/packages/linux-cachyos-bore) or [TT](https://aur.archlinux.org/packages/linux-tt)
- A quite complete [KDE stack build from master branch](https://invent.kde.org/explore/groups?sort=name_asc)
- Most of the existing emulators & gaming utilities like [Yuzu](https://yuzu-emu.org/), [RPCS3](https://github.com/RPCS3/rpcs3) or {[Proton](https://github.com/GloriousEggroll/proton-ge-custom),[Wine](https://github.com/GloriousEggroll/wine-ge-custom)}-GE-Custom
- A lot of browsers like [Firedragon](https://github.com/dr460nf1r3/firedragon-browser), [Ungoogled Chromium](https://github.com/Eloston/ungoogled-chromium), [Firefox-wayland-hg](https://aur.archlinux.org/packages/firefox-wayland-hg), [Icecat](http://www.gnu.org/software/gnuzilla/) or the [Tor Browser](https://www.torproject.org/projects/torbrowser.html)
- .. a lot more. Check out the [package lists](https://github.com/chaotic-aur/packages/find/main) to find out what exactly gets built and when! 🕵️‍♀️

#### Banished and rejected packages 📑

This is a list of packages that we will reject for good reasons:

- **snapd**: We didn't know how to help our users with it since it breaks *A LOT*. We recommend using native packages or [FlatPak](https://wiki.archlinux.org/title/Flatpak) instead. Also, [there are a lot of other reasons to not use Snaps](https://old.reddit.com/r/linuxmemes/comments/ppyz0g/damn_you_ubuntu/hd7jg1p/).

- **lib32-x265**:	There is absolutely no use case in which a 32-bit application (Linux or Windows) would want to ENCODE HEVC. We recommend disabling x265 for the packages depending on it (usually `FFmpeg` or `GStreamer`).

- **gst-plugins-{ugly,bad} (and lib32)**: These need too frequent rebuilds which can't be dealt with as we don't control the packages pkgrel. Ultimately this would result in a bad user experience - dependency requests however are welcome!

- **ffmpeg-{full,headless} (and lib32)**:  These need too frequent rebuilds which can't be dealt with as we don't control the packages pkgrel. Ultimately this would result in a bad user experience - dependency requests however are welcome!

- **mpv-amd, ffmpeg-amd**: This is just MPV/FFMPEG without CUDA and NVENC to achieve shorter build times without actual end-user benefit.

- **unreal-engine (and -git)**: Some mirrors don't have sufficient storage space.

- **python2**: Has been EOL for a couple of years, and was [removed from Arch repositories](https://archlinux.org/news/removing-python2-from-the-repositories/). Requests for packages that depend on it in any way will be rejected (see [#1958](https://github.com/chaotic-aur/packages/issues/1958)).



#### Banned due to licensing issues 🛑

- **aseprite{-git}**: Redistribution is explicitly prohibited in its [FAQ](https://www.aseprite.org/faq/#can-i-redistribute-aseprite).

- **multimc-git**: Redistribution of custom binaries that include their API keys and trademarked assets is [explicitly prohibited](https://multimc.org/#Branding).

- **tlauncher**: Legal gray area, as it potentially allows playing Minecraft in a reduced capacity without license.

- **feishu**: Unauthorized redistribution of their applications is explicitly prohibited per [ToS](https://www.feishu.cn/en/terms).
