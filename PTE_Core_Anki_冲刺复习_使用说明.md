# PTE Core Anki 冲刺复习

项目中的 113 道主练习题已整理成可导入 Anki 的牌组，并按题型分成子牌组。每张卡片正面顶部都会显示题型英文名称、缩写和中文名称；Describe Image 卡片正面包含原图。

| 题型 | 卡片数 |
| --- | ---: |
| Describe Image | 27 |
| Respond to a Situation (RTS) | 50 |
| Summarize Spoken Text (SST) | 8 |
| Summarize Written Text (SWT) | 15 |
| Write Email | 13 |
| **总计** | **113** |

## 导入与复习

1. 在 Anki 桌面版选择“文件 → 导入”，打开 `PTE_Core_Anki_冲刺复习.apkg`。
2. 可从总牌组复习全部题目，也可以进入子牌组选某一题型。
3. 正面顶部先确认题型，再看题目或图片；先口述/默写，再翻面核对参考答案和要点。
4. 十几天冲刺时，可每天新增约 8–12 张，并完成 Anki 当天安排的复习；考前最后 1–2 天集中复习标记为“困难”或反复答错的卡片。

### 已经导入过旧版牌组

如果这 113 张卡已经在 Anki 里，直接导入 `.apkg` 会被识别为重复笔记。先在导入选项的“Updates”中启用“Merge note types”，让 Anki 加入 `Type` 字段和正面题型标签；再导入 `PTE_Core_Anki_题型字段更新.tsv`，并将“Existing notes”设为“Update”。更新文件按现有笔记 GUID 精确对应，只写入 `Type` 字段；导入预览应显示 113 条更新、0 条新增。更新现有笔记会保留原卡片的复习进度。

卡片保留项目里的参考答案与措辞；答案用于练习表达，不代表唯一写法。
