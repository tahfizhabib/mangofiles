<div align="center">
  <img src="https://github.com/user-attachments/assets/ef221ce2-bd54-4f9c-8523-95f758aee62e" alt="MangoWC Logo" width="120"/>
  
  # Mangofiles
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=F7768E&center=true&vCenter=true&width=435&lines=Mangofiles;MangoWC+Configuration;Wayland+Compositor+Setup" alt="Typing SVG" />
</div>

---

<div align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&duration=2000&pause=1000&color=7DCFFF&center=true&vCenter=true&width=435&lines=About+MangoWC" alt="About MangoWC" />
  
</div>

MangoWC is a modern, high-performance Wayland compositor built on dwl, designed for speed and flexibility. It features tag-based window management, smooth animations with scenefx effects (blur, shadows, rounded corners), and excellent XWayland support. With hot-reload configuration, IPC control, and minimal resource usage, MangoWC delivers a powerful yet lightweight desktop experience.

**Key Features:** Tag-based workflow, Advanced window states, Smooth animations, Hot-reload config, Sway-like scratchpad

**Official Resources:** [Website](https://mangowc.vercel.app/) • [GitHub](https://github.com/DreamMaoMao/mangowc) • [Documentation](https://mangowc.vercel.app/docs) • [Discord](https://discord.gg/CPjbDxesh5)

<div align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&duration=2000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=435&lines=Dependencies" alt="Dependencies" />
  
</div>

<table>
<tr>
<td width="50%" valign="top">

### Core System
| Package | Purpose |
|---------|---------|
| `mangowc` | Wayland compositor |
| `waybar` | Status bar |
| `swaybg` | Wallpaper daemon |
| `vicinae-bin` | Application launcher |
| `foot` | Terminal emulator |

### Applications
| Package | Purpose |
|---------|---------|
| `firefox-developer-edition` | Web browser |
| `vesktop-bin` | Discord client |
| `spotify-launcher` | Music streaming |
| `nvim` | Text editor |
| `ranger` | File manager |
| `zed` | Code editor |
| `vscode` | IDE |

### Utilities
| Package | Purpose |
|---------|---------|
| `btop` | System monitor |
| `fastfetch` | System info |
| `mpv` | Media player |
| `wlogout` | Logout menu |

</td>
<td width="50%" valign="top">

### Screenshot Workflow
| Package | Purpose |
|---------|---------|
| `grim` | Screenshot capture |
| `slurp` | Area selection |
| `satty` | Image annotation |
| `wl-clipboard` | Clipboard manager |

### System Control
| Package | Purpose |
|---------|---------|
| `wireplumber` | Audio management |
| `brightnessctl` | Brightness control |

### Installation

**Core System:**
```bash
yay -S mangowc waybar swaybg vicinae-bin foot
```

**Applications:**
```bash
yay -S firefox-developer-edition vesktop-bin \
       spotify-launcher neovim ranger zed-bin code
```

**Utilities & Tools:**
```bash
yay -S btop fastfetch mpv wlogout \
       wireplumber brightnessctl \
       grim slurp satty wl-clipboard
```

</td>
</tr>
</table>

<div align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&duration=2000&pause=1000&color=9ECE6A&center=true&vCenter=true&width=435&lines=Keybindings" alt="Keybindings" />
  
</div>

<table>
<tr>
<td width="50%" valign="top">

### System Control
| Keybind | Action |
|---------|--------|
| `Super + R` | Reload configuration |
| `Super + Shift + E` | Quit compositor |
| `Super + Q` | Close window |
| `Super + Shift + Q` | Logout menu |

### Launch Applications
| Keybind | Action |
|---------|--------|
| `Super + D` | Application launcher |
| `Super + Return` | Terminal |
| `Super + B` | Firefox |
| `Super + E` | File manager |
| `Super + N` | Neovim |
| `Super + Z` | Zed editor |
| `Super + C` | VSCode |

### Window Focus
| Keybind | Action |
|---------|--------|
| `Super + H/J/K/L` | Focus direction (Vim) |
| `Alt + Arrow Keys` | Focus direction (Arrows) |
| `Super + Tab` | Focus next window |
| `Super + Shift + Tab` | Focus previous window |

### Window Movement
| Keybind | Action |
|---------|--------|
| `Super + Shift + H/J/K/L` | Move window (Vim) |
| `Super + Shift + Arrow Keys` | Move window (Arrows) |
| `Super + Shift + Return` | Swap with master |

### Window States
| Keybind | Action |
|---------|--------|
| `Super + F` | Toggle fullscreen |
| `Super + M` | Toggle maximize |
| `Super + Space` | Toggle floating |
| `Super + G` | Toggle global |
| `Super + Grave` | Toggle scratchpad |
| `Super + I` | Minimize window |
| `Super + Shift + I` | Restore minimized |
| `Alt + Tab` | Overview mode |

</td>
<td width="50%" valign="top">

### Layout Management
| Keybind | Action |
|---------|--------|
| `Super + T` | Switch layout |
| `Super + Comma` | Increase master count |
| `Super + Period` | Decrease master count |
| `Super + Ctrl + H/L` | Adjust master size |
| `Super + Equal` | Increase gaps |
| `Super + Minus` | Decrease gaps |
| `Super + Shift + G` | Toggle gaps |

### Workspace Navigation
| Keybind | Action |
|---------|--------|
| `Super + 1-9` | Switch to workspace |
| `Super + [` | Previous workspace |
| `Super + ]` | Next workspace |
| `Ctrl + [` | Previous workspace (occupied) |
| `Ctrl + ]` | Next workspace (occupied) |

### Move Window to Workspace
| Keybind | Action |
|---------|--------|
| `Super + Shift + 1-9` | Move window to workspace |
| `Super + Ctrl + [` | Move to previous workspace |
| `Super + Ctrl + ]` | Move to next workspace |

### Monitor Management
| Keybind | Action |
|---------|--------|
| `Super + Alt + H/L` | Focus monitor |
| `Super + Alt + Shift + H/L` | Move window to monitor |

### Screenshots
| Keybind | Action |
|---------|--------|
| `Super + S` | Area selection → Edit → Save & Copy |
| `Print` | Area selection → Clipboard |
| `Shift + Print` | Fullscreen → Clipboard |
| `Super + Print` | Fullscreen → File |
| `Ctrl + Print` | Area selection → File |

### Media Controls
| Keybind | Action |
|---------|--------|
| `XF86AudioRaiseVolume` | Volume up |
| `XF86AudioLowerVolume` | Volume down |
| `XF86AudioMute` | Toggle mute |
| `XF86MonBrightnessUp` | Brightness up |
| `XF86MonBrightnessDown` | Brightness down |

### Mouse Controls
| Action | Function |
|--------|----------|
| `Super + Left Click` | Move window |
| `Super + Right Click` | Resize window |
| `Super + Scroll` | Cycle workspaces |

### Floating Resize
| Keybind | Action |
|---------|--------|
| `Super + Alt + H/J/K/L` | Resize window (Vim) |
| `Super + Alt + Arrow Keys` | Resize window (Arrows) |
| `Super + Alt + C` | Center floating window |

</td>
</tr>
</table>

<div align="center">
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&duration=2000&pause=1000&color=BB9AF7&center=true&vCenter=true&width=435&lines=Previews" alt="Previews" />
  
</div>


![Preview 1](https://github.com/user-attachments/assets/a606a5fb-e33e-40ca-898b-9a8c3e50c32c)

![Preview 2](https://github.com/user-attachments/assets/71ca125d-9dcb-4fd8-b1df-1f9a990e89d7)

