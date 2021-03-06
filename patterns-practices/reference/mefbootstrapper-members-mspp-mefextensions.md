---
TOCTitle: MefBootstrapper Members
Title: 'MefBootstrapper Members (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'mefbootstrapper-members-mspp-mefextensions.md'
---

# MefBootstrapper Members

The [MefBootstrapper](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions) type exposes the following members.

## Constructors

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>MefBootstrapper</td>
<td><div class="summary">
Initializes a new instance of the [MefBootstrapper](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions) class
</div></td>
</tr>
</tbody>
</table>

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureAggregateCatalog](/patterns-practices/reference/mefbootstrapper-configureaggregatecatalog-method-mspp-mefextensions)</td>
<td><div class="summary">
Configures the [AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureContainer](/patterns-practices/reference/mefbootstrapper-configurecontainer-method-mspp-mefextensions)</td>
<td><div class="summary">
Configures the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureDefaultRegionBehaviors](/patterns-practices/reference/bootstrapper-configuredefaultregionbehaviors-method-mspp)</td>
<td><div class="summary">
Configures the [IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions). This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureModuleCatalog](/patterns-practices/reference/bootstrapper-configuremodulecatalog-method-mspp)</td>
<td><div class="summary">
Configures the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-addmodule-method-mspp-modularity) used by Prism.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureRegionAdapterMappings](/patterns-practices/reference/bootstrapper-configureregionadaptermappings-method-mspp)</td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureServiceLocator](/patterns-practices/reference/mefbootstrapper-configureservicelocator-method-mspp-mefextensions)</td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides [Bootstrapper.ConfigureServiceLocator()](/patterns-practices/reference/bootstrapper-configureservicelocator-method-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateAggregateCatalog](/patterns-practices/reference/mefbootstrapper-createaggregatecatalog-method-mspp-mefextensions)</td>
<td><div class="summary">
Configures the [AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateContainer](/patterns-practices/reference/mefbootstrapper-createcontainer-method-mspp-mefextensions)</td>
<td><div class="summary">
Creates the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553) that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateLogger](/patterns-practices/reference/bootstrapper-createlogger-method-mspp)</td>
<td><div class="summary">
Create the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-members-mspp-logging) used by the bootstrapper.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateModuleCatalog](/patterns-practices/reference/bootstrapper-createmodulecatalog-method-mspp)</td>
<td><div class="summary">
Creates the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-members-mspp-modularity) used by Prism.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateShell](/patterns-practices/reference/bootstrapper-createshell-method-mspp)</td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InitializeModules](/patterns-practices/reference/mefbootstrapper-initializemodules-method-mspp-mefextensions)</td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides [Bootstrapper.InitializeModules()](/patterns-practices/reference/bootstrapper-initializemodules-method-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InitializeShell](/patterns-practices/reference/mefbootstrapper-initializeshell-method-mspp-mefextensions)</td>
<td><div class="summary">
Initializes the shell.
</div>
(Overrides [Bootstrapper.InitializeShell()](/patterns-practices/reference/bootstrapper-initializemodules-method-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RegisterBootstrapperProvidedTypes](/patterns-practices/reference/mefbootstrapper-registerbootstrapperprovidedtypes-method-mspp-mefextensions)</td>
<td><div class="summary">
Helper method for configuring the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553). Registers all the types direct instantiated by the bootstrapper with the container.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RegisterDefaultTypesIfMissing](/patterns-practices/reference/mefbootstrapper-registerdefaulttypesifmissing-method-mspp-mefextensions)</td>
<td><div class="summary">
Helper method for configuring the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553). Registers defaults for all the types necessary for Prism to work, if they are not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RegisterFrameworkExceptionTypes](/patterns-practices/reference/bootstrapper-registerframeworkexceptiontypes-method-mspp)</td>
<td><div class="summary">
Registers the [Type](http://msdn.microsoft.com/en-us/library/42892f65)s of the Exceptions that are not considered root exceptions by the [ExceptionExtensions](/patterns-practices/reference/exceptionextensions).
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run()](/patterns-practices/reference/run-mthd)</td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run(Boolean)](/patterns-practices/reference/mefbootstrapper-run-method-boolean-mspp-mefextensions)</td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides [Bootstrapper.Run(Boolean)](/patterns-practices/reference/bootstrapper-run-method-boolean-mspp).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
</tbody>
</table>

## Properties

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions)</td>
<td><div class="summary">
Gets or sets the default [AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) for the application.
</div></td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Container](/patterns-practices/reference/mefbootstrapper-container-property-mspp-mefextensions)</td>
<td><div class="summary">
Gets or sets the default [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553) for the application.
</div></td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Logger](/patterns-practices/reference/bootstrapper-logger-property-mspp)</td>
<td><div class="summary">
Gets the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) for the application.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ModuleCatalog](/patterns-practices/reference/bootstrapper-modulecatalog-property-mspp)</td>
<td><div class="summary">
Gets the default [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) for the application.
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Shell](/patterns-practices/reference/bootstrapper-shell-property-mspp)</td>
<td><div class="summary">
Gets the shell user interface
</div>
(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)</td>
</tr>
</tbody>
</table>

## See Also

[MefBootstrapper Class](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions)  
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)  
