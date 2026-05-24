# grub2-theme-dharma-arc

Dark GRUB2 theme based on the Dharma theme by Malcer (Chakra Project), recolored to match the Arc Dark Gray KDE color scheme.

## Preview

Dark gradient background (`#13191c` → `#222831`) with Arc's accent blue (`#3daee9`), low brightness for night boots. Same clean Dharma layout and icons.

## Installation

### Manual

```bash
sudo cp -r dharma-arc /boot/grub/themes/
sudo sed -i 's|^GRUB_THEME=.*|GRUB_THEME="/boot/grub/themes/dharma-arc/theme.txt"|' /etc/default/grub
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

### AUR (coming soon)

```bash
yay -S grub2-theme-dharma-arc
```

## Colors

| Element | Color | ArcDarkGray KDE key |
|---------|-------|---------------------|
| Background (top) | `#13191c` | Window BackgroundAlternate |
| Background (bottom) | `#222831` | Window BackgroundNormal |
| Text / title | `#d3dae3` | ForegroundNormal |
| Unselected items | `#898d99` | ForegroundInactive |
| Selected items | `#fcfcfc` | Selection ForegroundActive |
| Accent blue | `#3daee9` | ForegroundActive |

## License

CC BY-SA 3.0 — derivative work of Dharma GRUB2 theme by Malcer (Chakra Project, 2012). Dark adaptation and Arc recolor by @fedebyes.
