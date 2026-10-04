# Obsidian CSS snippets

Two independent desktop appearance tweaks:

| Snippet | Behavior |
| --- | --- |
| `no-ribbon-offset.css` | Reduces excess macOS traffic-light spacing when the ribbon is hidden and in pop-out windows. The 44px value was tuned with Underwater; validate with the default theme. |
| `sidebar-tabs-on-hover.css` | Collapses sidebar tab headers to a 4px strip, revealing them on hover or keyboard focus. Removes sidebar navigation padding and bottom Bookmarks padding. Touch devices keep headers visible; reduced-motion settings disable transitions. |

## Installation

Copy either CSS file to `<vault>/.obsidian/snippets/`, then enable it under Settings → Appearance → CSS snippets. No plugin or build step is required.

In this local setup, the vault snippets directory is a symlink to this repository. Edits in either location update the same files. If styles do not refresh, toggle the snippet off and on. Git identity is configured locally as Ankur Gupta <rukna1000@gmail.com>.

## Relationship to Better Headers

[Better Headers](https://github.com/Guptologie/compact-headers) (formerly Compact Headers) includes the sidebar hover and spacing styles from `sidebar-tabs-on-hover.css` starting in version 1.1.0. It adds independent left/right hover toggles, spacing controls, an optional 100px Bookmarks pane minimum, and sidebar visibility commands.

When using Better Headers, disable **sidebar-tabs-on-hover** in Settings → Appearance → CSS snippets. Leaving it enabled overrides the plugin's per-sidebar controls. The standalone snippet remains available for users who do not want the plugin. `no-ribbon-offset.css` can remain enabled with either setup.

## Validation before distribution

Check the default and Underwater themes, ribbon visibility, pop-out windows, both sidebars, keyboard focus, and reduced motion. Internal CSS selectors may change with Obsidian updates. Choose and add a distribution license before public release.
