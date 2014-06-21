# pcd

shell function using peco and cd

![](http://gifzo.net/sPyvEHq2bs.gif)

# INSTALL

```
curl -fsSL https://raw.githubusercontent.com/trapple/pcd/master/pcd >> ~/.zshrc
```

## peco setting

`vi ~/.peco/config.json`

```
{
  "keymap": {
    "C-k": "peco.SelectPrevious",
    "C-j": "peco.SelectNext",
    "C-c": "peco.Cancel"
  }
}
```

# SEE ALSO

[https://github.com/peco/peco](https://github.com/peco/peco)

[Windows のコマンドプロンプトを10倍便利にするコマンド「peco」](http://mattn.kaoriya.net/software/peco.htm)