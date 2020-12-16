<h1 align="center">
	<img src="https://brave.com/wp-content/uploads/2019/03/brave-logo.png" alt="Brave" height=200 width=200 align="middle">
	Brave AppImage
</h1>

Brave Stable, Beta and Nightly (unofficial) AppImages by GitHub Actions Continuous Integration

## Get Started

Download the latest release from

![Brave Channels](https://brave.com/wp-content/uploads/2019/03/release-channel-icons.png)
| Stable | Beta | Nightly | Dev |
| ------- | --------- | --------| ------ | 
| [Download](/srevinsaju/Brave-AppImage/releases/tag/stable) | [Download](/srevinsaju/Brave-AppImage/releases/tag/beta) | [Download](/srevinsaju/Brave-AppImage/releases/tag/nightly) | [Download](/srevinsaju/Brave-AppImage/releases/tag/dev)


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
* https://github.com/brave/brave-browse

"GitHub Continuous Integration" is licensed under the MIT License. 
