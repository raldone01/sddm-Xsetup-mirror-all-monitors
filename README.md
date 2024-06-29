# sddm-Xsetup-mirror-all-monitors

## Installation

1. Configure sddm to use X11 as the display server
2. Copy the script to `/usr/share/sddm/scripts/Xsetup`
3. Ensure the script is executable
4. `systemctl restart sddm` or reboot
5. Profit from a useful multi-monitor setup
6. **Optional**: Zou can configure the primary monitor by setting the `primary_display` variable in the script
