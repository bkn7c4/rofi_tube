# rofi_tube

<p align="center">
  <!-- <img src="https://img.shields.io/badge/Maintained%3F-Yes-blueviolet?style=flat-square"> -->
  <img src="https://img.shields.io/github/license/broken7c4/rofi_tube?style=flat-square">
  <img src="https://img.shields.io/github/stars/broken7c4/rofi_tube?color=red&style=flat-square">
  <img src="https://img.shields.io/github/forks/broken7c4/rofi_tube?style=flat-square">
  <img src="https://img.shields.io/github/issues/broken7c4/rofi_tube?style=flat-square">
</p>

This project is bash script to play videos from YouTube using rofi and mpv.

* [Rofi](https://github.com/davatorium/rofi) is a window switcher, Application launcher and dmenu replacement

* [mpv](https://github.com/mpv-player/mpv) is a free (as in freedom) media player for the command line. It supports a wide variety of media file formats, audio and video codecs, and subtitle types.


inspired by 'rofi_mpvtube' from [elenapan@github](https://github.com/elenapan/dotfiles) I added the possibility to save all videos of a channel as a playlist. So you can navigate in playlist with rofi and select/search a video to play

# install
copy `rofi_tube` to a folder in your `$PATH`

Ex:
```
cp rofi_tube ~/.bin
```


# files
config files in `~/.config/rofi_tube`.
* `channels.list` (file): list to save all you favorite channels
* `playlists` (dir): save a playlist with all videos from a channel (urls, titles and some other info)

# usage

```
rofi_tube 
```
Without params this will show all channels in you playlist. You can grab one and mpv will play all videos from this channel. But if channel has a lot of videos you will notice that it takes a lot of time to load and play mpv. 
In this case you can save a playlist with all videos. You will wait only fist time to download. After you will seach localy

```
rofi_tube --playlist
```
open rofi menu to select a channel. After will create a playlist with ak videos of this channel. Now you can search for a video or play a set of videos

```
rofi_tube --random
```
if you want to play all videos form a channel in random mode

# Contact
if you have any problem or sugestion open a [issue](https://github.com/broken7c4/rofi_tube/issues/new).

sorry for my english. It's a working in progress! LoL

=)
