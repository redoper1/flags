# flags.ox3.in
Lots and lots of flags

## What is this?
This is a big repository of flag images for countries (and subdivisions). The flags are all named according to [ISO 3166 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) for easy use in applications. You can download the entire repository, or you can access individual flags via http://flags.ox3.in (see below for details).

You can see a list of all the flags available and the names/codes/aliases for the corresponding countries in [this spreadsheet](https://docs.google.com/spreadsheets/d/1GoDDhtoDuKwDv9pB5hKFkcHzhI420z2lr4szovryXaU/edit#gid=0).

## How do I use this?
You can get the flag for any country just by its two-letter code. Just access http://flags.ox3.in/svg/xx.svg, where "xx" is the [ISO 3166 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements) country code (in lowercase).

This repository also has flags for many subdivisions of countries (including U.S. states, Canadian provinces, etc). Just access http://flags.ox3.in/svg/xx/yyy.svg, where "xx" is the first part of the [ISO 3166-2](https://en.wikipedia.org/wiki/ISO_3166-2#Current_codes) code and "yyy" is the second part after the dash (again, both parts in lowercase).

If SVGs don't suit your purpose, you can also access very low resolution PNGs via http://flags.ox3.in/mini/xx.png and http://flags.ox3.in/mini/xx/yyy.png. However, be warned that I will probably be changing the directory structure for PNGs in the near future, so you shouldn't rely on it.

## Why does this exist?
I originally made this repository to allow me to easily embed flags in Google Sheets. You can read more about how to do that [here](https://github.com/oxguy3/flags/blob/gh-pages/GOOGLE_SHEETS.md).

## Is this freely usable?
Yes! Most of these flags are public domain images from Wikimedia Commons, so you can do with them what you want. Flags that are not freely licensed are listed in the SPECIAL_LICENSES text file. Everything else in this directory that is not an image file is licensed under [the MIT license](http://oxguy3.mit-license.org/).

## I don't recognize Country X as an independent state; why does this repository include them?
This repository is meant to be a useful developer resource, not an authority on which countries should and shouldn't be recognized. Any state that has an established unique ISO 3166 two-letter country code (more specifically, an ISO 3166-1 alpha-2 code) and a flag meets the criteria for inclusion in this repository, regardless of how widely recognized that state is.

If you don't want to recognize a country, just don't use that particular flag.
