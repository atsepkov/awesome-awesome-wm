# Awesome Awesome WM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of high-quality tools/scripts/configs for Awesome Window Manager.

This guide was created because out-of-the-box Awesome WM experience is miserable, yet the WM quickly grows on those courageous enough to tinker with it and weather version-incompatibility issues. This guide was created for those who need a head start with their awesome config.

One problem with Awesome WM is that newer versions of Awesome break a lot of backwards compatibility. Many of the below libraries have been updated to Awesome 4.2, ones that haven't will not work with latest version of Awesome. A library written for Awesome 3.5 will not work with Awesome 4.0 and one written for 3.4 will not work with either so make sure the versions between your modules match. This in itself creates a lot of frustration for users and a segmentation of Awesome user base.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Contents
- [Official Resources](official-resources)
- [Pre-Built Versions](pre-built-versions)
- [Configuration](configuration)
- [Theming](theming)
- [Widget Packs](widget-packs)
- [Basic Widgets](basic-widgets)
- [Productivity Widgets](productivity-widgets)
- [Wanted](wanted)

## Official Resources
- [Main repository](https://github.com/awesomeWM/awesome) - Latest development build.
- [Wiki](http://awesome.naquadah.org/wiki/Main_Page) - While not terse, a very useful resource.

## Pre-Built Versions
- [Ubuntu/Mint](https://launchpad.net/~klaus-vormweg/+archive/ubuntu/awesome) - Use this PPA instead of official which tends to be very old.
- [All Other Linuxes](http://pkgs.org/download/awesome) - Other distros are up-to-date here.

## Configuration
- [Valid Key Names](http://wiki.linuxquestions.org/wiki/List_of_keysyms) - Useful for figuring out things like `PgUp` is actually called `Prior` so you can map your shortcuts.
- [Dynamic Tagging](https://github.com/pw4ever/awesome-wm-config) - Those numbered tags in upper-left corner can now be renamed on the fly.
- [Menu Replacement](https://github.com/terceiro/awesome-freedesktop) - Unlike default menu that looks very basic compared to other window manager, this menu replaces the original with a more `Start`-like menu with icons.

## Theming
- [Awesome Copycats](https://github.com/copycat-killer/awesome-copycats) - A collection of well-polished themes with distinct look and feel.
- [Theme with fancy features](https://github.com/actionless/awesome_config) - A beautiful theme with screenshots.
- [Another polished theme](https://github.com/worron/awesome-config) - A theme showing that you don't have to settle for crappy ASCII art visuals.
- [compton](https://github.com/chjj/compton) - High-performance compositor for those who like transparent windows.
- [radical](https://github.com/Elv13/radical) - Fancy generator for custom menus

## Widget Packs
- [Awesome Zen](https://github.com/atsepkov/awesome-zen) - Collection of widgets with consistent interface that hide when they're not relevant to declutter your desktop. Also includes utilities for managing windows more effectivelly.
- [Awesome WM Widgets](https://github.com/streetturtle/awesome-wm-widgets) - Good options for battery, music, CPU/RAM, and Volume widgets
- [Lain](https://github.com/lcpz/lain) - Another set of polished Widgets for Awesome

## Basic Widgets
- [Volume Icon](https://github.com/Maato/volumeicon) - Stand-alone volume icon for lightweight WMs that fits well with nm-applet (C).
- [Network](https://github.com/plotnikovanton/net_widgets) - A wireless + wired network widget that replaces nm-applet (lua).
- [Battery](https://github.com/NuckChorris/assault/) - Stand-alone battery widget (C).
- [Weather](https://github.com/ralluri/yawn) - Widget that retrieves localized weather information from Yahoo.

## Productivity Widgets
- [Basic Calendar](https://github.com/cdump/awesome-calendar) - Simple, but pretty calendar.
- [Calendar w/ TODO](https://github.com/alexander-yakushev/Orglendar) - (orglendar) A calendar + to-do list for awesome that reads entries from a .org file (I have a cronjob dumping my Google Calendar to that file) (lua).
- [Pomodoro Timer](https://github.com/optama/awmodoro) - Hides clutter from the screen for 25 mins, replacing it with a progress bar (lua).

## Wanted
- Widgets for cpu monitoring, polished mail integration.
- Audio/mpd integration that's not overly complex like AwsoMPD (which is somewhat bloated and buggy).
- More theme bundles to share (if you want to share your theme, I ask that you attach a screenshot to your repo).
