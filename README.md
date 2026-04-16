# Lexi Dashboard

This README was updated by an LLM friend.

A customized EWW dashboard based on the original
[`adi1090x/widgets`](https://github.com/adi1090x/widgets) dashboard.

The dashboard was reworked into a darker black and pink setup with a cleaner
layout, larger Hacker News text, a new art widget, and a redesigned system
metrics panel.

![Dashboard preview](previews/dashboard.png)

## What Changed

- Replaced the original weather/quote area with an art-of-the-day widget.
- Added a Hacker News widget with top stories, ranks, article links, and refresh.
- Removed the concept/word widget.
- Moved Hacker News into the left column.
- Reworked the system widget into four metric cards: CPU, RAM, brightness, and battery.
- Enlarged the Hacker News text for readability.
- Enlarged and updated the power icons.
- Cleaned unused files, old weather scripts, old concept scripts, mail scripts, app-grid icons, and cache files.
- Added a dashboard-specific README in `eww/dashboard/README.md`.

## Visual Style

- Black transparent widget backgrounds.
- Pink/magenta accent color, mostly `#e93f77` and `#ff78a6`.
- Pale pink and white text.
- Thin pink borders.
- Rounded glass-style cards.
- Layout tuned for a Hyprland laptop setup.

## Included Widgets

- Profile
- Clock with uptime
- Music player
- Art of the day
- Hacker News
- System metrics
- Quick links
- Power controls
- Folders and disk free space

## Installation

Install Elkowar's Wacky Widgets:

```bash
https://elkowar.github.io/eww/
```

Clone this repo:

```bash
git clone https://github.com/jalexine/lexi-dashboard.git
```

Create the EWW config directory:

```bash
mkdir -p ~/.config/eww
```

Copy the EWW configs:

```bash
cp -a lexi-dashboard/eww/* ~/.config/eww/
```

Install the fonts from the `fonts` directory, then launch the dashboard:

```bash
~/.config/eww/dashboard/launch_dashboard
```

## Notes

- The dashboard display name is set to `YOUR NAME` in `eww/dashboard/eww.yuck`.
- The dashboard expects to live at `~/.config/eww/dashboard`.
- Some scripts expect common desktop tools such as `eww`, `firefox`, `brave`,
  `nautilus`, `mpc`, `brightnessctl`, and `systemctl`.
- Monitor names and geometry may need adjustment on another machine.
