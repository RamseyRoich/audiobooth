# Audio-booth

**Audio-booth** is a desktop music app that brings your streaming services into one player. Search YouTube Music, Spotify, Apple Music and other platforms in a single search bar, then play, queue, like and organize tracks no matter where they come from. Build playlists across services, reorder your queue by dragging, save it for later, and download tracks for offline listening. It supports multiple profiles, a clean dark interface and a mini-player that's always visible. Available for Windows now, with Linux support on the way.

> **Status:** early development. The features below describe the planned app.

## Features

### Navigation
- Collapsible sidebar with **Home**, **Search**, **Downloads**, **Your Library**, **Platforms** and **Now Playing**
- Plan badge (Free / PRO) with an **Upgrade to PRO** button
- **Add a profile** and **Settings** at the bottom of the sidebar

### Cross-platform search
- One search bar across YouTube Music, Spotify, Apple Music and other platforms
- Every track carries a badge showing the platform it comes from
- **Platforms** page to connect and manage your streaming accounts

### Now Playing
- Compact header: album art beside the title, artist and album, so the lyrics get most of the screen
- **Add to playlist**, **Download** and **Like** buttons
- "Playing from" label (queue, playlist or album)
- Seek bar with elapsed and total time
- Shuffle, previous, play/pause, next and repeat
- Volume slider with a percentage, playback speed picker (1×) and a "more" (…) menu
- **Lyrics panel** filling the rest of the view:
  - Synced lyrics highlight the current line, auto-scroll, and let you click a line to jump there
  - Plain lyrics show as a scrollable block
  - "No lyrics available" when none can be found
- Planned extras: blurred album-art background, and tabs for Lyrics, Credits / About the artist, and Related tracks

### Up Next queue
- Track count and drag to reorder
- **Save** the queue as a playlist, or **Clear** it

### Mini-player
Always visible at the bottom of the window:
- Album art, title, artist and like button
- Full transport controls and seek bar
- Source badge, volume, queue button with a count, and a button to expand to Now Playing

### Library and downloads
- Liked songs, playlists and saved queues
- Offline downloads

### Profiles and plans
- Multiple user profiles
- **Free** plan with limits on downloads, queue length, playlists and profiles
- **PRO** plan that lifts those limits

## Platform support

| Platform | Status |
| --- | --- |
| Windows | First target |
| Linux | Planned |

## Notes and roadmap

- **Spotify and Apple Music** don't allow their audio to be downloaded or streamed inside third-party apps. For those services Audio-booth will use their official SDKs or hand playback off to the official app, and offline downloads won't be available for their tracks.
- **Lyrics** on the major services come from licensed providers (mostly Musixmatch and LyricFind). The public release will need a licensed lyrics API rather than reading lyrics from each service directly.
