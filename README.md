# Kimi Search for OpenClaw

OpenClaw plugin for Kimi Search + Fetch tools.

## Installation

```bash
git clone https://github.com/hackceo/openclaw-kimi-search.git
```

## Configuration

Add to your `~/.openclaw/config.json`:

```json
{
  "kimi-search": {
    "search": {
      "baseUrl": "https://your-search-api.com"
    },
    "fetch": {
      "baseUrl": "https://your-fetch-api.com",
      "enableService": true
    }
  }
}
```

## License

MIT
