### [UnrealEngine.Framework](./UnrealEngine-Framework.md 'UnrealEngine.Framework').[World](./World.md 'UnrealEngine.Framework.World')
## World.SweepTestByChannel(System.Numerics.Vector3, System.Numerics.Vector3, System.Numerics.Quaternion, UnrealEngine.Framework.CollisionChannel, UnrealEngine.Framework.CollisionShape, bool, UnrealEngine.Framework.Actor, UnrealEngine.Framework.PrimitiveComponent) Method
Sweeps a shape against the world using a specific profile  
```csharp
public static bool SweepTestByChannel(in System.Numerics.Vector3 start, in System.Numerics.Vector3 end, in System.Numerics.Quaternion rotation, UnrealEngine.Framework.CollisionChannel channel, in UnrealEngine.Framework.CollisionShape shape, bool traceComplex=false, UnrealEngine.Framework.Actor ignoredActor=null, UnrealEngine.Framework.PrimitiveComponent ignoredComponent=null);
```
#### Parameters
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-start'></a>
`start` [System.Numerics.Vector3](https://docs.microsoft.com/en-us/dotnet/api/System.Numerics.Vector3 'System.Numerics.Vector3')  
  
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-end'></a>
`end` [System.Numerics.Vector3](https://docs.microsoft.com/en-us/dotnet/api/System.Numerics.Vector3 'System.Numerics.Vector3')  
  
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-rotation'></a>
`rotation` [System.Numerics.Quaternion](https://docs.microsoft.com/en-us/dotnet/api/System.Numerics.Quaternion 'System.Numerics.Quaternion')  
  
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-channel'></a>
`channel` [CollisionChannel](./CollisionChannel.md 'UnrealEngine.Framework.CollisionChannel')  
  
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-shape'></a>
`shape` [CollisionShape](./CollisionShape.md 'UnrealEngine.Framework.CollisionShape')  
  
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-traceComplex'></a>
`traceComplex` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
  
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-ignoredActor'></a>
`ignoredActor` [Actor](./Actor.md 'UnrealEngine.Framework.Actor')  
  
<a name='UnrealEngine-Framework-World-SweepTestByChannel(System-Numerics-Vector3_System-Numerics-Vector3_System-Numerics-Quaternion_UnrealEngine-Framework-CollisionChannel_UnrealEngine-Framework-CollisionShape_bool_UnrealEngine-Framework-Actor_UnrealEngine-Framework-PrimitiveComponent)-ignoredComponent'></a>
`ignoredComponent` [PrimitiveComponent](./PrimitiveComponent.md 'UnrealEngine.Framework.PrimitiveComponent')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` on success  
