# Pointbreak Documentation

This repository contains the source for [docs.withpointbreak.com](https://docs.withpointbreak.com) — the official documentation for Pointbreak.

## About Pointbreak

Pointbreak gives AI assistants real debugger access, letting them set breakpoints, step through code, and inspect variables in your IDE through natural language.

**Main repository:** [github.com/withpointbreak/pointbreak](https://github.com/withpointbreak/pointbreak)

## Documentation Site

The live documentation is available at **[docs.withpointbreak.com](https://docs.withpointbreak.com)**.

This site is built using [Mintlify](https://mintlify.com), a modern documentation platform.

## Local Development

To preview documentation changes locally:

1. **Install the Mintlify CLI:**
   ```bash
   npm i -g mint
   ```

2. **Run the dev server:**
   ```bash
   mint dev
   ```

3. **View at:** [localhost:3000](http://localhost:3000)

## Repository Structure

- `*.mdx` - Documentation pages (MDX format - Markdown with JSX)
- `docs.json` - Site configuration (navigation, theme, etc.)
- `reference/` - API and reference documentation
- `logo/` - Site logos and branding assets

## Publishing Changes

Changes pushed to the `main` branch are automatically deployed to production via Mintlify's GitHub integration.

## Contributing

Found an issue or want to suggest improvements to the documentation?

- **Issues:** [github.com/withpointbreak/pointbreak/issues](https://github.com/withpointbreak/pointbreak/issues)
- **Discussions:** [github.com/withpointbreak/pointbreak/discussions](https://github.com/withpointbreak/pointbreak/discussions)

## License

Documentation content in this repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Built by [Kevin Swiber](https://github.com/kevinswiber)
