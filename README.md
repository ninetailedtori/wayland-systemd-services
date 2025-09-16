# wayland-systemd-services

These are my personally written units for various Wayland WMs for Systemd management of automatically starting units! Let me know if you'd like to request specific changes or requests for WMs to add.

## Usage:

<details>
  <summary>Hyprland</summary>

  `exec-once = systemctl start --user hypr-session.service`

</details>

<details>
  <summary>Sway</summary>

  `exec --no-startup-id systemctl start --user sway-session.service`

</details>