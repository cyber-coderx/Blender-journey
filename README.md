# Blender-journey
Shortcuts for the tutorials

‎Here’s a **clean, README-ready version** of your content with consistent formatting, tighter wording, and GitHub-friendly Markdown.
Nothing essential was removed—only clarified, normalized, and cleaned for readability.

---

# Blender Head Modeling – Shortcut Reference (Tutorial-Based)

This document is a **chronological list of Blender shortcuts and actions** that are **explicitly mentioned or clearly implied** in the tutorial workflow.

* Organized to follow the modeling process: **setup → blocking → structure → details → cleanup**
* Actions not stated directly but clearly used are marked **(implied)**
* Helpful additions that fit the exact workflow stage are marked **(recommended)**

---

## 1. Initial Setup & Navigation

### Basic View Navigation *(implied, used constantly)*

* **Middle Mouse Button (MMB)** – Rotate view
* **Shift + MMB** – Pan view
* **Scroll Wheel** – Zoom

### View Switching

* **Numpad 1** – Front view
* **Numpad 3** – Side view
* **Numpad 7** – Top view
* **Numpad 5** – Toggle Perspective / Orthographic
* **Numpad 9** – Flip view (left/right checks)

### Recommended

* **`~` (Tilde)** – View pie menu (fast view switching)
* **`.` (Period)** – Frame selected

---

## 2. Add-ons & Preferences

* **Edit → Preferences**
* Enable add-ons:

  * Node Wrangler
  * Loop Tools
  * Rigify
* **Save Preferences**

*(UI-based, no shortcuts)*

---

## 3. Starting the Head Block

* **Shift + A → Mesh → Cube**
* **Tab** – Enter Edit Mode
* **A** – Select all
* **Ctrl + B** – Bevel edges
* **Mouse Wheel** – Increase bevel segments

### Recommended

* **Ctrl + 2** – Add Subdivision Surface modifier (preview smoothing)
* **Right Click → Shade Smooth**

---

## 4. Symmetry & Topology Setup

* **Ctrl + R** – Add center edge loop
* **X → Faces** – Delete half of the mesh
* **Modifiers → Mirror**
* Enable **Clipping**

### Recommended

* **Alt + Z** – X-Ray mode (visibility when deleting half)
* **Shift + D** – Duplicate (backup before changes)

---

## 5. Eye Socket Creation

* **Face Select Mode (3)**
* **I** – Inset faces
* **X → Faces** – Delete inset faces
* **N Panel → Loop Tools → Circle**
* **G G** – Edge/vertex slide *(used heavily)*

### Recommended

* **Alt + Click** – Fast edge loop selection
* **S + Shift + Z** – Scale without depth distortion

---

## 6. Proportional Editing & Profile Shaping

* **O** – Toggle Proportional Editing
* **G** – Move vertices
* **R** – Rotate with proportional editing
* **Scroll Wheel** – Adjust influence radius

### Recommended

* **Alt + S** – Shrink/Fatten (volume control)
* **Shift + O** – Change falloff type

---

## 7. Mouth Formation

* **Face Select**
* **I** – Inset (Boundary disabled)
* **S + Z** – Scale vertically
* **E** – Extrude inward (mouth cavity)
* **G G** – Slide to clean topology

### Recommended

* **Ctrl + E → Edge Flow** – Smooth mouth loops
* **Alt + S** – Lip volume control

---

## 8. Nose Blocking

* **Face Select**
* **E** – Extrude outward
* **X → Faces** – Delete center face
* **I** – Inset nostrils
* **Loop Tools → Circle**
* **E** – Extrude inward (nostrils)
* **Ctrl + R** – Add bridge loops

### Recommended

* **Alt + Click** – Fast loop selection
* **Ctrl + B** – Soft bevel for stylized edges

---

## 9. Subdivision Preview

* **Add Modifier → Subdivision Surface**
* Toggle modifier visibility
* **Tab** – Switch modes to evaluate form

### Recommended

* **Ctrl + 1 / 2 / 3** – Subdivision preview levels

---

## 10. Refining Lips & Face

* **Ctrl + R** – Supporting loops
* **G G** – Slide for even spacing
* **Smooth Tool** (Toolbar)

### Recommended

* **Vertex → Smooth Vertices**
* **Mesh → Clean Up → Merge by Distance**

---

## 11. Cheeks, Jaw & Volume

* **Alt + S** – Shrink/Fatten
* **O** – Proportional Editing
* **G / R** – Shape jaw and cheeks

### Recommended

* **Sculpt Mode → Smooth Brush** (very light pass)
* **Shift + Space → Sculpt Mode**

---

## 12. Topology Cleanup

* **X → Faces**
* **Ctrl + F → Grid Fill**
* **V** – Rip vertices (fix pinching)

### Recommended

* **Ctrl + E → Bridge Edge Loops**
* **Shift + N** – Recalculate normals outside

---

## 13. Ear Creation

* Select faces
* **E** – Extrude ear base
* **Ctrl + R** – Add loops
* **Loop Tools → Circle**
* **Smooth Tool**
* **Ctrl + B** – Bevel center edge

### Recommended

* **Alt + S** – Control ear thickness
* **L** – Select linked geometry

---

## 14. Neck Creation

* **Face Select**
* **E** – Extrude downward
* **Loop Tools → Circle**
* **S** – Scale neck
* **Ctrl + R** – Add loops
* **V** – Rip (resolve loop collisions)
* **Ctrl + F → Grid Fill**

### Recommended

* **Alt + Click** – Fast loop selection
* **Alt + S** – Shape neck volume

---

## 15. Eyelids & Shape Keys

* **Object Data → Shape Keys → +**
* **Edit Mode**
* Select eyelid loop
* **S + Z** – Scale for closure
* **O** – Proportional Editing
* **Ctrl + R** – Blink support loops

### Recommended

* **Alt + S** – Eyelid thickness
* Use **Shape Key Slider** to test motion

---

## 16. Final Cleanup & Polish

* **Smooth Tool**
* **G G** – Reduce pinching
* **Alt + S** – Final volume pass
* **Ctrl + R** – Optional support loops

### Final Checks

* **Overlay → Face Orientation**
* **Shade Smooth + Auto Smooth**
* **Apply Mirror Modifier** (when finished)

---

## Core Shortcuts to Memorize

```text
Tab, G, R, S
Ctrl + R
I, E
O
G G
Alt + S
Ctrl + B
Alt + Click
```

These form the **foundation of character modeling in Blender** and represent what the tutorial teaches—both explicitly and implicitly.

---

If you want next steps, this can be easily converted into:

* A **printable cheat sheet**
* A **beginner-only shortcut list**
* A **feature-based map** (eyes, nose, mouth, ears)
* A **practice checklist**

Just say which one you want.
