<p align="center">
    <a href="https://brave.com/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/Brave_lion_icon.svg" alt="Brave logo" width=110 height=128>
    </a>
<h2 align="center">Brave AppImage</h2>

  <p align="center">
    Brave Stable, Beta, Dev and Nightly (unofficial) AppImages by GitHub Actions Continuous Integration
    <br>
    <a href="https://github.com/srevinsaju/Brave-Appimage/issues/new">Report bug</a>
    ·
    <a href="https://github.com/srevinsaju/Brave-Appimage/issues/new">Request feature</a>
    ·
    <a href="https://github.com/srevinsaju/Brave-Appimage/releases/latest">Download AppImage</a>
  </p>
</p>

## Get Started

Download releases from

<p align="center">
    <a href="https://github.com/srevinsaju/Brave-AppImage/releases/tag/stable">
        <img alt="Latest Stable" src="https://img.shields.io/static/v1?label=latest&message=stable&color=orange&logo=brave&logoColor=orange&style=for-the-badge">
    </a>
    <a href="https://github.com/srevinsaju/Brave-AppImage/releases/tag/beta">
        <img alt="Latest Beta" src="https://img.shields.io/static/v1?label=latest&message=beta&color=blue&logo=brave&logoColor=blue&style=for-the-badge">
    </a>
    <a href="https://github.com/srevinsaju/Brave-AppImage/releases/tag/dev">
        <img alt="Latest Dev" src="https://img.shields.io/static/v1?label=latest&message=dev&color=blue&logo=brave&logoColor=blue&style=for-the-badge">
    </a>
    <a href="https://github.com/srevinsaju/Brave-AppImage/releases/tag/nightly">
        <img alt="Latest Nightly" src="https://img.shields.io/static/v1?label=latest&message=nightly&color=8250DF&logo=brave&logoColor=8250DF&style=for-the-badge">
    </a>
</p>
<p align="center">
    <a href="https://github.com/srevinsaju/Brave-AppImage/releases/latest/">
        <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/srevinsaju/Brave-Appimage?color=21BC29&label=stable&logo=brave&logoColor=21BC29&style=for-the-badge">
    </a>
    <a href="https://github.com/srevinsaju/Brave-AppImage/releases/">
        <img alt="GitHub tag (latest SemVer pre-release)" src="https://img.shields.io/github/v/tag/srevinsaju/Brave-Appimage?color=yellow&include_prereleases&label=pre-release&logo=brave&logoColor=yellow&style=for-the-badge">
    </a>
</p>

or, use [`zap`](https://github.com/srevinsaju/zap), the command line AppImage package manager:

```bash
zap install --github --from=srevinsaju/Brave-AppImage brave-appimage
```

### Executing

#### File Manager

Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
> the `+x` permissisions. So, right click > Properties > Allow Execution

#### Terminal

```bash
./Brave-*.AppImage
```

```bash
chmod +x Brave-*.AppImage
./Brave-*.AppImage
```

In case, if FUSE support libraries are not installed on the host system, it is
still possible to run the AppImage

```bash
./Brave-*.AppImage --appimage-extract
cd squashfs-root
./AppRun
```

## Note

> This is not an official AppImage. The developer of this continuous integration
> take no responsibility over anything which happen using this AppImage. USE IT ONLY
> ON YOUR OWN RISK. You are "free" to fork this repository, analyze the code and
> build your own AppImage under the MIT License and MPL 2.0 License.

## License

"Brave" is licensed under the [Mozilla Public License 2.0 (MPL 2.0)](https://en.wikipedia.org/wiki/Mozilla_Public_License)
The official source code of the Brave is available at links provided

- https://github.com/brave/brave-browser

"GitHub Continuous Integration" is licensed under the MIT License.
