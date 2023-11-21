# Code template for NodeJS project with TypeScript using bun

## Repo Cleanup

- Remove repo specific files: `rm -rf .git LICENSE README.md`
- Re-initialize git repo
- Rename project in `package.json`

## Additional steps

- Update all packages using `npm-check-updates` package: `bun run update-deps`

## Versions

- Bun v1.0.13
- TypeScript v5.3.2
- ESLint v8.54.0
- TypeScript-ESLint v6.12.0
- Prettier v3.1.0
- Jest v29.7.0
- TSJest v29.1.1
