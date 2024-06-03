# Awesome Awesome WM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of high-quality tools/scripts/configs for Awesome Window Manager.

This guide was created because an out-of-the-box Awesome WM experience is miserable, yet the WM quickly grows on those courageous enough to tinker with it and weather version-incompatibility issues. This guide was created for those who need a head start with their awesome config.

One problem with Awesome WM is that newer versions of Awesome break a lot of backwards compatibility. Many of the below libraries have been updated to Awesome 4.2, ones that haven't will not work with the latest version of Awesome. A library written for Awesome 3.5 will not work with Awesome 4.0 and one written for 3.4 will not work with either so make sure the versions between your modules match. This in itself creates a lot of frustration for users and a segmentation of Awesome user base.

This repository tries to keep up to date, most of the tools listed here are compatible with Awesome 4.0+, some 3.4-3.5 tools are listed if they're notable due to their use case or compatible with current version of Awesome.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Contents
- [Official Resources](#official-resources)
- [Pre-Built Versions](#pre-built-versions)
- [Configuration](#configuration)
- [Theming](#theming)
- [Widget Packs](#widget-packs)
- [Basic Widgets](#basic-widgets)
- [Productivity Widgets](#productivity-widgets)
- [Wanted](#wanted)

## Official Resources
- [Main repository](https://github.com/awesomeWM/awesome) - Latest development build.
- [Wiki](http://awesome.naquadah.org/wiki/Main_Page) - While not terse, a very useful resource.

## Pre-Built Versions
- [Ubuntu/Mint](https://launchpad.net/~klaus-vormweg/+archive/ubuntu/awesome) - Use this PPA instead of official which tends to be very old.

## Configuration
- [Valid Key Names](http://wiki.linuxquestions.org/wiki/List_of_keysyms) - Useful for figuring out things like `PgUp` is actually called `Prior` so you can map your shortcuts.
- [Dynamic Tagging](https://github.com/pw4ever/awesome-wm-config) - Those numbered tags in upper-left corner can now be renamed on the fly.
- [Menu Replacement](https://github.com/lcpz/awesome-freedesktop) - Unlike default menu that looks very basic compared to other window managers, this menu replaces the original with a more `Start`-like menu with icons.
- [Hydra](https://github.com/TommyX12/awesome-wm-hydra) - Multi-key-sequence framework for AwesomeWM with key hints display.

## Theming
- [Awesome Copycats](https://github.com/copycat-killer/awesome-copycats) - A collection of well-polished themes with distinct look and feel.
- [Theme with fancy features](https://github.com/actionless/awesome_config) - A beautiful theme with screenshots.
- [Another polished theme](https://github.com/worron/awesome-config) - A theme showing that you don't have to settle for crappy ASCII art visuals.
- [awesome-ban](https://github.com/4ban/awesome-ban) - A theme inspired by Copycats themes
- [awesome-pro](https://github.com/4ban/awesome-pro) - Pro theme updated to support Awesome 4.0
- [Minimalist theme](https://github.com/Relz/awesome-wm-theme) - Minimalist theme with high level of customization.
- [compton](https://github.com/chjj/compton) - High-performance compositor for those who like transparent windows.
- [radical](https://github.com/Elv13/radical) - Fancy generator for custom menus

## Widget Packs
- [Awesome Zen](https://github.com/atsepkov/awesome-zen) - Collection of widgets with a consistent interface that hides when they're not relevant to declutter your desktop. Also includes utilities for managing windows more effectively.
- [Awesome WM Widgets](https://github.com/streetturtle/awesome-wm-widgets) - Good options for battery, music, CPU/RAM, and Volume widgets
- [Lain](https://github.com/lcpz/lain) - Another set of polished Widgets for Awesome
- [Vicious](https://github.com/vicious-widgets/vicious) - Contains modules that gather data about your system

## Basic Widgets
- [Volume Icon](https://github.com/Maato/volumeicon) - Stand-alone volume icon for lightweight WMs that fits well with nm-applet (C).
- [Network](https://github.com/plotnikovanton/net_widgets) - A wireless + wired network widget that replaces nm-applet (Lua).
- [Battery](https://github.com/NuckChorris/assault/) - Stand-alone battery widget (C).
- [Weather](https://github.com/ralluri/yawn) - Widget that retrieves localized weather information from Yahoo.

## Productivity Widgets
- [Basic Calendar](https://github.com/cdump/awesome-calendar) - Simple, but pretty calendar.
- [Calendar w/ TODO](https://github.com/alexander-yakushev/Orglendar) - (orglendar) A calendar + to-do list for awesome that reads entries from a .org file (I have a cronjob dumping my Google Calendar to that file) (Lua).
- [Pomodoro Timer](https://github.com/optama/awmodoro) - Hides clutter from the screen for 25 mins, replacing it with a progress bar (Lua).
- [awesome-scratch](https://github.com/proteansec/awesome-scratch) - A stashing area for window to declutter the workspace and easily recall programs, doesn't seem to be actively maintained

## Multi-Monitor and Docking Stations
- [screenful](https://github.com/dluksza/screenful) - An extension that leverages udev to detect monitor connection/disconnection
- [autorandr](https://github.com/wertarbyte/autorandr) - Automatically select xrandr display configuration based on connected devices

## Other
- [tmux integration to manage terminal sessions](https://github.com/wheatdog/awesome-termgrp)
- [treesome](https://github.com/RobSis/treesome) - no longer maintained, a utility for splitting workspace in a manner similar to TMUX

## Wanted
- Widgets for CPU monitoring, polished mail integration.
- Audio/MPD integration that's not overly complex like AwsoMPD (which is somewhat bloated and buggy).
- More theme bundles to share (if you want to share your theme, I ask that you attach a screenshot to your repo).
