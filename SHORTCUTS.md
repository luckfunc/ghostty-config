# Ghostty 快捷键速查

以下内容基于 macOS 上的 Ghostty `1.3.1` 默认快捷键。

Ghostty 里的 `super` 在 macOS 上就是 `Command` 键，也就是 `Cmd`。

## 配置相关

| 快捷键 | 作用 |
| --- | --- |
| `Cmd + ,` | 打开配置文件 |
| `Cmd + Shift + ,` | 重新加载配置 |

## 窗口与标签页

| 快捷键 | 作用 |
| --- | --- |
| `Cmd + N` | 新建窗口 |
| `Cmd + W` | 关闭当前 surface |
| `Cmd + Option + W` | 关闭当前标签页 |
| `Cmd + Shift + W` | 关闭当前窗口 |
| `Cmd + T` | 新建标签页 |
| `Cmd + Shift + [` | 上一个标签页 |
| `Cmd + Shift + ]` | 下一个标签页 |
| `Cmd + 1` 到 `Cmd + 8` | 切到第 1 到第 8 个标签页 |
| `Cmd + 9` | 切到最后一个标签页 |

## 分屏工作流

| 快捷键 | 作用 |
| --- | --- |
| `Cmd + D` | 向右分屏 |
| `Cmd + Shift + D` | 向下分屏 |
| `Cmd + [` | 切到上一个分屏 |
| `Cmd + ]` | 切到下一个分屏 |
| `Cmd + Option + Up` | 切到上方分屏 |
| `Cmd + Option + Down` | 切到下方分屏 |
| `Cmd + Option + Left` | 切到左侧分屏 |
| `Cmd + Option + Right` | 切到右侧分屏 |
| `Cmd + Ctrl + Up` | 向上调整分屏大小 |
| `Cmd + Ctrl + Down` | 向下调整分屏大小 |
| `Cmd + Ctrl + Left` | 向左调整分屏大小 |
| `Cmd + Ctrl + Right` | 向右调整分屏大小 |
| `Cmd + Ctrl + =` | 平均分配所有分屏大小 |
| `Cmd + Shift + Enter` | 放大或还原当前分屏 |

## 复制、粘贴与搜索

| 快捷键 | 作用 |
| --- | --- |
| `Cmd + C` | 复制 |
| `Cmd + V` | 粘贴 |
| `Cmd + Shift + V` | 从 selection 粘贴 |
| `Cmd + F` | 开始搜索 |
| `Cmd + E` | 搜索当前选中内容 |
| `Cmd + G` | 下一个搜索结果 |
| `Cmd + Shift + G` | 上一个搜索结果 |

## 屏幕与导航

| 快捷键 | 作用 |
| --- | --- |
| `Cmd + K` | 清屏 |
| `Cmd + A` | 全选 |
| `Cmd + Enter` | 全屏切换 |
| `Cmd + Arrow Up` | 跳到上一个 prompt |
| `Cmd + Arrow Down` | 跳到下一个 prompt |
| `Cmd + Shift + Arrow Up` | 跳到上一个 prompt |
| `Cmd + Shift + Arrow Down` | 跳到下一个 prompt |
| `Cmd + Home` | 滚到顶部 |
| `Cmd + End` | 滚到底部 |
| `Cmd + Page Up` | 上翻一页 |
| `Cmd + Page Down` | 下翻一页 |

## 推荐的分屏体验命令

你可以在 Ghostty 里按下面顺序试一遍：

1. 先运行 `top -o cpu`
2. 按 `Cmd + D` 后运行 `git status -sb`
3. 再按 `Cmd + Shift + D` 后运行 `git diff`
4. 用 `Cmd + Option + Arrow` 在分屏之间切换
5. 用 `Cmd + Ctrl + Arrow` 调整分屏大小
6. 用 `Cmd + Shift + Enter` 临时放大当前分屏
