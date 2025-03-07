---
author: v-josjones
ms.author: v-josjones
title: Block Documentation - minecraft:flammable
ms.prod: gaming
---

# Block Documentation - minecraft:flammable

`minecraft:flammable` is a component controlled by a `JSON object` that contains the flammable properties for this block.

## Default Parameter

|Default Value|Type |
|:----|:----|
|*not set*| JSON Object|

## Extra Parameters

`minecraft:flammable` can use the following parameters:

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|burn_odds| 0| Integer| How likely the block will be destroyed by flames when on fire. Value must be greater than or equal to 0.|
|flame_odds| 0| Integer| How likely the block will catch flame when next to a fire. Value must be greater than or equal to 0.|

## Example

```json
"minecraft:flammable":{
    "burn_odds": 0,
    "flame_odds": 0
}
```
