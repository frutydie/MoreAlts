# MoreAlts+

A modern MoreAlts account switcher plugin for Revenge/Vendetta Discord Android clients.

## Install

In Revenge/Vendetta, open the plugin installer and use this manifest URL:

`https://raw.githubusercontent.com/frutydie/MoreAlts/main/manifest.json`

The compiled plugin bundle is available at the repository root as `index.js`, and the matching manifest is `manifest.json`.

## Material You theme

Install the Material You theme from this URL:

`https://raw.githubusercontent.com/frutydie/MoreAlts/main/themes/material-you-google.json`

In Revenge, open **Settings → Themes**, paste the URL, and press **Install**. Themes++ is recommended for the icon overlays and enhanced theme compatibility.

## Included features

- Native profile-bar account switcher button beside the notification control.
- Compact account picker with avatars, display names, usernames, and account switching.
- MoreAlts+ settings page with adaptive Discord/Revenge styling.
- Semantic action icons and password fields hidden by default.
- Eye controls for showing and hiding export and sign-in passwords.

The `plugins/MoreAlts` directory contains the maintainable source plugin. The repository workflow rebuilds the plugin and publishes the generated `dist/MoreAlts` folder to GitHub Pages when Pages is enabled.
