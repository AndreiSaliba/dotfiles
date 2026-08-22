# Zed

macOS/Linux:

```sh
chezmoi execute-template \
  --file "$(chezmoi source-path)/.chezmoitemplates/zed/merge.tmpl" \
  --output "$HOME/.config/zed/settings.json"
```

Windows:

```sh
chezmoi execute-template --file "$(chezmoi source-path)\.chezmoitemplates\zed\merge.tmpl" --output "$env:APPDATA\Zed\settings.json"
```
