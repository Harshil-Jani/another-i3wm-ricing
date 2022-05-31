# i3wm-ricing tutorial 
Alright, I bring a tutorial that will help you to rice your distros with i3wm and few additional softwares to make it more elegant. I personally used Ubuntu 22.04 as my distro. You may use any distro, that's completely upto  you. 
This tutorial will be written in a way that it is suitable for beginners. The ones who knows much about linux will definately get bored so, you may have your coffee brewed meanwhile someone new to this can learn about ricing on their own. 

This is what My Rice looks like ![image](https://user-images.githubusercontent.com/79367883/171294367-84c044fb-9a0e-405c-adf0-95e366eea3ee.png)


### Some personal Notes
- Try not to copy someone's configs. They might use different set of softwares and drivers installed. 
- Writing config step by step on your own, gives more clear insights of things. Also helps in remembering all shortcuts. 
- Once, get into i3 and allow auto config generation. Then keep updating the i3 config from the i3 session itself and keep reloading.
- Have some music streaming and your headphones set. Mashup songs would be better I suggest.
- If nothing works as expected, Try googling. If still problem remains, Open the Issue here. Afterall We help each other for survival.
- Don't love your system so much that it fears you to do experiments on it. 

##  Baby Steps

Obviously, We need some packages to be installed. In my case, I will be discussing each of them and their usage. 

```sh
sudo apt-get install i3
```
This will install the Window Manager. Now, Maybe based on your package manager, You may or may not get dunst, i3lock and i3status. If i3-wm, dunst, i3lock and i3status are not installed automatically, just install them manually.
```sh
sudo apt-get install i3-wm dunst i3lock i3status 
```
Now, Let's get some softwares which I will be using for Sound, Light control, Image setting etc. 
```sh
sudo apt-get install feh nm-applet pactl rofi brightnessctl
```
- feh : Background Wallpaper setter.
- nm-applet : Used for managing the network interfaces and make them quickly accessible.
- pactl : Used for controlling Sound.
- rofi : Beautiful themeing for dmenu which can just give finishing touch to rice.
- brightnessctl : used to control the brightness of the display. 

I will continue later. It's late and I am feeling Sleepy too. GoodNight to those who visits this repo at night. 
