# polybar-wakatime

A simple python script to integrate wakatime into your polybar.

## Screenshots

![](https://raw.githubusercontent.com/KekOnTheWorld/polybar-wakatime/main/screenshots/screenshot_1.png)

## Usage

1. Add this to `polybar/modules.ini`:

```ini
[module/wakatime]
type = custom/script
exec = <path to polybar-wakatime.py>
tail = true
interval = 1.0
```

2. Update your `polybar/config.ini`

3. Restart polybar
