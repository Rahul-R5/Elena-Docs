## Dependencies for cool rice

#### Main
| Dependency | Description | Why/Where is it needed? |
| --- | --- | --- |
| `awesome` (git `master` branch) | Window manager | (explains itself) |
| `rofi` | Window switcher, application launcher and dmenu replacement | (explains itself) |
| `light` | Gets/Sets screen brightness | Brightness keybinds |
| `lm_sensors` | CPU temperature sensor | CPU temperature widgets |
| `acpid` | Daemon for delivering ACPI events | Charger notifications |
| `pulseaudio` | Sound system **(Installed by default on most distros)** | Volume widgets and keybinds |
| `jq` | Parses `json` output | Weather widgets |
| `inotify-tools` |  Monitors filesystem events | Brightness widget updates |
| `fortune-mod` | Displays random quotations (fortune cookies) | Fortune widget |
| `redshift` | Controls screen temperature | Night mode command |
| `mpd` | Server-side application for playing music | Music widgets |
| `mpc` | Minimalist command line interface to MPD | Music widgets |
| `maim` | Takes screenshots (improved `scrot`) | Screenshot keybinds |
| `feh` | Image viewer and wallpaper setter | Screenshot previews, wallpapers |
| `xdotool` | command-line automation tool | Sending keys to `ncmpcpp` |
| [openweathermap](https://openweathermap.org/) key | Provides weather data | Weather widgets |

#### Music 

| Dependency | Description | Why/Where is it needed? |
| --- | --- | --- |
| `mpd` | Music Player Daemon | It serves the music to clients and can be controlled with keybinds |
| `ncmpcpp` | Music client for mpd | Terminal application to manage songs and playlists |
| `mpc` | Music Player Controller | Used to control mpd (Play/Pause) |
| `cava` | Music visualizer | Pretty visualizer |
| `easytag` | Tag editor | Used to edit meta information (tags) and add images to music files |

#### Video

| Dependency | Description | Why/Where is it needed? |
| --- | --- | --- |
| `mpv` | Video player | A minimal UI video player |
| `celluloid` | GTK+ based Video player | Frontend to mpv with more features |

#### Bluetooth Audio

| Dependency | Description | Why/Where is it needed? |
| --- | --- | --- |
| `pulseaudio` | Network capable sound server | Mixes and redirects sound input to output using kernal alsa audio stack |
| `pulseaudio-utils` | Command line tools for pulseaudio | Provides the command tools to interact with pulseaudio (Like pactl) |
| `pavucontrol` | PulseAudio Volume Control | Provides a GTK+ based volume control (mixer) |
| `pulseaudio-module-bluetooth` | Bluetooth module for PulseAudio | Enables pulseaudio to work with bluetooth devices |

#### Games

| Dependency | Description | Why/Where is it needed? |
| --- | --- | --- |
| `Steam` | It's steam dammit | Do you even game? |
| `Proton` | Compatibility layer of windows for linux | Makes a majority of games playable on linux |
| `Lutris` | Open game platform for linux | Game manager which handles install and environment setup for multiple launchers (GOG, Epic, Uplay) |

#### Programming
| Dependency | Description | Why/Where is it needed? |
| --- | --- | --- |
| `neovim` | Text editor | Improved vim with additional extensions |
| `venv` | Virtual environment manager | Create and manage environments for different python stacks |

#### Build Needed
| Application | Description | Why/Where is it needed? | Where to get it |
| --- | --- | --- | --- |
| `awesome` | Window manager | (Self explained) | [awesome-git](https://github.com/awesomeWM/awesome/) or use generated .deb package |
| `picom` | Compositor | Create and manage environments for different python stacks | [ibhagwan-fork](https://github.com/ibhagwan/picom) |
| `kitty` | Terminal emulator | Fast, lightweight GPU based terminal emulator | [kitty](https://sw.kovidgoyal.net/kitty/binary.html) |

#### Optional
| Application | Description | Why/Where is it needed? |
| --- | --- | --- |
| `thunar` | File manager | Customizable file manager |
| `pomodoro` | Task focus timer | Used to increase productivity by working in short bursts of time |
| `neomutt` | Mail client | Terminal based mail client |
| `neofetch` | System info | Displays system information on the terminal |


