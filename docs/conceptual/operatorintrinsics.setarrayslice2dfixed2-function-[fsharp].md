---
title: OperatorIntrinsics.SetArraySlice2DFixed2 Function (F#)
description: OperatorIntrinsics.SetArraySlice2DFixed2 Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 30708a92-0dab-4fc5-b957-37df94fa5c33 
---

# OperatorIntrinsics.SetArraySlice2DFixed2 Function (F#)

Sets a vector slice of a 2D array. The index of the second dimension is fixed.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators.OperatorIntrinsics

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
SetArraySlice2DFixed2 : 'T [,] -> int option -> int option -> int -> 'T [] -> unit

// Usage:
SetArraySlice2DFixed2 target start1 finish1 index2 source


```





#### Parameters
*target*
Type: **'T**[[,]](http://msdn.microsoft.com/en-us/library/077252f3-e6ce-441c-9d5b-a6030eaef7cd)


The target array.


*start1*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)[option](http://msdn.microsoft.com/en-us/library/e5b1450c-2779-4c65-ae28-e7f740c37871)


The start index of the first dimension.


*finish1*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)[option](http://msdn.microsoft.com/en-us/library/e5b1450c-2779-4c65-ae28-e7f740c37871)


The end index of the first dimension.


*index2*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)


The index of the second dimension.


*source*
Type: **'T**[[]](http://msdn.microsoft.com/en-us/library/077252f3-e6ce-441c-9d5b-a6030eaef7cd)


The source array.




## Remarks

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable


## See Also
[Operators.OperatorIntrinsics Module &#40;F&#35;&#41;](Operators.OperatorIntrinsics-Module-%5BFSharp%5D.md)

[Core.Operators Module &#40;F&#35;&#41;](Core.Operators-Module-%5BFSharp%5D.md)

