Original Addon: https://kindeyegames.itch.io/c3-3dobject-alpha
SDKv1 only (for now).

Requires Fraglight 8: https://kindeyegames.itch.io/c3-3d-effects

New features:
- Per-material environment mapping
- Per-material emissive surfaces
- Per-material roughness/specular

# 3DObject Addon for Construct 3

Reference manual for all Actions, Conditions, and Expressions.

---

## Actions

### Set gpu skinning
Set gpu skinning (static geometry must be enabled).

| Parameter | Description |
|-----------|-------------|
| Enable | Enable gpu skinning. |

### Rotate
Rotate object around a specific axis.

| Parameter | Description |
|-----------|-------------|
| Angle | Rotate object by a number of degrees |
| Axis | Axis to rotate object around. |

### Set z elevation
Set z elevation (world z axis, depth component).

| Parameter | Description |
|-----------|-------------|
| Zelevation | Zelevation (z axis, depth) |

### Set local center
Set the local center of the 3DObject in the model files coordinate system.

| Parameter | Description |
|-----------|-------------|
| X | X local coordinate of center |
| Y | Y local coordinate of center |
| Z | Z local coordinate of center |

### Set scale
Set scale from original object size.

| Parameter | Description |
|-----------|-------------|
| Scale | The size to scale from the original size. |

### Set z height
Set z height, used for viewport clipping.

| Parameter | Description |
|-----------|-------------|
| Z height | The z height of the object, used for viewport clipping. |

### Set X, Y, Z rotation
Set rotation of object from the original position, with rotation order.

| Parameter | Description |
|-----------|-------------|
| X | X angle of rotation. |
| Y | Y angle of rotation. |
| Z | Z angle of rotation. |
| Rotation order | Order to rotate object around axes. |

### Play animation
Play animation by name.

| Parameter | Description |
|-----------|-------------|
| Animation | The animation name to play. |
| Loop | Loop animation. |

### Pause animation
Pause playing animation.

### Resume animation
Unpause playing animation.

### Set animation rate
Set animation rate (FPS).

| Parameter | Description |
|-----------|-------------|
| Rate | Rate (FPS). |

### Set animation speed
Set animation speed.

| Parameter | Description |
|-----------|-------------|
| Speed | Speed (multiplier). |

### Set animation time
Set animation time.

| Parameter | Description |
|-----------|-------------|
| Time | Animation time (seconds). |

### Set X scale
Set X scale.

| Parameter | Description |
|-----------|-------------|
| X scale | X scale. |

### Set Y scale
Set Y scale.

| Parameter | Description |
|-----------|-------------|
| Y scale | Y scale. |

### Set Z scale
Set Z scale.

| Parameter | Description |
|-----------|-------------|
| Z scale | Z scale. |

### Update bounding box
Update bounding box based on current 3D animation.

### Load model
Load model from path.

| Parameter | Description |
|-----------|-------------|
| Gltf path | Gltf/glb project file name or URL to Gltf/glb file (with URL, it will not show in the editor). |

### Load material
Load material from path.

| Parameter | Description |
|-----------|-------------|
| Image path | Image project filename or URL to material (.png) file. |
| Material name | Material name. |

### Load material from sprite
Load material from sprite.

| Parameter | Description |
|-----------|-------------|
| Sprite UID | Sprite instance UID. |
| Material name | Material name. |

### Unload material from sprite
Unload material from sprite.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name. |

### Set node material
Set node to use a material.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name to set material to. |
| Material name | Material name (existing or the material name used when loading). |

### Enable node
Enable or disable node for render.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name to enable or disable. |
| Enable | Enable or disable node for render. |

### Enable all nodes
Enable all nodes for render.

### Disable all nodes
Disable all nodes for render.

### Delete material
Release material (remove from GPU memory).

| Parameter | Description |
|-----------|-------------|
| Material name | Material name (existing or the material name used when loading). |

### Set origin X
Set origin X (Normalized value, 0.5 is center).

| Parameter | Description |
|-----------|-------------|
| X origin | X origin (Normalized value, 0.5 is center). |

### Set origin Y
Set origin Y (Normalized value, 0.5 is center).

| Parameter | Description |
|-----------|-------------|
| Y origin | Y origin (Normalized value, 0.5 is center). |

### Set bounding box scale
Set bounding box scale.

| Parameter | Description |
|-----------|-------------|
| Scale | Scale factor for bounding box. |

### Enable wireframe
Enable or disable wireframe render.

| Parameter | Description |
|-----------|-------------|
| Enable | Enable or disable node wireframe render. |

### Set wireframe  X, Y, Z line widths
Set wireframe X, y, Z widths.

| Parameter | Description |
|-----------|-------------|
| X width | X wireframe width. |
| Y width | Y wireframe width. |
| Z width | Z wireframe width. |

### Set camera vector and position
Set camera vector and position.

| Parameter | Description |
|-----------|-------------|
| Vector X | X vector. |
| Vector Y | Y vector. |
| Vector Z | Z vector. |
| Camera X | X position. |
| Camera Y | Y position. |
| Camera Z | Z position. |

### Offset node UV
Offset a nodes UV texture coordinates.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name to offset UVs. |
| U Offset | U Offset (-1.0 to 1.0). |
| V Offset | V Offset (-1.0 to 1.0). |

### Offset material UV
Offset material UV texture coordinates.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name to offset UVs. |
| U Offset | U Offset (-1.0 to 1.0). |
| V Offset | V Offset (-1.0 to 1.0). |

### Rotate material UV
Rotate material UV texture coordinates around point.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name to rotate UVs. |
| Angle | Angle in degrees. |
| X | Center X to rotate around (0-1). |
| Y | Center Y to rotate around (0-1). |

### Set light direction
Set light direction.

| Parameter | Description |
|-----------|-------------|
| X | Set X light direction. |
| Y | Set Y light direction. |
| Z | Set Z light direction. |

### Set view position
Set view position for specular lighting.

| Parameter | Description |
|-----------|-------------|
| X | Set X view position. |
| Y | Set Y view position. |
| Z | Set Z view position. |

### Load model from prefab instance
Load model from prefab instance of object.

| Parameter | Description |
|-----------|-------------|
| Prefab uid | Prefab uid of instance to load model from, prefab must already be loaded. |

### Set animation blend time
Set animation blend time.

| Parameter | Description |
|-----------|-------------|
| Blend time | Blend time in seconds. |

### Enable lights
Enable lights

| Parameter | Description |
|-----------|-------------|
| Enable | Enable. |

### Update light
Update light.

| Parameter | Description |
|-----------|-------------|
| Update | Update light. |

### Add light
Add light.

| Parameter | Description |
|-----------|-------------|
| Name | Light name. |
| Enable | Enable. |
| Color | Color, use RgbEx(). |
| X | X. |
| Y | Y. |
| Z | Z. |
| Enable spot | Enable spot light. |
| Dir X | Direction X. |
| Dir Y | Direction Y. |
| Dir Z | Direction Z. |
| Spot cone angle | Spot light cone angle. |
| Soft edge | Soft edge (0-1). |
| Attenuation constant | Constant attenuation (1.0+). |
| Attenuation linear | Linear distance attenuation. |
| Attenuation square | Square distance attenuation. |
| Specular enable | Enable specular light. |
| Specular attenuation | Attenuate specular light. |
| Specular shininess | Shiniess of specular light (1-128). |

### Enable light
Enable light.

| Parameter | Description |
|-----------|-------------|
| Name | Light name. |
| Enable | Enable light. |

### Delete light
Delete light

| Parameter | Description |
|-----------|-------------|
| Name | Light name. |

### Set ambient color
Set ambient color

| Parameter | Description |
|-----------|-------------|
| Color | Color value, use rgbaEx(). |

### [DEPRECATED] Enable vertex lighting mode
DEPRECATED - Use 'Enable vertex lighting' instead. This action is kept for backward compatibility.

| Parameter | Description |
|-----------|-------------|
| Enable | Whether to enable vertex lighting mode |

### Enable vertex lighting
Enable or disable vertex lighting mode (per-vertex instead of per-pixel)

| Parameter | Description |
|-----------|-------------|
| Enable | Whether to enable vertex lighting |

### Set debug vertex light
Enable normal visualization for debugging vertex lighting

| Parameter | Description |
|-----------|-------------|
| Enable | Whether to show normals as RGB colors |

### Set node morph target weight
Set node morph target weight.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name. |
| Target | Target index. |
| Weight | Target weight. |

### Delete node morph target weight
Delete node morph target weight.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name. |
| Target | Target index. |

### Set vertex rounding
Set vertex rounding (typically 1, 2, 3, etc.).

| Parameter | Description |
|-----------|-------------|
| Round | Round value, typically an integer. |

### Set static geometry
Set static geometry.

| Parameter | Description |
|-----------|-------------|
| Enable | Enable static geometry. |

### Set blend mode
Set blend mode.

| Parameter | Description |
|-----------|-------------|
| Blend mode | Blend mode. |

### Set quaternion
Set quaternion for rotation (JSON array string).

| Parameter | Description |
|-----------|-------------|
| Quaternion | Quaternion (JSON array string). |
| Offsey X | Offset X - beware gimbal lock of offsets! |
| Offsey Y | Offset Y - beware gimbal lock of offsets! |
| Offsey Z | Offset Z - beware gimbal lock of offsets! |

### Enable quaternion
Enable quaternion for rotation.

| Parameter | Description |
|-----------|-------------|
| Enable | Enable quaternion for rotation. |

### Enable fragment light mode
Enable fragment light mode for fragment light effect.

| Parameter | Description |
|-----------|-------------|
| Enable | Enable fragment light mode. |
| Enable Phong | Enable phong lighting, requires model normals. |

### Set target to position
Set target to position.

| Parameter | Description |
|-----------|-------------|
| X | X. |
| Y | Y. |
| Z | Z. |
| Up X | Up X. |
| Up Y | Up Y. |
| Up Z | Up Z. |

---

## Conditions

### Is node enabled
True if node is enabled.

| Parameter | Description |
|-----------|-------------|
| Node | Enter the name of node to check if enabled. |

### On loaded
Triggers when 3DObject has completed loading the 3D model.

### Is Loaded
True if the 3DObject has loaded its 3D model.

### Is animation finished
True if the animation has finished (only true if not looping).

### On any animation finished
Triggers when the animation has finished (only triggered if not looping).

### On animation finished
Triggers when the named animation has finished (only triggered if not looping).

| Parameter | Description |
|-----------|-------------|
| Name | Enter the name of animation to check if playing. |

### Is wireframe enabled
True if model is renered as wireframe.

### Is playing
Is the named animation playing.

| Parameter | Description |
|-----------|-------------|
| Animation | Enter the name of animation to check if playing. |

---

## Expressions

### animation-names
Get animation names as JSON string.

### z-elevation-0
Get Z elevation-0.

### current-animation
Get the current animation name.

### current-animation-time
Get current animation time.

### current-animation-frame
Get the current animation frame.

### scale
Get scale.

### x-scale
Get X scale.

### y-scale
Get Y scale.

### z-scale
Get Z scale.

### mesh-names
Get mesh names.

### material-names
Get material names.

### x-angle
Get x angle.

### y-angle
Get Y angle.

### z-angle
Get Z angle.

### x-bb-min
Get X bounding box min.

### y-bb-min
Get Y bounding box min.

### z-bb-min
Get Z bounding box min.

### x-bb-max
Get X bounding box max.

### y-bb-max
Get y bounding box max.

### z-bb-max
Get z bounding box max.

### x-wireframe-width
X wireframe line width.

### y-wireframe-width
Y wireframe line width.

### z-wireframe-width
Z wireframe line width.

### u-offset
U offset on node.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name of offset U. |

### v-offset
V offset on node.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name of offset V. |

### material-u-offset
U offset on node.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name of offset U. |

### material-v-offset
V offset on material.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name of offset V. |

### material-rotate-angle
Rotation angle of material.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name of rotate angle. |

### material-rotate-x
Rotation center X of material.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name of rotation center x. |

### material-rotate-y
Rotation center Y of material.

| Parameter | Description |
|-----------|-------------|
| Material name | Material name of rotation center Y. |

### materials
Material list in JSON string format.

### node-point-position
Node point position, as JSON string, {x:<number>,y:<number>,z:<number>}.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name. |
| Point index | Point index. |

### node-vertex-length
Length of the nodes meshs vertex array.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name. |

### animation-blend-time
Animation blend time in seconds.

### light-color
Light color value.

| Parameter | Description |
|-----------|-------------|
| name | Color name. |

### lights-data
Lights data as JSON string.

### animation-speed
Animation speed.

### total-triangles
Total triangles to be rendered.

### total-triangles-culled
Total triangles culled.

### node-bounding-box
Node bounding box.

| Parameter | Description |
|-----------|-------------|
| Node name | Node name. |

### gltf-path
Get the current gltf/glb file path.
