# upcheckr downloads

Prebuilt binaries for **upcheckr** — the self-hosted, push-based live metrics wall.

Grab the build for your platform from the **[latest release](../../releases/latest)**:

| Platform | File |
|---|---|
| macOS (Apple Silicon) | `upcheckr-macos-arm64` |
| Linux x86-64 | `upcheckr-linux-x64` |
| Linux arm64 | `upcheckr-linux-arm64` |
| Windows | `upcheckr-windows-x64.exe` |
| Any OS (needs Java 21) | `upcheckr.jar` |

Each file ships with a matching `.sha256`. Then:

```sh
chmod +x upcheckr-macos-arm64
UPCHECKR_ADMIN_PASSWORD=secret ./upcheckr-macos-arm64
```

Open http://localhost:8080. Data lives in SQLite at `~/.upcheckr/upcheckr.db`.

See [LICENSE](LICENSE) for terms.
