# 个人音乐库

共 79 首，合计 705.73 MB。

## 链接形态

- mp3：`https://github.com/guiguhe/music-library/releases/download/v1/<序号>.mp3`（Releases 附件；302 跳转，206 分段，支持 Range）
- 歌词：`https://cdn.jsdelivr.net/gh/guiguhe/music-library@main/lyrics/<原名>.lrc`（带 CORS）
- 清单：`https://cdn.jsdelivr.net/gh/guiguhe/music-library@main/manifest.json`

## 为什么 mp3 是数字名

GitHub 的 Release 附件名只接受 ASCII：空格会被替换成点，非 ASCII 字符会被直接删除。
中文名会互相撞车（都变成 `-.mp3`），因此改用稳定的序号名，中文原名保存在 `manifest.json` 与附件 label 中。

## 文件

- `manifest.json` — 序号↔曲目↔链接 映射（机器可读）
- `音乐清单.md` — 可读表格
- `links.txt` — 纯 mp3 URL 列表
- `lyrics/` — 歌词（中文原名，jsDelivr 可读）
