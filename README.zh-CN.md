# crisd1337.github.io

这个账号的 GitHub Pages **用户站**，只做两件事：

1. `/` 跳转到复习站 [`/quiz/`](https://crisd1337.github.io/quiz/)。
2. 一组单字母短路径指向同一个站，方便手机上敲或发给同学：

| 路径 | 跳到 |
|---|---|
| `/a` | 综合卷（全部 428 题） |
| `/r` | 错题本 |
| `/k` | 商城 |
| `/e` `/c` `/m` `/m5` `/h` `/g` `/p` | 英语 · 科学 · 数学 P · 数学 5.3 · 历史 · 地理 · PDHPE |

每个短路径就是一个极小的 HTML 文件：`meta refresh` + `location.replace` 兜底 + 一个手动按钮，不用框架也没有构建步骤。

复习站本体在 [`quiz`](https://github.com/Crisd1337/quiz) 仓库。
