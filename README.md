# Awesome mpv with stars

A curated list of [awesome](https://github.com/topics/awesome) mpv resources.

# Table of contents

* [Media Player](#media-player)
  * [Cross-platform](#cross-platform)
  * [Windows](#windows)
  * [MacOS](#macos)
  * [Linux](#linux)
  * [Android](#android)
* [Installation/Download](#installationdownload)
* [Documentation](#documentation)
* [Support](#support)
* [User Script](#user-script)
  * [Menu](#menu)
  * [Playback](#playback)
  * [File](#file)
  * [On Screen Controller](#on-screen-controller)
  * [Input](#input)
  * [Subtitle](#subtitle)
  * [Learning](#learning)
  * [Music](#music)
  * [Streaming](#streaming)
  * [Video](#video)
  * [Audio](#audio)
  * [Image](#image)
  * [Video Editing](#video-editing)
  * [Social](#social)
  * [Configuration](#configuration)
  * [Library](#library)
  * [Other](#other)
* [Music Player](#music-player)
* [Media Center](#media-center)
* [Streaming Tools](#streaming-tools)
* [User Configuration](#user-configuration)
* [Social Tools](#social-tools)
* [Video Conversion](#video-conversion)
* [Shaders](#shaders)
* [VapourSynth Scripts](#vapoursynth-scripts)
* [Video Editing Tools](#video-editing-tools)
* [Image Viewer](#image-viewer)
* [Launcher](#launcher)
* [Remote Control](#remote-control)
* [Building](#building)
* [Library](#library-1)
* [Other Tools](#other-tools)

# Media Player

## Cross-platform

* [SMPlayer](https://github.com/smplayer-dev/smplayer) ⭐ 1,040 | 🐛 80 | 🌐 C++ | 📅 2026-08-11 - Based on C++/QT.
* [ImPlay](https://github.com/tsl0922/ImPlay) ⭐ 782 | 🐛 24 | 🌐 C++ | 📅 2026-02-23 - Based on C++/imgui.
* [MoonPlayer](https://github.com/coslyk/moonplayer) ⭐ 686 | 🐛 43 | 🌐 C++ | 📅 2024-09-03 - Based on C++/QT/QML.
* [Baka-MPlayer](https://github.com/u8sand/Baka-MPlayer) ⭐ 468 | 🐛 94 | 🌐 C++ | 📅 2026-06-21 - Unmaintained, based on C++/QT.
* [movie-monad](https://github.com/lettier/movie-monad) ⭐ 435 | 🐛 11 | 🌐 Haskell | 📅 2020-03-07 - Unmaintained, based on Haskell/GTK.
* [OvoPlayer](https://github.com/varianus/ovoplayer) ⭐ 65 | 🐛 2 | 🌐 Pascal | 📅 2026-08-25 - Unmaintained, based on Pascal.
* [mpv](https://mpv.io) - Based on C/Lua.

## Windows

* [mpv.net](https://github.com/mpvnet-player/mpv.net) ⭐ 5,346 | 🐛 156 | 🌐 C# | 📅 2026-02-09 - Based on C#/WinForms/WPF.
* [MPV-EASY Player](https://github.com/422658476/MPV-EASY-Player) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12
* [mpc-qt](https://github.com/mpc-qt/mpc-qt) ⭐ 1,068 | 🐛 121 | 🌐 C++ | 📅 2026-08-25 - Based on C++/QT.
* [mpv-hero](https://github.com/stax76/mpv-hero) ⭐ 136 | 🐛 8 | 🌐 Lua | 📅 2025-11-26 - mpv extended with GUI scripts and GUI tools.
* [MMP: Minimalist Media Player](https://github.com/BazzaCuda/MinimalistMediaPlayerX) ⭐ 55 | 🐛 3 | 🌐 Pascal | 📅 2026-07-31 - Player/Manager/Editor for audio and video, and Viewer/Manager for images/thumbnails; maintained, based on 64-bit Delphi Pascal. Official [wiki](https://minimalistmediaplayer.com).

## MacOS

* [IINA](https://iina.io) - Based on Swift/Cocoa.

## Linux

* [Kawaii Player](https://github.com/kanishka-linux/kawaii-player) ⭐ 710 | 🐛 17 | 🌐 Python | 📅 2026-08-20 - Player/Library/Server, based on Python/QT.
* [xt7-player-mpv](https://github.com/kokoko3k/xt7-player-mpv) ⭐ 105 | 🐛 2 | 🌐 Lua | 📅 2026-06-12 - Based on Gambas/QT.
* [Deepin Movie](https://github.com/linuxdeepin/deepin-movie-reborn) ⭐ 88 | 🐛 10 | 🌐 C++ | 📅 2026-08-25 - Unmaintained, based on C++/QT.
* [mpvz](https://github.com/Zren/mpvz) ⭐ 58 | 🐛 11 | 🌐 QML | 📅 2022-02-14 - Based on C++/QT/QML.
* [Celluloid](https://celluloid-player.github.io) - Based on C/GTK.
* [Haruna](https://invent.kde.org/multimedia/haruna) - Based on C++/QT/QML.
* [bomi player](https://bomi-player.github.io) - Unmaintained, based on C++/QT.

## Android

* [android](https://github.com/mpv-android/mpv-android) ⭐ 3,493 | 🐛 164 | 🌐 Kotlin | 📅 2026-08-26 - Player for Android, based on Kotlin.
* [Kt](https://github.com/abdallahmehiz/mpvKt) ⚠️ Archived - Player for Android, based on Kotlin.

# Installation/Download

* [shinchiro GitHub](https://github.com/shinchiro/mpv-winbuild-cmake) ⭐ 1,721 | 🐛 59 | 🌐 CMake | 📅 2026-08-14 - Daily Windows builds of mpv and libmpv. This is the most popular choice on Windows.
* [zhongfly](https://github.com/zhongfly/mpv-winbuild) ⭐ 879 | 🐛 0 | 🌐 Shell | 📅 2026-08-26 - Windows builds of mpv and libmpv. This choice is very similar to `shinchiro GitHub`, so it's also a recommendation.
* [mpsm](https://github.com/mpv-easy/mpv-easy/tree/main/mpv-mpsm) ⭐ 137 | 🐛 75 | 🌐 TypeScript | 📅 2026-08-20 - mpsm is a mpv script manager, you can install scripts provided by [mpsm-scripts](https://github.com/mpv-easy/mpsm-scripts) ⭐ 22 | 🐛 0 | 🌐 Lua | 📅 2026-07-22, or install any script with added [meta info](https://github.com/mpv-easy/mpsm-scripts?tab=readme-ov-file#meta-info) ⭐ 22 | 🐛 0 | 🌐 Lua | 📅 2026-07-22 via url.
* [mitzsch](https://github.com/mitzsch/mpv-winbuild) ⭐ 29 | 🐛 0 | 🌐 Shell | 📅 2026-08-08 - Windows builds of mpv and libmpv.
* [Andarwinux](https://github.com/Andarwinux/mpv-winbuild) ⭐ 23 | 🐛 3 | 🌐 Shell | 📅 2026-08-24 - Daily Windows builds of mpv and libmpv including ARM64 architecture.
* [Official mpv installation instruction](https://mpv.io/installation)
* [shinchiro Sourceforge](https://sourceforge.net/projects/mpv-player-windows/files/) - Windows builds of mpv and libmpv. The advantage of this choice is that it has old builds for the case of new builds having issues.

# Documentation

* [Manual](https://mpv.io/manual/stable/)
* [Wiki](https://github.com/mpv-player/mpv/wiki) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26
* [How to Use MPV on Windows](https://www.makeuseof.com/how-to-use-mpv-on-windows)
* [mpv: The Best Video Player for Language Learning](https://www.youtube.com/watch?v=bbg6ztWecbU)
* <https://wiki.archlinux.org/title/mpv>
* <https://manpages.ubuntu.com/manpages/bionic/en/man1/mpv.1.html>

# Support

* <https://github.com/mpv-player/mpv/issues> ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26
* <https://github.com/mpv-player/mpv/discussions> ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26
* <https://mpv.io/community/>
* <https://www.reddit.com/r/mpv>

# User Script

The most complete/up-to-date list of user scripts can be found
in the [wiki](https://github.com/mpv-player/mpv/wiki/User-Scripts) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26,
the advantage of the following list is that everything is categorized
into popular sections, like Subtitles etc.

## Menu

* [select](https://github.com/mpv-player/mpv/blob/master/player/lua/select.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Menu script built into mpv.
* [uosc](https://github.com/tomasklaen/uosc) ⭐ 3,339 | 🐛 33 | 🌐 Lua | 📅 2026-08-03 - Popular OSC with menu.
* [command\_palette](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Searchable menu for
  bindings, playlist, chapters, profiles, all tracks, audio tracks, video tracks,
  subtitle tracks, secondary subtitle tracks, subtitle lines, commands, properties,
  options, audio devices, Blu-ray titles, stream quality, aspect ratio, recent files.
* [search-menu](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Searchable and configurable menu to quickly find key bindings, commands, properties, audio/subtitle tracks and playlist entries.
* [osm](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Configurable on screen menu to run custom commands.
* [menu-plugin](https://github.com/tsl0922/mpv-menu-plugin) ⭐ 204 | 🐛 10 | 🌐 C | 📅 2025-01-15 - Win32 context menu, file dialog, clipboard support for mpv on Windows.
* [dyn\_menu](https://github.com/tsl0922/mpv-menu-plugin/blob/main/src/lua/dyn_menu.lua) ⭐ 204 | 🐛 10 | 🌐 C | 📅 2025-01-15 - Context Menu with support for defining the context menu in input.conf.
* [mpvc-tui](https://github.com/gmt4/mpvc) ⭐ 157 | 🐛 1 | 🌐 Shell | 📅 2026-08-23 - Command-line and TUI for mpv.
* [M-x](https://github.com/Seme4eg/mpv-scripts/tree/master#m-x) ⭐ 74 | 🐛 1 | 🌐 Lua | 📅 2026-02-24 - Searchable and configurable menu to quickly find key bindings and commands.
* [search-page](https://github.com/CogentRedTester/mpv-search-page) ⭐ 56 | 🐛 7 | 🌐 Lua | 📅 2023-01-16 - Searchable and configurable menu to quickly find key bindings, commands, options and properties.
* [menu](https://github.com/jonniek/mpv-menu) ⭐ 53 | 🐛 3 | 🌐 Lua | 📅 2020-05-09 - Configurable on screen menu to run custom commands.
* [menu](https://github.com/nezumisama/mpvmenu) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2018-10-23 - Configurable on screen context-menu.
* [mdmenu](https://codeberg.org/NRK/mpv-toolbox/src/branch/master/mdmenu) - Use dmenu (Linux launcher) for selecting audio/subtitle/chapters etc.
* [Tcl/Tk context-menu](https://gist.github.com/avih/bee746200b5712220b8bd2f230e535de) - Configurable context-menu based on Tcl/Tk (cross-platform).
* [contextmenu](https://gitlab.com/carmanaught/mpvcontextmenu) - Comprehensive context-menu forked from [Tcl/Tk context menu](https://gist.github.com/avih/bee746200b5712220b8bd2f230e535de).
* [playlist-kdialog](https://gist.github.com/ftk/5e26656a2ec9a6cb0fef46918f741d0a) - Use KDE's KDialog or GTK's zenity to show current playlist or select playlist entry.
* [mpvselectmenu](https://gitlab.com/carmanaught/mpvselectmenu) - Context-menu inspired by `select.lua` utilising mpv's `input` and `console` script functionality. Uses other scripts (see Requirements).

## Playback

* [betterchapters](https://gist.github.com/Hakkin/4f978a5c87c31f7fe3ae) ([update](https://github.com/mpv-player/mpv/issues/4738#issuecomment-321298846) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26) - Loads the next or previous playlist entry if there are no more chapters in the seek direction.
* [autoload](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Automatically load playlist entries before and after the currently playing file, by scanning the directory. **Obsolete:** mpv now has a native `--autocreate-playlist` option.
* [print-playlist](https://git.sr.ht/~jagrg/dotfiles/tree/master/item/common/.config/mpv/scripts/print-playlist.lua) - Cleans [the playlist formatting](https://github.com/mpv-player/mpv/issues/5868#issue-327675880) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 on the terminal.
* [playlistnoplayback](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/playlistnoplayback.lua) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12 - If you enable the save play history and progress function, this lua script can solve the problem of automatically jumping to the previous playback progress when playing the next file when playing the playlist, that is, let the playlist always play the next file from the beginning every time. the limitations of this script, please see the comments section in the content.
* [pause-indicator-lite](https://github.com/Samillion/ModernZ/tree/main/extras/pause-indicator-lite) ⭐ 1,180 | 🐛 25 | 🌐 Lua | 📅 2026-06-04 - A simple script that displays an indicator on pause, with options to adjust icon, color, height, width, opacity and whether to toggle pause with a keybind or not.
* [UndoRedo](https://github.com/Eisa01/mpv-scripts#undoredo) ⭐ 839 | 🐛 56 | 🌐 Lua | 📅 2025-06-21 - Undo and Redo feature for mpv. If you seek/jump to a different time in the video, press undo \[ctrl]+\[z] to linearly undo the seeks/jumps in the video, and press redo \[ctrl]+\[y] to linearly return to previous undo positions. More details in the link above.
* [SimpleBookmark-1.0](https://github.com/Eisa01/mpv-scripts#simplebookmark) ⭐ 839 | 🐛 56 | 🌐 Lua | 📅 2025-06-21 - Bookmark with a \[ctrl]+\[b], then list and access your bookmarks with \[b]. Assign your favorites to a keybind then access your favorites with that same keybind. Much more explained in the link above.
* [SimpleHistory-1.0](https://github.com/Eisa01/mpv-scripts#simplehistory) ⭐ 839 | 🐛 56 | 🌐 Lua | 📅 2025-06-21 - Powerful history features that logs videos that you opened into a log file along with the time you have reached on each video. Select, filter, and search from your history list, Optional resume by \[ctrl]+\[r] for all videos you have played. Much more explained in the link above.
* [SimpleUndo-3.2](https://github.com/Eisa01/mpv-scripts#simpleundo) ⭐ 839 | 🐛 56 | 🌐 Lua | 📅 2025-06-21 - Simple undo feature. If you accidentally seek/jump to a different time in the video, press undo \[ctrl]+\[z] to return to your previous time and vice-versa. More details in the link above.
* [SmartSkip](https://github.com/Eisa01/mpv-scripts/#smartskip) ⭐ 839 | 🐛 56 | 🌐 Lua | 📅 2025-06-21 - Automatically or manually skip opening, intro, outro, and preview, like never before. Jump to next file, previous file, and save your chapter changes! Much more explained in the link above.
* [playlist-manager](https://github.com/jonniek/mpv-playlistmanager) ⭐ 695 | 🐛 12 | 🌐 Lua | 📅 2026-03-16 - Create and manage playlists.
* [seek-to](https://github.com/occivink/mpv-scripts#seek-tolua) ⭐ 491 | 🐛 43 | 🌐 Lua | 📅 2025-11-01 - Seek to an absolute timestamp specified via keyboard input.
* [playlist-view](https://github.com/occivink/mpv-gallery-view) ⭐ 257 | 🐛 26 | 🌐 Lua | 📅 2024-09-27 - Display and navigate the playlist in a grid view of thumbnails.
* [history](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Writes date, time, playtime and filename to a log file: `10.09.2022 19:50  3 D:\Samples\Big Buck Bunny.mkv`
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - When seeking display position and duration like so: 70:00 / 80:00
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Navigate in playlist to next/previous/first/last file.
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Jump to a random position in the playlist.
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Load or append files/URLs from clipboard.
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Cycle audio and subtitle tracks, include only languages you know.
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Show detailed media info on screen.
* [stats](https://github.com/Argon-/mpv-stats/) ⭐ 212 | 🐛 1 | 🌐 Lua | 📅 2018-12-09 - Display some statistics about the currently played file on-screen.
* [censor](https://github.com/zenyd/mpv-scripts) ⭐ 193 | 🐛 1 | 🌐 Lua | 📅 2025-12-07 - Skip over parts of videos you don't want (others) to view
* [speed-transition](https://github.com/zenyd/mpv-scripts) ⭐ 193 | 🐛 1 | 🌐 Lua | 📅 2025-12-07 - Increases playback speed if a subtitle will not be displayed soon. Resumes normal speed just before the subtitle shows up.
* [reload](https://github.com/4e6/mpv-reload) ⭐ 154 | 🐛 8 | 🌐 Lua | 📅 2025-02-07 - When an online video is stuck during buffering or got slow CDN source, restarting often helps. This script provides automatic reloading of videos that didn't have buffering progress for some time, keeping the current time position. It also adds `Ctrl+r` keybinding to reload video manually.
* [bookmarker-menu](https://github.com/NurioHin/mpv-bookmarker) ⭐ 131 | 🐛 20 | 🌐 Lua | 📅 2021-01-27 - Menu to manage all your bookmarks.
* [chapter-make-read](https://github.com/dyphire/mpv-scripts/blob/main/chapter-make-read.lua) ⭐ 123 | 🐛 1 | 🌐 Lua | 📅 2026-08-17 - Automatically read an load the namesake external chapter file with extension of CHP. Temporarily mark the current playback position as a chapter so you can seek to it later. Also allows writing current chapters as CHP or XML. Based on `createchapter`.
* [track-list](https://github.com/dyphire/mpv-scripts/blob/main/track-list.lua) ⭐ 123 | 🐛 1 | 🌐 Lua | 📅 2026-08-17 - Interractive track-list menu.
* [skiptosilence dyphire](https://github.com/dyphire/mpv-scripts/blob/main/skiptosilence.lua) ⭐ 123 | 🐛 1 | 🌐 Lua | 📅 2026-08-17 - Skips to the next silence in the file.
* [memo](https://github.com/po5/memo) ⭐ 121 | 🐛 11 | 🌐 Lua | 📅 2024-11-01 - A recent files/history menu for mpv with optional uosc integration.
* [btime](https://github.com/butterw/bShaders/blob/master/mpv/settings/scripts/btime.js) ⭐ 110 | 🐛 3 | 🌐 HLSL | 📅 2024-01-19 - Shows a shorter time format when seeking: 0:15 / 3:10, 08:20 / 55:00, 0:00:05 / 1:30:14.
* [countdown](https://github.com/butterw/bShaders/blob/master/mpv/settings/scripts/countdown.lua) ⭐ 110 | 🐛 3 | 🌐 HLSL | 📅 2024-01-19 - Display a countdown on OSD for the final seconds of the video (or music file).
* [nextfile](https://github.com/jonniek/mpv-nextfile) ⭐ 87 | 🐛 4 | 🌐 Lua | 📅 2023-08-09 - Force opens next or previous file in the currently playing files directory.
* [recent](https://github.com/hacel/recent) ⭐ 85 | 🐛 6 | 🌐 Lua | 📅 2024-10-14 - Recently (history) played menu.
* [skipchapters](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/scripts/avail/skipchapters.lua) ⚠️ Archived - Automatically skip chapters matching a given list of regular expressions (eg. "OP" or "Opening").
* [chapters\_for\_mpv](https://github.com/mar04/chapters_for_mpv) ⭐ 82 | 🐛 5 | 🌐 Lua | 📅 2025-01-29 - Add, remove and edit chapters of the currently played media. Chapters you create can be saved into a separate text file and automatically loaded when you open the same media file again.
* [chapters-menu](https://github.com/Seme4eg/mpv-scripts/tree/master#chapters-menu) ⭐ 74 | 🐛 1 | 🌐 Lua | 📅 2026-02-24 - List all chapters of current video, search and choose any.
* [skipsilence](https://github.com/ferreum/mpv-skipsilence) ⭐ 74 | 🐛 2 | 🌐 Lua | 📅 2025-09-06 - Increase playback speed during quiet parts of the file.
* [reload](https://github.com/dya-tel/mpv-scripts) ⭐ 70 | 🐛 2 | 🌐 Lua | 📅 2024-07-31 - Sometimes you have unstable internet connection, or YouTube server dies, or your computer was sleeping for too long, or whatever. The thing is: you were watching something, you lost the connection, MPV doesn't want to play it further, you don't want to find the video again and then seek it to the moment you were watching.
* [skiptosilence detuur](https://github.com/detuur/mpv-scripts) ⭐ 66 | 🐛 6 | 🌐 Lua | 📅 2023-08-27 - Skips to the next silence in the file.
* [evafast](https://github.com/po5/evafast) ⭐ 59 | 🐛 13 | 🌐 Lua | 📅 2024-02-09 - Fast-forwarding and seeking on a single key, with quality of life features like slowing down a bit when subtitles are shown.
* [trackselect](https://github.com/po5/trackselect) ⭐ 54 | 🐛 3 | 🌐 Lua | 📅 2023-08-01 - Select tracks based on their title.
* [createchapter](https://github.com/shinchiro/mpv-createchapter) ⭐ 54 | 🐛 3 | 🌐 Lua | 📅 2020-09-06 - Temporarily mark the current playback position as a chapter so you can seek to it later. Also allows writing current chapters as XML.
* [chapterskip](https://github.com/po5/chapterskip) ⭐ 50 | 🐛 4 | 🌐 Lua | 📅 2022-09-08 - Skip chapters based on their title.
* [chapter-list](https://github.com/CogentRedTester/mpv-scroll-list/blob/master/examples/chapter-list.lua) ⭐ 48 | 🐛 3 | 🌐 Lua | 📅 2025-01-10 - Interractive chapter-list menu.
* [bookmarker](https://github.com/nimatrueway/mpv-bookmark-lua-script) ⚠️ Archived - Bookmark your favorite time on media files
* [fastforward](https://github.com/jgreco/mpv-scripts/blob/master/fastforward.lua) ⭐ 47 | 🐛 3 | 🌐 Lua | 📅 2019-10-10 - Instead of skipping forward in media files, speed up the playback for a few seconds.  Playback speed decays back to 1x after a few seconds.  Tap rapidly or hold down to go faster.
* [when-to-loop](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/when-to-loop.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - Intelligently decide when mpv should loop, i.e. while shuffling or while playing a short file.
* [lats](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/lats.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - The Low ATtention Span mpv script. Plays brief segments from random positions of one or more files, kinda like flipping through TV channels.
* [auto-save-state](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/auto-save-state.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - Periodically saves progress with write-watch-later-config, and also cleans up the watch later data after the file is finished playing (so playlists may continue at the correct file).
* [lilskippa](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/lilskippa.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - Skip to black, skip to silence, skip to scene change.
* [recent-menu](https://github.com/natural-harmonia-gropius/recent-menu) ⭐ 45 | 🐛 2 | 🌐 Lua | 📅 2026-07-26 - Recently (history) played menu integrated with uosc.
* [interactive-video](https://github.com/mosquito-byte/mpv-interactive-video) ⭐ 43 | 🐛 3 | 🌐 Lua | 📅 2019-09-20 - Script for watching interactive videos (such as Netflix's *Black Mirror: Bandersnatch*).
* [chapters](https://github.com/zxhzxhz/mpv-chapters) ⭐ 41 | 🐛 3 | 🌐 JavaScript | 📅 2021-08-08 - Display chapters and allow you to jump to them with a mouse click. ([Preview](https://i.imgur.com/f7WtKYN.png))
* [autoloop](https://github.com/zc62/mpv-scripts/blob/master/autoloop.lua) ⭐ 41 | 🐛 0 | 🌐 Lua | 📅 2020-08-28 - Automatically loops files that are under a given duration (default 5 seconds).
* [total\_playtime](https://github.com/oltodosel/mpv-scripts/blob/master/total_playtime.lua) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2024-11-03 - Shows total playtime of current playlist.
* [speed - adjusted timings](https://github.com/oltodosel/mpv-scripts#speed_osd3lua) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2024-11-03 - Recalculates osd-msg3 timecodes with speed != 1
* [speed](https://github.com/oltodosel/mpv-scripts#speedlua) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2024-11-03 - Changing speed based on regex of filename/path.
* [permanent-pause-indicator](https://github.com/oltodosel/mpv-scripts#pause-indicatorlua) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2024-11-03 - Displays a permanent indicator in the middle of the screen while mpv is paused. [Preview](https://github.com/oltodosel/mpv-scripts/raw/master/pause-indicator.jpg) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2024-11-03
* [List chapters](https://github.com/oltodosel/mpv-scripts#show_chapterslua) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2024-11-03 - Shows chapters and their time at the bottom left corner. [example](https://github.com/oltodosel/mpv-scripts/raw/master/show_chapters.jpeg) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2024-11-03
* [guess-media-title](https://github.com/zenwarr/mpv-config/blob/master/scripts/guess-media-title.lua) ⭐ 35 | 🐛 3 | 🌐 Lua | 📅 2025-11-16 - Uses [guessit](https://github.com/guessit-io/guessit) ⭐ 931 | 🐛 16 | 🌐 Python | 📅 2026-08-09 to detect a media title by filename and set `force-media-title` variable. Useful for getting cleaner screenshot file names.
* [tree-profiles](https://github.com/fbriere/mpv-scripts/blob/master/scripts/tree-profiles.lua) ⭐ 30 | 🐛 2 | 🌐 Lua | 📅 2022-02-16 - Automatically apply profiles to certain directories or files.
* [autochapters](https://github.com/po5/mpv-auto-chapters) ⭐ 27 | 🐛 0 | 🌐 Lua | 📅 2025-12-27 - Automatically finds chapters for your anime files.
* [trakt](https://github.com/LiTO773/trakt-mpv) ⚠️ Archived - Connects trakt.tv with mpv and automatically scrobbles movies/shows.
* [quack](https://github.com/CounterPillow/mpv-quack) ⭐ 22 | 🐛 0 | 🌐 Lua | 📅 2020-05-26 - Reduces audio volume temporarily after seeking.
* [history-bookmark](https://github.com/yuukidach/mpv-scripts) ⭐ 22 | 🐛 2 | 🌐 Lua | 📅 2026-04-12 - Create a history file to store the episode we watched last time. And let us easily jump to the video we watched last time.
* [chapter-converter](https://github.com/VimWei/mpv-config/blob/main/scripts/chapter-converter.lua) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2026-05-20 - Converts chapter format between YouTube (e.g., "00:10 chapter title") and mpv (FFmpeg metadata).
* [segment-linking](https://github.com/CogentRedTester/mpv-segment-linking) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2022-11-22 - Supports Matroska hard segment linking.
* [control](https://github.com/oe-d/control) ⭐ 20 | 🐛 0 | 🌐 Lua | 📅 2021-09-20 - Various features mainly for controlling playback.
* [skip-silence](https://github.com/idMysteries/mpv-skip-silence) ⭐ 20 | 🐛 0 | 🌐 Lua | 📅 2024-10-17 - Playback mode that automatically skips/speed up silent parts.
* [fastforward](https://github.com/zsugabubus/mpv-fastforward) ⭐ 19 | 🐛 0 | 🌐 Lua | 📅 2020-12-06 - Fast-forward instead of skipping.
* [multiloop](https://github.com/unusualpepe/mpv-multiloop) ⭐ 18 | 🐛 1 | 🌐 Lua | 📅 2020-11-29 - Loop over multiple A-B points.
* [sort\_script](https://github.com/TheAMM/mpv_sort_script) ⭐ 17 | 🐛 1 | 🌐 Lua | 📅 2018-12-30 - Sort directories and files.
* [dvd-browser](https://github.com/CogentRedTester/mpv-dvd-browser) ⭐ 17 | 🐛 0 | 🌐 Lua | 📅 2025-01-15 - Browse and load DVD titles.
* [plugin-bookmark](https://github.com/yozorayuki/mpv-plugin-bookmark) ⭐ 16 | 🐛 1 | 🌐 Lua | 📅 2018-08-06 - Record your playing history for each folder.
* [libunity](https://github.com/mrlotfi/mpv-libunity) ⭐ 15 | 🐛 3 | 🌐 C | 📅 2025-09-16 - Show a nice progress bar on your Linux panel/dock.
* [groupwatch\_sync](https://github.com/po5/groupwatch_sync) ⭐ 13 | 🐛 1 | 🌐 Lua | 📅 2022-11-04 - Automatically start and get back in sync with a group watch.
* [Change-OSD-Media-Title](https://github.com/nmoorthy1/mpv-Change-OSD-Media-Title) ⭐ 13 | 🐛 1 | 🌐 Lua | 📅 2021-09-08 - Displays filename, percentage watched, current chapter, and number of frames dropped in the OSD media title and updates it whenever one of the values has changed.
* [unseen-playlistmaker](https://github.com/jonniek/unseen-playlistmaker) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2022-10-13 - Keeps track of your watched files from a directory, and on keypress enters playlist-mode to watch unseen files from that specified directory.
* [mpv-PiP](https://github.com/WatanabeChika/mpv-PiP) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2025-11-03 - Allow users to switch to borderless and top-level picture-in-picture mode with shortcut keys.
* [playlist-navigator](https://github.com/drogers141/mpv-playlist-navigator) ⭐ 10 | 🐛 0 | 🌐 Lua | 📅 2025-07-03 - OSD display features easy navigation with scrolling and search to select files to play or remove from playlist.
* [time](https://github.com/mustaqimM/mpv-scripts/blob/master/time.lua) ⭐ 9 | 🐛 2 | 🌐 Lua | 📅 2023-12-27 - Shows the current time or the time at which playback will end.
* [save-playlist](https://github.com/NaiveInvestigator/save-playlist) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2023-09-30 - This script saves your playlist to the working directory of the mpv process.
* [bluetooth-av-delay](https://github.com/fatihkaan22/mpv-bluetooth-av-delay) ⭐ 8 | 🐛 1 | 🌐 Lua | 📅 2020-12-17 - Adds desired A-V delay automatically, if default audio sink is a bluetooth device.
* [writename](https://github.com/paradox460/mpv-scripts/tree/master/writename) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2025-07-25 - Write the currently playing filename/path to a file, optionally skipping/removing from current playlist and muting.
* [bookmarks](https://github.com/texiwustion/bookmarks) ⭐ 7 | 🐛 1 | 🌐 Lua | 📅 2025-09-15 - Support add/delete/prev/next bookmarks, and persistence to sidecar JSON or config directory.
* [timer](https://github.com/AdamD2/mpv-timer) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2018-01-05 - Allows the user to set a starting time and an ending time and see the time elapsed between those points with millisecond precision.
* [radio-title](https://github.com/olivierlemoal/mpv-radio-title-script/) ⚠️ Archived - Automatically fetch current playing title from webradio website when not provided by stream.
* [plugin-myshows](https://github.com/gim-/mpv-plugin-myshows) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2026-03-01 - Automatically marks a currently watched episode in MyShows.
* [loop-until](https://github.com/ZreXoc/mpv-loop-until) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2024-01-31 - Loop the video until a specified amount of time. (e.g. loop a 30s wallpaper video to 30min)
* [mpvclip-mpvival-mpvloop](https://github.com/o770/mpvclip-mpvival-mpvloop) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-09-09 - Run MPV with options for loops and playback start and end times set according to a pattern or intervals of the total duration of a file.
* [speed](https://github.com/vflorelle/mpv-scripts#speed) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2020-03-08 - Always show current playback speed on the OSD.
* [mpv\_segment\_length](https://github.com/shadax1/mpv_segment_length) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2023-11-21 - Displays the length of a segment/range from point A to point B.
* [LoopToFile](https://github.com/NovaFormaLab/LoopToFile) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2025-05-15 - Functional script that allows you to generate playback loops and extract media fragments into new files. L∞p → file.ext.
* [abstime-osd](https://github.com/whether1/mpv-abstime-osd) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2025-10-09 - Show absolute time of the playing audio or video.(OSD).
* [heuristic-autoload](https://github.com/notuxic/mpv-heuristic-autoload) ⭐ 0 | 🐛 1 | 🌐 Lua | 📅 2026-02-02 - Automatically load files with similar names as the playing file into the playlist.
* [history](https://gist.github.com/garoto/e0eb539b210ee077c980e01fb2daef4a) - Simple played media logger. Will generate a `mpvhistory.log` in the default mpv config folder (%APPDATA%/mpv/ or $HOME/.config/mpv/) in the format `[$DATE $TIME] $PATH ($?MEDIA-TITLE)`. Only tested on Windows.
* [history](http://git.smrk.net/mpv-scripts/file/history.lua.html) - Autosave played media items in an SQLite database, restore last played position, select (with dmenu(1)) and play item from history.
* [excessive-history](https://gist.github.com/Abject-Web/3f4f0e85dad73303b9dd1ef1f55c3147) - Excessive played media logger. Logs file name, time, and which parts were played. Will generate a `history.txt` in the mpv config folder. Only tested on Windows.
* [speed-transition-Audio](https://gist.github.com/bitingsock/e8a56446ad9c1ed92d872aeb38edf124) - Changes playback speed based on volume thresholds.
* [skiptofade](https://gist.github.com/bossen/3cfe86a6cdd61452dbb96865128fb327) - Seeks forward until a black screen appears. Built to skip openings. Uses the lavfi blackdetect filter.
* [rewindPlaylist](https://gist.github.com/bitingsock/0f22c631295273d5a53e4337c25fe161) - keybind to rewind to the end of the previous playlist entry
* [review](https://gitlab.com/lvml/mpv-plugin-review) - Allows to remove files viewed quickly from within mpv
* [pause-indicator](https://gist.github.com/torque/9dbc69543118347d2e5f43239a7e609a) - Displays a momentary icon that flashes in the middle of the screen, similar to YouTube.
* [autosave](https://gist.github.com/Hakkin/5489e511bd6c8068a0fc09304c9c5a82) - Periodically saves "watch later" data during playback, rather than only saving on quit. Newer [fork](https://gist.github.com/CyberShadow/2f71a97fb85ed42146f6d9f522bc34ef).
* [mpv-slash-search](https://codeberg.org/Anakiev/mpv-slash-search) - Simple and lightweight script that allows you to search for a file in the playlist and jump to the first match.
* [generate-edl](https://gist.github.com/guidocella/5f05794d0a8400b2393fe7a9995ebb43) - Bookmark scenes in EDL files.
* [autoload-archive-hook](https://gist.github.com/po5/2415cb39c94760ac8c2c7666a30bf02c) - When playing a direct file from within an archive with e.g. `archive://test.rar|/09.png`, mpv doesn't fill the playlist. This script does so transparently. It also supports nested and remote archives.

## File

* [file-browser](https://github.com/CogentRedTester/mpv-file-browser) ⭐ 329 | 🐛 3 | 🌐 Lua | 📅 2026-03-27 - On screen file browser.
* [delete-current-file](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Moves the current file instantly to the recycle bin.
* [file-rating](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Writes a star rating to the filename of the current file.
* [delete-file](https://github.com/zenyd/mpv-scripts) ⭐ 193 | 🐛 1 | 🌐 Lua | 📅 2025-12-07 - Delete files being played.
* [filenavigator](https://github.com/jonniek/mpv-filenavigator) ⭐ 76 | 🐛 10 | 🌐 Lua | 📅 2024-11-03 - Navigate and open local files.
* [fuzzydir](https://github.com/sibwaf/mpv-scripts) ⭐ 70 | 🐛 2 | 🌐 Lua | 📅 2024-07-31 - Allows using wildcards for `sub-file-paths` and `audio-file-paths`.
* [Serkio Tagger](https://github.com/SerkioTeam/Tagger) ⭐ 45 | 🐛 0 | 🌐 Lua | 📅 2020-12-28 - Annotate videos with tags while you watch.
* [open-file-dialog](https://github.com/rossy/mpv-open-file-dialog) ⭐ 42 | 🐛 3 | 🌐 Lua | 📅 2020-04-15 - Launch a Windows open file dialog.
* [locate-file](https://github.com/nimatrueway/mpv-locatefile-lua-script) ⭐ 28 | 🐛 4 | 🌐 Lua | 📅 2022-06-28 - Locate current media file on your OS file browser
* [rename](https://github.com/Kayizoku/mpv-rename) ⭐ 24 | 🐛 6 | 🌐 Lua | 📅 2025-02-05 - Rename files on the go directly from within MPV player window without leaving it.
* [show-filename](https://github.com/yuukidach/mpv-scripts) ⭐ 22 | 🐛 2 | 🌐 Lua | 📅 2026-04-12 - Show the name of the current playing file.
* [zenity-open-files](https://github.com/alifarazz/mpv-zenity-open-files) ⭐ 14 | 🐛 0 | 🌐 Lua | 📅 2026-08-07 - Use GTK's zenity to add files to playlist, subtitles to playing video or open URLs.
* [simple-loader](https://github.com/fhlfibh/simple-loader) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2016-12-25 - (Linux) Browse dirs and files on OSD, and launch them with mpv.
* [limited-autoload](https://github.com/glubsy/mpv-limited-autoload) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2021-08-26 - Auto-load files in a lazy way by limiting how many are loaded into playlist at once
* [separator](https://github.com/pvpscript/mpv-separator) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2023-07-08 - Copy or move video files you wanna keep.
* [mpv-file-organizer](https://github.com/borasavkar/mpv-file-organizer) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2026-01-28 - Automatically organizes media files into folders based on metadata tags.
* [open-dir](https://github.com/ayghub/open-dir) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2025-04-27 - Opens the path of the current file in Windows File Explorer.
* [KDialog-open-files](https://gist.github.com/ntasos/d1d846abd7d25e4e83a78d22ee067a22) - Use KDE's KDialog to add files to playlist, subtitles to playing video or open URLs.
* [open-in-explorer](https://gist.github.com/Sneakpeakcss/05a97d509b8be67a6f11400b0bee54ab) - Shows the currently playing file in Windows File Explorer.

## On Screen Controller

* [uosc](https://github.com/tomasklaen/uosc) ⭐ 3,339 | 🐛 33 | 🌐 Lua | 📅 2026-08-03 - Popular OSC with menu.

* [osd-bar](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/osd-bar.lua) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12 - Always show osd progress bar, with the more beautiful color matching in the [configuration file](https://github.com/422658476/MPV-EASY-Player/blob/master/mpv-easy-data/rjno1.conf) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12, you can make the osd progress bar display the current progress at the bottom of the window beautifully,this is a [preview](https://raw.githubusercontent.com/422658476/MPV-EASY-Player/master/img/mpv-easy-player-osd-bar-lua.jpg).

* [osc-style](https://github.com/422658476/MPV-EASY-Player/tree/master/mpv-easy-data/osc-style) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12 - Change the mpv OSC to a more beautiful and practical look, which is the osc theme feature, a variety of styles to choose from,this is a [tutorial and a preview](https://github.com/422658476/MPV-EASY-Player#%E7%9C%8B%E5%88%B0%E4%B8%8A%E9%9D%A2%E5%9B%BE%E4%B8%8A%E8%BF%99%E4%BA%9Bosc%E6%A0%B7%E5%BC%8F%E4%BA%86%E5%90%97%E5%AE%83%E4%BB%AC%E4%B8%8D%E4%BB%85%E5%8F%AF%E4%BB%A5%E5%AD%98%E5%9C%A8%E4%BA%8Empv-easy-player%E4%B8%AD%E4%BD%A0%E4%BD%BF%E7%94%A8%E7%9A%84mpv%E7%9A%84osc%E4%B9%9F%E5%8F%AF%E4%BB%A5%E5%8F%98%E6%88%90%E8%BF%99%E6%A0%B7) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12.

* [ModernZ](https://github.com/Samillion/ModernZ) ⭐ 1,180 | 🐛 25 | 🌐 Lua | 📅 2026-06-04 - A fork of ModernX designed to enhance functionality by adding more features, all while preserving the core standards of mpv's OSC.

* [ModernX cyl0](https://github.com/cyl0/ModernX) ⭐ 755 | 🐛 20 | 🌐 Lua | 📅 2026-02-04 - Modern OSC replacement.

* [thumbnail\_script](https://github.com/TheAMM/mpv_thumbnail_script) ⭐ 715 | 🐛 57 | 🌐 Lua | 📅 2023-08-07 - Shows preview thumbnails in the seekbar.

* [osc-modern](https://github.com/maoiscat/mpv-osc-modern) ⭐ 427 | 🐛 15 | 🌐 Lua | 📅 2024-04-20 - Modern OSC replacement.

* [thumbnail\_script](https://github.com/marzzzello/mpv_thumbnail_script) ⭐ 317 | 🐛 31 | 🌐 Lua | 📅 2024-07-01 - Shows preview thumbnails in the seekbar.

* [ModernX zydezu](https://github.com/zydezu/ModernX) ⭐ 289 | 🐛 3 | 🌐 Lua | 📅 2026-08-11 - A fork of ModernX with many additional features and customization.

* [tethys](https://github.com/Zren/mpv-osc-tethys) ⭐ 214 | 🐛 20 | 🌐 Lua | 📅 2024-04-30 - OSC replacement with seekbar thumbnail preview.

* [progressbar](https://github.com/torque/mpv-progressbar) ⭐ 169 | 🐛 10 | 🌐 MoonScript | 📅 2025-03-05 - A minimalistic OSC replacement. It provides a small, unintrusive progress bar that persists at the bottom of the video window.

* [modern-x-compact](https://github.com/1-minute-to-midnight/mpv-modern-x-compact) ⭐ 98 | 🐛 5 | 🌐 Lua | 📅 2024-08-10 - Compact version of modern-x.

* [osc-modern-f](https://github.com/FinnRaze/mpv-osc-modern-f) ⭐ 92 | 🐛 2 | 🌐 Lua | 📅 2024-09-17 - OSC script forked from [mpv-osc-modern](https://github.com/maoiscat/mpv-osc-modern) ⭐ 427 | 🐛 15 | 🌐 Lua | 📅 2024-04-20.

* [oscc](https://github.com/longtermfree/oscc) ⭐ 69 | 🐛 3 | 🌐 Lua | 📅 2024-10-02 - Dark-themed OSC.

* [dark-box](https://github.com/maoiscat/mpv-dark-box) ⭐ 55 | 🐛 4 | 🌐 Lua | 📅 2022-02-04 - OSC replacement.

* [osc-show-hide](https://github.com/linguisticmind/mpv-scripts/tree/master/osc-show-hide) ⭐ 38 | 🐛 3 | 🌐 Lua | 📅 2025-07-28 - Toggles the on-screen controller with a hotkey.

* [osc-simple](https://github.com/maoiscat/mpv-osc-simple) ⭐ 13 | 🐛 0 | 🌐 Lua | 📅 2023-05-11 - An OSC/UI replacement of white theme.

* [uosc\_history\_menu](https://github.com/Koopex/uosc_history_menu) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2026-08-20 - A history and bookmark management menu integrated with uosc.

* [osc-orange](https://github.com/maoiscat/mpv-osc-orange) ⭐ 11 | 🐛 1 | 🌐 Lua | 📅 2023-05-11 - An osc/ui replacement in dark theme.

* [thumbnail\_script](https://github.com/felipefacundes/mpv_thumbnail_script) ⭐ 10 | 🐛 0 | 🌐 Lua | 📅 2020-11-01 - Shows preview thumbnails in the seekbar.

* [mfpbar-drag](https://github.com/layercak3/mfpbar-drag) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2025-07-02 - mfpbar with support for dragging the bar.

* [sosc](https://github.com/christoph-heinrich/sosc) ⭐ 4 | 🐛 1 | 🌐 Lua | 📅 2023-12-09 - An OSC supplement for OSC replacements. Provides the idle message and script messages from the original OSC.

* [mfpbar](https://codeberg.org/NRK/mpv-toolbox/src/branch/master/mfpbar) - A minimalistic progressbar and osc replacement.

## Input

* [cycle-commands](https://github.com/CogentRedTester/mpv-scripts/blob/master/cycle-commands.lua) ⭐ 300 | 🐛 4 | 🌐 Lua | 📅 2026-01-11 - Allows input.conf commands to be cycled through with keybinds.
* [auto-mode](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Use mpv as video player, music player and image viewer, switch automatically between, video, audio and image mode.
* [multi-command-if](https://github.com/VideoPlayerCode/mpv-tools/) ⭐ 192 | 🐛 3 | 🌐 JavaScript | 📅 2021-07-07 - Very powerful conditional logic and multiple action engine for your keybindings, without having to write a single line of code!
* [zones](https://github.com/wiiaboo/mpv-scripts/blob/master/zones.lua) ⭐ 97 | 🐛 3 | 🌐 Lua | 📅 2020-09-19 - Handles commands depending on where the mouse pointer is at, mostly for mouse wheel handling.
* [InputEvent](https://github.com/Natural-Harmonia-Gropius/InputEvent) ⭐ 94 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Enhanced input.conf with better, conflict-free, low-latency event mechanism.
* [repl](https://github.com/rossy/mpv-repl) ⭐ 82 | 🐛 2 | 🌐 Lua | 📅 2019-12-07 - A REPL for input commands that is displayed on the video window.
* [Sockets](https://github.com/wis/mpvSockets) ⭐ 80 | 🐛 3 | 🌐 Lua | 📅 2024-02-13 - creates one IPC sockets per mpv instance, instead of one socket for the last started instance.   *Supports*: Linux, MacOS and Windows.
* [leader key](https://github.com/Seme4eg/mpv-scripts/tree/master#leader) ⭐ 74 | 🐛 1 | 🌐 Lua | 📅 2026-02-24 - Adds *leader* key to your mpv. With prefixes and [which-key](https://github.com/justbur/emacs-which-key) ⚠️ Archived functionality. [demo](https://i.imgur.com/dUWFu3u.gif)
* [blackout](https://github.com/dya-tel/mpv-scripts) ⭐ 70 | 🐛 2 | 🌐 Lua | 📅 2024-07-31 - Couldn't find the "Boss key", but you don't want someone (or simply anyone) to see what you are watching?
* [blackout](https://github.com/sibwaf/mpv-scripts) ⭐ 70 | 🐛 2 | 🌐 Lua | 📅 2024-07-31 - A fast crossplatform boss-key, but without window minimization (and possible problems with some VO drivers).
* [boss-key](https://github.com/detuur/mpv-scripts) ⭐ 66 | 🐛 6 | 🌐 Lua | 📅 2023-08-27 - Minimise and pause video at the same time. Windows/Linux. Eliminated the time lag in previous versions.
* [cheatsheet](https://github.com/ento/mpv-cheatsheet) ⭐ 60 | 🐛 1 | 🌐 JavaScript | 📅 2024-06-03 - Looking up keyboard shortcuts (bindings).
* [multisocket](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/multisocket.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - Creates a numbered socket for each instance of mpv.
* [gestures](https://github.com/omeryagmurlu/mpv-gestures) ⭐ 37 | 🐛 1 | 🌐 Lua | 📅 2022-09-04 - Touchscreen and mouse gestures.
* [russian-layout-bindings](https://github.com/zenwarr/mpv-config/blob/master/scripts/russian-layout-bindings.lua) ⭐ 35 | 🐛 3 | 🌐 Lua | 📅 2025-11-16 - As mpv does not support shortcuts independent of the keyboard layout (<https://github.com/mpv-player/mpv/issues/351> ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26), this script tries to workaround this issue for some limited cases with russian (йцукен) keyboard layout. Upon startup, it takes currently active bindings from `input-bindings` property and duplicates them for russian layout. You can adapt the script for your preferred layout, but it won't (of course) work for layouts sharing unicode characters with english.
* [audio-file-keys](https://github.com/fbriere/mpv-scripts/blob/master/scripts/audio-file-keys.lua) ⭐ 30 | 🐛 2 | 🌐 Lua | 📅 2022-02-16 - Automatically apply key bindings when playing audio files.
* [touch-gestures](https://github.com/christoph-heinrich/mpv-touch-gestures) ⭐ 29 | 🐛 1 | 🌐 Lua | 📅 2023-02-03 - Gestures for play/pause, speed, volume, seeking and next/previous playlist-item.
* [pointer-event](https://github.com/christoph-heinrich/mpv-pointer-event) ⭐ 13 | 🐛 0 | 🌐 Lua | 📅 2023-02-03 - Mutually exclusive, low latency mouse/touch input event detection. Executes configurable commands on single-click, double-click, long-click and dragging.
* [mpv-omniGlass](https://github.com/guarapicci/mpv-omniGlass) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2024-05-29 - Touchpad gestures for mpv.
* [boss-key-wayland](https://github.com/Man2Dev/mpv-wayland-Boss-key) ⭐ 1 | 🐛 1 | 🌐 Lua | 📅 2024-05-30 - Minimise and pause video at the same time in Linux through xdg-portals.
* [cycle\_messages](https://gist.github.com/rrooij/59f57ff5f5a952e56bbb) - Cycle between custom OSD messages.

## Subtitle

* [autosub](https://github.com/davidde/mpv-autosub) ⭐ 378 | 🐛 22 | 🌐 Lua | 📅 2023-12-24 - Automatic subtitle downloading.
* [playphrase](https://github.com/kelciour/playphrase) ⚠️ Archived - Search and play phrases from movies and audiobooks.
* [subselect Tk](https://github.com/zenyd/mpv-scripts) ⭐ 193 | 🐛 1 | 🌐 Lua | 📅 2025-12-07 - Download subtitles with a GUI - select the one you want and automatically load them up in mpv. Supports searching for arbitrary names and different subtitle languages. Works on Windows and Linux, possibly macOS.
* [autosubsync](https://github.com/joaquintorres/autosubsync-mpv) ⭐ 189 | 🐛 7 | 🌐 Lua | 📅 2026-05-17 - Automatically sync subtitles using **ffsubsync**.
* [sub-bilingual](https://github.com/kelciour/mpv-scripts/blob/master/sub-bilingual.lua) ⚠️ Archived - Generate bilingual subtitles.
* [sub-bookmarks](https://github.com/kelciour/mpv-scripts/blob/master/sub-bookmarks.lua) ⚠️ Archived - Save current position and subtitles in .txt file.
* [sub-export](https://github.com/kelciour/mpv-scripts/blob/master/sub-export.lua) ⚠️ Archived - original, outdated
* [sub-playback](https://github.com/kelciour/mpv-scripts/blob/master/sub-playback.lua) ⚠️ Archived - Add interactive move, i.e. automatically pause at the end of the fragment with option to continue playback or replay it again with or without subtitles.
* [sub-replay](https://github.com/kelciour/mpv-scripts/blob/master/sub-replay.lua) ⚠️ Archived - Replay previous sentence.
* [sub-search](https://github.com/kelciour/mpv-scripts/blob/master/sub-search.lua) ⚠️ Archived - Search for phrase in subtitles and skip to it.
* [sub-sentences](https://github.com/kelciour/mpv-scripts/blob/master/sub-sentences.lua) ⚠️ Archived - Generate subtitles with sentences.
* [assrt by AssrtOSS](https://github.com/AssrtOSS/mpv-assrt) ⭐ 137 | 🐛 7 | 🌐 Lua | 📅 2023-10-03 - Download subtitles from assrt.net.
* [sub-select](https://github.com/CogentRedTester/mpv-sub-select) ⭐ 134 | 🐛 2 | 🌐 Lua | 📅 2025-04-04 - Advanced conditional subtitle track selector.
* [sub\_export](https://github.com/dyphire/mpv-scripts/blob/main/sub_export.lua) ⭐ 123 | 🐛 1 | 🌐 Lua | 📅 2026-08-17 - fork, updated. Extract selected subtitles from .mkv file.
* [whisper-subs](https://github.com/GhostNaN/whisper-subs) ⭐ 105 | 🐛 1 | 🌐 Lua | 📅 2025-02-09 - Generates subtitles at runtime with whisper.cpp on Linux.
* [subit](https://github.com/wiiaboo/mpv-scripts/blob/master/subit.lua) ⭐ 97 | 🐛 3 | 🌐 Lua | 📅 2020-09-19 - Yet another script for downloading subtitles using subliminal. Supports better customization of options, such as easy language selection, authentication for providers that need it, and support for URLs.
* [fix\_sub\_timing](https://github.com/wiiaboo/mpv-scripts/blob/master/fix-sub-timing.lua) ⭐ 97 | 🐛 3 | 🌐 Lua | 📅 2020-09-19 - Compute the correct speed/delay of subtitles by manually synching two points in time.
* [sub-pause](https://github.com/Ben-Kerman/mpv-sub-scripts) ⭐ 93 | 🐛 7 | 🌐 Lua | 📅 2024-07-11 - Automatically pause just before the end of each subtitle line. Also allows replaying the currently active line.
* [sub-skip](https://github.com/Ben-Kerman/mpv-sub-scripts) ⭐ 93 | 🐛 7 | 🌐 Lua | 📅 2024-07-11 - Automatically skip parts of a video that don't contain any subtitles. Does so by either fast-forwarding or seeking.
* [auto-load-fonts](https://github.com/Hill-98/mpv-config/blob/main/scripts/auto-load-fonts.js) ⭐ 84 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-01 - Auto load the font files in the fonts folder under the play file path.
* [autosub](https://github.com/vayan/autosub-mpv/blob/master/autosub.lua) ⭐ 68 | 🐛 3 | 🌐 Lua | 📅 2020-05-25 - Automatically download subtitles using **subliminal**.
* [tts-subs](https://github.com/jgreco/mpv-scripts/blob/master/tts-subs.lua) ⭐ 47 | 🐛 3 | 🌐 Lua | 📅 2019-10-10 - Use voice synthesis to read subtitles out-loud.
* [autosubsync](https://github.com/Ajatt-Tools/autosubsync-mpv) ⭐ 43 | 🐛 1 | 🌐 Lua | 📅 2026-05-17 - Automatic subtitle synchronization script.
* [save-sub-delay](https://github.com/zc62/mpv-scripts/blob/master/save-sub-delay.lua) ⭐ 41 | 🐛 0 | 🌐 Lua | 📅 2020-08-28 - This script saves the sub-delay quantity for each file. When next time the file is opened, sub-delay is automatically restored.
* [sub-fastwhisper](https://github.com/dyphire/mpv-sub-fastwhisper) ⭐ 39 | 🐛 2 | 🌐 Lua | 📅 2026-05-30 - Generate SRT subtitles through voice transcription using faster-whisper.
* [copy-subtitle](https://github.com/linguisticmind/mpv-scripts/tree/master/copy-subtitle) ⭐ 38 | 🐛 3 | 🌐 Lua | 📅 2025-07-28 - Copies currently displayed subtitle line to clipboard.
* [subtitle-search](https://github.com/zenwarr/mpv-config/blob/master/scripts/subtitle-search.lua) ⭐ 35 | 🐛 3 | 🌐 Lua | 📅 2025-11-16 - Script to search for a phrase inside an active `.srt` subtitle. Displays matched lines in OSD list, takes `sub-delay` into account and allows searching for Unicode text in utf8 subtitle files.
* [restore-subtitles](https://github.com/zenwarr/mpv-config/blob/master/scripts/restore-subtitles.lua) ⭐ 35 | 🐛 3 | 🌐 Lua | 📅 2025-11-16 - Saves selected subtitle tracks and visibility state to `saved-subs.json` file in config directory and restores them whenever file is loaded. Differs from `watch-later`-saved data in that it saves secondary subtitles too (and uses subtitle file paths instead of ids).
* [subtitle-lines](https://github.com/christoph-heinrich/mpv-subtitle-lines) ⭐ 35 | 🐛 1 | 🌐 Lua | 📅 2026-07-19 - List and search subtitle lines of the selected subtitle track.
* [subai](https://github.com/zenwarr/mpv-config?tab=readme-ov-file#subai) ⭐ 35 | 🐛 3 | 🌐 Lua | 📅 2025-11-16 - Translate and explain the currently displayed subtitle line into your preferred language. Helps learning a foreign language.
* [find\_subtitles](https://github.com/directorscut82/find_subtitles) ⭐ 31 | 🐛 3 | 🌐 Lua | 📅 2024-11-30 - (Down)load subtitles with subliminal.
* [sub-transition](https://github.com/Ajatt-Tools/sub-transition) ⭐ 29 | 🐛 2 | 🌐 Lua | 📅 2026-08-09 - Speed up the video if no subtitles are visible.
* [sub-transition](https://github.com/Ajatt-Tools/sub_transition) ⭐ 29 | 🐛 2 | 🌐 Lua | 📅 2026-08-09 - Speed up playback when no subtitles are visible.
* [dualsubs utils](https://github.com/VimWei/mpv-config) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2026-05-20 - Auto load dual subs; Auto reload dual subs; Swap primary/secondary subs position; Merge dual subs to one ASS sub.
* [srt-resegment](https://github.com/VimWei/mpv-config/blob/main/scripts/srt-resegment.lua) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2026-05-20 - Resegment srt by synchronize plain text with whisper's word-level timestamps JSON.
* [trueautosub](https://github.com/fullmetalsheep/mpv-iina-scripts) ⭐ 19 | 🐛 0 | 🌐 Lua | 📅 2018-10-15 - Fork of autosub, automatically downloads subtitles if not present using **subliminal**. (osx/linux only)
* [llm-subtrans](https://github.com/sorz/mpv-llm-subtrans/) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2025-04-07 - Extract & translate subtitles with OpenAI API. Streaming & contextual.
* [intersubs](https://github.com/abdnh/intersubs) ⭐ 12 | 🐛 3 | 🌐 Python | 📅 2023-08-20 - Interactive subtitles.
* [ytsub](https://github.com/Idlusen/mpv-ytsub/) ⭐ 12 | 🐛 2 | 🌐 Lua | 📅 2026-08-12 - Load automatic captions from Youtube, can select language interactively or automatically.
* [sub-assrt by dyphire](https://github.com/dyphire/mpv-sub-assrt) ⭐ 11 | 🐛 1 | 🌐 Lua | 📅 2026-04-30 - Download Chinese subtitles from assrt.
* [sub-not-forced-not-sdh](https://github.com/pzim-devdata/mpv-scripts) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2024-04-30 - Prevents the selection of FORCED and SDH subtitles when you start playing a video.
* [libass\_sub\_selector](https://github.com/po5/libass_sub_selector) ⭐ 8 | 🐛 2 | 🌐 Lua | 📅 2019-12-09 - Visually select individual subtitles a la PotPlayer.
* [dessubdb](https://github.com/demanuel/dessubdb/blob/master/mpv.lua) ⭐ 8 | 🐛 0 | 🌐 Perl | 📅 2018-07-23 - Download automatically subtitles from the thesubdb.com using [DESSubdb](https://github.com/demanuel/dessubdb) ⭐ 8 | 🐛 0 | 🌐 Perl | 📅 2018-07-23.
* [Audio WebDAV & Sub WebDAV](https://github.com/Kibakus/mpv-scripts) ⭐ 6 | 🐛 0 | 🌐 Lua | 📅 2025-06-17 - Auto connection of external subtitles and sound, using the "WEBDAV" protocol. The connection is explicit due to explicitly specifying folders on the WebDAV server.
* [autoselect-forced-sub](https://github.com/pierretom/autoselect-forced-sub) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2025-05-30 - Automatically select forced subtitles in a different way.
* [sub](https://github.com/yassin-l/submpv) ⚠️ Archived - Python script to automate downloading and loading subtitle from subscence.
* [rename-sub](https://github.com/ayghub/rename-sub) ⭐ 2 | 🐛 1 | 🌐 Lua | 📅 2024-01-31 - Rename current subtitle file as the playing video.
* [sub](https://github.com/vflorelle/mpv-scripts#sub) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2020-03-08 - Select subtitle by id via input box (Windows)
* [subber](https://framagit.org/Midgard/mpv-subber) - Write subtitles in mpv.

## Learning

* [mpvacious](https://github.com/Ajatt-Tools/mpvacious) ⭐ 880 | 🐛 12 | 🌐 Lua | 📅 2026-08-16 - Add keybindings to create Anki flashcards for (language) learning.
* [interSubs](https://github.com/oltodosel/interSubs) ⭐ 264 | 🐛 3 | 🌐 Python | 📅 2025-03-18 - Interactive subtitles, instantly translate selected word/sentence.
* [subs2srs](https://github.com/kelciour/mpv-scripts/blob/master/subs2srs.lua) ⚠️ Archived - Automatically add new card in Anki with audio, picture and text.
* [sub-voracious](https://github.com/kelciour/mpv-scripts/blob/master/sub-voracious.lua) ⚠️ Archived - Reading and listening practice.
* [immersive](https://github.com/Ben-Kerman/immersive) ⭐ 94 | 🐛 5 | 🌐 Lua | 📅 2024-04-25 - Looking up words generating Anki flashcards.
* [lang-learner](https://github.com/liberlanco/mpv-lang-learner) ⭐ 47 | 🐛 0 | 🌐 Lua | 📅 2025-07-08 - Turn MPV into language learner tool. Includes:  AB-loop current subtitle or auto loop each one, quick switch between lang you know and lang you are learning, forward to browser (dictionaries, translators), record for future extra learning, export to external script for integrations, and a bit more.
* [rikai](https://github.com/fxmarty/rikai-mpv) ⭐ 46 | 🐛 5 | 🌐 TypeScript | 📅 2022-10-26 - Integrated Japanese dictionary and parser to translate by hovering over words. Works on Linux.
* [mpv2anki SenneH](https://github.com/SenneH/mpv2anki) ⭐ 25 | 🐛 2 | 🌐 Lua | 📅 2021-05-28 - A simple way to add notes to Anki with Audio, screenshots and/or subtitles, with few dependencies.
* [migaku](https://github.com/migaku-official/migaku-mpv) ⭐ 24 | 🐛 9 | 🌐 Python | 📅 2023-01-14 - Learn languages together with the Migaku browser extension.
* [mpv2anki alyssabedard](https://github.com/alyssabedard/mpv2anki) ⭐ 19 | 🐛 0 | 🌐 Lua | 📅 2025-10-26 - (Different script with Windows, macOS and Linux support) A simple script to assist your language learning journey in any language by automatically capturing multimedia content from mpv to Anki.
* [Yomichampv](https://github.com/laelnasan/yomichampv) ⭐ 11 | 🐛 3 | 🌐 Lua | 📅 2020-11-13 - A simple solution for integration with Yomichan - a browser-based japanese dictionay.
* [mpv-Subtitle-Definition](https://github.com/tripasect/mpv-Subtitle-Definition) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-02-06 - Instant, on-screen definitions for difficult or obscure words found in subtitles.

## Music

* [lrc](https://github.com/guidocella/mpv-lrc) ⭐ 38 | 🐛 0 | 🌐 Lua | 📅 2026-04-16 - Download synchronized lyrics of the currently playing song.
* [metadata-osd](https://github.com/vc-01/metadata-osd) ⭐ 26 | 🐛 0 | 🌐 Lua | 📅 2026-01-09 - Adds OSD showing song name, album name and other metadata.
* [coverart](https://github.com/CogentRedTester/mpv-coverart) ⭐ 21 | 🐛 4 | 🌐 Lua | 📅 2023-08-08 - Automatically loads external cover art for music files.

## Audio

* [acompressor](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/acompressor.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Dynamic range compressor using acompressor ffmpeg filter with controls to dynamically adjust parameters.
* [smart-volume](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Replay gain alternative.
* [visualizer](https://github.com/mfcc64/mpv-scripts/blob/master/visualizer.lua) ⭐ 207 | 🐛 19 | 🌐 Lua | 📅 2025-11-07 - Various audio visualizations.
* [firequalizer15](https://github.com/mfcc64/mpv-scripts/blob/master/firequalizer15.lua) ⭐ 207 | 🐛 19 | 🌐 Lua | 📅 2025-11-07 - Linear phase 15-bands equalizer.
* [adevice-list](https://github.com/dyphire/mpv-scripts/blob/main/adevice-list.lua) ⭐ 123 | 🐛 1 | 🌐 Lua | 📅 2026-08-17 - Interractive audio-device list menu.
* [audio-balance](https://github.com/wiiaboo/mpv-scripts/blob/master/audio-balance.lua) ⭐ 97 | 🐛 3 | 🌐 Lua | 📅 2020-09-19 - Port of mpv's balance property to FFmpeg lavfi pan filter.
* [aspeed.lua](https://github.com/TinosNitso/mpv-scripts/blob/main/aspeed.lua) ⭐ 18 | 🐛 1 | 🌐 Lua | 📅 2024-10-05 - Multi-stereo speed randomization & tri-color clocks. Applies arbitrary speed formula & has chipmunk mode for left-channel. Also has double-mute insta-toggle. Primary channel may be left or right. A filterchain applies to all speakers - each is its own mpv. Has many script-messages.  For mpv v0.34→v0.38, SMPlayer, Windows, Linux, MacOS, Android, YouTube, mp4, mp3, jpg, etc. But no randomization for Android. ([Example](https://raw.githubusercontent.com/TinosNitso/mpv-scripts/main/SCREENSHOT.webp) clock).
* [afilter](https://github.com/he2a/mpv-scripts) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2026-02-26 - Script for easy access to certain audio compressors and HRTF sofalizer in mpv with option to whitelist filters based on type of media.
* [pitchcontrol](https://github.com/FichteFoll/mpv-scripts/blob/master/pitchcontrol.lua) ⭐ 10 | 🐛 1 | 🌐 Lua | 📅 2024-11-21 - Adjusts audio pitch in half-tone steps.
* [ff-silence](https://github.com/mesvam/ff-silence) ⭐ 8 | 🐛 1 | 🌐 Lua | 📅 2026-07-11 - Fast forward through silences and quiet parts of audio, useful on videos where the speaker uses many long pauses.
* [Open Sound Control](https://github.com/lvm/mpv-osc) ⭐ 6 | 🐛 0 | 🌐 Lua | 📅 2019-01-21 - Open Sound Control listener.
* [Audio WebDAV & Sub WebDAV](https://github.com/Kibakus/mpv-scripts) ⭐ 6 | 🐛 0 | 🌐 Lua | 📅 2025-06-17 - Auto connection of external subtitles and sound, using the "WEBDAV" protocol. The connection is explicit due to explicitly specifying folders on the WebDAV server.
* [switch-both-audio](https://github.com/70sh1/mpv-switch-both-audio) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2024-04-05 - Switch between playing one or two audio tracks simultaneously upon file load or with a hotkey.
* [volnorm](https://gitlab.com/derobert/mpv-volnorm) - Client-server setup to provide EBU R.128 volume leveling to MPV, even if files stored on a server and played on multiple machines. (Works on Linux, probably all Unix-like; server in Perl).
* [drcbox](https://gist.github.com/richardpl/0c8011dc23d7ac7b7831b2e6d680114f) - Dynamic Audio Normalizer filter with visual feedback.
* [dbvol](https://gist.github.com/Artefact2/0a9c87d6d0f0ef6a565e44d830943fff) - Replaces the default volume controls with a decibel (dB) scale instead of arbitrary percentages.
* [cycle-audio-device](https://gist.github.com/bitingsock/ad58ee5da560ecb922fa4a867ac0ecfd) - Cycle through available audio devices with key binds.
* [channel mixer](https://gist.github.com/bitingsock/1e7ef04a151963b38e347a723d7e3201) - A set of keybindings using a modifier (Shift or Ctrl) and the function keys (F8-F12) to can adjust the mixing level of surround channels on the fly.
* [audio-dupe](https://gist.github.com/bitingsock/5e9714efff963c9689b0671d68f195ad) - Runs a child process to play a second audio stream. Synced through named pipe.
* [cycle-adevice](https://gist.github.com/bitingsock/ad58ee5da560ecb922fa4a867ac0ecfd) - Cycle through available audio devices.
* [Sofalizer](https://gist.github.com/kevinlekiller/9fd21936411d8dc5998793470c6e3d16#file-sofalizer-lua) - Simulates 7.1 surround sound to your headset. Get the sofa file from [here](https://sofacoustics.org/data/database/clubfritz/ClubFritz6.sofa)

## Streaming

* [sponsorblock](https://github.com/po5/mpv_sponsorblock) ⭐ 628 | 🐛 29 | 🌐 Lua | 📅 2024-05-01 - Script to skip sponsored segments of YouTube videos.
* [youtube-search](https://github.com/CogentRedTester/mpv-scripts/blob/master/youtube-search.lua) ⭐ 300 | 🐛 4 | 🌐 Lua | 📅 2026-01-11 - A script that allows users to search youtube and open results from within mpv. Requires a couple of extra API scripts, along with curl and a personal youtube API key.
* [quality-menu](https://github.com/christoph-heinrich/mpv-quality-menu) ⭐ 235 | 🐛 3 | 🌐 Lua | 📅 2026-01-30 - Change the streamed video and audio quality (ytdl-format) on the fly.
* [streamsave](https://github.com/Sagnac/streamsave) ⭐ 128 | 🐛 2 | 🌐 Lua | 📅 2024-07-19 - Save live streams without encoding.
* [webtorrent-hook](https://github.com/noctuid/mpv-webtorrent-hook) ⭐ 128 | 🐛 8 | 🌐 Lua | 📅 2026-02-20 - Allows streaming torrents using webtorrent (same as mpv-peerflix-hook but using webtorrent instead). Webtorrent-cli can play in mpv with `webtorrent --mpv`, but this script allows using torrent identifiers as the file argument to mpv or pasting them into the current playlist using one of the pasting scripts listed here. It also supports additional functionality like automatic file cleanup and the ability to remember the last file played in the torrent. See the readme for more information. See [here](https://github.com/noctuid/mpv-webtorrent-hook#comparison-with-webtorrent-mpv-hook) ⭐ 128 | 🐛 8 | 🌐 Lua | 📅 2026-02-20 for a comparison with the other javascript webtorrent plugin. I recommend this plugin over my others (mpv-peerflix-hook and btfs-stream).
* [play-with](https://github.com/grmat/play-with) ⭐ 105 | 🐛 4 | 🌐 JavaScript | 📅 2020-05-28 - A web browser extension that can open a video stream on a web page with an external player.
* [youtube-download](https://github.com/cvzi/mpv-youtube-download) ⭐ 104 | 🐛 2 | 🌐 Lua | 📅 2023-10-17 - Download YouTube audio and video with one key press.
* [mpvDLNA](https://github.com/chachmu/mpvDLNA) ⭐ 85 | 🐛 9 | 🌐 JavaScript | 📅 2024-08-18 - Browse and watch content hosted on DLNA servers.
* [youtube-upnext](https://github.com/cvzi/mpv-youtube-upnext) ⭐ 81 | 🐛 6 | 🌐 Lua | 📅 2026-07-20 - A menu for (auto) playing YouTube's "up next"/recommended videos, that show up on the right side on the website.
* [jellyfin](https://github.com/EmperorPenguin18/mpv-jellyfin) ⭐ 73 | 🐛 5 | 🌐 Lua | 📅 2026-03-22 - Turns mpv into a Jellyfin client.
* [ytdlautoformat](https://github.com/Samillion/mpv-ytdlautoformat) ⭐ 58 | 🐛 0 | 🌐 Lua | 📅 2026-04-10 - Automatically adjusts `ytdl-format` (yt-dlp) for specified domains.
* [acestream](https://github.com/Digitalone1/mpv-acestream) ⭐ 47 | 🐛 5 | 🌐 Lua | 📅 2025-01-08 - Add AceStream protocol handler to mpv. Let the user open streams by dropping Acestream links into mpv GUI or by passing them as command line argument.
* [selectformat](https://github.com/ghesy/mpv-selectformat) ⭐ 36 | 🐛 0 | 🌐 Lua | 📅 2025-12-11 - Select the format (quality) of internet videos.
* [show-stream-title](https://github.com/blue-sky-r/mpv/blob/master/scripts/show-stream-title.lua) ⭐ 29 | 🐛 2 | 🌐 Lua | 📅 2021-02-09 - Show OSD stream/channel title when switching the IPTV channels from m3u playlist.
* [youtube-search](https://github.com/rozari0/mpv-youtube-search) ⭐ 27 | 🐛 1 | 🌐 Lua | 📅 2025-12-12 - Use zenity and youtube-dl to search YouTube. Linux only.
* [ytdl-preload](https://github.com/bitingsock/ytdl-preload) ⭐ 20 | 🐛 6 | 🌐 Lua | 📅 2026-08-20 - Precache the next entry in your playlist if it is a network source by downloading it to a temp file ahead of time. Updated to download all streams in parallel so you can watch it while it downloads.
* [mpvf](https://github.com/seanbreckenridge/mpvf) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2024-11-12 - Select youtube-dl format for streaming.
* [youtube-queue](https://github.com/ksyasuda/mpv-youtube-queue) ⭐ 18 | 🐛 0 | 🌐 Lua | 📅 2026-03-09 - Implements the YouTube 'Add to Queue' functionality. Allows adding video urls to the queue from the clipboard, and provides a menu for interacting with the queue.
* [btfs-stream](https://github.com/noctuid/mpv-btfs-stream) ⭐ 17 | 🐛 1 | 🌐 Lua | 📅 2021-07-16 - Allows streaming torrents using btfs. As far as I can tell, it is much simpler than the above scripts (no long shell script execution) and much more configurable (the other scripts have no settings). This is much slower than using webtorrent though, so I recommend using webtorrent-hook instead.
* [reduce\_stream\_cache](https://github.com/divout/mpv_reduce_stream_cache) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-02 - Reduces MPV cache for streams by increasing playback speed. Works with Twitch through Streamlink.
* [confluence](https://github.com/ftk/mpv-confluence) ⭐ 12 | 🐛 3 | 🌐 Lua | 📅 2023-11-19 - Open magnet links using [confluence](https://github.com/anacrolix/confluence) ⭐ 264 | 🐛 6 | 🌐 Go | 📅 2025-07-23 HTTP service. Recommended to use [modified script](https://github.com/ftk/mpv-confluence/tree/torrserver) ⭐ 12 | 🐛 3 | 🌐 Lua | 📅 2023-11-19 for [TorrServer](https://github.com/YouROK/TorrServer) ⭐ 2,969 | 🐛 33 | 🌐 Go | 📅 2026-08-17 instead.
* [spotify](https://github.com/olivierlemoal/mpv-spotify-script) ⚠️ Archived - Add current playing title to an user defined Spotify playlist.
* [btfs-hook](https://github.com/aitet/mpv-btfs-hook) ⭐ 10 | 🐛 1 | 🌐 Lua | 📅 2023-08-06 - Allows streaming torrents using FUSE via btfs.
* [peerflix-hook](https://github.com/noctuid/mpv-peerflix-hook) ⚠️ Archived - Stream magnet links in mpv with peerflix.
* [torrserver](https://github.com/kritma/mpv-torrserver) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2024-02-05 - Allows streaming torrents using [TorrServer](https://github.com/YouROK/TorrServer) ⭐ 2,969 | 🐛 33 | 🌐 Go | 📅 2026-08-17. Support magnet links and .torrent files
* [last.fm scrobbler](https://github.com/MugoSquero/mpv_scrobbler) ⭐ 8 | 🐛 2 | 🌐 Lua | 📅 2025-07-25 - Sends the information about playing tracks to [last.fm](http://last.fm/), see <http://www.last.fm/help/faq?category=99> for more info.
* [torrserver-hook](https://github.com/eNV25/mpv-torrserver-hook) ⭐ 6 | 🐛 0 | 🌐 Lua | 📅 2026-06-07 - Allows for playback of media from the BitTorrent network using [TorrServer](https://github.com/YouROK/TorrServer) ⭐ 2,969 | 🐛 33 | 🌐 Go | 📅 2026-08-17.
* [yledl](https://github.com/pekkarr/mpv-yledl) ⭐ 6 | 🐛 1 | 🌐 Lua | 📅 2021-05-14 - Watch videos from YLE Areena in mpv using yle-dl
* [sopcast](https://github.com/Akemi/mpv-sopcast-hook) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2017-01-23 - Adds support for sop\:// urls.
* [sponsorblock\_minimal](https://codeberg.org/jouni/mpv_sponsorblock_minimal) - More simple version of the sponsorblock script.
* [streamcache](https://gitlab.com/lvml/mpv-plugin-streamcache) - Provides for more network-glitch-robust caching of live streams by adjusting replay speed.
* [stopCache](https://gist.github.com/bitingsock/19c3094cc8680bb7b97b09aaf7d11176) - stops the demuxer from downloading more if it is already past --end
* [peerflix-hook](https://gist.github.com/ekisu/bba287693830055a6bad90081c1ad4e2) - Allows streaming of magnet links using peerflix, similar to youtube-dl.
* [http-ytproxy](https://gist.github.com/ftk/253347b2c9a53bbd6087f086970106b6) - Simple MitM http proxy to modify Range http headers. Can be used to speed up youtube videos.
* [torrserver-browser](https://codeberg.org/m45k/torrserver-browser) - This script lets you search and play torrents from Rutor via TorrServer directly in mpv, without using a browser or external applications. The search is bound to the f key inside mpv and uses a user input module to get text from the keyboard. The M key opens the main script UI, showing everything that has already been added to your TorrServer, with support for launching torrent files and magnet links without any additional Lua scripts.

## Video

* [autocrop](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autocrop.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Automatically crop the video by using lavfi's cropdetect filter to detect black bars.
* [autodeint](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autodeint.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Automatically deinterlace the video by using lavfi's idet filter to detect interlaced content.
* [cycle-deinterlace-pullup](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/cycle-deinterlace-pullup.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Cycle between deinterlacing, pullup (IVTC), and both filters off.
* [use-cpu](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/use-cpu.lua) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12 - If the width of the video is greater than 3000 or the height of the video is greater than 2000, it will automatically switch back to using cpu decoding.
* [crop](https://github.com/occivink/mpv-scripts#croplua) ⭐ 491 | 🐛 43 | 🌐 Lua | 📅 2025-11-01 - Crop the video by defining the target rectangle with the cursor.
* [blur-edges](https://github.com/occivink/mpv-scripts#blur-edgeslua) ⭐ 491 | 🐛 43 | 🌐 Lua | 📅 2025-11-01 - Replace black bars with a blurry copy of the video.
* [cycle-video-rotate](https://github.com/VideoPlayerCode/mpv-tools/) ⭐ 192 | 🐛 3 | 🌐 JavaScript | 📅 2021-07-07 - Allows you to perform video rotation which perfectly cycles through all 360 degrees without any glitches.
* [dynamic-crop](https://github.com/Ashyni/mpv-scripts#dynamic-croplua) ⭐ 132 | 🐛 5 | 🌐 Lua | 📅 2024-09-14 - Dynamically crop the video by using lavfi's cropdetect filter to detect hard-coded black bars for Ultra Wide Screen (21:9) or any screen different from 16:9 (phone/old TV).
* [hdr-mode](https://github.com/dyphire/mpv-scripts/blob/main/hdr-mode.lua) ⭐ 123 | 🐛 1 | 🌐 Lua | 📅 2026-08-17 - Automatically switches the display's SDR and HDR modes for HDR passthrough based on the content of the video being played.
* [store-shaders](https://github.com/butterw/bShaders/blob/master/mpv/settings/scripts/store-shaders.js) ⭐ 110 | 🐛 3 | 🌐 HLSL | 📅 2024-01-19 - Store current glsl-shaders config on first run, this config will then be restored by subsequent calls.
* [switch-shader](https://github.com/butterw/bShaders/blob/master/mpv/settings/scripts/switch-shader.js) ⭐ 110 | 🐛 3 | 🌐 HLSL | 📅 2024-01-19 - Provides a switch to disable/restore shaders and vf filters.
* [mpv360](https://github.com/kasper93/mpv360) ⭐ 75 | 🐛 3 | 🌐 Lua | 📅 2026-01-30 - Interactive 360° Video Viewer. With full camera control through mouse and keyboard inputs.
* [autospeed](https://github.com/kevinlekiller/mpv_scripts/blob/master/autospeed/) ⭐ 72 | 🐛 9 | 🌐 Lua | 📅 2018-08-26 - Adjusts the display refresh rate and video speed for almost 1:1 playback (Unix-like OSes, Xorg / X11).
* [autospeedwin](https://github.com/kevinlekiller/mpv_scripts/tree/master/autospeedwin) ⭐ 72 | 🐛 9 | 🌐 Lua | 📅 2018-08-26 - Adjusts the display refresh rate and video speed for almost 1:1 playback (Windows).
* [histogram](https://github.com/detuur/mpv-scripts) ⭐ 66 | 🐛 6 | 🌐 Lua | 📅 2023-08-27 - Exposes a configurable way to overlay ffmpeg histograms in mpv. There is a substantial amount of config available.
* [live-filters](https://github.com/hdb/mpv-live-filters) ⭐ 55 | 🐛 0 | 🌐 Lua | 📅 2020-12-23 - Add, remove or toggle ffmpeg video filters during mpv playback.
* [changerefresh](https://github.com/CogentRedTester/mpv-changerefresh) ⭐ 50 | 🐛 4 | 🌐 Lua | 📅 2024-03-05 - Automatically change the refresh rate of the current display to match the playing video (Windows).
* [cropmode](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/cropmode.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - Adds a keyboard-oriented mode for cropping, outputting the result in a format suitable for ffmpeg.
* [pickshader](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/pickshader.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - Provides a ^R-esque interface for easily setting/appending to --glsl-shaders (this does not install shaders for you).
* [vlcaspectratio](https://github.com/kism/mpvscripts/blob/main/scripts/vlcaspectratio.lua) ⭐ 28 | 🐛 0 | 🌐 Lua | 📅 2025-09-09 - Implements a VLC style aspect ratio hotkey 'a' that stretches the video to different aspect ratios.
* [vlccrop](https://github.com/kism/mpvscripts/blob/main/scripts/vlccrop.lua) ⭐ 28 | 🐛 0 | 🌐 Lua | 📅 2025-09-09 - Implements a VLC style crop hotkey 'c' that cycles through crop settings, useful for cropping letter-boxed or pillar-boxed content.
* [frame\_info](https://github.com/Kagami/mpv_frame_info) ⭐ 23 | 🐛 1 | 🌐 Lua | 📅 2017-10-12 - Show frame info, similar to ffdshow's OSD.
* [autocrop.lua](https://github.com/TinosNitso/mpv-scripts/blob/main/autocrop.lua) ⭐ 18 | 🐛 1 | 🌐 Lua | 📅 2024-10-05 - Modded version randomizes aspect ratio & crops black bars off videos & images while maintaining center in horizontal & vertical. Double-mute toggles the crop & auto\_aspect. Has tolerance options, & varies limit (& start/end limits) with media-title. Can display all cropdetect or bbox metadata. Handles transparent input.  For mpv v0.34→v0.38, SMPlayer, Windows, Linux, MacOS, Android, YouTube, mp4, mp3, jpg, etc. [Example](https://raw.githubusercontent.com/TinosNitso/mpv-scripts/main/SCREENSHOT.webp) of auto\_aspect btwn 16:9 & 4:3.
* [autocomplex.lua](https://github.com/TinosNitso/mpv-scripts/blob/main/autocomplex.lua) ⭐ 18 | 🐛 1 | 🌐 Lua | 📅 2024-10-05 - Accurate stereo spectrum overlay, with volume bars. Has many options for showfreqs, showvolume, moving overlays, colormixes, normalizers, interpolation, etc. Easy to distinguish stereo from mono.  Has many script-messages. For mpv v0.34→v0.38, SMPlayer, Windows, Linux, MacOS, Android, YouTube, mp4, mp3, etc.  [Example](https://github.com/TinosNitso/mpv-scripts/releases/download/v1.5.5/SCREENSHOT.webp) ⭐ 18 | 🐛 1 | 🌐 Lua | 📅 2024-10-05 of dual-complex.
* [automask.lua](https://github.com/TinosNitso/mpv-scripts/blob/main/automask.lua) ⭐ 18 | 🐛 1 | 🌐 Lua | 📅 2024-10-05 - Applies filterchain to animated masked region with inversion (blinking) & invisibility. `geq` uses any formula. Smooth toggle with double-mute. Comes with 14 examples, including blinking monacle, binacles, pentagon, spinning triangle, scanning visors etc. Has many script-messages.  For mpv v0.34→v0.38, SMPlayer, Windows, Linux, MacOS, Android, YouTube, mp4, mp3, jpg, etc. [Example](https://raw.githubusercontent.com/TinosNitso/mpv-scripts/main/SCREENSHOT.webp) mask.
* [display-plugin](https://github.com/dyphire/mpv-display-plugin) ⭐ 18 | 🐛 0 | 🌐 C | 📅 2025-05-26 - More display properties for mpv, support toggle Windows HDR.
* [BoxToWide](https://github.com/Samillion/mpv-boxtowide) ⭐ 13 | 🐛 0 | 🌐 Lua | 📅 2026-02-25 - A simple mpv script to change 4:3 aspect-ratio of video files/streams to 16:9 automatically.
* [sview](https://github.com/he2a/mpv-scripts) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2026-02-26 - Displays all loaded shaders in a clean format. It suppresses the default OSD message, allowing the custom list to be viewed by toggling it or when changing shaders.
* [mvtools-script](https://github.com/maoiscat/mpv-mvtools-script) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-02-22 - vapoursynth-mvtools script.
* [waveform](https://github.com/MikelSotomonte/mpv-waveform/tree/main) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2023-02-02 - Displays a waveform of the video in real-time.
* [if](https://github.com/layercak3/mpvif) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2025-09-26 - A wayland VO patch and C plugin which forwards keyboard and mouse input to a headless compositor for playing 2D games with upscaling mpv user shaders.
* [gpufreq](https://github.com/CounterPillow/mpv-gpufreq) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2020-05-21 - Displays the current and maximum GPU frequency as an osd message.
* [matroska-crop](https://github.com/sbruder/mpv-matroska-crop) ⚠️ Archived - Automatically crop video using the Matroska PixelCrop properties. Includes optional workaround for hardware decoding.
* [delogo](https://github.com/GitHubUserKaito/mpv-delogo) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2016-06-26 - Remove channel logo from videos.
* [Fast Catmull-Rom](https://github.com/garamond13/Fast-Catmull-Rom) ⭐ 0 | 🐛 0 | 🌐 GLSL | 📅 2025-10-27 - Fast Catmull-Rom approximation using 5 samples by omitting corners.
* [xrandr](https://gitlab.com/lvml/mpv-plugin-xrandr) - Automatically sets the display refresh rate to the one best suitable for the video played
* [mpv-kscreen-doctor](https://gitlab.com/smaniottonicola/mpv-kscreen-doctor) - Like the xrandr script automatically sets the display refresh rate to the one best suitable for the video played, works for KDE Plasma Wayland sessions.
* [filter-test](https://gitlab.com/mozbugbox/mpv-script-mozbugbox) - Test mpv/FFmpeg video filter(vf) strings with editable popup dialog.
* [cycle-denoise](https://gist.github.com/myfreeer/d744c445aa71c0eeb165ca39cf6c0511) - Cycle between lavfi's denoise filters (press n)
* [curvesman](https://gitlab.com/mozbugbox/mpv-script-mozbugbox) - Manipulate color curves filter of FFmpeg with hotkeys. Brighten up color, change color temperature/tone, hopefully more. Adjust yellow light tone to white light tone.

## Image

* [thumbfast](https://github.com/po5/thumbfast) ⭐ 1,673 | 🐛 55 | 🌐 Lua | 📅 2026-08-12 - High-performance on-the-fly thumbnailer for mpv.
* [image-viewer](https://github.com/occivink/mpv-image-viewer) ⭐ 363 | 🐛 18 | 🌐 Lua | 📅 2024-11-23 - Configuration, scripts and tips for using mpv as an image viewer.
* [contact-sheet](https://github.com/occivink/mpv-gallery-view) ⭐ 257 | 🐛 26 | 🌐 Lua | 📅 2024-09-27 - Display thumbnails of the current file in the style of a contact sheet.
* [auto-mode](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Use mpv as video player, music player and image viewer, switch automatically between, video, audio and image mode.
* [screenshotfolder](https://github.com/zydezu/mpvconfig/blob/main/scripts/screenshotfolder.lua) ⭐ 107 | 🐛 1 | 🌐 Lua | 📅 2026-08-25 - Place screenshots into folders for each video, along with timestamping them.
* [crop\_script](https://github.com/TheAMM/mpv_crop_script) ⭐ 101 | 🐛 3 | 🌐 Python | 📅 2020-02-21 - Take cropped screenshots.
* [clipshot](https://github.com/ObserverOfTime/mpv-scripts/blob/master/clipshot.lua) ⭐ 54 | 🐛 1 | 🌐 Lua | 📅 2025-06-28 - Screenshot the video (with subs, without subs or the whole window) and copy it to the clipboard. For Windows, Linux/BSD and MacOs
* [gif-generator](https://github.com/the-honey/mpv-gif-generator) ⭐ 54 | 🐛 8 | 🌐 Lua | 📅 2022-01-26 - Creates animated gifs using hotkeys.
* [gallery-dl\_hook](https://github.com/jgreco/mpv-scripts/blob/master/gallery-dl_hook.lua) ⭐ 47 | 🐛 3 | 🌐 Lua | 📅 2019-10-10 - Load online image galleries (imgur, etc) as playlists using [gallery-dl](https://github.com/mikf/gallery-dl/) ⭐ 19,331 | 🐛 1,149 | 🌐 Python | 📅 2026-08-01.
* [screenshot-mosaic](https://github.com/noaione/mpv-js-scripts) ⭐ 42 | 🐛 4 | 🌐 TypeScript | 📅 2026-05-22 - Create a mosaic/thumbnail image.
* [screenshot-to-clipboard](https://github.com/zc62/mpv-scripts/blob/master/screenshot-to-clipboard.js) ⭐ 41 | 🐛 0 | 🌐 Lua | 📅 2020-08-28 - Takes a screenshot and saves it to the clipboard.
* [waifu2x](https://github.com/jonniek/mpv-waifu2x) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2019-11-17 - Take screenshot and convert images with waifu2x.
* [image-config](https://github.com/guidocella/mpv-image-config) ⭐ 34 | 🐛 0 | 🌐 Lua | 📅 2026-03-14 - A configuration to use mpv as an image viewer.
* [gallery-dl-view](https://github.com/noctuid/gallery-dl-view) ⭐ 26 | 🐛 1 | 🌐 Clojure | 📅 2026-03-19 - Load image galleries directly in mpv like gallery-dl\_hook but with extra functionality like binding a key to download images, optionally only loading images that are new since the gallery was last opened, and more.
* [webp-avif-generator](https://github.com/outlook84/mpv-webp-avif-generator) ⭐ 18 | 🐛 0 | 🌐 Lua | 📅 2026-05-01 - Creates animated webp/avif using mpv A-B loop and FFmpeg. (Support Windows and Linux)
* [webp-generator](https://github.com/DonCanjas/mpv-webp-generator) ⭐ 16 | 🐛 2 | 🌐 Lua | 📅 2022-04-28 - Creates animated webp using mpv hotkeys. (Windows only)
* [takeSsSequence](https://github.com/Arieleg/mpv-takeSsSequence) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2019-11-30 - Take a sequence of equispaced screenshots.
* [gallery-screenshots](https://github.com/XeinyX/mpv_gallery-screenshots) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2025-09-22 - In‑player tiled screenshot gallery that turns your screenshots into visual bookmarks for fast navigation. Click thumbnails to jump instantly. Export screenshots to contact sheets (PNG), CSV, and Excel table XLSX.
* [abs-screenshot](https://github.com/Thann/mpv-abs-screenshot/blob/master/abs-screenshot.lua) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2020-02-26 - Uses Exiftool to get the "Date/Time Original" and saves a screenshot with the name being the actual time the video was taken.
* [sorted-screenshots](https://github.com/BanchouBoo/mpv-sorted-screenshots) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2025-03-06 - Sort screenshots based on the file they're screenshotted from and nested directories.

## Video Editing

* [videoclip](https://github.com/Ajatt-Tools/videoclip) ⭐ 196 | 🐛 7 | 🌐 Lua | 📅 2026-07-30 - Create video and audio clips.
* [sub-cut](https://github.com/kelciour/mpv-scripts/blob/master/sub-cut.lua) ⚠️ Archived - Extract a part of the video as audio or video with subtitles.
* [cut zydezu](https://github.com/zydezu/mpvconfig/blob/main/scripts/mpvcut.lua) ⭐ 107 | 🐛 1 | 🌐 Lua | 📅 2026-08-25 - Easily clip, compress and re-encode selected clips.
* [trim](https://github.com/aerobounce/trim.lua) ⭐ 102 | 🐛 3 | 🌐 Lua | 📅 2024-05-20 - Trim clips without transcoding.
* [easycrop](https://github.com/aidanholm/mpv-easycrop) ⭐ 87 | 🐛 4 | 🌐 Lua | 📅 2018-01-23 - Cropping videos with ease.
* [slicing](https://github.com/Kagami/mpv_slicing) ⭐ 86 | 🐛 8 | 🌐 Lua | 📅 2024-04-12 - Cut uncompressed fragments of the video.
* [video-splice](https://github.com/pvpscript/mpv-video-splice) ⭐ 70 | 🐛 1 | 🌐 Lua | 📅 2024-04-30 - Create a video out of cuts.
* [Pure](https://github.com/4ndrs/PureMPV) ⭐ 47 | 🐛 1 | 🌐 TypeScript | 📅 2024-08-17 - Get the file path, timestamps, and cropping coordinates for ffmpeg.
* [slicing\_copying](https://github.com/snylonue/mpv_slicing_copy) ⭐ 41 | 🐛 7 | 🌐 Lua | 📅 2023-12-04 - Cut fragments of video in original format.
* [cut b1scoito](https://github.com/b1scoito/mpv-cut) ⭐ 15 | 🐛 8 | 🌐 Lua | 📅 2022-09-15 - Video cutting/clipping/slicing script.
* [clipper](https://github.com/lunagus/mpv-clipper) ⭐ 6 | 🐛 2 | 🌐 Lua | 📅 2025-08-15 - Quickly trim videos using ffmpeg within mpv.
* [excerpt](https://gitlab.com/lvml/mpv-plugin-excerpt) - Allows you to quickly create excerpts from media files, you just have to set begin and end markers.

## Social

* [discord](https://github.com/tnychn/mpv-discord) ⚠️ Archived - A cross-platform Discord Rich Presence integration for mpv with no external dependencies. Consists of a Go binary for updating the presence and a Lua script for launching it.
* [discordRPC](https://github.com/cniw/mpv-discordRPC) ⭐ 163 | 🐛 15 | 🌐 Lua | 📅 2022-08-08 - Discord Rich Presence integration.
* [twitch-chat](https://github.com/CrendKing/mpv-twitch-chat/) ⭐ 101 | 🐛 0 | 🌐 Lua | 📅 2026-07-02 - Show Twitch chat messages as subtitles when watching Twitch VOD with mpv.
* [discordRPC](https://github.com/noaione/mpv-discordRPC) ⭐ 63 | 🐛 3 | 🌐 Lua | 📅 2023-02-27 - Discord RPC integration for mpv using lua-discordRPC as base.
* [youtube-chat](https://github.com/BanchouBoo/mpv-youtube-chat) ⭐ 59 | 🐛 5 | 🌐 Lua | 📅 2024-06-08 - Overlays YouTube chat on top of a video using yt-dlp.
* [mpv-rpc](https://github.com/ryze312/mpv-rpc) ⚠️ Archived - Discord Rich Presence integration. Also displays cover art from MusicBrainz archive.
* [twitch-chat-irc](https://github.com/morrah/mpv-twitch-chat-irc) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2024-03-03 - Show Twitch chat messages as subtitles when watching Twitch LIVE.
* [cord](https://github.com/yutotakano/mpvcord) ⭐ 16 | 🐛 6 | 🌐 Lua | 📅 2021-09-27 - Discord integration for mpv, using the Game SDK instead of Discord RPC. Supports: MacOS and Windows. (Linux is not supported by Game SDK)
* [irc](https://github.com/po5/mpv_irc) ⭐ 9 | 🐛 2 | 🌐 Lua | 📅 2020-09-29 - Displays lines from an irc channel.
* [LoadDanmaku](https://github.com/huisedenanhai/LoadDanmaku) ⭐ 5 | 🐛 1 | 🌐 Lua | 📅 2020-02-24 - Load local damaku files.

## Configuration

* [auto-keep-gui-open](https://github.com/VideoPlayerCode/mpv-tools/) ⭐ 192 | 🐛 3 | 🌐 JavaScript | 📅 2021-07-07 - Intelligently switches mpv's "keep-open" behavior based on whether you are running in video-mode or audio-only mode.
* [persist-properties](https://github.com/d87/mpv-persist-properties) ⭐ 99 | 🐛 1 | 🌐 Lua | 📅 2022-11-15 - Keep selected property values (like volume) between player sessions.
* [remember-props](https://github.com/zenwarr/mpv-config/blob/master/scripts/remember-props.lua) ⭐ 35 | 🐛 3 | 🌐 Lua | 📅 2025-11-16 - When a property changes, it saves it to restore on next start. Saved values are not file-specific. List of properties to save is configured in `script-opts/remember-props.conf` file.
* [celebi](https://github.com/po5/celebi) ⭐ 15 | 🐛 3 | 🌐 Lua | 📅 2023-10-28 - An optimized script to restore properties from past sessions. Alternative to persist-properties and remember-props scripts.
* [config-saver](https://github.com/Static39/mpv-scripts/tree/main/config-saver) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2022-10-04 - Saves current audio track, subtitle track, subtitle position, etc. for all videos in the folder.
* [cycle-through-existing](https://github.com/viniciusbm/mpv-cycle-through-existing) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2025-01-10 - Cycle through existing video/audio/subtitle tracks, skipping the "none" option.
* [show-conf-osd](https://github.com/pierretom/show-conf-osd) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2025-05-25 - Display configuration files on the OSD.

## Library

* [extended-menu](https://github.com/Seme4eg/mpv-scripts/tree/master/script-modules) ⭐ 74 | 🐛 1 | 🌐 Lua | 📅 2026-02-24 - API to create a searchable menu (command palette).
* [osc-framework](https://github.com/maoiscat/mpv-osc-framework) ⭐ 59 | 🐛 1 | 🌐 Lua | 📅 2026-08-23 - OSC framework to help build your custom OSC.
* [user-input](https://github.com/CogentRedTester/mpv-user-input) ⭐ 57 | 🐛 1 | 🌐 Lua | 📅 2023-12-27 - API to request text user input.
* [scroll-list](https://github.com/CogentRedTester/mpv-scroll-list) ⭐ 48 | 🐛 3 | 🌐 Lua | 📅 2025-01-10 - API to create interactive scrollable lists

## Other

* [ontop-playback](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/ontop-playback.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Disables the ontop property when pausing, and enables it again when unpausing the video, if it was disabled. Change it only when the player is not in fullscreen to prevent screen flickering.
* [pause-when-minimize](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/pause-when-minimize.lua) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Pauses the player video when minimizing, and unpauses it when brought up again.
* [single-instance](https://github.com/mpv-player/mpv/issues/43#issuecomment-2496083283) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26 - Reuse the existing mpv window when opening new files rather than spawning a new window.
* [local-language](https://github.com/422658476/MPV-EASY-Player/blob/master/portable-data/scripts/local-language.lua) ⭐ 1,424 | 🐛 1 | 🌐 Lua | 📅 2026-07-12 - Let the text displayed by osd become the language you are most familiar with, that is, language localization, such as 【volume: 100%】 becomes 【音量:100%】.
* [SmartCopyPaste-3.0](https://github.com/Eisa01/mpv-scripts#smartcopypaste) ⭐ 839 | 🐛 56 | 🌐 Lua | 📅 2025-06-21 - Powerful copy paste features. Paste URL or local videos directly to mpv. Copy URL or currently playing video in mpv player then paste to access at a later time. Add videos to playlist simply by pasting. Much more explained in the link above.
* [SmartCopyPaste-II-3.0](https://github.com/Eisa01/mpv-scripts#smartcopypaste_ii) ⭐ 839 | 🐛 56 | 🌐 Lua | 📅 2025-06-21 - Powerful copy paste and clipboard list features using a log file. Select, filter, and search from your clipboard list. Paste URL or local videos directly to mpv. Copy URL or currently playing video in mpv player then paste to access at a later time. Paste to access previously copied times of same video. Much more explained in the link above.
* [webm](https://github.com/ekisu/mpv-webm) ⭐ 676 | 🐛 70 | 🌐 MoonScript | 📅 2026-03-01 - WebM converter based on MoonScript.
* [encode](https://github.com/occivink/mpv-scripts#encodelua) ⭐ 491 | 🐛 43 | 🌐 Lua | 📅 2025-11-01 - Re-encode or remux part of the current video. Can also preserve some filters, such as "crop".
* [vr-reversal](https://github.com/dfaker/VR-reversal) ⭐ 398 | 🐛 11 | 🌐 Lua | 📅 2024-05-21 - View 3D side-by-side video as a 2D video, allows you to look around and zoom within the video, logs the head motions to a file for later rendering out to a 2D video with ffmpeg.
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Execute Lua code from input.conf.
* [misc](https://github.com/stax76/mpv-scripts) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2025-11-26 - Restart mpv restoring the properties path, time-pos, pause and volume.
* [copy-paste-URL](https://github.com/zenyd/mpv-scripts) ⭐ 193 | 🐛 1 | 🌐 Lua | 📅 2025-12-07 - Paste URLs directly from clipboard into mpv
* [quick-scale](https://github.com/VideoPlayerCode/mpv-tools/) ⭐ 192 | 🐛 3 | 🌐 JavaScript | 📅 2021-07-07 - Quickly scale the video player to a target size, with full control over target scale and max scale. Helps you effortlessly resize a video to fit on your desktop, or any other video dimensions you need!
* [manga-reader](https://github.com/Dudemanguy/mpv-manga-reader) ⭐ 175 | 🐛 7 | 🌐 Lua | 📅 2026-06-23 - Script for using mpv as a manga reader.
* [bstat](https://github.com/butterw/bShaders/blob/master/mpv/settings/scripts/bstat.js) ⭐ 110 | 🐛 3 | 🌐 HLSL | 📅 2024-01-19 - Calculates new user-data properties (req mpv v0.36) including avg-bitrate, rounded file-size, exact aspect ratio, etc. Output to terminal or OSD. Updates when a new file is loaded or on demand.
* [minesweeper](https://github.com/wiiaboo/mpv-scripts/blob/master/mines.lua) ⭐ 97 | 🐛 3 | 🌐 Lua | 📅 2020-09-19 - Minesweeper game.
* [copyTime](https://github.com/Arieleg/mpv-copyTime) ⭐ 94 | 🐛 12 | 🌐 Lua | 📅 2022-12-28 - Copies the current time to the clipboard.
* [force-window-profile](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/scripts/force-window-profile.lua) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - Applies the force-window profile when force-window is set (i.e. when starting mpv from the .desktop file)
* [manager](https://github.com/po5/mpv_manager) ⭐ 42 | 🐛 0 | 🌐 Lua | 📅 2023-08-08 - Script and shader manager.
* [exit-fullscreen](https://github.com/zc62/mpv-scripts/blob/master/exit-fullscreen.lua) ⭐ 41 | 🐛 0 | 🌐 Lua | 📅 2020-08-28 - If you use `--keep-open=yes`, this script exits fullscreen mode when the playback reaches the end of file/playlist.
* [anilist-updater](https://github.com/AzuredBlue/mpv-anilist-updater) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2026-08-22 - Automatically updates your AniList when reaching 80% completion based on the file name.
* [copy-timestamp](https://github.com/linguisticmind/mpv-scripts/tree/master/copy-timestamp) ⭐ 38 | 🐛 3 | 🌐 Lua | 📅 2025-07-28 - Copies current timecode in HH:MM:SS.MS format to clipboard.
* [inhibit\_gnome](https://github.com/Guldoman/mpv_inhibit_gnome) ⭐ 36 | 🐛 1 | 🌐 C | 📅 2023-01-20 - Prevent screen blanking on GNOME while content is playing
* [debug-plugin](https://github.com/tsl0922/mpv-debug-plugin) ⭐ 35 | 🐛 3 | 🌐 C++ | 📅 2024-05-04 - A debug tool for mpv script developers, with GUI support for properties and console.
* [notify-send](https://github.com/emilazy/mpv-notify-send) ⭐ 34 | 🐛 6 | 🌐 Lua | 📅 2025-09-25 - A simpler and more recent notifications script for libnotify-compatible (i.e. Unix-like) notifications daemons only. Supports cover art.
* [tv-output](https://github.com/blue-sky-r/mpv/blob/master/scripts/tv.lua) ⭐ 29 | 🐛 2 | 🌐 Lua | 📅 2021-02-09 - TV output handling - activate on mpv playback and deactivate on mpv shutdown.
* [osd-clock](https://github.com/blue-sky-r/mpv/blob/master/scripts/osd-clock.lua) ⭐ 29 | 🐛 2 | 🌐 Lua | 📅 2021-02-09 - Periodically shows OSD clock (many configurable options).
* [taskbar-buttons](https://github.com/qwerty12/mpv-taskbar-buttons) ⭐ 28 | 🐛 0 | 🌐 Lua | 📅 2022-10-19 - (Windows) Adds thumbbar buttons.
* [txt](https://github.com/jgreco/mpv-txt) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2018-10-30 - Play text files using text-to-speech (TTS). (Works on Linux, MacOS).
* [copyStuff](https://github.com/rofe33/mpv-copyStuff) ⚠️ Archived - Copy to clipboard the filename or URL, full filename path, current video time, current displayed subtitle text, video duration/metadata.
* [cp-paste-URL](https://github.com/yassin-l/cp-paste-url.git) ⭐ 21 | 🐛 1 | 🌐 Lua | 📅 2022-04-18 - Fork of copy-paste-URL with support for Linux.
* [open-imdb-page](https://github.com/ctlaltdefeat/mpv-open-imdb-page) ⭐ 20 | 🐛 0 | 🌐 Lua | 📅 2022-02-12 - Opens the IMDb page that corresponds to the currently playing media file.
* [main.lua](https://github.com/TinosNitso/mpv-scripts/blob/main/main.lua) ⭐ 18 | 🐛 1 | 🌐 Lua | 📅 2024-10-05 - Loads other scripts, hooks in yt-dlp, displays title, has subtitle override, loops short files, sets options (with delay), & has detailed commentary. Has many script-messages. For mpv v0.34→v0.38, SMPlayer, Windows, Linux, MacOS, Android, YouTube, mp4, mp3, jpg, etc. But no yt-dlp for Android. [Example](https://youtu.be/le2JGgjRJBw) title.
* [notify](https://github.com/rohieb/mpv-notify) ⚠️ Archived - Adds desktop notifications to the mpv media player, which show metadata like artist, album name and track name when the track changes.
* [open-anilist-page](https://github.com/ehoneyse/mpv-open-anilist-page) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2020-09-12 - Opens the Anilist page that corresponds to the currently playing (anime) file.
* [mpvMatroska](https://github.com/hubblec4/mpvMatroska) ⭐ 14 | 🐛 2 | 🌐 Lua | 📅 2023-12-14 - mpvMatroska turns mpv into a Matroska player.
* [oled-screensaver](https://github.com/Akemi/mpv-oled-screensaver) ⭐ 13 | 🐛 4 | 🌐 Lua | 📅 2024-05-27 - To prevent burn-ins on OLED TVs, this script fades-in a black screen after 15 seconds when paused in fullscreen.
* [pdf](https://github.com/jgreco/mpv-pdf) ⭐ 12 | 🐛 2 | 🌐 Lua | 📅 2018-11-18 - View PDFs in mpv using ImageMagick. (for Linux, MacOS)
* [clipboard](https://github.com/CogentRedTester/mpv-clipboard) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2022-11-10 - Provides a set of generic commands to interact with the clipboard. Specifically it allows user to copy arbitrary text to the clipboard and provides the ability to paste the contents of the clipboard into other commands.
* [trakt-scrobble](https://github.com/dyphire/trakt-scrobble) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2026-04-30 - Connects trakt.tv with mpv and automatically scrobbles movies/shows.
* [equalizer](https://github.com/he2a/mpv-scripts) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2026-02-26 - Script for togglable parametric equalizer with EQ configuration similar to EqualizerAPO format present in a csv format. Script can be whitelisted based on whether the content is audio, video or a movie. Settings are located in equalizer.conf in ./script-opts folder and equalizer configuration in ./script-opts/equalizer folder.
* [ontop-only-while-playing](https://github.com/kungfubeaner/mpv-ontop-only-while-playing-lua/blob/master/on_top_only_while_playing.lua) ⭐ 10 | 🐛 0 | 🌐 Lua | 📅 2019-11-15 - Ontop is only active during video playback. Ontop is automatically disabled during idle, pause and is able to be dynamically disabled without having to restart unlike the previous script.
* [i3-floating-centered](https://github.com/mdnghtman/mpv-i3-floating-centered) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2021-05-10 - Show mpv window in the center of the display when it is in floating mode (i3wm)
* [lua-repl](https://github.com/guidocella/mpv-lua-repl) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2026-02-26 - A Lua REPL in the console with autocompletion and pretty-printing of returned tables. It lets you test mpv's and Lua's API without writing a script.
* [lines-meme-generator](https://github.com/WatanabeChika/mpv-lines-meme-generator) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2025-05-22 - Allow users to take screenshots in MPV, crop them to keep only the bottom portion, and stitch them together into a long vertical image, just like a meme of lines.
* [notify](https://github.com/mpv-notify/mpv-notify) ⭐ 6 | 🐛 1 | 🌐 Lua | 📅 2021-06-10 - Converging point for all forks of rohieb's notify scrip.
* [mpegts-truncate](https://github.com/hoehermann/mpv-mpegts-truncate) ⭐ 5 | 🐛 1 | 🌐 Lua | 📅 2018-07-09 - Removes beginning of MPEG TS file up to current position without re-writing the whole file.
* [notify](https://github.com/kauron/mpv-notify) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2017-10-27 - Now-playing-desktop notifications.
* [copy to music](https://github.com/yazeed44/mpv-scripts) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2020-11-30 - Copies the current media file you're playing to a predefined directory, and plays the next entry in the playlist (Unix-like)
* [open-kinopoisk-page](https://github.com/WANDEX/mpv-open-kinopoisk-page) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-12-09 - Opens the kinopoisk page that corresponds to the currently playing media file.
* [xfce-genmonify](https://github.com/budRich/mpv-xfce-genmonify) ⚠️ Archived - Update a [xfce4-panel](https://docs.xfce.org/xfce/xfce4-panel/start) [genmon](https://docs.xfce.org/panel-plugins/xfce4-genmon-plugin/start) plugin that is set up with [genmonify](https://github.com/budlabs/genmonify) ⚠️ Archived to display the currently playing media file and elpapsed or remaining time in xfce4-panel.
* [kodi hook](https://github.com/Eskander/kodi-mpv-hook) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2025-02-13 - Allows Kodi streaming add-ons to work correctly when using mpv as an [external player for Kodi](https://kodi.wiki/view/External_players) by parsing and extracting protocol options from Kodi's [custom URL format](https://kodi.wiki/view/HTTP).
* [ontop-window](https://github.com/wishyu/mpv-ontop-window/blob/main/ontop-window.lua) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2021-02-01 - Disables the ontop property when in fullscreen, and enables it again when in window mode, if it was disabled.
* [composition guides](https://github.com/Ares-0/mpv-composition-guides) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2023-04-02 - Overlay basic composition guides onto your video.
* [user-data-loader](https://github.com/CogentRedTester/mpv-user-data-loader) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2023-12-25 - Allows the `user-data` property to be set at launch using config files and changed using profiles and script-opts during runtime.
* [profile-cycle](https://github.com/Funami580/dotfiles/blob/master/.config/mpv/scripts/profile-cycle.lua) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2025-06-01 - Cycle between your custom defined profiles while watching the video.
* [notification-osd](https://github.com/layercak3/mpv-notification-osd) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2025-10-10 - XDG desktop notification OSD plugin for track changes or media key playback control while the window is unfocused. Supports cover art and video thumbnail of the current time position.
* [deframe](https://github.com/dimitris888/mpv-deframe) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2016-06-27 - Removes the frame of YouTube videos.
* [socket](https://github.com/Farzat07/mpv_socket) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2024-11-12 - Creates one IPC socket per mpv instance. Configurable. Socket name can be modified while playing.
* [copy-permalink](https://gist.github.com/olejorgenb/a5194d9bc183dbe0bfb02aac18fe37f9) - Copy `mpv --time=<current-position> <path-playing>` to clipboard. Useful for sharing when playing URLs.
* [vo\_battery](https://gist.github.com/ekisu/04924e899648e84f2e18) - Choose the VO based on if the laptop is on battery or not.
* [scale-win](https://gist.github.com/garoto/920b7456d2bdd8f48aa8e7094a12ce47) - Restore old "window-scale" behavior, so to make "add window-scale +/-<value>" keybinds work again when any of the autofit-\* options are defined.
* [clock](https://gitlab.com/mozbugbox/mpv-script-mozbugbox) - Constantly show current time on the lower left corner of the video screen.
* [redshift\_toggle](https://git.sr.ht/~q3cpma/dotfiles/tree/master/.config/mpv/scripts/redshift_toggle.lua) - Toggle redshift when loading a video file and when reaching the end of said file. Now also handles pause.
* [toggle-redshift-on-play](https://gist.github.com/CreamyCookie/d036b66af4e17ea527d08e303eb96145) - Toggle redshift when viewing videos with mpv.
* [toggle-redshift-on-play kill-restart-version](https://gist.github.com/CreamyCookie/079570ad0dd27d322421f6637c828ab8) - Toggle redshift when viewing videos with mpv.
* [kde-do-not-disturb](https://gitlab.com/smaniottonicola/kde-do-not-disturb) - Disable the notifications while mpv is running
* [kde-night-color](https://gitlab.com/smaniottonicola/kde-night-color) - Disable Night Color while mpv is running.
* [gnome-inhibit](https://gist.github.com/crazygolem/a7d3a2d3c0cee5d072c0cbbbdee69286) - Prevent the screen from blanking under GNOME+Wayland while a video is playing.
* [xscreensaver](https://gist.github.com/elenril/f8ff9475a7882b7a16cdd723c7dce150) - (Linux) Disables XScreensaver while video playback is active, a replacement for heartbeat-cmd.
* [convert\_script](https://gist.github.com/Zehkul/25ea7ae77b30af959be0) - Script to quickly convert and crop videos from within mpv, with a GUI.
* [change-screen-by-aspect-ratio](https://gist.github.com/stt/9e55ffa7f5047605b2dd8af417cf36f0) - Change the active fs-screen based on video's aspect ratio (for systems with monitors in landscape and portrait orientations).

# Music Player

* [Olivia](https://github.com/keshavbhatt/olivia) ⭐ 377 | 🐛 22 | 🌐 C++ | 📅 2022-10-19 - Linux cloud music player, based on C++/QT/Web.
* [vmn](https://github.com/Dudemanguy/vmn) ⭐ 40 | 🐛 2 | 🌐 C | 📅 2025-10-02 - Cross-platform CLI music player, based on C/TUI.
* [Harmonoid](https://harmonoid.com) - Cross-platform, based on Dart/Flutter.

# Media Center

* [Stremio](https://github.com/Stremio) - Cross-platform, based on C++/QT.

# Streaming Tools

* [jellyfin mpv shim](https://github.com/jellyfin/jellyfin-mpv-shim) ⭐ 2,336 | 🐛 179 | 🌐 Python | 📅 2026-08-26 - Jellyfin (Emby/Plex alternative) Client, based on Python.
* [ff2mpv](https://github.com/woodruffw/ff2mpv) ⭐ 639 | 🐛 10 | 🌐 PowerShell | 📅 2026-01-08 - A Firefox/Chrome extension for playing URLs in mpv, based on PowerShel/Shell/Python/JavaScript.
* [Botflix/stream-cli](https://github.com/kaboussi/Botflix) ⚠️ Archived - Command-line tool that combines scrapy and webtorrent for streaming movies, based on Python/TUI.
* [plex-mpv-shim](https://github.com/iwalton3/plex-mpv-shim) ⭐ 411 | 🐛 70 | 🌐 Python | 📅 2025-10-20 - Cast media from Plex Mobile and Web apps to MPV, based on Python.
* [play-with-mpv](https://github.com/Thann/play-with-mpv) ⭐ 372 | 🐛 54 | 🌐 JavaScript | 📅 2024-06-08 - Chrome extension for playing URLs in mpv, based on JavaScript/Python/Web.
* [orion](https://github.com/alamminsalo/orion) ⚠️ Archived - Unmaintained cross platform Twitch.tv client, based on C++/QT/QML.
* [webtorrent-mpv-hook](https://github.com/mrxdst/webtorrent-mpv-hook) ⭐ 196 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-23 - Adds a hook that allows mpv to stream torrents using webtorrent.
* [Plaincast](https://github.com/aykevl/plaincast) ⚠️ Archived - Unmaintained Linux server that acts like a lightweight/headless Chromecast that only includes YouTube, based on Golang.
* [DLNAmpvRenderer](https://github.com/PCigales/DLNAmpvRenderer) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2024-09-26 - Windows DLNA/UPnP renderer based on Python.
* [qtube](https://github.com/hdb/qtube) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2021-03-19 - Linux YouTube frontend, based on Python/QT.
* [Macast](https://xfangfang.github.io/Macast) - DLNA Media Renderer. You can push videos, pictures or musics from your mobile phone to your computer, based on Python/Web.
* [TubiTui](https://codeberg.org/777/TubiTui) - Cross-platform YouTube client based on Rust/TUI.

# User Configuration

* [dyphire](https://github.com/dyphire/mpv-config) ⭐ 1,856 | 🐛 6 | 🌐 GLSL | 📅 2026-08-26
* [Zabooby](https://github.com/Zabooby/mpv-config) ⭐ 561 | 🐛 0 | 🌐 GLSL | 📅 2026-08-13
* [noelsimbolon](https://github.com/noelsimbolon/mpv-config) ⭐ 306 | 🐛 2 | 🌐 GLSL | 📅 2026-04-30
* [Natural-Harmonia-Gropius](https://github.com/Natural-Harmonia-Gropius/mpv_config) ⭐ 105 | 🐛 0 | 🌐 GLSL | 📅 2026-08-21
* [tuilakhanh](https://github.com/tuilakhanh/mpv-config) ⭐ 74 | 🐛 0 | 🌐 GLSL | 📅 2026-08-18
* [Awan](https://github.com/Awan/cfg/tree/master/mpv/.config/mpv) ⭐ 37 | 🐛 0 | 🌐 Vim Script | 📅 2026-08-21
* [zenwarr](https://github.com/zenwarr/mpv-config) ⭐ 35 | 🐛 3 | 🌐 Lua | 📅 2025-11-16
* [lazy](https://github.com/hooke007/MPV_lazy) ⚠️ Archived
* [qwerty12](https://github.com/qwerty12/mpv-config) ⭐ 13 | 🐛 1 | 🌐 Lua | 📅 2023-08-03
* [DonCanjas](https://github.com/DonCanjas/mpv-dotfiles) ⭐ 11 | 🐛 1 | 🌐 Lua | 📅 2025-12-02
* [mustaqimM](https://github.com/mustaqimM/mpv-scripts) ⭐ 9 | 🐛 2 | 🌐 Lua | 📅 2023-12-27
* [Glow](https://glowmpv.github.io)

# Social Tools

* [Syncplay](https://syncplay.pl) - Synchronize playback on mpv/VLC/MPC on many computers and chat with friends. Cross-platform, based on Python.
* [KikoPlay](https://github.com/KikoPlayProject/KikoPlay) ⭐ 2,219 | 🐛 7 | 🌐 C++ | 📅 2026-07-18 - Cross-platform [Danmu](https://en.wikipedia.org/wiki/Danmu) player, based on C++/QT.

# Video Conversion

* [boram](https://github.com/Kagami/boram) ⭐ 463 | 🐛 27 | 🌐 JavaScript | 📅 2023-01-28 - Unmaintained cross-platform WebM converter, based on JavaScript/Web/Electron.
* [webm.py](https://github.com/Kagami/webm.py) ⭐ 145 | 🐛 4 | 🌐 Python | 📅 2020-08-02 - Cross-platform command-line WebM converter, based on Python.

# Shaders

* [Anime4K](https://github.com/bloc97/Anime4K) ⭐ 21,294 | 🐛 123 | 🌐 Jupyter Notebook | 📅 2024-08-17 - A series of shaders designed to scale and enhance anime. Includes shaders for line sharpening, artefact removal, denoising, upscaling, and more.
* [FSRCNN](https://github.com/igv/FSRCNN-TensorFlow/releases) ⭐ 501 | 🐛 0 | 🌐 Python | 📅 2021-04-12 - Prescaler based on layered convolutional networks.
* [nnedi3 and ravu](https://github.com/bjin/mpv-prescalers/tree/master) ⭐ 448 | 🐛 5 | 📅 2024-01-24 - User shaders for prescaling.
* [ArtCNN](https://github.com/Artoriuz/ArtCNN) ⭐ 361 | 🐛 1 | 🌐 GLSL | 📅 2026-08-18 - Luma doublers trained on Manga109.
* [AniSD ArtCNN](https://github.com/Sirosky/Upscale-Hub/releases/tag/AniSD-ArtCNN) ⭐ 361 | 🐛 5 | 📅 2025-06-08 - AniSD ArtCNN shader for standard definition anime content.
* [Ani4K v2 ArtCNN](https://github.com/Sirosky/Upscale-Hub/releases/tag/Ani4k-v2-ArtCNN) ⭐ 361 | 🐛 5 | 📅 2025-06-08 - Ani4K shader v2 targets modern anime, from high quality Bluray to crappy WEB releases, for upscaling to either 2K or 4K.
* [hdr-toys](https://github.com/natural-harmonia-gropius/hdr-toys) ⭐ 190 | 🐛 18 | 🌐 GLSL | 📅 2026-08-20 - Componentized Rec.2100 to Rec.709 conversion shader.
* [CuNNy](https://github.com/funnyplanter/CuNNy) ⭐ 166 | 🐛 3 | 🌐 GLSL | 📅 2025-08-29 - Cute and funny CNN-based upscaler optimized for anime.
* [A-Pack](https://github.com/butterw/bShaders/tree/master/A-pack) ⭐ 110 | 🐛 3 | 🌐 HLSL | 📅 2024-01-19 - Shaders pack for quick Adjustment of (web) video: brightness/contrast curves (tooDark, tooBright, bShadows, bDim, etc.) and color (vibrance, skintones, Black\&White). Runs on integrated graphics.
* [Noise](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/shaders/noise.glsl) ⚠️ Archived - Simplistic filter that adds a tunable amount of uniform white noise to the output.
* [Antiringing](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/shaders/antiring.hook) ⚠️ Archived - This is an antiringing filter that works by clamping to the local neighbourhood. Sort of inspired by the mpv built-in antiringing algorithm, but it's extended in such a way that it also works well for polar (EWA) filters, which the mpv built-in algorithm does not support at all.
* [nlmeans, hdeband, & more](https://github.com/AN3223/dotfiles/blob/master/.config/mpv/shaders/) ⭐ 46 | 🐛 4 | 🌐 C | 📅 2026-04-02 - nlmeans is a featureful implementation of the Non-local Means algorithm, it does both denoising and adaptive sharpening. hdeband is an implementation of a debanding algorithm that blurs homogeneous regions together.
* [JointBilateral & FastBilateral](https://github.com/Artoriuz/glsl-joint-bilateral) ⭐ 29 | 🐛 0 | 🌐 GLSL | 📅 2024-11-08 - Chroma upsamplers that use the luma plane as a guide to achieve sharper transitions without introducing any ringing.
* [Pixel Clipper](https://github.com/Artoriuz/glsl-pixel-clipper) ⭐ 15 | 🐛 1 | 🌐 GLSL | 📅 2024-01-24 - Simple anti-ringing filter based on pixel clipping/clamping.
* [Alt Scale](https://github.com/garamond13/alt-scale) ⭐ 9 | 🐛 0 | 🌐 GLSL | 📅 2025-10-27 - An alternative to mpv's built in scaling. It can be slightly faster than built in scaling with equivalent quality.
* [Jinc](https://github.com/garamond13/Jinc) ⭐ 7 | 🐛 0 | 🌐 GLSL | 📅 2025-10-27 - Jinc based image scaling. Similar to mpv's ewa or polar.
* [Post upscale unsharp masking](https://github.com/garamond13/unsharp_masking.glsl) ⭐ 4 | 🐛 0 | 🌐 GLSL | 📅 2022-09-28 - This is mpvs original image sharpening algorithm ported into the shader, in order to work only after upscaling is done.
* [Unsharp mask and Gaussian blur](https://github.com/garamond13/Unsharp-mask-and-Gaussian-blur) ⭐ 2 | 🐛 0 | 🌐 GLSL | 📅 2023-07-19 - A 2 pass unsharp mask and a 2 pass gaussian blur. Similar to those in Photoshop, Image Magick, Gimp, etc.
* [2D Image Resampling](https://github.com/garamond13/2D-Image-Resampling) ⭐ 1 | 🐛 0 | 🌐 GLSL | 📅 2025-06-03 - 2D Image Resampling is a general resampling algorithm made for experimental / testing use.
* [NLS-Next](https://github.com/NotMithical/MPV-NLS-Next/blob/main/NLS-Next.glsl) ⭐ 0 | 🐛 0 | 🌐 GLSL | 📅 2025-12-08 - A nonlinear stretch shader and helper script for MPV, featuring bi-directional stretching and multiple tunable options.
* [LumaSharpenHook](https://gist.github.com/voltmtr/8b4404b4e23129b226b9e64863d3e28b) - A sharpen filter similar to using Unsharp Mask in Photoshop ported from SweetFX shader pack.
* [SSimDownscaler, SSimSuperRes, Krig, Adaptive Sharpen, etc.](https://gist.github.com/igv) - \* SSimDownscaler: Perceptually based downscaler. SSimSuperRes: The aim of this shader is to make corrections to the image upscaled by mpv built-in scaler (removes ringing artifacts, restores original sharpness, etc). Krig: Chroma scaler that uses luma information for high quality upscaling.
* [Film Grain v1](https://raw.githubusercontent.com/haasn/gentoo-conf/xor/home/nand/.mpv/shaders/filmgrain.glsl)\*\* and \*\*[Film Grain v2](https://raw.githubusercontent.com/haasn/gentoo-conf/xor/home/nand/.mpv/shaders/filmgrain-smooth.glsl) - Two configurable shaders for applying gaussian-weighted white noise to the image. v2 is a smoothed version of v1, which uses an extra gaussian blur pass to shift the grain frequency spectrum. Both versions can trivially be adapted to add film grain to other channels besides `LUMA` by just adding it to the list of hooks.
* [acme-0.5x](https://gist.github.com/bjin/15f307e7a1bdb55842bbb663ee1950ed) - Fastest 0.5x downscaler for mpv, useful for 4K video playback on FHD screen (bypass chroma upscaling and color conversion in 4K resolution).
* [lensfix](https://gist.github.com/bjin/33ffbc0fbdbc00aefa21b2e44bbd27cd#file-lensfix-hook) - Fix radial distortion commonly found in wide angle action cameras.
* [hyperview](https://gist.github.com/bjin/399cb23818ad210941725ef768893499) - Dynamic stretching filter aiming to bring effects similar to GoPro SuperView.
* [un360](https://gist.github.com/tesu/196db5421559de3e9555d4f9da9d847d) - Converts equirectangular 360 degree video to be watchable, at a fixed perspective.
* [Nonlinear stretch](https://gist.github.com/sarahzrf/c9909aee70e3656895820f20ac395956) - Non-linear stretch scaling. use with `--no-keepaspect`.
* [FidelityFX CAS](https://gist.github.com/agyild/bbb4e58298b2f86aa24da3032a0d2ee6) - AMD FidelityFX Contrast Adaptive Sharpening (CAS) provides a mixed ability to sharpen and optionally scale an image. The algorithm adjusts the amount of sharpening per pixel to target an even level of sharpness across the image. Areas of the input image that are already sharp are sharpened less, while areas that lack detail are sharpened more. This allows for higher overall natural visual sharpness with fewer artifacts.
* [FidelityFX FSR](https://gist.github.com/agyild/82219c545228d70c5604f865ce0b0ce5) - AMD FidelityFX Super Resolution is a spatial upscaler: it works by taking the current anti-aliased frame and upscaling it to display resolution without relying on other data such as frame history or motion vectors. At the heart of FSR is a cutting-edge algorithm that detects and recreates high-resolution edges from the source image. Those high-resolution edges are a critical element required for turning the current frame into a “super resolution” image. FSR provides consistent upscaling quality regardless of whether the frame is in movement, which can provide quality advantages compared to other types of upscalers.
* [NVIDIA Image Scaling](https://gist.github.com/agyild/7e8951915b2bf24526a9343d951db214) - NVIDIA Image Scaling is a spatial scaling and sharpening algorithm. The scaling algorithm uses a 6-tap scaling filter combined with 4 directional scaling and adaptive sharpening filters, which creates nice smooth images and sharp edges. In addition, an adaptive-directional sharpening-only algorithm is available. The directional scaling and sharpening algorithm is named NVScaler while the adaptive-directional-sharpening-only algorithm is named NVSharpen.
* [Snapdragon Game Super Resolution (GSR) v1](https://gist.github.com/agyild/7715b6b1f38427839d58f80884902cab) - Snapdragon Game Super Resolution (GSR) v1 is a single-pass spatial upscaling technique originally developed by Qualcomm for mobile devices. It integrates upscaling and edge sharpening into one GPU shader pass, leveraging a 12-tap Lanczos-like scaling filter and an adaptive sharpening filter.

# VapourSynth Scripts

* [mvtools](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/filters/mvtools.vpy) ⚠️ Archived - Use [MVTools](https://github.com/dubhater/vapoursynth-mvtools) ⭐ 223 | 🐛 3 | 🌐 C++ | 📅 2026-06-21's BlockFPS function to perform motion interpolation on the video in realtime.
* [nnedi3](https://github.com/haasn/gentoo-conf/blob/xor/home/nand/.mpv/filters/nnedi3.vpy) ⚠️ Archived - Use [NNEDI3](https://github.com/dubhater/vapoursynth-nnedi3) ⚠️ Archived to double the resolution of the video. This always performs a single doubling. Note that the vapoursynth-nnedi3 filter is so slow that this practically can't be used in realtime, so it's not much use in practice.

# Video Editing Tools

* [vidcutter](https://github.com/ozmartian/vidcutter) ⭐ 1,977 | 🐛 297 | 🌐 Python | 📅 2025-04-24 - Cross-platform video cutter/joiner, based on Python/QT.
* [tsv\_edl.vim](https://github.com/scateu/tsv_edl.vim) ⭐ 102 | 🐛 1 | 🌐 Python | 📅 2026-07-27 - Linux video editing with vim/spreadsheet/sed/python.

# Image Viewer

* [qimgv](https://github.com/easymodo/qimgv) ⭐ 3,115 | 🐛 307 | 🌐 C++ | 📅 2026-01-19 - Cross-platform, based on C++/QT.

# Launcher

* <https://github.com/mpv-player/mpv/blob/master/TOOLS/umpv> ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26
* <https://github.com/davatorium/rofi> ⭐ 16,349 | 🐛 117 | 🌐 C | 📅 2026-08-09
* <https://github.com/Flow-Launcher/Flow.Launcher> ⭐ 15,439 | 🐛 302 | 🌐 C# | 📅 2026-08-25
* <https://github.com/ikas-mc/ContextMenuForWindows11> ⭐ 2,868 | 🐛 20 | 🌐 C# | 📅 2026-07-25
* <https://github.com/stax76/OpenWithPlusPlus> ⭐ 436 | 🐛 10 | 🌐 Visual Basic .NET | 📅 2025-11-26
* <https://github.com/stax76/Flow.Launcher.Plugin.Favorites> ⭐ 74 | 🐛 9 | 🌐 C# | 📅 2025-11-26
* <https://www.google.com/search?q=external+application+launcher>
* <https://albertlauncher.github.io>

# Remote Control

* [mpv-mpris](https://github.com/hoyon/mpv-mpris) ⭐ 737 | 🐛 4 | 🌐 C | 📅 2026-07-22 - On Linux allows controlling mpv using standard media keys.
* [simple-mpv-webui](https://github.com/open-dynaMIX/simple-mpv-webui) ⭐ 165 | 🐛 9 | 🌐 Lua | 📅 2024-01-31 Based on Python/Lua/JavaScript/Web.
* [mpv-remote-app](https://github.com/mcastorina/mpv-remote-app) ⭐ 101 | 🐛 31 | 🌐 Java | 📅 2023-05-01 - For Android, based on Java/Python.
* [mpv-remote-app](https://github.com/husudosu/mpv-remote-app) ⭐ 100 | 🐛 14 | 🌐 Vue | 📅 2026-07-25 - For Android, based on Vue.js/Ionic/Node.js.
* [MPVMediaControl](https://github.com/datasone/MPVMediaControl) ⭐ 70 | 🐛 3 | 🌐 C# | 📅 2025-09-02 - Windows 10 System Media Transport Controls (SMTC).
* [lua-mpris](https://github.com/dodo/lua-mpris) ⭐ 24 | 🐛 9 | 🌐 Lua | 📅 2019-10-25 - Adds mpris support to mpv.
* [KDE Connect](https://kdeconnect.kde.org) - Enabling communication between all your devices.
  * [GSConnect](https://extensions.gnome.org/extension/1319/gsconnect/) - Implementation of KDE Connect for GNOME.
* Classic remote control used by stax76: 'One For All Contour URC1210' using Philips code 0556 together with 'FLIRC USB (gen2)'.

# Building

* [Compiling for Windows](https://github.com/mpv-player/mpv/blob/master/DOCS/compile-windows.md) ⭐ 36,687 | 🐛 1,138 | 🌐 C | 📅 2026-08-26
* [Building mpv and libmpv using wsl2 and Ubuntu](https://github.com/mpvnet-player/mpv.net/wiki/Building-mpv-and-libmpv-using-wsl2-and-Ubuntu) ⭐ 5,346 | 🐛 156 | 🌐 C# | 📅 2026-02-09
* [Media Auto Build Suite (MABS)](https://github.com/m-ab-s/media-autobuild_suite) ⭐ 1,812 | 🐛 219 | 🌐 Shell | 📅 2026-08-18
* [Helper scripts to compile mpv on Linux](https://github.com/mpv-player/mpv-build) ⭐ 491 | 🐛 9 | 🌐 Shell | 📅 2025-11-02
* [crosscompile-mingw-tedious](https://github.com/qyot27/mpv/blob/extra-new/DOCS/crosscompile-mingw-tedious.txt) ⭐ 2 | 🐛 3 | 🌐 C | 📅 2025-04-19

# Library

* [python](https://github.com/jaseg/python-mpv) ⭐ 630 | 🐛 30 | 🌐 Python | 📅 2025-04-25 - Python interface.
* [js](https://github.com/Kagami/mpv.js) ⭐ 446 | 🐛 20 | 🌐 C++ | 📅 2024-01-17 - Embeddable player for Electron/NW\.js (JavaScript).
* [Kit](https://github.com/mpvkit/MPVKit) ⭐ 195 | 🐛 10 | 🌐 Swift | 📅 2026-08-17 - MPVKit is a collection of tools to use mpv in iOS, macOS, tvOS applications. It includes scripts to build mpv native libraries.
* [easy](https://github.com/mpv-easy/mpv-easy) ⭐ 137 | 🐛 75 | 🌐 TypeScript | 📅 2026-08-20 - TS and React GUI toolkit for mpv script.
* [object pascal](https://github.com/URUWorks/UW_MPVPlayer) ⭐ 27 | 🐛 2 | 🌐 Pascal | 📅 2026-07-01 - Embeddable player for Object Pascal.
* [py](https://github.com/marcan/pympv) ⭐ 20 | 🐛 0 | 🌐 Cython | 📅 2025-07-26 - Another Python interface.
* [ruby](https://github.com/woodruffw/ruby-mpv) ⭐ 15 | 🐛 1 | 🌐 Ruby | 📅 2021-04-29 - Ruby interface.
* [node](https://github.com/rcombs/node-mpv) ⭐ 3 | 🐛 2 | 🌐 JavaScript | 📅 2016-05-08 - Node.js interface (JavaScript).
* [mpv.d.ts](https://github.com/Cerlancism/mpv.d.ts) ⭐ 2 | 🐛 0 | 📅 2026-03-05 - TypeScript definition file (JavaScript).
* [script](https://www.npmjs.com/package/@types/mpv-script) - TypeScript definitions for builtin `mp` modules and globals.
* [mpv.d.ts](https://www.npmjs.com/package/mpv.d.ts) - Another TypeScript definitions for mpv JavaScript API.
* [promise](https://www.npmjs.com/package/mpv-promise) - Promise polyfill for mpv JavaScript runtime.
* [assdraw](https://www.npmjs.com/package/mpv-assdraw) - mpv assdraw module for JavaScript.

# Other Tools

* [Memento](https://github.com/ripose-jp/Memento) ⭐ 1,471 | 🐛 26 | 🌐 C++ | 📅 2026-08-24 - Cross-platform video player for studying Japanese, based on C++/QT.
* [gnome-shell-extension-caffeine](https://github.com/eonpatapon/gnome-shell-extension-caffeine) ⭐ 774 | 🐛 41 | 🌐 JavaScript | 📅 2026-05-20 - Prevent the display from turning off (Gnome doesn't support the idle-inhibit protocol on Wayland) and disable the 'night light' when a mpv window is in focus.
* [install](https://github.com/rossy/mpv-install) ⭐ 469 | 🐛 7 | 🌐 Batchfile | 📅 2021-09-03 - Sets up file associations for mpv on Windows.
* [blitzloop](https://github.com/marcan/blitzloop) ⭐ 230 | 🐛 14 | 🌐 Python | 📅 2021-05-02 - Linux karaoke software, based on Python/OpenGL.
* [mpvQC](https://github.com/mpvqc/mpvQC) ⭐ 79 | 🐛 5 | 🌐 Python | 📅 2026-08-25 - Cross-platform application for quality control of videos, based on Python/QT.
* [vidify](https://vidify.org) - Cross-platform app that detects playing songs on your device and plays their music videos anywhere, based on Python.
* [Karaoke Mugen](https://karaokes.moe/de/) - Cross-platform karaoke management app, based on JavaScript/node.js/Web.

## Other projects from me

A list of my other projects can be found here:

<https://stax76.github.io/software-list>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
