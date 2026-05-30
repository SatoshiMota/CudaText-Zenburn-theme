CudaText Zenburn theme (dark/grey nodepad++ DarkModeDefault)

#### To install, you need to download the files in a zip and drag it to the CudaText window and select the Zenburn theme in the settings.

I was inspired: https://github.com/jkesanen/notepadplusplus-zenburn + https://github.com/jnurmine/Zenburn

#### To fully copy the Notepad++ style, I recommend using the configuration config below (the "pylib__linux" version will probably be different for you):
```
{
  "pylib__linux": "/usr/lib/x86_64-linux-gnu/libpython3.13.so.1.0",
  "ui_theme": "zenburn",
  "ui_theme_syntax": "zenburn",
  "ui_font_name__linux": "Consolas",
  "ui_font_size__linux": 11,
  "font_name__linux": "Consolas",
  "font_size__linux": 11,
  "ui_font_output_name__linux": "Consolas",
  "ui_font_output_size__linux": 11,
  "ui_toolbar_show": true,
  "ui_statusbar_show": true,
  "show_cur_line": true,
  "links_show": true,
  "ui_links_confirm": false
}
```

#### "Consolas" font from windows can be downloaded using the commands (ArchLinux):
```
yay -S ttf-vista-fonts ttf-ms-fonts
```

#### For the command above, you need to install yay (ArchLinux):
```
sudo pacman -S --needed git base-devel
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```

#### During the execution of any of the two sets of commands above, there may be errors, you must first update the mirrors ArchLinux (pacman):
```
sudo pacman -S reflector
sudo reflector --latest 10 --sort rate --save /etc/pacman.d/mirrorlist
sudo pacman -Syy
```

### Screenshots:

### #1

<img width="1307" height="839" alt="image" src="https://github.com/user-attachments/assets/c04fc081-749e-46cf-b7b4-96bb53e94afd" />

### #2

<img width="1313" height="888" alt="image" src="https://github.com/user-attachments/assets/1e3c46eb-78a8-4960-88b5-522408d8b508" />
