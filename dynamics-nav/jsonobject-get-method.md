---
title: "Get Method"
ms.author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 02/21/2017
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: "dynamics-nav-2017"
ms.assetid: 620f0e32-eadc-43e9-8f6e-8fc0b12c3aaf
caps.latest.revision: 9
manager: edupont
author: solsen
---

# Get Method
Retrieves the value of a property with a given key from a JsonObject.

```
[Ok := ] JsonObject.Get(Key, Value)
```

## Parameters
*Key*
Type: String

*Result*
Type: JsonToken

A variable of type JsonToken that will contain the result if the operation is successful.

## Return Value
Type : Boolean

**true** if the operation was successful; otherwise, **false**. 
If you omit this optional return value and if the select does not execute successfully, then a run-time error occurs.

## Remarks
The operation will fail if the object does not contain a property with the given *Key*.

## See Also
