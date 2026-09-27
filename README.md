# 个人音乐库

共 2 首，合计 19.04 MB。mp3 以 Releases 附件形式提供直链；歌词与清单在仓库里，可用 jsDelivr 读取。

## 链接形态

- mp3：`https://github.com/guiguhe/music-library/releases/download/v1/<文件名>`（302 跳转，206 分段，支持 Range）
- 歌词：`https://cdn.jsdelivr.net/gh/guiguhe/music-library@main/lyrics/<文件名>`（带 CORS）
- 清单：`https://cdn.jsdelivr.net/gh/guiguhe/music-library@main/manifest.json`

## 文件

- `manifest.json` — 曲目→链接映射（机器可读）
- `音乐清单.md` — 可读表格
- `links.txt` — 纯 mp3 URL 列表
- `lyrics/` — 歌词
