<sub>Go back to [Linux Apps Library](../linuxAppsLibrary.md)</sub>

# Essentials

## [Flatseal](https://flathub.org/apps/com.github.tchx84.Flatseal)

GUI to modify Flatpak permissions

**Flatpak (System)**

```bash
flatpak install flathub com.github.tchx84.Flatseal
```

**Flatpak (User)**

```bash
flatpak install --user flathub com.github.tchx84.Flatseal
```

## [Timeshift](https://github.com/linuxmint/timeshift)

Create snapshots of your computer, especially if you use Arch.

**SELinux Compatibility**

If you want to use Timeshift with SELinux, you might want to set SELinux mode from “enforcing” to “permissive” to enable proper function among kernel versions.

**Go to the file `/etc/selinux/config`, scroll down and set SELinux to "permissive."**

```bash
# SELINUX=enforcing
SELINUX=permissive
```

**Debian/Ubuntu**

```bash
sudo apt-get timeshift
```

**Fedora**

```bash
sudo dnf install timeshift
```

**Arch**

```bash
sudo pacman -S timeshift
```
