# 3x-ui-auto_add_ssl

Bash script to execute after 3x-ui installation to automatically add self-signed SSL cert for the admin panel

## WARNING
  This script is intended to be ran only once on a VPS that has freshly-configured 3x-ui panel that has no SSL certificates set.

## How to use

1. Run after installation of 3x-ui panel

```
bash <(curl -Ls https://raw.githubusercontent.com/cyb3rm4gus/3x-ui-auto_add_ssl/refs/heads/main/3x-ui-autossl.sh)
```
2. Restart the panel

