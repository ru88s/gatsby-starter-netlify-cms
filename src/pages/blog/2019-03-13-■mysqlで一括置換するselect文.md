---
templateKey: blog-post
title: ■MySQLで一括置換するSELECT文
date: 2019-03-13T08:41:32.355Z
description: MySQLで一括置換するSELECT文です
tags:
  - MySQ
---
## ■MySQLで一括置換するSELECT文

```
update rssdate set subject = replace(subject ,'嫁に内緒にしていること','恥ずかしい体験・黒歴史・秘密') WHERE \`sid\` = 47 AND subject like '%嫁に内緒にしていること%';
```
