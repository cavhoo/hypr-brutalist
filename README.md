# Hypr Brutalist

A minimalist, brutalist-inspired configuration for [Hyprland](https://hyprland.org/), a dynamic tiling Wayland compositor. This project provides a clean, functional, and aesthetically raw setup for users who appreciate simplicity and efficiency in their desktop environment. Designed to be lightweight and highly customizable, Hypr Brutalist delivers a no-frills experience with a focus on productivity and a distinctive, unpolished visual style.

## Features

- **Brutalist Aesthetic**: Embraces a raw, utilitarian design with bold contrasts and minimal ornamentation.
- **Hyprland Integration**: Leverages Hyprland's dynamic tiling for efficient window management.
- **Custom Keybinds**: Intuitive shortcuts for seamless navigation and control.
- **Lightweight**: Optimized for performance, keeping resource usage low.
- **Modular Configuration**: Easily tweak settings to suit your workflow.

## Installation

### Prerequisites

- [Hyprland](https://hyprland.org/) installed (version >= v0.33.1 recommended).
- A Wayland-compatible system (Arch Linux or other Arch-based distributions work best).
- Basic familiarity with Linux configuration files.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/cavhoo/hypr-brutalist.git ~/.config/hypr-brutalist
   ```

2. **Copy Configuration Files**:
   Move the configuration files to your Hyprland config directory:
   ```bash
   cp -r ~/.config/hypr-brutalist/* ~/.config/hypr/
   ```

3. **Install Dependencies**:
   Ensure you have the necessary dependencies for Hyprland and any additional tools used in this configuration (e.g., `waybar`, `walker`, `hyprpaper` for wallpaper management). Refer to the [Hyprland Wiki](https://wiki.hyprland.org/) for a full list of recommended packages.

4. **Customize (Optional)**:
   Edit `~/.config/hypr/configs/keyboard/keybinds.conf` to adjust keybinds.

5. **Restart Hyprland**:
   Log out and back into your Hyprland session, or run:
   ```bash
   hyprctl reload
   ```

## Configuration

The configuration is stored in `~/.config/hypr/hyprland.conf` and related files. Key components include:

- **Window Management**: Dynamic tiling with customizable layouts.
- **Keybinds**: Preconfigured for common tasks (e.g., launching apps, switching workspaces).
- **Appearance**: Brutalist-inspired color scheme with high-contrast elements.
- **Scripts**: Custom scripts for wallpaper switching and system controls.

For detailed configuration options, see the [Hyprland Wiki](https://wiki.hyprland.org/Configuring/Configuring-Hyprland/).

## Screenshots

*Insert screenshot of the desktop here* ![Desktop Center Layout](/screenshots/desktop_full.jpg?raw=true "Full Desktop Style")
*Insert screenshot of the workspace overview here*

*Insert screenshot of the application launcher here*

## Usage

- **Status Bar**: Configured with `waybar` for a minimal, functional interface.
- **Application Launcher**: Launch apps with `walker` using `SUPER + R`.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests on [GitHub](https://github.com/cavhoo/hypr-brutalist). Please ensure your changes align with the brutalist aesthetic and maintain compatibility with Hyprland.

## Acknowledgments

- [Hyprland](https://hyprland.org/) for the powerful compositor.
- The Linux and Wayland communities for their open-source contributions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
