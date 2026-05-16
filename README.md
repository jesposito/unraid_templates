# Jed Esposito's Unraid Templates

Docker container templates for [Unraid](https://unraid.net) Community Apps.

## Available Templates

| App | Description |
|-----|-------------|
| [Facet](templates/facet.xml) | Self-hosted personal profile platform. Multiple views of your profile for different audiences (recruiters, conferences, clients). |
| [Translarr](templates/translarr.xml) | AI subtitle translator for the arr stack. Plugs into Sonarr, Radarr, Emby, Jellyfin. Translates wrong-language subtitle tracks with an LLM and drops a clean `.srt` next to the video. |

## Installation

These templates are submitted to the official Unraid Community Apps catalog at [ca.unraid.net](https://ca.unraid.net). After approval, install them from the **Apps** tab on your Unraid server.

To use this repository directly as a third-party template repo, add this URL in Community Applications:

```
https://github.com/jesposito/unraid_templates
```

## Repository Layout

```
unraid_templates/
├── LICENSE                       MIT
├── README.md
├── ca_profile.xml                Maintainer profile (required by CA)
├── images/                       Template icons (1024x1024 PNG)
│   ├── facet-icon.png
│   └── translarr-icon.png
└── templates/                    Docker container templates
    ├── facet.xml
    └── translarr.xml
```

## Support

- **Facet** issues: <https://github.com/jesposito/Facet/issues>
- **Translarr** issues: <https://github.com/jesposito/translarr/issues>
- **This template repo** issues: <https://github.com/jesposito/unraid_templates/issues>

## License

[MIT](LICENSE)
