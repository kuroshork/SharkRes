# sharkres

Switch your monitor to a stretched resolution (4:3, 16:9 or 16:10) with one hotkey, and switch back with the same key. Built for stretched-res gaming.

- Pick an aspect ratio, then a resolution and refresh rate your monitor supports
- Set your own hotkey (default **Ctrl + Shift + J**)
- Works with several monitors, with an Identify button
- Runs in the system tray
- Twelve themes, dark and light

## Download

Go to the [Releases](../../releases) page and download `sharkres-setup-1.0.0.exe`. Run it, and to remove it later use **Settings → Apps** in Windows.

Windows may show "Windows protected your PC" because the app isn't code-signed. Click **More info → Run anyway**.

## One-time setup: stop black bars

Windows only changes the resolution. Your graphics card has to stretch the picture to fill the screen.

**NVIDIA:** Control Panel → Display → *Adjust desktop size and position*. While in the stretched resolution, set Scaling mode to **Full-screen** and *Perform scaling on* to **GPU**, then Apply.

**AMD:** Adrenalin → Settings → Display → turn on **GPU Scaling** and set Scaling Mode to **Full panel**.

If your display lists no 4:3 modes, create a custom resolution in your GPU control panel first.

## Credits

The font is [Geist Pixel](https://github.com/vercel/geist-font) by Vercel, used under the SIL Open Font License.
