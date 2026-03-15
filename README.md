# ghostty-config

这个目录已经整理成可以直接提交到 GitHub 的结构。

## 文件说明

- `config.ghostty`：当前正在使用的 Ghostty 配置
- `SHORTCUTS.md`：常用快捷键和分屏速查表

## 在 macOS 上应用配置

把 `config.ghostty` 复制到下面这个位置：

```text
~/Library/Application Support/com.mitchellh.ghostty/config.ghostty
```

复制之后，在 Ghostty 里按：

```text
Cmd + Shift + ,
```

重新加载配置即可。

## 备注

- 这份配置是从 macOS `Terminal.app` 的默认 `Pro` 配置同步过来的。
- `Terminal.app` 里存的是语义化系统字体，Ghostty 不适合直接复用，所以这里改成了 `Menlo 14`。

## 如果你要推到 GitHub

在这个目录里执行：

```bash
git init
git add .
git commit -m "chore: add ghostty config and shortcuts"
```
