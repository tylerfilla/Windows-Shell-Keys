# Windows Shell Keys

These are some registry tweaks that I have created to boost my own productivity as a student/hobbyist/amateur software developer who occasionally works on a Windows 10 system. They add context menu entries to Windows Explorer for launching various types of CLI shells that I use (like WSL and Cygwin).

They come in two variants:
  - Background tweaks
  - Foreground tweaks

### Background entries

These keys are in the _Background_ folder. They add entries to the context menu where you right click on the empty background of Windows Explorer. This includes the explorer.exe process running on the default interactive desktop, so these entries will appear when you right click the empty space around desktop icons.

### Foreground entries

These keys are in the _Foreground_ folder. They add entries to the context menu where you right click on a file in Windows Explorer. This covers icons on the desktop, too.

## Hold down shift (or not)

These registry files follow my personal preference. It is my preference to not clutter up the context menus, so all of these tweaks require holding down the shift key while right clicking. You can make one of the entries persistent (visible without holding shift) by removing the ```"Extended"=""``` line from the corresponding file.

## Disclaimer

No lifeguard on duty!

This code comes with no guarantee that it won't break things (or that it even works, for that matter!). The Windows registry is an integral part of the OS, and myriad horror stories online indicate that it's easy to screw something up. Still, I encourage playing around with it, but I suggest not doing so on your daily driver (e.g. do it in a virtual machine).

It may seem like a spooky place 🎃👻👀, but it doesn't have to be. Just be careful!

## License

Technically, I'm not licensing this stuff. In fact, I dedicate this repository to the public domain via [the aptly-named Unlicense](https://github.com/tylerfilla/Windows-Shell-Keys/blob/master/LICENSE).
