# 🚀 m1klls-mihomo-rules

Fast, lightweight rule providers for Mihomo.

## Rule Sets

| Rule | Description |
|------|-------------|
| ai | AI services (ChatGPT, Claude, Gemini...) |
| dev | GitHub, GitLab, Docker, PyPI... |
| social | Discord, Instagram, Reddit... |
| streaming | YouTube, Twitch, Spotify... |
| games | iRacing, Nexus Mods... |
| mail | Proton Mail |

## Example

```yaml
rule-providers:

  ai:
    type: http
    behavior: classical
    format: yaml
    url: https://raw.githubusercontent.com/m1klls/m1klls-mihomo-rules/main/ai.yaml
    path: ./rule-sets/ai.yaml
    interval: 86400
```

MIT License.
