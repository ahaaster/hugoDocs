---
title: upper
# linktitle: upper
description: Converts all characters in a string to uppercase
date: 2017-02-01
publishdate: 2017-02-01
lastmod: 2017-02-01
keywords: []
categories: [functions]
menu:
  docs:
    parent: "functions"
toc:
signature: ["upper INPUT"]
workson: []
hugoversion:
relatedfuncs: []
deprecated: false
draft: false
aliases: []
---

Note that `upper` can be applied in your templates in more than one way:

```go-html-template
{{ upper "BatMan" }} → "BATMAN"
{{ "BatMan" | upper }} → "BATMAN"
```
