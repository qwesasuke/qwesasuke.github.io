---
publish: true
permalink: /ru/short-cartoons/short-cartoons.md
created: 2026-09-14T19:20:29+05:00
modified: 2026-10-03T17:43:36+05:00
---

```dataview
TABLE choice(source, link(source, "Смотреть"), "—") AS "Ссылка", Category AS "Категория", viewing-time AS "Длительность"
WHERE file.folder = this.file.folder AND file.link != this.file.link
```
