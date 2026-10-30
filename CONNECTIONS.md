# Connection continuity checklist

Record names and verification status only. Never record credentials or sensitive endpoints here.

| Connection | Where it runs | Verified from another device? |
| --- | --- | --- |
| GitHub workflow hub | GitHub | Pending |
| Other AI services | Not yet inventoried | Pending |
| MCP servers | Not yet inventoried | Pending |

## Choose a portable connection

- Account-managed connector: reconnect through the AI app's account settings on the new device if required.
- Hosted MCP: configure the supported remote connection and authentication in each client; verify a read-only operation.
- Local MCP: requires its host to stay online. Move it to an available host or install it on the new device before relying on it.
- Local project: push source to the appropriate private repository. Store secrets separately and back up uncommitted files before losing access.

## Before retiring a device

Verify from a second device that required repositories open, current work is present, and each essential connection completes a read-only operation. Logging out alone does not upload local files.
