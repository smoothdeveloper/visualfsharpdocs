---
title: QueryBuilder.SumByNullable<'T,'Q,^Value> Method (F#)
description: QueryBuilder.SumByNullable<'T,'Q,^Value> Method (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.assetid: 8f71086b-a725-4dd6-9af2-30778056e6a6 
---

# QueryBuilder.SumByNullable<'T,'Q,^Value> Method (F#)

A query operator that selects a nullable value for each element selected so far and returns the sum of these values. If any nullable element does not have a value, it is ignored.

**Namespace/Module Path**: Microsoft.FSharp.Linq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax



```




// Signature:
member this.SumByNullable : QuerySource<'T,'Q> * ('T -> Nullable<^Value>) -> Nullable<^Value> when ^Value with static member (+) and ^Value with static member Zero and ^Value : (new : unit ->  ^Value) and ^Value : struct and ^Value :> ValueType

// Usage:
queryBuilder.SumByNullable (source, valueSelector)


```





#### Parameters
*source*
Type: [QuerySource](http://msdn.microsoft.com/en-us/library/873589c1-c5dc-47d9-8abf-fee7258dfb00)&lt;'T,'Q&gt;


The input query.


*valueSelector*
Type: 'T -&gt;
**T:System.Nullable&#96;1**&lt;^Value&gt;


A function to compute the values to sum.




## Return Value
The resulting sum.


## Remarks
For more information and examples, see [Query Expressions (F#)](http://msdn.microsoft.com/en-us/library/ff72235c-3ad8-4215-8679-2754484823db).


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 4.0, Portable




## See Also
[Linq.QueryBuilder Class &#40;F&#35;&#41;](Linq.QueryBuilder-Class-%5BFSharp%5D.md)

[Microsoft.FSharp.Linq Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Linq-Namespace-%5BFSharp%5D.md)

[Query Expressions (F#)](http://msdn.microsoft.com/en-us/library/ff72235c-3ad8-4215-8679-2754484823db)

