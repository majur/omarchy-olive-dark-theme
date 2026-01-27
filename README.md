# 🫒 Olive Dark

A clean, modern dark theme with a refreshing olive/green palette and subtle glassmorphism for a cohesive, focused desktop experience.

**Features:**

* **Dark Theme:** Easy on the eyes with a warm, dark background.
* **Glassmorphism:** Elegant, semi-transparent blur across all windows.
* **Fluid Animations:** Smooth, responsive transitions for a modern feel.
* **Custom Island Style Waybar:** Distinct pill-shaped modules, giving a clean and modern "dynamic island" aesthetic.

---

## Quick Install

```bash
omarchy-theme-install https://github.com/YOUR_USERNAME/omarchy-olive-dark-theme
```

## Olive Dark Waybar Installation

To install the **Olive Dark Waybar**, run the following commands in your terminal:

```bash
# Backup existing Waybar config
mkdir -p ~/Documents/default-waybar
[ -d ~/.config/waybar ] && mv ~/.config/waybar ~/Documents/default-waybar

# Copy Olive Dark Waybar files
mkdir -p ~/.config/waybar
cp ~/.config/omarchy/themes/olive-dark/waybar/config.jsonc ~/.config/waybar/
cp ~/.config/omarchy/themes/olive-dark/waybar/style.css ~/.config/waybar/

# Restart Waybar
omarchy-restart-waybar
```

---

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Background | `#1e1e1e` | Main background |
| Foreground | `#a7a7a7` | Primary text |
| Green (Primary) | `#82a966` | Accents, strings |
| Yellow/Gold | `#bc9172` | Warnings, highlights |
| Blue | `#6fa3cd` | Links, info |
| Red | `#c26f76` | Errors, critical |
| Magenta | `#a87bb6` | Keywords |
| Cyan | `#68b1ba` | Special elements |
| Orange | `#bc9172` | Constants, numbers |

---

## Screenshots

<!-- Add your screenshots here -->
