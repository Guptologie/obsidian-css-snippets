# Obsidian CSS snippets

Two independent desktop appearance tweaks:

| Snippet | Behavior |
| --- | --- |
| `no-ribbon-offset.css` | Reduces excess macOS traffic-light spacing when the ribbon is hidden and in pop-out windows. The 44px value was tuned with Underwater; validate with the default theme. |
| `sidebar-tabs-on-hover.css` | Collapses sidebar tab headers to a 4px strip, revealing them on hover or keyboard focus. Removes sidebar navigation padding and bottom Bookmarks padding. Touch devices keep headers visible; reduced-motion settings disable transitions. |

## Installation

Copy either CSS file to `<vault>/.obsidian/snippets/`, then enable it under Settings → Appearance → CSS snippets. No plugin or build step is required.

In this local setup, the vault snippets directory is a symlink to this repository. Edits in either location update the same files. If styles do not refresh, toggle the snippet off and on. Git identity is configured locally as Ankur Gupta <rukna1000@gmail.com>.

## Relationship to Compact Headers

The sidebar snippet changes appearance. The separate `compact-headers` plugin changes the JavaScript-enforced Bookmarks pane minimum to 100px. Either can be used independently.

## Validation before distribution

Check the default and Underwater themes, ribbon visibility, pop-out windows, both sidebars, keyboard focus, and reduced motion. Internal CSS selectors may change with Obsidian updates. Choose and add a distribution license before public release.
