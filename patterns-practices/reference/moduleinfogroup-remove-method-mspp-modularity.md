---
TOCTitle: Remove Method
Title: 'ModuleInfoGroup.Remove Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Remove(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405915(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup.Remove Method
=================================

Removes the first occurrence of a specific object from the [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

Syntax
------

```C#
public bool Remove( ModuleInfo item )
```
```VB
'Declaration
Public Function Remove ( item As ModuleInfo ) As Boolean
```

#### Parameters

*item*  
	Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))
	The object to remove from the [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)).

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

true if item was successfully removed from the [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)); otherwise, false. This method also returns false if item is not found in the original [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)).
#### Implements

[ICollection&lt;T&gt;.Remove(T)](http://msdn2.microsoft.com/en-us/library/bye7h94w)

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInfoGroup Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50))

[ModuleInfoGroup Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))