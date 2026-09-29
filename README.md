<div align="center">

# Catppuccin for Beeper

😸 Soothing pastel theme for Beeper Desktop

</div>

Four standalone themes for Beeper Desktop v4, using the official Catppuccin palette. Each file colors the app panes, conversation list, message bubbles, composer, menus, controls, and status indicators. Mauve is the base interface accent. Latte uses Sapphire for sent-message bubbles; the dark flavors use Mantle for sent messages and Surface 0 for received messages. Accent variants can be added later.

## Flavors

| Flavor | Theme file | Appearance |
| --- | --- | --- |
| 🌻 Latte | [latte.css](themes/latte.css) | Light |
| 🪴 Frappé | [frappe.css](themes/frappe.css) | Dark |
| 🌺 Macchiato | [macchiato.css](themes/macchiato.css) | Dark |
| 🌿 Mocha | [mocha.css](themes/mocha.css) | Dark |

## Usage

1. Open the CSS file for your preferred flavor and copy its entire contents.
2. In Beeper Desktop v4, open **Settings → Appearance → Custom CSS → Open CSS file in editor**.
3. Replace the editor contents with the copied CSS and save.
4. Back in Beeper, click **Reload CSS**.

Each file is self-contained. Install one flavor at a time. To return to Beeper's default appearance, use **Reset CSS** in the same settings panel. The flavor stays fixed when your system changes between light and dark appearance.

## Palette and compatibility

The themes use [Catppuccin's official colors](https://github.com/catppuccin/catppuccin#-palette) and [style guide](https://github.com/catppuccin/catppuccin/blob/main/docs/style-guide.md): Base for the conversation pane, Mantle for the sidebar, Surface colors for controls and received messages, Text and Subtext for copy, and Mauve for selected items and sent messages. Green, Yellow, and Red retain their status meanings.

These files target the [Beeper Desktop v4 custom properties](https://github.com/beeper/themes/blob/main/current-v4/variables.css), including active v4 surface tokens and direct message rules. Current Beeper versions render outgoing bubbles from per-message `--bubble-out-*` properties and incoming bubbles from `--color-secondary-container`. Beeper can change those properties between releases, so please report visual regressions with the Beeper version, flavor, and a screenshot.

## 💝 Thanks to

- [Catppuccin](https://github.com/catppuccin/catppuccin) for the palette, style guide, and [port guidelines](https://github.com/catppuccin/catppuccin/blob/main/docs/port-creation.md).
- [harukayamazaki](https://github.com/catppuccin/catppuccin/discussions/2205) for the original Beeper port request.
- [PoorPocketsMcNewHold](https://gist.github.com/PoorPocketsMcNewHold/4ae6d7052208d01103159a0617d77316) for the Frappé theme reference.
- [Beeper's theme contributors](https://github.com/beeper/themes) for documenting the v4 custom properties and installation flow.

## License

[MIT](LICENSE)
# beeper
