---
title: OperatorIntrinsics.PowUInt64 Function (F#)
description: OperatorIntrinsics.PowUInt64 Function (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: bae917c5-ff02-476c-8f10-eb04116f7743 
---

# OperatorIntrinsics.PowUInt64 Function (F#)

This is a library intrinsic. Calls to this function may be generated by uses of the generic [pown](http://msdn.microsoft.com/en-us/library/c6163b1d-a8f9-4a87-8704-f34d8b2918ff) operator on values of type **uint64**.

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators.OperatorIntrinsics

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
PowUInt64 : uint64 -> int -> uint64

// Usage:
PowUInt64 x n


```





#### Parameters
*x*
Type: [uint64](http://msdn.microsoft.com/en-us/library/3c4f3a04-06eb-48aa-b38e-16646bda2f33)


The value to raise to a power.


*n*
Type: [int](http://msdn.microsoft.com/en-us/library/025d5455-3622-4ea5-9573-3ecbd4ee1375)


The power to raise the value to.



**The result of the exponentiation operation.**
## Remarks
This function is for use by compiled F# code and should not be used directly.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable, Portable




## See Also
[Operators.OperatorIntrinsics Module &#40;F&#35;&#41;](Operators.OperatorIntrinsics-Module-%5BFSharp%5D.md)

[Core.Operators Module &#40;F&#35;&#41;](Core.Operators-Module-%5BFSharp%5D.md)

