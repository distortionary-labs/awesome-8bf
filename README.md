# Awesome 8bf [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Free Photoshop-compatible filter plug-ins (`.8bf`), and the programs that run them.

`.8bf` is the filter plug-in format Photoshop has used since the 1990s.
Thousands of filters were written for it, many by people who gave them away.
Plenty of those creators' sites are gone now. This list keeps track of the
free filters that can still be downloaded, who made them, and whether a
modern 64-bit host can load them.

Every filter here is a Windows plug-in. Older ones are often 32-bit only and
won't load in a 64-bit host. The **64-bit** column says which ones will.

## Contents

- [Filters](#filters)
- [Filter makers](#filter-makers)
- [Programs that run 8bf filters](#programs-that-run-8bf-filters)
- [Archived filters](#archived-filters)
- [Contributing](#contributing)

## Filters

Best first. "Freeware" means free to use under the creator's own terms; read
each license before using a filter commercially.

| Filter | Creator | 64-bit | License | What it does |
| --- | --- | --- | --- | --- |
| [G'MIC-8bf](https://github.com/0xC0000054/gmic-8bf) | Nicholas Hayes; G'MIC by David Tschumperlé (GREYC) | Yes | MIT, GPL-3.0, CeCILL | The whole G'MIC-Qt filter browser, 500+ filters, in one plug-in. |
| [Richard Rosenman Freeware](https://richardrosenman.com/product-category/freeware/) | Richard Rosenman | Yes | Freeware ([EULA](https://richardrosenman.com/eula/)) | 35 filters: fractals and attractors, halftone, ASCII art, lens effects, scanlines, spherify, tiler. |
| [Flaming Pear Freebies](https://www.flamingpear.com/freebies.html) | Lloyd Burchill, Flaming Pear Software | Yes | Freeware | About 40 small effects, including Kyoto Color, Pixel Trash, Solidify and Sphere Warp. |
| [Harry's Filters](https://www.thepluginsite.com/products/harrysfilters/index.htm) | Harald Heim, The Plugin Site | Yes | Freeware | 69 effects in one interface. Download link sent by email. |
| [PhotoFreebies](https://www.thepluginsite.com/products/photowiz/photofreebies/index.htm) | Harald Heim, The Plugin Site | Yes | Freeware | 12 photo filters. Download link sent by email. |
| [Mehdi Plugins](https://www.mehdiplugins.com/) | Mehdi | 5 of 29 | Freeware | Colour, curves, LUTs, textures, kaleidoscope and distortion tools. |
| [Pattern Suppressor / FT suite](https://ft.rognemedia.no) | Ron Chambers, Francesco Pierfederici, Jonas Rogne | Yes | Free, personal and commercial ([source](https://github.com/rechmbrs/FtPattern)) | Removes halftone screens and paper texture with Fourier transforms. Needs the FFTW DLL beside the host. |
| [VanDerLee](https://www.vanderlee.com/download.html) | Martijn W. van der Lee | Unverified | Freeware | Ten filters, including formerly paid ones (Halftone, OldMovie, UnPlugged-X) with published unlock keys. |
| [Redfield Plugins](https://www.redfieldplugins.com/Downloads.htm) | Redfield Plugins | Some | Freeware | Sharplet, Saturation Equalizer, Fine Touch, Face Control. Unsigned installers. |
| [Martin Vicanek](https://www.vicanek.de/imageprocessing.htm) | Martin Vicanek | Wire Worm only | Freeware, commercial use allowed | Color Cube, Contrast Mask, PanoWarp, Perspective, Vignette Corrector and more. |
| [Cybia](https://www.cybia.co.uk/) | Steve Upham | No | Freeware, commercial use allowed | 21 filters in The Works, Fotomatic and Colour Studio. |
| [NVIDIA Normal Map Filter 8.55](https://developer.download.nvidia.com/tools/files/Photoshop_Plugins_x64_8.55.0109.1800.exe) | NVIDIA | Yes | Free | Legacy normal-map and DDS plug-ins. Direct installer link; the landing page is gone. |
| [AutoInterlace Free](https://www.namesuppressed.com/design/plugins-autint.shtml) | Kohan Ikin, namesuppressed | Yes | Free | Scanline and interlace effects. |
| [ViaThinkSoft filters](https://misc.daniel-marschall.de/photoshop_filters/) | Daniel Marschall | Yes | Free | Nine utilities: greyscale, gradient colorize, two-colour, colour to transparency. |
| [Telegraphics filters](http://www.telegraphics.net/sw/browse/Filters) | Toby Thain | 2 of 6 | GPL | Count Colours, Scramble, Life and others. |
| [Photo-Plugins](https://www.photo-plugins.com/) | George Fournaris | No | Donationware | B/W conversion, local contrast, soft focus, lens correction. |
| [Graphic Filters](https://github.com/hayabuzo/Graphic-Filters) | Sergey Egorov (hayabuzo) | No | MIT | WindyPixel, RevoStamp, PatTrick, Zebra and more. |
| [RC Filters](https://www.russellcottrell.com/RCFilters/) | Russell Cottrell | Yes | GPL-3.0 | VHR Unsharp Mask. Unregistered builds save up to 720 px; a $9 key removes the limit. |

## Filter makers

Tools for building your own `.8bf` filters.

- [Filter Foundry](https://www.viathinksoft.com/projects/filter_foundry) - A replacement for Adobe's Filter Factory. Write per-pixel formulas and save them as standalone 64-bit filters. GPL-2.0, by Toby Thain and Daniel Marschall ([releases](https://github.com/danielmarschall/filter_foundry/releases)).

## Programs that run 8bf filters

- [Adobe Photoshop](https://www.adobe.com/products/photoshop.html) - The original host.
- [Affinity](https://www.affinity.studio/help/filters-plugins/) - Loads 64-bit `.8bf` filters on Windows and macOS.
- [PhotoLine](https://www.pl32.com/) - Windows and macOS.
- [IrfanView](https://www.irfanview.com/) - Through its Adobe 8BF plug-in support.
- [XnView](https://www.xnview.com/) - Windows.
- [PSFilterPdn](https://github.com/0xC0000054/PSFilterPdn) - Runs `.8bf` filters in Paint.NET.
- [8bf-host](https://github.com/distortionary-labs/8bf-host) - Runs filters with no editor at all, from the command line or as an HTTP server, on Linux, Windows and macOS. Windows filters run under Wine on Linux.
- [krita-8bfhost-bridge](https://github.com/distortionary-labs/krita-8bfhost-bridge) - `.8bf` filters in Krita, through 8bf-host.
- [comfy-8bfhost-bridge-nodes](https://github.com/distortionary-labs/comfy-8bfhost-bridge-nodes) - `.8bf` filters as ComfyUI nodes, through 8bf-host.

GIMP 2.10 could load `.8bf` filters through the PSPI plug-in. GIMP 3 can't.

## Archived filters

These creators' sites are gone, and the only copies left are in the Internet
Archive. All are 32-bit. **Don't visit the old live domains**: xero-graphics.co.uk,
8bf.net and littleinkpot.co.uk now belong to spammers.

| Filter | Creator | What it does | Archived page |
| --- | --- | --- | --- |
| Xero Classic | Pete Bailey, Xero Graphics | 40 subtle artistic and photo effects: Porcelain, Lineart, Soft Vignette. | [2016 snapshot](https://web.archive.org/web/2016/http://www.xero-graphics.co.uk/) |
| AAA Filters and Frames | Jim Clatfelter | AAA Options, Blender, Foto Frame, Frame Works, Multi-Filter. | [2012 snapshot](https://web.archive.org/web/2012/http://8bf.net/) |
| Little Ink Pot | Little Ink Pot / Software Geezers | Xpose, Thredgeholder, Chalkaholic Lite. | [2006 snapshot](https://web.archive.org/web/2006/http://www.littleinkpot.co.uk/) |
| Mura's Meister | MuRa | Copies, Cloud, Perspective Tiling, Pole Transform. LHa archives. | [GeoCities mirror](https://www.oocities.org/murakuma/) |
| Redfield classic freeware | Redfield Plugins | Jama 3D, Lattice Composer, Seamless Workshop, Water Ripples, Craquelure 3D. | Search the Internet Archive for redfieldplugins.com |

## Contributing

Additions and corrections are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).
Reports of which filters load in which hosts are especially useful.

---

Maintained by [Distortionary](https://distortionary.com). We make paid
filters, so none of ours are listed here; this list is for free ones.
