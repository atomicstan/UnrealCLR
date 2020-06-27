### [UnrealEngine.Framework](./UnrealEngine-Framework.md 'UnrealEngine.Framework').[Actor](./UnrealEngine-Framework-Actor.md 'UnrealEngine.Framework.Actor')
## Actor.GetComponentByTag&lt;T&gt;(uint) Method
Returns the component of the actor if matches the specified type and ID  
```csharp
public T GetComponentByTag<T>(uint id);
```
#### Type parameters
<a name='UnrealEngine-Framework-Actor-GetComponentByTag-T-(uint)-T'></a>
`T`  
The type of the component  
  
#### Parameters
<a name='UnrealEngine-Framework-Actor-GetComponentByTag-T-(uint)-id'></a>
`id` [System.UInt32](https://docs.microsoft.com/en-us/dotnet/api/System.UInt32 'System.UInt32')  
The ID of the component  
  
#### Returns
[T](#UnrealEngine-Framework-Actor-GetComponentByTag-T-(uint)-T 'UnrealEngine.Framework.Actor.GetComponentByTag&lt;T&gt;(uint).T')  
A component or `null` on failure  