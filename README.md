# my-posh-theme

## How to use?

Execute in PowerShell 7:

```bash
# install oh-my-posh
winget install JanDeDobbeleer.OhMyPosh --source winget

# install nerd font
oh-my-posh font install JetBrainsMono
```

Add the following lines to `$PROFILE` of PowerShell 7:

```bash
oh-my-posh init powershell --config 'https://raw.githubusercontent.com/YXHXianYu/my-posh-theme/refs/heads/main/yxhxianyu.omp.json' | Invoke-Expression
```

Configure in VSCode or WindowsTerminal:

* Ref
  * https://ohmyposh.dev/docs/installation/fonts#configuration
* VSCode
  * Press `ctrl + ,`
  * Search `terminal.integrated.fontFamily`
  * Enter `JetBrainsMono NF`
  * **Restart VSCode!**
