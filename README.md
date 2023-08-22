# Home Assistant Battery Notes

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

[![hacs][hacsbadge]][hacs]

[![Community Forum][forum-shield]][forum]

_Integration to add battery types to a device._

## UNDER EARLY DEVELOPMENT ##  
Do not use until there is a release.

**This integration will set up the following platforms.**

Platform | Description
-- | --
`sensor` | Show battery type.

## Installation

### HACS

1. Make sure the [HACS](https://github.com/custom-components/hacs) component is installed and working.
1. Add the project repository `https://github.com/andrew-codechimp/HA-Battery-Types` as a custom repository to HACS, see: https://hacs.xyz/docs/faq/custom_repositories
1. Search for `Battery Notes` in HACS and install it under the "Integrations" category.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Mastodon Profile Stats"

### Manual Installation

<details>
<summary>Show detailed instructions</summary>
1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `battery_notes`.
1. Download _all_ the files from the `custom_components/battery_notes/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Battery Notes"
</details>

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

## Acknowledgements

This integration has been heavily inspired by and a lot of code cribbed from the awesome [PowerCalc](https://github.com/bramstroker/homeassistant-powercalc).

***

[battery_notes]: https://github.com/andrew-codechimp/ha-battery-notes
[commits-shield]: https://img.shields.io/github/commit-activity/y/andrew-codechimp/battery-notes.svg?style=for-the-badge
[commits]: https://github.com/andrew-codechimp/ha-battery-notes/commits/main
[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[discord]: https://discord.gg/Qa5fW2R
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg?style=for-the-badge
[exampleimg]: example.png
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]: https://img.shields.io/github/license/andrew-codechimp/battery-notes.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/andrew-codechimp/battery-notes.svg?style=for-the-badge
[releases]: https://github.com/andrew-codechimp/ha-battery-notes/releases
