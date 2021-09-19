# qBittorrent Dark theme
Derived from: [**jagannatharjun**/qbt-theme/material](https://github.com/jagannatharjun/qbt-theme)

**ICEBERG.qbtheme**<br>
<img src="https://user-images.githubusercontent.com/41102508/133913803-9a05d282-8946-4e34-964a-397b33f44852.png" width=50%>

*[Other qbtheme pictures](https://github.com/maboroshin/qBittorrentDarktheme/issues/9#issuecomment-922406777)*
- Color Themes: [Absinthe](https://github.com/maboroshin/Absinthe.color) (My original color theme) / [Solarized](https://github.com/altercation/solarized#solarized) / [ICEBERG](https://github.com/cocopon/iceberg.vim#readme) / [ayu dark](https://github.com/dempfi/ayu#screenshots) / 

## Usage
Download the ZIP (green button) or individual RAW `.qbtheme` files. Please use Theme function in Options.

## Q&A
Please use [this place](https://github.com/maboroshin/qBittorrentDarktheme/issues/1).

* *[Can I make the title bar to dark?](https://github.com/maboroshin/qBittorrentDarktheme/issues/19)* <br>
* Torrents for testing: [Public Domain Torrents](https://www.publicdomaintorrents.info/)

## Known issue
*[Unknown issue](https://github.com/maboroshin/qBittorrentDarktheme/issues/3)* <br>
*[Colors don't change on Linux](https://github.com/qbittorrent/qBittorrent/issues/13410)*

Probably cannot be changed in the theme file.
- strangeness of check items, In right-click transfer list.

## Compile
*[More info...](https://github.com/maboroshin/qBittorrentDarktheme/wiki/How-to-compile-.qbtheme)*

Rename `src\stylesheet~~.qss` to `src\stylesheet.qss`, Rename `src\config~~.json` to `src\config.json`, and compile `resources.qrc` by Qt rcc. 

* [List of icons](https://github.com/maboroshin/qBittorrentDarktheme/wiki)
* [qBittorrentSVGiconConverter](https://github.com/maboroshin/qBittorrentSVGiconConverter)

## License
[Jagannatharjun says](https://github.com/qbittorrent/qBittorrent/issues/6434#issuecomment-581101910):
> none of the stylesheets belongs to me<br>
>just google search the style name without .qbttheme + github suffix<br>
>I just pack it around for testing the theme support when I was implementing it<br>
>I'll be mentioning this in the repo just that I'm bit busy with college and stuff

He created the .qbttheme for qBittorrent. So I think it's not copyrightable or means public domain. However, `stylesheet.qss` is similar to QDarkStyleSheet. License inheritance may be necessary.

- [qBittorrent: Icons by Code Charm: MIT License](https://github.com/qbittorrent/qBittorrent/blob/master/src/icons/qbt-theme/README.md).
- [(Used Icons, stylesheet.qss) QDarkStyleSheet by Colin Duquesnoy et al: MIT and CCBY4.0 License](https://github.com/ColinDuquesnoy/QDarkStyleSheet).
