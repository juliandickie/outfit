# juliandickie-plugins

Plugins by Julian Dickie for [Claude Code](https://www.anthropic.com/claude-code).

## What's here

This is a marketplace catalog repo. The actual plugins live in their own repos and are referenced via `marketplace.json`.

| Plugin | Description |
|---|---|
| [ac-builder](https://github.com/juliandickie/ac-builder) | Build ActiveCampaign email sequences from markdown via MJML |
| [linkedin-post-studio](https://github.com/juliandickie/linkedin-post-studio) | Profile-driven LinkedIn content generation |
| [creators-studio](https://github.com/juliandickie/creators-studio) | AI image and video Creative Director |
| [scribe](https://github.com/juliandickie/scribe-plugin) | Google Workspace automation (Drive, Docs, Gmail) |

## Install

In Claude Code:

```
/plugin marketplace add juliandickie/plugins
```

Then browse and install with:

```
/plugin install <plugin-name>@juliandickie-plugins
```

For example, to install `ac-builder`:

```
/plugin install ac-builder@juliandickie-plugins
```

## Author

Julian Dickie - [github.com/juliandickie](https://github.com/juliandickie)

## License

This catalog (the marketplace.json and README) is MIT licensed. Each plugin has its own license; see the individual plugin repos.
