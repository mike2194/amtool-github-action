# AMTool GitHub Actions
AMTool GitHub Actions allows you to check Alertmanager configuration with Github Actions

# Usage
```
- name: Check Altermanager configuration
  uses: mike2194/amtool-github-actions@v0.27.0
  with:
    amtool_check_file: 'am.yaml' # Default to alertmanager.yaml
```
