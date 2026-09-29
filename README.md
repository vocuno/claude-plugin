# Vocuno for Claude

Official Claude plugin for [Vocuno](https://vocuno.com), the AI music studio. It connects Claude to Vocuno's remote MCP server so Claude can create and edit music directly in your Vocuno account.

## What Claude can do with it

- **Generate songs**: full AI songs with vocals from a text prompt or your own lyrics, across multiple state-of-the-art music models.
- **Covers and remixes**: reimagine a song in a new style, or build mashups of two tracks.
- **Stems**: separate any track into vocals, drums, bass, and instruments; remove reverb; extract MIDI from stems.
- **Voice**: convert vocals to a different voice, or clone a voice for use in generations.
- **Song tools**: extend a song, replace a section, mix, master, detect BPM and chords, convert audio formats.
- **Audio editing**: a set of free FFmpeg-based editing tools (trim, fade, speed, pitch, volume, and more).
- **Account**: check remaining credits and fetch the status and shareable links of your generations.

Everything runs in your Vocuno library: songs created through Claude appear at [vocuno.com/app](https://vocuno.com/app) like anything you make on the site, with shareable streaming links returned as results.

## Installation

In Claude apps (web, desktop, mobile) and Cowork: open **Customize**, go to
**Plugins**, then **Discover**, and search for Vocuno.

In Claude Code:

```
/plugin install vocuno
```

Or add the MCP server directly without the plugin:

```
claude mcp add --transport http vocuno https://vocuno.com/mcp
```

On first use Claude opens a browser window to sign in to Vocuno (OAuth 2.1). Approve the connection and you are done; no API keys to manage.

## Requirements

- A Vocuno account ([sign up free](https://vocuno.com)). New accounts include free credits.
- Generation tools consume Vocuno credits, exactly as on the website. Editing and analysis tools marked free consume none.

## Support

- Homepage: [vocuno.com](https://vocuno.com)
- Contact: contact@vocuno.com
- Privacy policy: [vocuno.com/privacy](https://vocuno.com/privacy)

## License

This plugin package is MIT licensed. The Vocuno service itself is governed by the [Vocuno Terms of Service](https://vocuno.com/terms).
