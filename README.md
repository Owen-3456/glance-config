# Glance Dashboard

Personal homelab dashboard running on Unraid via [Glance](https://github.com/glanceapp/glance).

## Widgets

| Widget             | Service                    | Source    |
| ------------------ | -------------------------- | --------- |
| Clock              | -                          | Built-in  |
| Verse of the Day   | YouVersion + ESV Bible API | Custom    |
| Notifications      | Gotify                     | Custom    |
| Markets            | Yahoo Finance              | Built-in  |
| Now Playing        | Tautulli                   | Community |
| Upcoming Episodes  | Sonarr                     | Custom    |
| Immich Stats       | Immich                     | Community |
| Overseerr Requests | Overseerr                  | Custom    |
| qBittorrent        | qBittorrent                | Community |
| Docker Containers  | Docker socket              | Built-in  |
| Server Stats       | Local (Unraid disks)       | Built-in  |
| Uptime Kuma        | Uptime Kuma                | Community |
| Internet Speed     | Speedtest Tracker          | Custom    |
| Tailscale Devices  | Tailscale API              | Community |
| Bookmarks          | Static                     | Built-in  |

## Environment Variables

All secrets are injected via environment variables set in the Unraid Docker template.

```txt
YOUVERSION_API_KEY
ESV_API_KEY
GOTIFY_CLIENT_TOKEN
TAUTULLI_KEY
SONARR_KEY
IMMICH_API_KEY
OVERSEERR_API_KEY
UPTIME_KUMA_STATUS_SLUG
SPEEDTEST_TRACKER_API_TOKEN
TAILSCALE_API_KEY
SERVER_ADDRESS
TAILSCALE_ADDRESS
```
