<p align="center">
<a href="http://retroflag.com/GPi-CASE.html"><img style="text-align: center" width="500px" src="https://user-images.githubusercontent.com/260/59818886-aeddf200-92f3-11e9-93f2-030c25380aea.jpeg" /></a>
</p>

<br>


This repo collects a few things that are helpful for setting up your GPI case from RetroFlag. If you're nostalgic and have played with emulation for a while, this is a great project.

## Resources
* [ETAPrime](https://youtube.com/etaprime)'s [overview](https://www.youtube.com/watch?v=X473iXjF3iU&t=2s)  - RetroFlag Gpi Case The Best Raspberry Pi GameBoy?
* [Subreddit](https://reddit.com/r/retroflag_gpi)
* [Retropie](https://retropie.org.uk)
* [sselph scraper](https://github.com/sselph/scraper) - fastest scraper to fetch metadata for your roms.


## Customizations

* [RetroPie Splash Screen](https://github.com/RetroPie/RetroPie-Setup/wiki/splashscreen)
* [Splash Screens](https://github.com/HerbFargus/retropie-splashscreens-extra)
* [Add custom launch images](https://github.com/RetroPie/RetroPie-Setup/wiki/runcommand#adding-custom-launching-images)
* [Launch images](https://github.com/ehettervik/es-runcommand-splash)
* [WiFI & Bluetooth Toggle](https://retropie.org.uk/forum/topic/15839/toggling-wifi-and-bluetooth-on-and-off-inside-retropie-menus)
* [Stereo/Mono Toggle](https://www.reddit.com/r/retroflag_gpi/comments/c176wg/sound_fix_for_gpi_mono_sound_link_inside/ercmmxy/)

## Suggested Themes

Here's some themes that work well on a small 4:3 screen

## GBZ35
<img src="https://user-images.githubusercontent.com/260/59818966-0e3c0200-92f4-11e9-9a2a-fa91396733fc.png" width="300px"> <img src="https://user-images.githubusercontent.com/260/59818967-1005c580-92f4-11e9-9bd9-29b9bb11c156.png" width="300px">

## TFT

<img src="https://user-images.githubusercontent.com/260/59819110-8efafe00-92f4-11e9-85dc-ae7e963c6de0.png" width="300px"> <img src="https://user-images.githubusercontent.com/260/59819116-915d5800-92f4-11e9-9092-14dd875dc9a5.png" width="300px">


## Comic Book 4:3
<img src="https://user-images.githubusercontent.com/260/59818995-33307500-92f4-11e9-899b-4a6fdb9254ef.png" width="300px"> <img src="https://user-images.githubusercontent.com/260/59819002-375c9280-92f4-11e9-99a3-52b6c31e8733.png" width="300px">


## Advanced RetroPie/Raspberry Pi Customizations

Here's some tricks of the trade to make your GPI look more official.

### Hide console output on boot

Edit `/boot/cmdline.txt` and set `console=tty3`

### Hide Raspbery Pi Logo on boot

Edit `/boot/cmdline.txt` and add `logo.nologo`

### Hide EmulationStation Splash screen

This disables EmulationStation's splash screen so that your custom splash screen shows until everything is completely booted up.

Edit `/opt/retropie/configs/all/autostart.sh` to be

    emulationstation --no-splash #auto
