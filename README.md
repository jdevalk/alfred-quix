# Quix AlfredApp workflow

<img src="icon.png" alt="Quix logo" align="right" width="150" height="150">

An [AlfredApp](https://www.alfredapp.com/) workflow to quickly perform numerous checks on websites.

This workflow pretty much works straight ouf the box, as soon as you **assign the hotkeys**!

This workflow comes with 3 built-in commands:

- Quix itself, which I always open with `⎇ + Q` or by typing `quix`
- Site search, which I always open with `⌘ + ⎇ + S`, or by typing `site-search`
- Whois, opened by typing `whois` in Quix, or as a command when you open Quix, so you can use it for the current domain you're looking at.

The main command opens a list of possible commands, which you can scroll through or just type the first few letters and then press enter to select. The commands will order based on usage, so if you use something more often, it'll float to the top.

## Usage

When you invoke Quix (if you assign a hotkey like `⎇ + Q` you can quickly do that by pressing that), it'll grab the foremost URL from your browser, either Chrome or Safari, and performs the command you select on it:

<img src="alfred-quix.gif" alt="Gif showing the usage of Quix in AlfredApp" width="400">

For instance, opening the Speed check would open a [PageSpeed Insights](https://pagespeed.web.dev/) test for the current URL.

## How to install

Download the [`Quix.alfredworkflow`](https://github.com/jdevalk/alfred-quix/raw/main/Quix.alfredworkflow) file and double click to install it.

## Changelog

### 3.1

* Added support for archive.org with two new commands to access Archive.org, one for the page and one for the whole site as well as a third: _save_ this page in Archive.org.

### 3.0

* **Major browser support improvements**: added support for Firefox, Firefox developer edition, Chrome Canary Safari Technology Preview, Brave Beta and Vivaldi.
* Added a user config option to select a default browser, for cases when you open Quix from outside a browser.
* Added an "is this site down for everyone" command
* Added a "who hosts this site" command.
* Re-built much of the workflow to work a bit more intuitive.

### 2.1

* Added support for Brave Browser.

### 2.0.1

* Some fixes as AlfredApp updated how the automation tasks work slightly.

### 2.0

* Made Alfred Quix compatible with AlfredApp V5 workflow builder.
* Added [OneUpdater](https://www.alfredforum.com/topic/9224-oneupdater-%E2%80%94-update-workflows-with-a-single-node/) so the Workflow can be updated easily.

### 1.0

Initial version.
