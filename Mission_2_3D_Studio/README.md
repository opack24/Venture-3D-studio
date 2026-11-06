# Venture 3D Studio — Mission 2

**[Open the live studio](https://opack24.github.io/Venture-3D-studio/)** · [Repository folder](https://github.com/opack24/Venture-3D-studio/tree/main/Mission_2_3D_Studio)

This browser studio starts with an editable, procedural interpretation of the supplied laundry folding station concept. It uses real 3D mesh geometry; the image is a reference, not a scan or automatic image-to-3D reconstruction.

## Explore and edit

- Drag to orbit, scroll to zoom and right-drag to pan. Choose Isometric, Front, Side or Top. Switch between perspective and orthographic projection or toggle the grid.
- Select a component from the scene list or click it in the viewport. Set its color, scale, material feel and transparency. Use the Move, Rotate or Scale gizmo, or type position and rotation values.
- Rename, duplicate, delete or reset parts. Undo and Redo cover common edits.
- Add editable bottle, box, bag, mascot, merchandise, room or abstract sculpture template parts.
- Upload front, side, back and detail references. Upload an image texture for the selected part and adjust its repeat scale.

## Save and hand off

**Save project** stores an editable project snapshot in this browser with IndexedDB where available. Download **JSON backup** for a portable backup. **Open project** accepts a project JSON or confirmed ZIP. **Export GLB** downloads a binary 3D model. **Confirm model** checks the scene, exports and reloads the GLB, then downloads `Venture_3D_Confirmed_Handoff.zip` with `model.glb`, `model-manifest.json`, `project.json`, `preview.png`, `README.txt`, and included reference or texture assets.

Take the confirmed ZIP into Mission 3. The ZIP contains the actual model geometry; `preview.png` is only a visual preview. Check the manifest's SHA-256 value to verify the GLB.

## Notes

Browser saves stay on this device and browser profile. Use downloaded backups to move work between devices or recover after browser data is cleared. The studio loads Three.js and JSZip from public CDNs, so it needs an internet connection. No paid service or account is needed to use the editor.
