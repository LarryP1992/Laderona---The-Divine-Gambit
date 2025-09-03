---
{"dg-publish":true,"permalink":"/np-cs/npc-list/"}
---

```base
views:
  - type: cards
    name: All NPCs
    filters:
      and:
        - file.folder.contains("NPCs")
        - file.basename != "NPC List"
        - note["dg-publish"] == true
    order:
      - file.name
      - tags
    image: note.cardPic
```


