Original Addon: https://kindeyegames.itch.io/c3-3dobject-alpha
SDKv1 only (for now).

Requires Fraglight 8: https://kindeyegames.itch.io/c3-3d-effects

New features:
- Per-material environment mapping
- Per-material emissive surfaces
- Per-material roughness/specular

3DObject Addon for Construct 3 — Reference Manual
====================================================

This manual describes all available Actions, Conditions, and Expressions
for use in Construct 3 event sheets.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ACTIONS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

▸ Set gpu skinning
  Set gpu skinning (static geometry must be enabled).
  Parameters:
    • Enable: Enable gpu skinning.

▸ Rotate
  Rotate object around a specific axis.
  Parameters:
    • Angle: Rotate object by a number of degrees
    • Axis: Axis to rotate object around.

▸ Set z elevation
  Set z elevation (world z axis, depth component).
  Parameters:
    • Zelevation: Zelevation (z axis, depth)

▸ Set local center
  Set the local center of the 3DObject in the model files coordinate system.
  Parameters:
    • X: X local coordinate of center
    • Y: Y local coordinate of center
    • Z: Z local coordinate of center

▸ Set scale
  Set scale from original object size.
  Parameters:
    • Scale: The size to scale from the original size.

▸ Set z height
  Set z height, used for viewport clipping.
  Parameters:
    • Z height: The z height of the object, used for viewport clipping.

▸ Set X, Y, Z rotation
  Set rotation of object from the original position, with rotation order.
  Parameters:
    • X: X angle of rotation.
    • Y: Y angle of rotation.
    • Z: Z angle of rotation.
    • Rotation order: Order to rotate object around axes.

▸ Play animation
  Play animation by name.
  Parameters:
    • Animation: The animation name to play.
    • Loop: Loop animation.

▸ Pause animation
  Pause playing animation.

▸ Resume animation
  Unpause playing animation.

▸ Set animation rate
  Set animation rate (FPS).
  Parameters:
    • Rate: Rate (FPS).

▸ Set animation speed
  Set animation speed.
  Parameters:
    • Speed: Speed (multiplier).

▸ Set animation time
  Set animation time.
  Parameters:
    • Time: Animation time (seconds).

▸ Set X scale
  Set X scale.
  Parameters:
    • X scale: X scale.

▸ Set Y scale
  Set Y scale.
  Parameters:
    • Y scale: Y scale.

▸ Set Z scale
  Set Z scale.
  Parameters:
    • Z scale: Z scale.

▸ Update bounding box
  Update bounding box based on current 3D animation.

▸ Load model
  Load model from path.
  Parameters:
    • Gltf path: Gltf/glb project file name or URL to Gltf/glb file (with URL, it will not show in the editor).

▸ Load material
  Load material from path.
  Parameters:
    • Image path: Image project filename or URL to material (.png) file.
    • Material name: Material name.

▸ Load material from sprite
  Load material from sprite.
  Parameters:
    • Sprite UID: Sprite instance UID.
    • Material name: Material name.

▸ Unload material from sprite
  Unload material from sprite.
  Parameters:
    • Material name: Material name.

▸ Set node material
  Set node to use a material.
  Parameters:
    • Node name: Node name to set material to.
    • Material name: Material name (existing or the material name used when loading).

▸ Enable node
  Enable or disable node for render.
  Parameters:
    • Node name: Node name to enable or disable.
    • Enable: Enable or disable node for render.

▸ Enable all nodes
  Enable all nodes for render.

▸ Disable all nodes
  Disable all nodes for render.

▸ Delete material
  Release material (remove from GPU memory).
  Parameters:
    • Material name: Material name (existing or the material name used when loading).

▸ Set origin X
  Set origin X (Normalized value, 0.5 is center).
  Parameters:
    • X origin: X origin (Normalized value, 0.5 is center).

▸ Set origin Y
  Set origin Y (Normalized value, 0.5 is center).
  Parameters:
    • Y origin: Y origin (Normalized value, 0.5 is center).

▸ Set bounding box scale
  Set bounding box scale.
  Parameters:
    • Scale: Scale factor for bounding box.

▸ Enable wireframe
  Enable or disable wireframe render.
  Parameters:
    • Enable: Enable or disable node wireframe render.

▸ Set wireframe  X, Y, Z line widths
  Set wireframe X, y, Z widths.
  Parameters:
    • X width: X wireframe width.
    • Y width: Y wireframe width.
    • Z width: Z wireframe width.

▸ Set camera vector and position
  Set camera vector and position.
  Parameters:
    • Vector X: X vector.
    • Vector Y: Y vector.
    • Vector Z: Z vector.
    • Camera X: X position.
    • Camera Y: Y position.
    • Camera Z: Z position.

▸ Offset node UV
  Offset a nodes UV texture coordinates.
  Parameters:
    • Node name: Node name to offset UVs.
    • U Offset: U Offset (-1.0 to 1.0).
    • V Offset: V Offset (-1.0 to 1.0).

▸ Offset material UV
  Offset material UV texture coordinates.
  Parameters:
    • Material name: Material name to offset UVs.
    • U Offset: U Offset (-1.0 to 1.0).
    • V Offset: V Offset (-1.0 to 1.0).

▸ Rotate material UV
  Rotate material UV texture coordinates around point.
  Parameters:
    • Material name: Material name to rotate UVs.
    • Angle: Angle in degrees.
    • X: Center X to rotate around (0-1).
    • Y: Center Y to rotate around (0-1).

▸ Set light direction
  Set light direction.
  Parameters:
    • X: Set X light direction.
    • Y: Set Y light direction.
    • Z: Set Z light direction.

▸ Set view position
  Set view position for specular lighting.
  Parameters:
    • X: Set X view position.
    • Y: Set Y view position.
    • Z: Set Z view position.

▸ Load model from prefab instance
  Load model from prefab instance of object.
  Parameters:
    • Prefab uid: Prefab uid of instance to load model from, prefab must already be loaded.

▸ Set animation blend time
  Set animation blend time.
  Parameters:
    • Blend time: Blend time in seconds.

▸ Enable lights
  Enable lights
  Parameters:
    • Enable: Enable.

▸ Update light
  Update light.
  Parameters:
    • Update: Update light.

▸ Add light
  Add light.
  Parameters:
    • Name: Light name.
    • Enable: Enable.
    • Color: Color, use RgbEx().
    • X: X.
    • Y: Y.
    • Z: Z.
    • Enable spot: Enable spot light.
    • Dir X: Direction X.
    • Dir Y: Direction Y.
    • Dir Z: Direction Z.
    • Spot cone angle: Spot light cone angle.
    • Soft edge: Soft edge (0-1).
    • Attenuation constant: Constant attenuation (1.0+).
    • Attenuation linear: Linear distance attenuation.
    • Attenuation square: Square distance attenuation.
    • Specular enable: Enable specular light.
    • Specular attenuation: Attenuate specular light.
    • Specular shininess: Shiniess of specular light (1-128).

▸ Enable light
  Enable light.
  Parameters:
    • Name: Light name.
    • Enable: Enable light.

▸ Delete light
  Delete light
  Parameters:
    • Name: Light name.

▸ Set ambient color
  Set ambient color
  Parameters:
    • Color: Color value, use rgbaEx().

▸ [DEPRECATED] Enable vertex lighting mode
  DEPRECATED - Use 'Enable vertex lighting' instead. This action is kept for backward compatibility.
  Parameters:
    • Enable: Whether to enable vertex lighting mode

▸ Enable vertex lighting
  Enable or disable vertex lighting mode (per-vertex instead of per-pixel)
  Parameters:
    • Enable: Whether to enable vertex lighting

▸ Set debug vertex light
  Enable normal visualization for debugging vertex lighting
  Parameters:
    • Enable: Whether to show normals as RGB colors

▸ Set node morph target weight
  Set node morph target weight.
  Parameters:
    • Node name: Node name.
    • Target: Target index.
    • Weight: Target weight.

▸ Delete node morph target weight
  Delete node morph target weight.
  Parameters:
    • Node name: Node name.
    • Target: Target index.

▸ Set vertex rounding
  Set vertex rounding (typically 1, 2, 3, etc.).
  Parameters:
    • Round: Round value, typically an integer.

▸ Set static geometry
  Set static geometry.
  Parameters:
    • Enable: Enable static geometry.

▸ Set blend mode
  Set blend mode.
  Parameters:
    • Blend mode: Blend mode.

▸ Set quaternion
  Set quaternion for rotation (JSON array string).
  Parameters:
    • Quaternion: Quaternion (JSON array string).
    • Offsey X: Offset X - beware gimbal lock of offsets!
    • Offsey Y: Offset Y - beware gimbal lock of offsets!
    • Offsey Z: Offset Z - beware gimbal lock of offsets!

▸ Enable quaternion
  Enable quaternion for rotation.
  Parameters:
    • Enable: Enable quaternion for rotation.

▸ Enable fragment light mode
  Enable fragment light mode for fragment light effect.
  Parameters:
    • Enable: Enable fragment light mode.
    • Enable Phong: Enable phong lighting, requires model normals.

▸ Set target to position
  Set target to position.
  Parameters:
    • X: X.
    • Y: Y.
    • Z: Z.
    • Up X: Up X.
    • Up Y: Up Y.
    • Up Z: Up Z.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
CONDITIONS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

▸ Is node enabled
  True if node is enabled.
  Parameters:
    • Node: Enter the name of node to check if enabled.

▸ On loaded
  Triggers when 3DObject has completed loading the 3D model.

▸ Is Loaded
  True if the 3DObject has loaded its 3D model.

▸ Is animation finished
  True if the animation has finished (only true if not looping).

▸ On any animation finished
  Triggers when the animation has finished (only triggered if not looping).

▸ On animation finished
  Triggers when the named animation has finished (only triggered if not looping).
  Parameters:
    • Name: Enter the name of animation to check if playing.

▸ Is wireframe enabled
  True if model is renered as wireframe.

▸ Is playing
  Is the named animation playing.
  Parameters:
    • Animation: Enter the name of animation to check if playing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
EXPRESSIONS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

▸ animation-names
  Returns: Get animation names as JSON string.

▸ z-elevation-0
  Returns: Get Z elevation-0.

▸ current-animation
  Returns: Get the current animation name.

▸ current-animation-time
  Returns: Get current animation time.

▸ current-animation-frame
  Returns: Get the current animation frame.

▸ scale
  Returns: Get scale.

▸ x-scale
  Returns: Get X scale.

▸ y-scale
  Returns: Get Y scale.

▸ z-scale
  Returns: Get Z scale.

▸ mesh-names
  Returns: Get mesh names.

▸ material-names
  Returns: Get material names.

▸ x-angle
  Returns: Get x angle.

▸ y-angle
  Returns: Get Y angle.

▸ z-angle
  Returns: Get Z angle.

▸ x-bb-min
  Returns: Get X bounding box min.

▸ y-bb-min
  Returns: Get Y bounding box min.

▸ z-bb-min
  Returns: Get Z bounding box min.

▸ x-bb-max
  Returns: Get X bounding box max.

▸ y-bb-max
  Returns: Get y bounding box max.

▸ z-bb-max
  Returns: Get z bounding box max.

▸ x-wireframe-width
  Returns: X wireframe line width.

▸ y-wireframe-width
  Returns: Y wireframe line width.

▸ z-wireframe-width
  Returns: Z wireframe line width.

▸ u-offset
  Returns: U offset on node.
  Parameters:
    • Node name: Node name of offset U.

▸ v-offset
  Returns: V offset on node.
  Parameters:
    • Node name: Node name of offset V.

▸ material-u-offset
  Returns: U offset on node.
  Parameters:
    • Material name: Material name of offset U.

▸ material-v-offset
  Returns: V offset on material.
  Parameters:
    • Material name: Material name of offset V.

▸ material-rotate-angle
  Returns: Rotation angle of material.
  Parameters:
    • Material name: Material name of rotate angle.

▸ material-rotate-x
  Returns: Rotation center X of material.
  Parameters:
    • Material name: Material name of rotation center x.

▸ material-rotate-y
  Returns: Rotation center Y of material.
  Parameters:
    • Material name: Material name of rotation center Y.

▸ materials
  Returns: Material list in JSON string format.

▸ node-point-position
  Returns: Node point position, as JSON string, {x:<number>,y:<number>,z:<number>}.
  Parameters:
    • Node name: Node name.
    • Point index: Point index.

▸ node-vertex-length
  Returns: Length of the nodes meshs vertex array.
  Parameters:
    • Node name: Node name.

▸ animation-blend-time
  Returns: Animation blend time in seconds.

▸ light-color
  Returns: Light color value.
  Parameters:
    • name: Color name.

▸ lights-data
  Returns: Lights data as JSON string.

▸ animation-speed
  Returns: Animation speed.

▸ total-triangles
  Returns: Total triangles to be rendered.

▸ total-triangles-culled
  Returns: Total triangles culled.

▸ node-bounding-box
  Returns: Node bounding box.
  Parameters:
    • Node name: Node name.

▸ gltf-path
  Returns: Get the current gltf/glb file path.
