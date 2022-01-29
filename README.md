<p align="center">
    <img src="https://brave.com/wp-content/uploads/2019/03/brave-logo.png" alt="Brave logo" width=110 height=128>

<h2 align="center">Brave AppImage</h2>

  <p align="center">
    Brave Stable, Beta and Nightly (unofficial) AppImages by GitHub Actions Continuous Integration
    <br>
    <a href="https://github.com/srevinsaju/Brave-Appimage/issues/new">Report bug</a>
    ·
    <a href="https://github.com/srevinsaju/Brave-Appimage/issues/new">Request feature</a>
    ·
    <a href="https://github.com/srevinsaju/Brave-Appimage/releases/latest">Download AppImage</a>
  </p>
</p>

## Get Started

Download the latest release from

| Stable | Nightly | Dev |
| ------- | --------| ------ | 
| [Download](https://github.com/srevinsaju/Brave-AppImage/releases/tag/stable) | [Download](https://github.com/srevinsaju/Brave-AppImage/releases/tag/nightly) | [Download](https://github.com/srevinsaju/Brave-AppImage/releases/tag/dev)

or, use [`zap`](https://github.com/srevinsaju/zap), the command line AppImage package manager:
```bash
zap install --github --from=srevinsaju/Brave-AppImage brave-appimage
```

### Executing
#### File Manager
Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
the `+x` permissisions. So, right click > Properties > Allow Execution

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
"Brave" is licensed under the [Mozilla Public License 2.0  (MPL 2.0)](https://en.wikipedia.org/wiki/Mozilla_Public_License)
The official source code of the Brave is available at links provided 
* https://github.com/brave/brave-browser

"GitHub Continuous Integration" is licensed under the MIT License. 
