# CAMotics Flatpak

This is an attempt to package [CAMotics](https://camotics.org/) into a [Flatpak](https://flatpak.org/).

## Building and running

```
flatpak install flathub org.kde.Platform//5.15 org.kde.Sdk//5.15
flatpak-builder --user --install build-dir org.camotics.CAMotics.yml
flatpak run org.camotics.CAMotics
```
