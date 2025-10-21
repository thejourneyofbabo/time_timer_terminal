# Time Timer

A circular countdown timer for the terminal, inspired by the Time Timer visual timer.

## Features

- Visual circular countdown display
- Flexible time format support (seconds, minutes, hours)
- **Pause/Resume functionality** - Press SPACE to pause or resume the timer
- Responsive layout that adapts to terminal size
- Terminal bell notification when time is up

## Usage

```bash
./timetimer 15m      # 15 minutes
./timetimer 30s      # 30 seconds
./timetimer 1h       # 1 hour
./timetimer 1h30m    # 1 hour 30 minutes
```

### Controls

- **SPACE** - Pause/Resume the timer
- **Ctrl+C** - Cancel the timer

## Installation

```bash
chmod +x timetimer
sudo cp timetimer /usr/local/bin/
```

Then use it from anywhere:

```bash
timetimer 15m
```

## Requirements

- Python 3.x
- Linux/Unix terminal (uses `termios` for keyboard input)
