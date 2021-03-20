# i3wm configuration files
i3wm configurations that I use, I will update it when I need more elements.

I use laptop and and use fn key to make some operations; such as brightness, volume control and play-pause-next-previous control. So I used XF86 keys to make it work. If you don't need those(such as if you use a desktop pc), you can get rid of them easily, as I commented every code to be more understandable for beginners, like me.

Folder contains a config file, which is the primary config file for the i3. and there's a i3status folder there; and that is for the i3 taskbar, which contains the config file for the i3status(the taskbar). If you put the i3 folder inside the .config folder on your PC, it will be operative. That's all you need to do. **But I think you should look at it, and write it yourself in order to learn how to, properly**.

## External programs and such

If I remember correctly, I used:
* [lux](https://github.com/Lux-core/lux/releases) - for controlling brightness of monitor
* [AwesomeFont 5 Free](https://fontawesome.com/) - for icons on i3status bar
* [trayer](https://linuxx.info/trayer/) - to show trayer on most right side of status bar(probably comes with i3 package, not sure bout' dat)
* [nitrogen](https://wiki.archlinux.org/index.php/Nitrogen) - to draw a wallpaper on startup(not sure nitrogen's code is correct, beware)
* [Fira Mono](https://fonts.google.com/specimen/Fira+Mono?preview.text_type=custom) - Fira font family comes default with pop!OS, and I love it. You can download it from web as I used it if you want to
* [rofi](https://wiki.archlinux.org/index.php/Rofi) - to use as a execute menu. Its like a dmenu but I like it more, and I couldn't managed to get dmenu worked, so yeah I used it as a main app
