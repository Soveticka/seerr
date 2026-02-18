<p align="center">
<img src="./public/logo_full.svg" alt="Seerr" style="margin: 20px 0;">
</p>

> **⚠️ This is a personal fork of [Seerr](https://github.com/seerr-team/seerr).**
> It adds support for a **Default Anime Sonarr Instance** — anime TV show requests are automatically routed to a dedicated Sonarr server, separate from the default server used for regular TV shows.
> For the official project, please visit [seerr-team/seerr](https://github.com/seerr-team/seerr).

---

**Seerr** is a free and open source software application for managing requests for your media library. It integrates with the media server of your choice: [Jellyfin](https://jellyfin.org), [Plex](https://plex.tv), and [Emby](https://emby.media/). In addition, it integrates with your existing services, such as **[Sonarr](https://sonarr.tv/)**, **[Radarr](https://radarr.video/)**.

## Fork Additions

- **Default Anime Sonarr Instance** — Mark a Sonarr server as "Default Anime Server" in Settings → Services → Sonarr. Anime TV show requests (detected via TMDB keyword) are automatically routed to that server. Falls back to the regular default server if no anime server is configured. Explicit server overrides on individual requests always take priority.

## Current Features

- Full Jellyfin/Emby/Plex integration including authentication with user import & management.
- Support for **PostgreSQL** and **SQLite** databases.
- Supports Movies, Shows and Mixed Libraries.
- Ability to change email addresses for SMTP purposes.
- Easy integration with your existing services. Currently, Seerr supports Sonarr and Radarr. More to come!
- Jellyfin/Emby/Plex library scan, to keep track of the titles which are already available.
- Customizable request system, which allows users to request individual seasons or movies in a friendly, easy-to-use interface.
- Incredibly simple request management UI. Don't dig through the app to simply approve recent requests!
- Granular permission system.
- Support for various notification agents.
- Mobile-friendly design, for when you need to approve requests on the go!
- Support for watchlisting & blocklisting media.

With more features on the way! Check out our [issue tracker](/../../issues) to see the features which have already been requested.

## Getting Started

Check out the upstream documentation for instructions on how to install and run Seerr:

https://docs.seerr.dev/getting-started/

## Preview

<img src="./public/preview.jpg" alt="Seerr application preview" />

## Migrating from Overseerr/Jellyseerr to Seerr

Read the upstream [release announcement](https://docs.seerr.dev/blog/seerr-release) to learn what Seerr means for Jellyseerr and Overseerr users.

Please follow the upstream [migration guide](https://docs.seerr.dev/migration-guide) for detailed instructions on migrating from Overseerr or Jellyseerr.

## Support

- Check out the [Seerr Documentation](https://docs.seerr.dev) before asking for help. Your question might already be in the docs!
- For issues specific to this fork, open an issue in [this repository](https://github.com/Soveticka/seerr/issues).
- For general Seerr support, join the [Discord](https://discord.gg/seerr) or use [GitHub Discussions](https://github.com/seerr-team/seerr/discussions).

## API Documentation

You can access the API documentation from your local Seerr install at http://localhost:5055/api-docs

## Contributing

This fork is based on [seerr-team/seerr](https://github.com/seerr-team/seerr). Contributions to the upstream project are welcome via their [Contribution Guide](https://github.com/seerr-team/seerr/blob/develop/CONTRIBUTING.md).
