# ube
open-source kernel concept

## editing in vscode
add the following to `.vscode/settings.json`:

for `rust`
```json
{
    "rust.target": "x86_64-ube.json",
    "rust.all_targets": false
}
```

for `rust-analyzer`
```json
{
    "rust-analyzer.cargo.target": "x86_64-ube.json",
    "rust-analyzer.checkOnSave.allTargets": false
}
```