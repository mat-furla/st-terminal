# st - simple terminal

## Patches

- alpha 
- Ligatures
- sixel 
- scrollback
- Clipboard
- Alpha(Transparency)
- Boxdraw
- w3m
- font2
- right click paste
- st desktop entry
- newterm
- anysize
- anygeometry
- xresources
- sync patch
- live reload

## Dependencies


```sh
# Void Linux
>> xbps-install libXft-devel libX11-devel harfbuzz-devel libXext-devel libXrender-devel libXinerama-devel

# Debian
>> apt install build-essential libxft-dev libharfbuzz-dev 
```

## Install

```sh
>> make
>> sudo make install
```

## Default Keybindings

<pre>
ctrl + shift + c        Copy
ctrl + shift + v        Paste
alt  + comma            Zoom in
alt  + .                Zoom out
alt  + g                Reset Zoom
alt  + s                Increase Transparency
alt  + a                Decrease Transparency
alt  + m                Reset Transparency
copy anything and right click on the terminal ( will paste the copied thing ) 
mod + shift + enter    open a new terminal with same cwd ( current working directory )
alt + k                 scroll down 
alt + j                 scroll up
</pre>

# Credits

- [st-sexy-terminal](https://github.com/siduck76/st) 
