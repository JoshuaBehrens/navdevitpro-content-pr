---
title: "Replace Method"
ms.author: solsen
ms.custom: na
ms.date: 06/29/2017
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: "dynamics-nav-2017"
ms.assetid: 620f0e32-eadc-43e9-8f6e-8fc0b12c3aaf
caps.latest.revision: 9
manager: edupont
author: SusanneWindfeldPedersen
---

[!INCLUDE[newdev_dev_preview](../includes/newdev_dev_preview.md)]

# Replace Method

Replaces the value of the property with the given key with the new value.

```
[Ok := ] JsonObject.Replace(Key, Value)
```

## Parameters
*Key*
Type: String

*Value*
Type: JsonToken | JsonObject | JsonValue | JsonArray | Boolean | Char | Byte | Integer | BigInteger | Decimal | Duration | String | Date | Time | DateTime


## Return Value
Type: Boolean

**True** if the operation was successful; otherwise, **false**.

If you omit this optional return value and if the select does not execute successfully, then a run-time error occurs.

## Remarks
The operation will fail if the object does not contain a property with the given key.

## See Also
[Getting Started](../devenv-get-started.md)  
[Developing Extensions](../devenv-dev-overview.md)