---
publish: true
permalink: /ru/short-cartoons/short-cartoons.md
created: 2026-09-14T14:20:29.000Z
modified: 2026-10-03T12:43:38.758Z
---

```dataview
TABLE choice(source, link(source, "Смотреть"), "—") AS "Ссылка", Category AS "Категория", viewing-time AS "Длительность"
WHERE file.folder = this.file.folder AND file.link != this.file.link
```
