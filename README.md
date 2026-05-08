# claude-code-browser-act

A [Claude Code](https://claude.com/claude-code) plugin for browser automation via the [`browser-act` CLI](https://pypi.org/project/browser-act-cli/) — stealth browsing, captcha solving, proxy support, Real Chrome control, and structured page interaction.

Homepage: <https://www.browseract.com>

## Install

Add the marketplace:

```text
/plugin marketplace add browser-act/claude-code-browser-act
```

Then install the plugin:

```text
/plugin install browser-act@browseract
```

On first use, the plugin will prompt to install the underlying CLI (requires Python 3.12+ and [`uv`](https://github.com/astral-sh/uv)):

```bash
uv tool install browser-act-cli --python 3.12
```

## Update

```text
/plugin marketplace update browseract
```

Versioning follows [semver](https://semver.org/) via the `version` field in `plugins/browser-act/.claude-plugin/plugin.json`.

## License

MIT — see [LICENSE](LICENSE).
