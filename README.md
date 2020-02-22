# qBittorrent Dark theme

Derived from: [**jagannatharjun**/qbt-theme/material](https://github.com/jagannatharjun/qbt-theme)

## Usage
Download the ZIP (green button) or individual RAW `.qbtheme` files. Please use Theme function in Options.

## Known issue
Probably cannot be changed in the theme file.
- Text color fixed to black. (Supported with background gray)
- Link color fixed to blue.
- Progress bar color fixed.
- Icon layout, strangeness of check items、In right-click transfer list.

## Compile
rename `src\~stylesheet.qss`  to `src\stylesheet.qss`, and compile `resources.qrc` by qt rcc.

## License
[Jagannatharjun says](https://github.com/qbittorrent/qBittorrent/issues/6434#issuecomment-581101910):
> none of the stylesheets belongs to me<br>
>just google search the style name without .qbttheme + github suffix<br>
>I just pack it around for testing the theme support when I was implementing it<br>
>I'll be mentioning this in the repo just that I'm bit busy with college and stuff

He created the .qbttheme for qBittorrent. So I think it's not copyrightable or means public domain.

- [qBittorrent: Icon by Code Charm: MIT License](https://github.com/qbittorrent/qBittorrent/blob/master/src/icons/qbt-theme/README.md).
- [QDarkStyleSheet by Colin Duquesnoy et al: MIT and CCBY4.0 License](https://github.com/ColinDuquesnoy/QDarkStyleSheet).
