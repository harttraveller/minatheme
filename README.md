# minatheme

A minimalistic theme for obsidian publish. The theme is a work in progress. Features are covered in the [features](#features) section of this README. Notes in the [design](#design) section are potentially worth skimming. Note that these lists aren't exhaustive, they just cover the stuff which stood out to me while skimming the code. You can find an example of the theme on [this](https://rokosphoenix.com) site.

## Setup

1. Ensure you have configured a custom domain with obsidian publish. More information can be found on the [obsidian](https://help.obsidian.md/Obsidian+Publish/Set+up+a+custom+domain) docs.
2. Add the [publish.js](publish.js) and [publish.css](publish.css) files to the home directory of the vault you are publishing.
3. Configure your publish settings according to the [settings](#settings) section. The theme may work, or may break other settings. This is untested.

## Settings

- theme: dark
- show hover preview: off
- hide page title: off
- readable line length: on
- strict line breaks: off
- stack pages: off
- show navigation: on
- show search bar: on
- show graph view: on
- show table of contents: on
- show backlinks: on

## Features

### Keyboard Shortcuts

If you would like a keyboard shortcut added, or think a shortcut key should be changed, please submit a GitHub issue.

- [x] pressing `/` toggles quick search
- [x] pressing `:` returns to the home page
- [x] pressing `[` toggles the local graph
- [x] pressing `]` toggle the global graph

### Interface

- [x] Add copy code button to code blocks
  - [ ] adjust code block padding so there isn't overlap
- [x] clicking on site logo returns to home page
- [x] left and right sidebars are dimmed when not hovering

### Interoperability

- [x] `publish.jss` detects whether the user is on mobile and accordingly disables left sidebar dimming

### Classes

- [x] Add extra callouts
  - [x] aperture
  - [x] fingerprint
- [x] add `header-image` class for header images so the text is overlaid
- [x] dim header images so the text is visible

## Design

### Fonts Used

- [x] [Oxygen Mono](https://fonts.google.com/specimen/Oxygen+Mono?query=oxygen+mono) is used for the sidebar text.
- [x] [Inter](https://fonts.google.com/specimen/Inter?query=inter) is used for the page text.

### Markdown Embeds
- [x] Markdown embed aesthetics are (imho) improved.

### Other Adjustments

- [x] site color is black
- [x] heading colors are light to dark red gradient
- [x] heading sizes are adjusted
- [x] tooltips are removed
- [x] site footer is removed
- [x] inline code is green
- [x] question callout is green
- [x] minimalize page title
- [x] underlines are removed from links
- [x] external links are blue, internal links are red
- [x] external link icon is removed
- [x] site name is removed
- [x] text is justified
- [x] hovering on site logo increases brightness and size
- [x] backlink box is improved
- [x] heading links are removed
- [x] graph view is flush with page
- [x] hovering on tags is animated
- [x] tag color adjusted
- [x] tags squared
