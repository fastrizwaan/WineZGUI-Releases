# WineZGUI-Releases

Release of Binary flatpak of [WineZGUI: Wine GUI using Zenity](https://github.com/fastrizwaan/WineZGUI) WineZGUI flatpak uses Wine Stable from Flathub. Download and install WineZGUI flatpak from [WineZGUI-Releases](https://github.com/fastrizwaan/WineZGUI-Releases/releases).  But first the dependencies.

### Dependencies:

Replace `--user` with `--system` to install system-wide.

##### Enable Flathub Repo:

```
flatpak --user remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

##### Install Wine stable from flathub (org.winehq.Wine)

```
flatpak --user -y install org.winehq.Wine/x86_64/stable-21.08
```

##### If flatpak dependencies has trouble installing, try flatpak --repair

```
flatpak repair
flatpak repair --user
flatpak repair --system
```
