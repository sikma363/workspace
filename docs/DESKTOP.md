Desktop Docs and Deps

---

## Wayland
Display Protocol Compositor Modern di Linux

- [Repo](https://github.com/XQuartz/wayland)
- [Docs](https://wayland.freedesktop.org/)

## Niri
Wayland Compositor Dengan Layout scrollable tilling.

- [Repo](https://github.com/niri-wm/niri)
- [Docs](https://niri-wm.github.io)

> Note
> Niri Berjalan Di Atas Wayland

---
## Dependencies
| Package             | Kegunaan                   |
| ------------------- | -------------------------- |
| `wayland`           | Display protocol           |
| `wayland-protocols` | Extension protokol standar |
| `libxkbcommon`      | Keyboard input handling    |
| `rust / cargo`      | Build Niri dari source     |

## Instalasi
### Wayland
```bash
sudo pacman -S wayland wayland-protocols
```

### Niri
```bash
sudo pacman -S niri
```