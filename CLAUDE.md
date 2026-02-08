# CLAUDE.md

MCP server for Apple Notes on macOS. Lets AI assistants create, search, read, and manage notes via AppleScript.

## Stack

- TypeScript, Node.js, ES modules
- MCP SDK (`@modelcontextprotocol/sdk`)

## Build

```sh
npm run build  # tsc
npm start      # node dist/index.js
npm run dev    # tsc --watch
```

## Notes

- Source is a single file: `src/index.ts`
- No test runner or linter is configured in this repo
- `npm install` triggers a build automatically via the `prepare` script
