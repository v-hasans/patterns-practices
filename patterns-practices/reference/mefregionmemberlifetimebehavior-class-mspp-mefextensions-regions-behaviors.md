---
TOCTitle: MefRegionMemberLifetimeBehavior Class
Title: 'MefRegionMemberLifetimeBehavior Class (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionMemberLifetimeBehavior'
ms:mtpsurl: 'mefregionmemberlifetimebehavior-class-mspp-mefextensions-regions-behaviors.md'
---

# MefRegionMemberLifetimeBehavior Class

Exports the AutoPopulateRegionBehavior using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionMemberLifetimeBehavior : RegionMemberLifetimeBehavior
```

```VB
'Declaration
Public Class MefRegionMemberLifetimeBehavior
	Inherits RegionMemberLifetimeBehavior
```

## Remarks

This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions.Behaviors.RegionMemberLifetimeBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors) Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionMemberLifetimeBehavior

## See Also

[MefRegionMemberLifetimeBehavior Members](/patterns-practices/reference/mefregionmemberlifetimebehavior-members-mspp-mefextensions-regions-behaviors)  
[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)