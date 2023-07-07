
# Azure Developer CLI (azd)

Installs the Azure Developer CLI along with needed dependencies.

## Example Usage

```json
"features": {
    "ghcr.io/hemarina/feature-starter/azd:0": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Select or enter an Azure Developer CLI version. (Available versions may vary by Linux distribution.) | string | stable |

## Customizations

### VS Code Extensions

- `ms-azuretools.vscode-bicep`
- `ms-vscode.vscode-node-azure-pack`

## OS Support

This Feature should work on recent versions of Debian/Ubuntu-based distributions with the `apt` package manager installed.

`bash` is required to execute the `install.sh` script.

---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/hemarina/feature-starter/blob/main/src/azd/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
