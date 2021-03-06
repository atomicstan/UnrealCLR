### [UnrealEngine.Framework](./UnrealEngine-Framework.md 'UnrealEngine.Framework')
## SceneComponent Class
The base class of components that can be transformed or attached, but has no rendering or collision capabilities  
```csharp
public class SceneComponent : ActorComponent
```
Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; [ActorComponent](./ActorComponent.md 'UnrealEngine.Framework.ActorComponent') &#129106; SceneComponent  

Derived  
&#8627; [AudioComponent](./AudioComponent.md 'UnrealEngine.Framework.AudioComponent')  
&#8627; [CameraComponent](./CameraComponent.md 'UnrealEngine.Framework.CameraComponent')  
&#8627; [ChildActorComponent](./ChildActorComponent.md 'UnrealEngine.Framework.ChildActorComponent')  
&#8627; [LightComponentBase](./LightComponentBase.md 'UnrealEngine.Framework.LightComponentBase')  
&#8627; [PostProcessComponent](./PostProcessComponent.md 'UnrealEngine.Framework.PostProcessComponent')  
&#8627; [PrimitiveComponent](./PrimitiveComponent.md 'UnrealEngine.Framework.PrimitiveComponent')  
&#8627; [RadialForceComponent](./RadialForceComponent.md 'UnrealEngine.Framework.RadialForceComponent')  
&#8627; [SpringArmComponent](./SpringArmComponent.md 'UnrealEngine.Framework.SpringArmComponent')  
### Constructors
- [SceneComponent(UnrealEngine.Framework.Actor, string, bool, UnrealEngine.Framework.Blueprint)](./SceneComponent-SceneComponent(Actor_string_bool_Blueprint).md 'UnrealEngine.Framework.SceneComponent.SceneComponent(UnrealEngine.Framework.Actor, string, bool, UnrealEngine.Framework.Blueprint)')
### Properties
- [HasAnySockets](./SceneComponent-HasAnySockets.md 'UnrealEngine.Framework.SceneComponent.HasAnySockets')
- [IsVisible](./SceneComponent-IsVisible.md 'UnrealEngine.Framework.SceneComponent.IsVisible')
### Methods
- [Activate()](./SceneComponent-Activate().md 'UnrealEngine.Framework.SceneComponent.Activate()')
- [AddLocalOffset(System.Numerics.Vector3)](./SceneComponent-AddLocalOffset(Vector3).md 'UnrealEngine.Framework.SceneComponent.AddLocalOffset(System.Numerics.Vector3)')
- [AddLocalRotation(System.Numerics.Quaternion)](./SceneComponent-AddLocalRotation(Quaternion).md 'UnrealEngine.Framework.SceneComponent.AddLocalRotation(System.Numerics.Quaternion)')
- [AddLocalTransform(UnrealEngine.Framework.Transform)](./SceneComponent-AddLocalTransform(Transform).md 'UnrealEngine.Framework.SceneComponent.AddLocalTransform(UnrealEngine.Framework.Transform)')
- [AddRelativeLocation(System.Numerics.Vector3)](./SceneComponent-AddRelativeLocation(Vector3).md 'UnrealEngine.Framework.SceneComponent.AddRelativeLocation(System.Numerics.Vector3)')
- [AddRelativeRotation(System.Numerics.Quaternion)](./SceneComponent-AddRelativeRotation(Quaternion).md 'UnrealEngine.Framework.SceneComponent.AddRelativeRotation(System.Numerics.Quaternion)')
- [AddWorldOffset(System.Numerics.Vector3)](./SceneComponent-AddWorldOffset(Vector3).md 'UnrealEngine.Framework.SceneComponent.AddWorldOffset(System.Numerics.Vector3)')
- [AddWorldRotation(System.Numerics.Quaternion)](./SceneComponent-AddWorldRotation(Quaternion).md 'UnrealEngine.Framework.SceneComponent.AddWorldRotation(System.Numerics.Quaternion)')
- [AddWorldTransform(UnrealEngine.Framework.Transform)](./SceneComponent-AddWorldTransform(Transform).md 'UnrealEngine.Framework.SceneComponent.AddWorldTransform(UnrealEngine.Framework.Transform)')
- [AttachToComponent(UnrealEngine.Framework.SceneComponent, UnrealEngine.Framework.AttachmentTransformRule, string)](./SceneComponent-AttachToComponent(SceneComponent_AttachmentTransformRule_string).md 'UnrealEngine.Framework.SceneComponent.AttachToComponent(UnrealEngine.Framework.SceneComponent, UnrealEngine.Framework.AttachmentTransformRule, string)')
- [CanAttachAsChild(UnrealEngine.Framework.SceneComponent, string)](./SceneComponent-CanAttachAsChild(SceneComponent_string).md 'UnrealEngine.Framework.SceneComponent.CanAttachAsChild(UnrealEngine.Framework.SceneComponent, string)')
- [Deactivate()](./SceneComponent-Deactivate().md 'UnrealEngine.Framework.SceneComponent.Deactivate()')
- [DetachFromComponent(UnrealEngine.Framework.DetachmentTransformRule)](./SceneComponent-DetachFromComponent(DetachmentTransformRule).md 'UnrealEngine.Framework.SceneComponent.DetachFromComponent(UnrealEngine.Framework.DetachmentTransformRule)')
- [ForEachAttachedChild&lt;T&gt;(System.Action&lt;T&gt;)](./SceneComponent-ForEachAttachedChild-T-(Action-T-).md 'UnrealEngine.Framework.SceneComponent.ForEachAttachedChild&lt;T&gt;(System.Action&lt;T&gt;)')
- [GetAttachedSocketName()](./SceneComponent-GetAttachedSocketName().md 'UnrealEngine.Framework.SceneComponent.GetAttachedSocketName()')
- [GetBounds(UnrealEngine.Framework.Transform, UnrealEngine.Framework.Bounds)](./SceneComponent-GetBounds(Transform_Bounds).md 'UnrealEngine.Framework.SceneComponent.GetBounds(UnrealEngine.Framework.Transform, UnrealEngine.Framework.Bounds)')
- [GetForwardVector()](./SceneComponent-GetForwardVector().md 'UnrealEngine.Framework.SceneComponent.GetForwardVector()')
- [GetForwardVector(System.Numerics.Vector3)](./SceneComponent-GetForwardVector(Vector3).md 'UnrealEngine.Framework.SceneComponent.GetForwardVector(System.Numerics.Vector3)')
- [GetLocation()](./SceneComponent-GetLocation().md 'UnrealEngine.Framework.SceneComponent.GetLocation()')
- [GetLocation(System.Numerics.Vector3)](./SceneComponent-GetLocation(Vector3).md 'UnrealEngine.Framework.SceneComponent.GetLocation(System.Numerics.Vector3)')
- [GetRightVector()](./SceneComponent-GetRightVector().md 'UnrealEngine.Framework.SceneComponent.GetRightVector()')
- [GetRightVector(System.Numerics.Vector3)](./SceneComponent-GetRightVector(Vector3).md 'UnrealEngine.Framework.SceneComponent.GetRightVector(System.Numerics.Vector3)')
- [GetRotation()](./SceneComponent-GetRotation().md 'UnrealEngine.Framework.SceneComponent.GetRotation()')
- [GetRotation(System.Numerics.Quaternion)](./SceneComponent-GetRotation(Quaternion).md 'UnrealEngine.Framework.SceneComponent.GetRotation(System.Numerics.Quaternion)')
- [GetScale()](./SceneComponent-GetScale().md 'UnrealEngine.Framework.SceneComponent.GetScale()')
- [GetScale(System.Numerics.Vector3)](./SceneComponent-GetScale(Vector3).md 'UnrealEngine.Framework.SceneComponent.GetScale(System.Numerics.Vector3)')
- [GetSocketLocation(string)](./SceneComponent-GetSocketLocation(string).md 'UnrealEngine.Framework.SceneComponent.GetSocketLocation(string)')
- [GetSocketLocation(string, System.Numerics.Vector3)](./SceneComponent-GetSocketLocation(string_Vector3).md 'UnrealEngine.Framework.SceneComponent.GetSocketLocation(string, System.Numerics.Vector3)')
- [GetSocketRotation(string)](./SceneComponent-GetSocketRotation(string).md 'UnrealEngine.Framework.SceneComponent.GetSocketRotation(string)')
- [GetSocketRotation(string, System.Numerics.Quaternion)](./SceneComponent-GetSocketRotation(string_Quaternion).md 'UnrealEngine.Framework.SceneComponent.GetSocketRotation(string, System.Numerics.Quaternion)')
- [GetTransform()](./SceneComponent-GetTransform().md 'UnrealEngine.Framework.SceneComponent.GetTransform()')
- [GetTransform(UnrealEngine.Framework.Transform)](./SceneComponent-GetTransform(Transform).md 'UnrealEngine.Framework.SceneComponent.GetTransform(UnrealEngine.Framework.Transform)')
- [GetUpVector()](./SceneComponent-GetUpVector().md 'UnrealEngine.Framework.SceneComponent.GetUpVector()')
- [GetUpVector(System.Numerics.Vector3)](./SceneComponent-GetUpVector(Vector3).md 'UnrealEngine.Framework.SceneComponent.GetUpVector(System.Numerics.Vector3)')
- [GetVelocity()](./SceneComponent-GetVelocity().md 'UnrealEngine.Framework.SceneComponent.GetVelocity()')
- [GetVelocity(System.Numerics.Vector3)](./SceneComponent-GetVelocity(Vector3).md 'UnrealEngine.Framework.SceneComponent.GetVelocity(System.Numerics.Vector3)')
- [IsAttachedToActor(UnrealEngine.Framework.Actor)](./SceneComponent-IsAttachedToActor(Actor).md 'UnrealEngine.Framework.SceneComponent.IsAttachedToActor(UnrealEngine.Framework.Actor)')
- [IsAttachedToComponent(UnrealEngine.Framework.SceneComponent)](./SceneComponent-IsAttachedToComponent(SceneComponent).md 'UnrealEngine.Framework.SceneComponent.IsAttachedToComponent(UnrealEngine.Framework.SceneComponent)')
- [IsSocketExists(string)](./SceneComponent-IsSocketExists(string).md 'UnrealEngine.Framework.SceneComponent.IsSocketExists(string)')
- [SetMobility(UnrealEngine.Framework.ComponentMobility)](./SceneComponent-SetMobility(ComponentMobility).md 'UnrealEngine.Framework.SceneComponent.SetMobility(UnrealEngine.Framework.ComponentMobility)')
- [SetRelativeLocation(System.Numerics.Vector3)](./SceneComponent-SetRelativeLocation(Vector3).md 'UnrealEngine.Framework.SceneComponent.SetRelativeLocation(System.Numerics.Vector3)')
- [SetRelativeRotation(System.Numerics.Quaternion)](./SceneComponent-SetRelativeRotation(Quaternion).md 'UnrealEngine.Framework.SceneComponent.SetRelativeRotation(System.Numerics.Quaternion)')
- [SetRelativeTransform(UnrealEngine.Framework.Transform)](./SceneComponent-SetRelativeTransform(Transform).md 'UnrealEngine.Framework.SceneComponent.SetRelativeTransform(UnrealEngine.Framework.Transform)')
- [SetVisibility(bool, bool)](./SceneComponent-SetVisibility(bool_bool).md 'UnrealEngine.Framework.SceneComponent.SetVisibility(bool, bool)')
- [SetWorldLocation(System.Numerics.Vector3)](./SceneComponent-SetWorldLocation(Vector3).md 'UnrealEngine.Framework.SceneComponent.SetWorldLocation(System.Numerics.Vector3)')
- [SetWorldRotation(System.Numerics.Quaternion)](./SceneComponent-SetWorldRotation(Quaternion).md 'UnrealEngine.Framework.SceneComponent.SetWorldRotation(System.Numerics.Quaternion)')
- [SetWorldScale(System.Numerics.Vector3)](./SceneComponent-SetWorldScale(Vector3).md 'UnrealEngine.Framework.SceneComponent.SetWorldScale(System.Numerics.Vector3)')
- [SetWorldTransform(UnrealEngine.Framework.Transform)](./SceneComponent-SetWorldTransform(Transform).md 'UnrealEngine.Framework.SceneComponent.SetWorldTransform(UnrealEngine.Framework.Transform)')
- [UpdateToWorld(UnrealEngine.Framework.TeleportType, UnrealEngine.Framework.UpdateTransformFlags)](./SceneComponent-UpdateToWorld(TeleportType_UpdateTransformFlags).md 'UnrealEngine.Framework.SceneComponent.UpdateToWorld(UnrealEngine.Framework.TeleportType, UnrealEngine.Framework.UpdateTransformFlags)')
