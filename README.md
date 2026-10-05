# ya-google-lee

![ya-google-lee](docs/cover.webp)

Agent skill: take an AI Studio / Firebase Studio export and make it run without Google APIs. Replace the transport, keep the call sites.

An agent skill from [VIOLINET Tech](https://github.com/Violinet-tech). It is a folder with a `SKILL.md`, written from a real job and the mistakes made on the way. It works in Claude Code and any harness that reads the `SKILL.md` format, and the markdown is readable as plain docs without an agent.

Page: https://violinet-tech.github.io/ya-google-lee/

## Use it when

you want to take an AI Studio or Firebase Studio export and make it run without Google APIs.

## Install

Clone it into your skills folder. The folder name must match the `name:` in `SKILL.md`, which is why it is cloned under that name:

```bash
git clone https://github.com/Violinet-tech/ya-google-lee ~/.claude/skills/ya-google-lee
```

For one project only, clone into `.claude/skills/ya-google-lee` instead.

## What's inside

- `SKILL.md`: the skill
- `cover.webp`: cover image

## More skills

See [all VIOLINET Tech skills](https://github.com/orgs/Violinet-tech/repositories?q=topic%3Aagent-skills).

## Contributing

Issues and PRs welcome. Keep it generic: no personal paths, keys or machine addresses.

## License

MIT, see [LICENSE](LICENSE).
