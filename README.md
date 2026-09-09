# CachaçaFlix Theme

A personalized fork of **[ElegantFin](https://github.com/lscambo13/ElegantFin)** by [lscambo13](https://github.com/lscambo13) — a dark theme for [Jellyfin](https://jellyfin.org).

This version exists purely as a personal customization, made in homage to my cat. All credit for the original theme, its structure, and its features goes to lscambo13.

## What's different from the original

- Accent color changed to purple (`#5200c1`), with the rest of the palette (backgrounds, borders, header) derived from it
- Custom logo in the header and on the loading screen
- Custom background image on the login screen
- Custom cover art for every media library type (Movies, TV Shows, Music, Live TV, Playlists, Collections, Home Videos, Books, Folders, Mixed, Recorded Movies, Recorded TV, Anime, Sports)

Everything else — layout, behavior, all other ElegantFin features and add-ons — is unchanged from upstream. See the [original repo](https://github.com/lscambo13/ElegantFin) for full documentation on how the base theme works.

## Install

In Jellyfin, go to **Dashboard → General → Custom CSS** and paste:

```css
@import url("https://cdn.jsdelivr.net/gh/ELR0SA/CachacaFlix-Theme@main/Theme/CachacaFlix-Theme.css");
```

Save and refresh your browser.
