# settings sync

- extension id: `zokugun.sync-settings`
- repo: [vscode-sync-settings](https://github.com/zokugun/vscode-sync-settings)

## settings
```yaml
# more details at https://github.com/zokugun/vscode-sync-settings/blob/master/docs/hostname.md
# minimal settings example

# current machine's name, optional; it can be used to filter settings or in the commit message
hostname: ""

# selected profile, required
profile: main

# repository to sync the settings with, required
repository:
  type: git
  branch: main
  url: https://ansemb:<PAT_TOKEN>@gitlab.com/ansemb/vscode-settings.git
```
