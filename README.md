# scoop-bucket

[Scoop](https://scoop.sh/) bucket for Windows packages by
[Felix Stubner](https://github.com/fstubner).

## Usage

```powershell
scoop bucket add fstubner https://github.com/fstubner/scoop-bucket
scoop install <manifest>
```

## Manifests

| Manifest | Description |
|----------|-------------|
| [`netscli`](./bucket/netscli.json) | Network scanner with CLI, TUI, desktop app, and MCP server. https://netscli.com |

## Updates

Manifests include `checkver` + `autoupdate` blocks so each new GitHub
release is picked up automatically on the next `scoop update`.

Manual refresh:

```powershell
scoop update
scoop update <manifest>
```

## License

MIT.
