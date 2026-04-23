# Quix

<img src="icon.png" alt="Quix logo" align="right" width="150" height="150">

Quickly run website checks and SEO tools on the current browser URL via the `quix` keyword.

## Usage

Invoke Quix to grab the URL from the frontmost browser tab and choose from a filterable list of tools to run on it via the `quix` keyword or configure the <kbd>⎇</kbd><kbd>Q</kbd> Hotkey.

![Gif showing the usage of Quix in AlfredApp](alfred-quix.gif)

Start typing to filter the list, or scroll and press <kbd>↩</kbd> to run. Results reorder by frequency of use.

Available tools include speed checks, SEO analysis, social previews, schema validators, security headers, robots.txt, archive lookups, and more.

Alternatively, configure the <kbd>⌘</kbd><kbd>⎇</kbd><kbd>S</kbd> Hotkey for a quick site search on the current domain. Whois lookups are also available via the `whois` keyword.

## Changelog

### 3.2

* Added Robots.txt command to quickly open the robots.txt file for the current domain.
* Added Security headers command to check HTTP security headers via securityheaders.com.
* Renamed "Social" to "Clear social cache" and added a new "Social" command for a unified social preview via metatags.io.

### 3.1.2

* Fix for site search commands when your search term is more than one word.

### 3.1.1

* Minor fix for archive.org site command.

### 3.1

* Added support for archive.org with two new commands to access Archive.org, one for the page and one for the whole site, as well as a third to save the current page in Archive.org.

### 3.0

* **Major browser support improvements**: added support for Firefox, Firefox Developer Edition, Chrome Canary, Safari Technology Preview, Brave Beta, and Vivaldi.
* Added a user config option to select a default browser, for cases when you open Quix from outside a browser.
* Added an "is this site down for everyone" command.
* Added a "who hosts this site" command.
* Re-built much of the workflow to work more intuitively.

### 2.1

* Added support for Brave Browser.

### 2.0.1

* Some fixes as AlfredApp updated how the automation tasks work slightly.

### 2.0

* Made Alfred Quix compatible with AlfredApp V5 workflow builder.

### 1.0

Initial version.
