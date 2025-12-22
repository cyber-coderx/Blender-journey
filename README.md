# Blender-journey
Shortcuts for the tutorials

‎Below is a **clean, ordered list of Blender shortcuts and actions** that are **explicitly mentioned or clearly implied by the transcript**, followed by **helpful suggested shortcuts** that make sense at that exact moment in the workflow.
‎
‎I’ve organized this **chronologically**, matching the tutorial flow (setup → blocking → structure → details → cleanup).
‎Where something is *not said directly* but is **obviously being used**, I label it **(implied)**.
‎Suggestions are marked **(recommended)**.
‎
‎---
‎
‎## 1. Initial Setup & Navigation
‎
‎**Implied basic navigation (used constantly):**
‎
‎* **Middle Mouse Button** – Rotate view
‎* **Shift + MMB** – Pan view
‎* **Scroll Wheel** – Zoom
‎
‎**View changes:**
‎
‎* **Numpad 1** – Front View
‎* **Numpad 3** – Side View
‎* **Numpad 7** – Top View
‎* **Numpad 5** – Toggle Perspective / Orthographic
‎* **Numpad 9** – Flip view (used for left/right checks)
‎
‎**Recommended:**
‎
‎* **`~` (tilde)** → View pie menu (fast view switching)
‎* **`.` (period)** – Frame selected
‎
‎---
‎
‎## 2. Add-ons & Preferences
‎
‎* **Edit → Preferences**
‎* **Enable Add-ons:**
‎
‎  * Node Wrangler
‎  * Loop Tools
‎  * Rigify
‎* **Save Preferences**
‎
‎(No shortcuts here, UI-based)
‎
‎---
‎
‎## 3. Starting the Head Block
‎
‎* **Shift + A → Mesh → Cube**
‎* **Tab** – Enter Edit Mode
‎* **A** – Select all
‎* **Ctrl + B** – Bevel edges (cube → rounded form)
‎* **Mouse Wheel** – Increase bevel segments
‎
‎**Recommended:**
‎
‎* **Ctrl + 2** – Add Subdivision modifier (preview smoothing)
‎* **Shade Smooth** (Right-click)
‎
‎---
‎
‎## 4. Symmetry & Topology Setup
‎
‎* **Ctrl + R** – Add edge loop (center loop for symmetry)
‎* **X → Faces** – Delete half of the mesh
‎* **Modifiers Panel → Add Modifier → Mirror**
‎* **Enable Clipping** (Mirror Modifier)
‎
‎**Recommended:**
‎
‎* **Alt + Z** – X-Ray mode (helpful when deleting half)
‎* **Shift + D** – Duplicate (for backups)
‎
‎---
‎
‎## 5. Eye Socket Creation
‎
‎* **Face Select Mode (3)**
‎* **I** – Inset faces
‎* **X → Faces** – Delete inset faces
‎* **N Panel → Loop Tools → Circle**
‎* **G G** – Edge/vertex slide (used heavily)
‎
‎**Recommended:**
‎
‎* **Alt + Click** – Select edge loops faster
‎* **S + Shift + Z** – Scale without depth distortion
‎
‎---
‎
‎## 6. Proportional Editing & Profile Shaping
‎
‎* **O** – Toggle Proportional Editing
‎* **G** – Move vertices
‎* **R** – Rotate with proportional editing
‎* **Scroll Wheel** – Adjust influence radius
‎
‎**Recommended:**
‎
‎* **Alt + S** – Shrink/Fatten (volume control)
‎* **Shift + O** – Change falloff type
‎
‎---
‎
‎## 7. Mouth Formation
‎
‎* **Face Select**
‎* **I** – Inset (Boundary disabled)
‎* **S + Z** – Scale vertically
‎* **E** – Extrude inward (mouth cavity)
‎* **G G** – Slide to clean topology
‎
‎**Recommended:**
‎
‎* **Ctrl + E → Edge Flow** (smooth mouth loops)
‎* **Alt + S** – Lip volume control
‎
‎---
‎
‎## 8. Nose Blocking
‎
‎* **Face Select**
‎* **E** – Extrude nose outward
‎* **X → Faces** – Delete center face
‎* **I** – Inset nostrils
‎* **Loop Tools → Circle**
‎* **E** – Extrude inward (nostrils)
‎* **Ctrl + R** – Add nose bridge loops
‎
‎**Recommended:**
‎
‎* **Alt + Click** – Quickly select nose loops
‎* **Ctrl + B** – Soft bevel for stylized nose edges
‎
‎---
‎
‎## 9. Subdivision Preview
‎
‎* **Modifiers → Subdivision Surface**
‎* **Toggle modifier visibility**
‎* **Tab** – Switch modes for evaluation
‎
‎**Recommended:**
‎
‎* **Ctrl + 1 / 2 / 3** – Subdivision levels
‎
‎---
‎
‎## 10. Refining Lips & Face
‎
‎* **Ctrl + R** – Add supporting loops
‎* **G G** – Slide for even spacing
‎* **Smooth Tool** (Toolbar)
‎
‎**Recommended:**
‎
‎* **Vertex → Smooth Vertices**
‎* **Mesh → Clean Up → Merge by Distance**
‎
‎---
‎
‎## 11. Cheeks, Jaw & Volume
‎
‎* **Alt + S** – Shrink/Fatten
‎* **O** – Proportional Editing
‎* **G / R** – Shape jawline & cheeks
‎
‎**Recommended:**
‎
‎* **Sculpt Mode → Smooth Brush** (very light pass)
‎* **Shift + Space → Sculpt Mode**
‎
‎---
‎
‎## 12. Topology Cleanup
‎
‎* **X → Faces**
‎* **Ctrl + F → Grid Fill**
‎* **V** – Rip vertices (used to fix pinching)
‎
‎**Recommended:**
‎
‎* **Ctrl + E → Bridge Edge Loops**
‎* **Mesh → Normals → Recalculate Outside (Shift + N)**
‎
‎---
‎
‎## 13. Ear Creation
‎
‎* **Select faces**
‎* **E** – Extrude ear base
‎* **Ctrl + R** – Add ear loops
‎* **Loop Tools → Circle**
‎* **Smooth Tool**
‎* **Ctrl + B** – Bevel center ear edge
‎
‎**Recommended:**
‎
‎* **Alt + S** – Ear thickness control
‎* **L** – Select linked geometry (entire ear)
‎
‎---
‎
‎## 14. Neck Creation
‎
‎* **Face Select**
‎* **E** – Extrude downward
‎* **Loop Tools → Circle**
‎* **S** – Scale to narrow neck
‎* **Ctrl + R** – Add neck loops
‎* **V** – Rip (fix loop collisions)
‎* **Ctrl + F → Grid Fill**
‎
‎**Recommended:**
‎
‎* **Alt + Click** – Fast neck loop selection
‎* **Alt + S** – Neck volume shaping
‎
‎---
‎
‎## 15. Eyelids & Shape Keys
‎
‎* **Object Data → Shape Keys → +**
‎* **Edit Mode**
‎* **Select eyelid loop**
‎* **S + Z** – Scale for eyelid closure
‎* **O** – Proportional Editing
‎* **Ctrl + R** – Add blink support loops
‎
‎**Recommended:**
‎
‎* **Alt + S** – Eyelid thickness
‎* **Shape Key Slider** – Test blinking motion
‎
‎---
‎
‎## 16. Final Cleanup & Polish
‎
‎* **Smooth Tool**
‎* **G G** – Slide to reduce pinching
‎* **Alt + S** – Final volume pass
‎* **Ctrl + R** – Optional supporting loops
‎
‎**Recommended Final Checks:**
‎
‎* **Overlay → Face Orientation**
‎* **Shade Smooth + Auto Smooth**
‎* **Apply Mirror Modifier (when finished)**
‎
‎---
‎
‎## Summary (Core Shortcuts You Should Memorize)
‎
‎If you remember nothing else, remember these:
‎
‎```
‎Tab, G, R, S
‎Ctrl + R
‎I, E
‎O
‎G G
‎Alt + S
‎Ctrl + B
‎Alt + Click
‎```
‎
‎These are the **backbone of character modeling in Blender** and exactly what this tutorial is teaching—whether explicitly or implicitly.
‎
‎If you want, I can:
‎
‎* Turn this into a **printable cheat sheet**
‎* Highlight **only beginner-critical shortcuts**
‎* Map shortcuts → **specific facial features** (eyes, nose, mouth, ears)
‎* Convert this into a **practice checklist**
‎
‎Just tell me 👍
‎
