# Awesome 8bf [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Photoshop-compatible filter plug-ins (`.8bf`), and the programs that run them.

`.8bf` is the filter plug-in format Photoshop has used since the 1990s. Thousands of filters were written for it, many by people who gave them away, and plenty of those creators' sites are gone now. This list tracks the free filters that can still be downloaded, who made them, and whether a modern 64-bit host can load them.

Every filter here is a Windows plug-in. Older ones are often 32-bit only and won't load in a 64-bit host; each entry says which. "Freeware" means free under the creator's own terms, so read each license before using a filter commercially.

## Contents

- [Filters](#filters)
- [Filter Makers](#filter-makers)
- [Hosts](#hosts)

## Filters

- [G'MIC-8bf](https://github.com/0xC0000054/gmic-8bf) - The G'MIC-Qt filter browser, with 500+ filters, as one plug-in. By Nicholas Hayes, on G'MIC by David Tschumperlé (GREYC). 64-bit. MIT, GPL-3.0 and CeCILL.
- [Richard Rosenman Freeware](https://richardrosenman.com/product-category/freeware/) - 35 filters, including fractals and attractors, halftone, ASCII art, lens effects, scanlines, spherify and tiler. 64-bit. Freeware under his [EULA](https://richardrosenman.com/eula/).
- [Flaming Pear Freebies](https://www.flamingpear.com/freebies.html) - About 40 small effects, including Kyoto Color, Pixel Trash, Solidify and Sphere Warp. By Lloyd Burchill. 64-bit. Freeware.
- [Harry's Filters](https://www.thepluginsite.com/products/harrysfilters/index.htm) - 69 effects in one interface. By Harald Heim, The Plugin Site. 64-bit. Freeware; the download link is sent by email.
- [PhotoFreebies](https://www.thepluginsite.com/products/photowiz/photofreebies/index.htm) - 12 photo filters. By Harald Heim, The Plugin Site. 64-bit. Freeware; the download link is sent by email.
- [Mehdi Plugins](https://www.mehdiplugins.com/) - Colour, curves, LUT, texture, kaleidoscope and distortion tools. 5 of 29 are 64-bit. Freeware.
- [Pattern Suppressor](https://ft.rognemedia.no) - Removes halftone screens and paper texture with Fourier transforms. By Ron Chambers, Francesco Pierfederici and Jonas Rogne. 64-bit. Free for personal and commercial use ([source](https://github.com/rechmbrs/FtPattern)). Needs the FFTW DLL beside the host.
- [VanDerLee](https://www.vanderlee.com/download.html) - Ten filters, including formerly paid ones (Halftone, OldMovie, UnPlugged-X) with published unlock keys. By Martijn W. van der Lee. 64-bit support unverified. Freeware.
- [Redfield Plugins](https://www.redfieldplugins.com/Downloads.htm) - Sharplet, Saturation Equalizer, Fine Touch and Face Control. Partly 64-bit. Freeware; the installers are unsigned.
- [Martin Vicanek](https://www.vicanek.de/imageprocessing.htm) - Color Cube, Contrast Mask, PanoWarp, Perspective, Vignette Corrector and more. Only Wire Worm is 64-bit. Freeware, commercial use allowed.
- [Cybia](https://www.cybia.co.uk/) - 21 filters in The Works, Fotomatic and Colour Studio. By Steve Upham. 32-bit. Freeware, commercial use allowed.
- [NVIDIA Normal Map Filter](https://developer.download.nvidia.com/tools/files/Photoshop_Plugins_x64_8.55.0109.1800.exe) - Legacy normal-map and DDS plug-ins, version 8.55. Direct installer link; the landing page is gone. 64-bit. Free.
- [AutoInterlace Free](https://www.namesuppressed.com/design/plugins-autint.shtml) - Scanline and interlace effects. By Kohan Ikin. 64-bit. Free.
- [ViaThinkSoft Filters](https://misc.daniel-marschall.de/photoshop_filters/) - Nine utilities: greyscale, gradient colorize, two-colour and colour to transparency. By Daniel Marschall. 64-bit. Free.
- [Telegraphics Filters](http://www.telegraphics.net/sw/browse/Filters) - Count Colours, Scramble, Life and others. By Toby Thain. 2 of 6 are 64-bit. GPL.
- [Photo-Plugins](https://www.photo-plugins.com/) - Black-and-white conversion, local contrast, soft focus and lens correction. By George Fournaris. 32-bit. Donationware.
- [Graphic Filters](https://github.com/hayabuzo/Graphic-Filters) - WindyPixel, RevoStamp, PatTrick, Zebra and more. By Sergey Egorov. 32-bit. MIT.
- [RC Filters](https://www.russellcottrell.com/RCFilters/) - VHR Unsharp Mask. By Russell Cottrell. 64-bit. GPL-3.0; unregistered builds save up to 720 px, and a $9 key removes the limit.

Filters whose creators' sites are gone survive only in the Internet Archive. They are listed separately in [archived.md](archived.md).

## Filter Makers

- [Filter Foundry](https://www.viathinksoft.com/projects/filter_foundry) - Replacement for Adobe's Filter Factory: write per-pixel formulas and save them as standalone 64-bit filters. By Toby Thain and Daniel Marschall. GPL-2.0 ([releases](https://github.com/danielmarschall/filter_foundry/releases)).

## Hosts

- [Adobe Photoshop](https://www.adobe.com/products/photoshop.html) - The original host.
- [Affinity](https://www.affinity.studio/help/filters-plugins/) - Loads 64-bit filters on Windows and macOS.
- [PhotoLine](https://www.pl32.com/) - Image editor for Windows and macOS.
- [IrfanView](https://www.irfanview.com/) - Image viewer for Windows, with 8bf support through a plug-in.
- [XnView](https://www.xnview.com/) - Image viewer for Windows.
- [PSFilterPdn](https://github.com/0xC0000054/PSFilterPdn) - Runs 8bf filters in Paint.NET.
- [8bf-host](https://github.com/distortionary-labs/8bf-host) - Runs filters with no editor, from the command line or as an HTTP server, on Linux, Windows and macOS. Windows filters run under Wine on Linux.
- [krita-8bfhost-bridge](https://github.com/distortionary-labs/krita-8bfhost-bridge) - Runs 8bf filters in Krita, through 8bf-host.
- [comfy-8bfhost-bridge-nodes](https://github.com/distortionary-labs/comfy-8bfhost-bridge-nodes) - Runs 8bf filters as ComfyUI nodes, through 8bf-host.

GIMP 2.10 could load 8bf filters through the PSPI plug-in. GIMP 3 can't.

## Contributing

Additions and corrections are welcome; see [contributing.md](contributing.md). Reports of which filters load in which hosts are especially useful.

## Footnotes

Maintained by [Distortionary](https://distortionary.com). We make paid filters, so none of ours are listed; this list is for free ones.
