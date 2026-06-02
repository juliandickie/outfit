# Outfit

A growing set of advanced AI marketing, sales, and automation skills and plug-ins for [Claude Code](https://www.anthropic.com/claude-code), by Julian Dickie. Copywriting, email sequences, social content, AI creative, Google Workspace, and commerce, all driven by natural-language conversation.

## What's here

This is a marketplace catalog repo. The actual plugins live in their own repos and are referenced via `marketplace.json`. Adding this one marketplace gives you all of them.

| Plugin | Description |
|---|---|
| [ac-builder](https://github.com/juliandickie/ac-builder) | Build ActiveCampaign email sequences from markdown via MJML. Rendering, validation, V1 campaign creation, V3 click-action wiring, theme-driven multi-brand workflows. |
| [linkedin-post-studio](https://github.com/juliandickie/linkedin-post-studio) | Profile-driven LinkedIn content - posts, carousels, hooks, polls, video scripts, newsletters, calendars, repurposing. |
| [creators-studio](https://github.com/juliandickie/creators-studio) | AI image and video Creative Director powered by Gemini Nano Banana, Kling v3, VEO 3.1, ElevenLabs, and Lyria. |
| [scribe](https://github.com/juliandickie/scribe-plugin) | Google Workspace orchestration - Gmail, Calendar, Drive, Docs, Sheets, Slides, Contacts, Tasks, Forms, Chat. 14 cross-service workflow commands plus 10 service skills. |
| [spiffy](https://github.com/juliandickie/spiffy-plugin) | Talk to the Spiffy checkout platform - customer lookup, MRR, affiliate, and churn reports, customer notes, one-off promo codes. Works with any Spiffy account. |
| [clickup](https://github.com/juliandickie/clickup-plugin) | Talk to ClickUp - token-disciplined task access, gated single and bulk writes, and a large-job batch runner with deeper API coverage than the stock connector. Works with any ClickUp workspace. |
| [vimeo](https://github.com/juliandickie/vimeo-plugin) | Push Descript exports from Google Drive into your Vimeo library - multi-language captions and subtitles, title and description sync, and a gated source-file replace. Driven by a Google Sheet manifest read through the Scribe plugin. |
| [descript](https://github.com/juliandickie/descript-plugin) | Full programmatic access to the Descript API - import media, Underlord AI agent edits, publish compositions, inspect jobs, and run bulk video pipelines. Node CLI wrapped by skills with an optional MCP shim. Supply your own Descript API token. |
| [stripe](https://github.com/juliandickie/stripe-plugin) | Full multi-account Stripe API access - every endpoint the pinned stripe-node SDK exposes, standalone keys and Stripe Connect. Binary-enforced read, mutating, and destructive safety tier with live-mode arming, read-only multi-account fan-out, and the bundled Stripe CLI for webhooks. Replaces the single-account MCP connector. Supply your own Stripe keys. |
| [wp-index](https://github.com/juliandickie/wp-index) | Extract and index any WordPress site via its REST API - per-item Markdown, CSV, a JSON archive, and a Claude knowledge-base file. Standard-library Python, zero install, any post type via a flag. Supply your own site URL and optional Application Password. |

## Install

In Claude Code, add the marketplace:

```
/plugin marketplace add juliandickie/outfit
```

Then install any plugin from it:

```
/plugin install <plugin-name>@outfit
```

For example:

```
/plugin install scribe@outfit
```

```
/plugin install spiffy@outfit
```

Each plugin has its own setup (some need OAuth or an API key). Follow the install prompts or the plugin's own README.

## Author

Julian Dickie - [github.com/juliandickie](https://github.com/juliandickie)

## License

This catalog (the marketplace.json and README) is MIT licensed. Each plugin has its own license; see the individual plugin repos.
