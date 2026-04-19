# System Content

Internal system content — prompts and runtime text served via the Hub API.

Content in this repo is fetched by the skrptiq app at runtime via `GET /api/system-content/:slug`. It is not visible in the public Hub catalogue.

## Structure

Each content item is a directory with a markdown file:

```
quick-voice-analysis/
  prompt.md          ← system prompt content
onboarding-tips/
  content.md         ← text content
```

## Adding content

1. Create a directory with a descriptive slug (lowercase, hyphens)
2. Add `prompt.md` (for prompts) or `content.md` (for general text)
3. Push to main
4. Add an entry to the Internal admin system content registry
5. Content is available via Hub API within seconds (CF edge cache: 1h)
