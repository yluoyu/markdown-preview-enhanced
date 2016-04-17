Markdown Preview Katex (atom-markdown-katex)
===
**By Yiyi Wang (shd101wyy)**
Still Beta Version!

Post [here](https://github.com/shd101wyy/atom-markdown-katex/issues) if you request new features or you want to report bugs ;)

(Toc below was created by this package)
<!-- toc -->

- [Markdown Preview Katex (atom-markdown-katex)](#markdown-preview-katex-atom-markdown-katex)
	- [How it works](#how-it-works)
	- [Support Features:](#support-features)
	- [Usages](#usages)
	- [Preview Context Menu](#preview-context-menu)
	- [Settings Panel](#settings-panel)
	- [TODO](#todo)

<!-- tocstop -->
---

![demo](https://cloud.githubusercontent.com/assets/1908863/14586110/159a9e86-0453-11e6-9d85-98d6ef2a142b.gif)

## How it works
- [remarkable](https://github.com/jonschlinkert/remarkable) to convert markdown to html
- [KaTeX](https://github.com/Khan/KaTeX) to render math expressions.
    - expression within `$...$` will be rendered normally
    - expression within `$$...$$` will be rendered in displayMode.
    - <img src="https://cloud.githubusercontent.com/assets/1908863/14398210/0e408954-fda8-11e5-9eb4-562d7c0ca431.gif">

## Support Features:
- **2-way scroll sync**
- markdown preview with **KaTeX** math expression support
- export PDF
- export beautiful HTML (mobile device supported)
- customize Markdown Preview css
- settings panel
- [TOC] generation **(beta)**

## Usages
To use this package, press <strong> cmd + shift + p </strong> in atom editor first to toggle <strong> Command Palette </strong>. Then choose the commands below:
- <strong>Markdown KaTeX Preview: Toggle</strong>
    - Toggle Markdown file preview with KaTeX support.
- <strong>Markdown KaTeX Preview: Customize CSS</strong>
    - Customize preview page css.  
- <strong>Markdown KaTex Preview: Toc Create </strong>
  - Generate TOC
	 or simply write ` <!-- toc -->` in editor (need preview toggled)
- <strong>Markdown KaTex Preview: Toggle Scroll Sync </strong>
    - Enable/Disable scroll sync for preview

## Preview Context Menu
Right click at preview to see the menu

![context menu](https://cloud.githubusercontent.com/assets/1908863/14586062/18852988-0451-11e6-9cc0-578d54384926.gif)

- <strong> Save as PDF </strong>
  - Create PDF in the same directory
- <strong> Save as HTML </strong>
  - Create HTML in the same directory
- <strong> Open in Browser </strong>
  - Open HTML in browser
- <strong> Copy as HTML </strong>
  - Copy HTML content to clipboard

## Settings Panel
![settings](https://cloud.githubusercontent.com/assets/1908863/14586083/fc84195a-0451-11e6-9778-5d09c0cbd252.gif)

## TODO
- fix bugs
- modify css to make preview look nice
- epub output

Thanks for using this package, I feel happy! ;)
