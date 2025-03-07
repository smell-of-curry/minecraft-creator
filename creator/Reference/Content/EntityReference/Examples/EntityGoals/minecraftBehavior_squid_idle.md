---
author: v-josjones
ms.author: v-josjones
title: Entity Documentation - minecraft:behavior.squid_idle
ms.prod: gaming
---

# Entity Documentation - minecraft:behavior.squid_idle

`minecraft:behavior.squid_idle` allows an entity to swim in place.

> [!NOTE]
> This behavior can only be used by the `squid` entity type.

## Example

```json
"minecraft:behavior.squid_idle":{
    "priority": 2,
}
```

## Vanilla entities examples

### squid

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/squid.json" range="86-88":::

## Vanilla entities using `minecraft:behavior.squid_idle`

- [glow_squid](../../../../Source/VanillaBehaviorPack_Snippets/entities/glow_squid.md)
- [squid](../../../../Source/VanillaBehaviorPack_Snippets/entities/squid.md)
