---
publish: true
permalink: /ru/short-cartoons/short-cartoons.md
created: 2026-08-17T17:51:15.670Z
modified: 2026-08-17T18:07:09.098Z
---

```dataview
TABLE choice(source, link(source, "Смотреть"), "—") AS "Ссылка", Category AS "Категория", viewing-time AS "Длительность"
WHERE file.folder = this.file.folder AND file.link != this.file.link
```
