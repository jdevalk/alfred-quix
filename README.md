# Quix AlfredApp workflow

<img src="icon.png" alt="Quix logo" align="right" width="150" height="150">

An [AlfredApp](https://www.alfredapp.com/) workflow to quickly perform numerous checks on websites.

:warning: *This workflow requires [AlfredApp V5](https://www.alfredapp.com/blog/releases/alfred-5-early-access-now-available/)* :warning:

This workflow comes with 3 built-in commands:

- Quix itself, which I always open with `⎇ + Q` or by typing `quix`
- Site search, which I always open with `⌘ + ⎇ + S`, or by typing `site-search`
- Whois, opened by typing `whois`

The main command opens a list of possible commands, which you can scroll through or just type the first few letters and then press enter to select. The commands will order based on usage, so if you use something more often, it'll float to the top.

## Usage

When you invoke Quix (if you assign a hotkey like `⎇ + Q` you can quickly do that by pressing that), it'll grab the foremost URL from your browser, either Chrome or Safari, and performs the command you select on it:

<img src="alfred-quix.gif" alt="Gif showing the usage of Quix in AlfredApp" width="400">

For instance, opening the Speed check would open a [PageSpeed Insights](https://pagespeed.web.dev/) test for the current URL.

## How to install

Download the [`Quix.alfredworkflow`](https://github.com/jdevalk/alfred-quix/raw/main/Quix.alfredworkflow) file and double click to install it.

## Changelog

### 2.0

* Made Alfred Quix compatible with AlfredApp V5 workflow builder.
* Added [OneUpdater](https://www.alfredforum.com/topic/9224-oneupdater-%E2%80%94-update-workflows-with-a-single-node/) so the Workflow can be updated easily.

### 1.0

Initial version.
