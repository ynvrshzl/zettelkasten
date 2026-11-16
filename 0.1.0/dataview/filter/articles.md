---
description: Shows only Articles (Files in longform format.)
cssclasses:
---

###### Articles (39)
```dataview
TABLE WITHOUT ID "!"+elink(default(image, "https://placehold.co/1x1/lightgray/lightgray")) as "Img", default(title, "No title"), file.name + "<span style='float:right;'>" + link(file.path, "Open") WHERE length(file.outlinks) >= 3  AND file.size / 1032 >= 1
```