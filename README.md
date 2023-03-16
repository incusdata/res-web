# Web Resources (CSS/Fonts) 

This repository contains Web resources like CSS files and copies of free fonts.
Some of the fonts have been optimized for Web use by removing some characters,
and adjusting the X-height.

The TrueType fonts (TTF) can be installed, and will be search for first in the
‘font stack’. This should prevent the `.woff` files from being downloaded.

## Usage

This repository is intended to be used as a **git** sub-module. Here is an
example command-line, to be executed in a git repository that wants to use this
as a sub-module. Our repositories expect resources in a `res` subdirectory, so
we use the `--name res` option:

```sh
git submodule add --name res \
   -- git@github.com:incusdata/res-web
```

## Font Licences

All font licences are under the [SIL Open Font License][w-sil-ofl]. All fonts
are are downloadable from their respective GitHub repositories.

* [**FiraGO**][firago-home] —  SIL [Open Font Licence][w-sil-ofl] (OFL) (also
  on [GitHub][gh-firago]).
* [**Source Serif**][sserif-home] — SIL [Open Font License][gh-sserif-lic].
* [**Iosevka**][gh-iosevka] — SIL [Open Font License][gh-iosveka-lic]

This reposity contains a modified version of **Iosevka**, called **IvcusCode**.

[firago-home]:
   https://bboxtype.com/typefaces/FiraGO/#!layout=specimen
   "bBoxType — FiraGO Specimen View & Download" 
[w-sil-ofl]:
   https://bboxtype.com/downloads/FiraGO/OFL.txt
   "bBoxType — FiraGO OFL License"
[gh-firago]:
   https://github.com/bBoxType/FiraGO
   "GitHub — bBoxType/FiraGO"
[gh-sserif]:
   https://github.com/adobe-fonts/source-serif
   "GitHub — adobe-fonts/source-serif"
[gh-sserif-lic]:
   https://github.com/adobe-fonts/source-serif/blob/release/LICENSE.md
   "GitHub — adobe-fonts/source-serif LICENSE.md"
[gh-iosevka]:
   https://github.com/be5invis/Iosevka
   "GitHub — be5invis/Iosevka"
[gh-iosevka-lic]:
   https://github.com/be5invis/Iosevka/blob/main/LICENSE.md
   "GitHub — be5invis/Iosevka LICENSE"
