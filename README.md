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


---

# Blender Character Head Modeling

### Master-Level Shortcut Reference (Block → Form → Detail)

This guide documents **practical Blender shortcuts and workflows** used by experienced character modelers when building a stylized or realistic head.
It focuses on *what professionals actually use* during production—not just what tutorials mention.

Use this as a **reference, checklist, or training aid** while modeling.

---

## 1. Blocking & Early Form (Most Important Stage)

### Core Shortcuts (Muscle Memory)

| Shortcut      | Purpose                     |
| ------------- | --------------------------- |
| `Tab`         | Toggle Object / Edit Mode   |
| `1 / 2 / 3`   | Vertex / Edge / Face select |
| `A / Alt + A` | Select / Deselect           |
| `G / R / S`   | Move / Rotate / Scale       |
| `Ctrl + R`    | Add edge loops              |
| `Alt + Click` | Select edge/face loops      |

### Workflow Recommendations

* Work in **Orthographic View** (`Numpad 5`) to avoid perspective distortion
* **Disable Subdivision** during blocking — the form must work unsmoothed
* Keep topology minimal and readable

### Useful Power Moves

* `Shift + D` — Duplicate before major changes (manual checkpoints)
* `M → New Collection` — Organize head, eyes, references
* `.` (Period) — Focus view on selection

---

## 2. Eyes & Eye Sockets (Topology-Critical)

### Essential Tools

| Shortcut            | Use                    |
| ------------------- | ---------------------- |
| `I`                 | Inset for eye loops    |
| Loop Tools → Circle | Even circular topology |
| `G G`               | Edge/vertex sliding    |
| `O`                 | Proportional Editing   |

### Advanced Control

* `Alt + S` — Adjust eye depth without breaking loops
* `Ctrl + E → Edge Flow` — Fix uneven topology
* `Shift + O` — Change proportional falloff (Sharp / Sphere recommended)

**Rule:**
If eye loops look bad *before* subdivision, they will look worse *after*.

---

## 3. Nose (Common Failure Point)

### Core

| Shortcut   | Use                      |
| ---------- | ------------------------ |
| `E`        | Extrusion                |
| `I`        | Nostril inset            |
| `Ctrl + R` | Bridge and support loops |
| `G G`      | Refine width             |

### Shape Control

* `Alt + S` — Nostril thickness
* `S + Shift + Z` — Scale without depth distortion
* Constant side-view checks (`Numpad 3`)

**Tip:** Shape the nose from the **side view first**, not the front.

---

## 4. Mouth & Lips (Expression-Ready Topology)

### Essentials

| Shortcut   | Use                |
| ---------- | ------------------ |
| `I`        | Lip loops          |
| `E`        | Mouth cavity       |
| `Ctrl + R` | Support loops      |
| `O`        | Smooth transitions |

### Advanced Techniques

* `Alt + Click` — Select full lip rings
* `Alt + S` — Control lip volume
* `Ctrl + B` (very small) — Stylized lip crease

**Animation Guideline:**
Minimum **4–5 edge loops** around the mouth for clean deformation.

---

## 5. Cheeks, Jaw & Head Volume

### Core

| Shortcut  | Use               |
| --------- | ----------------- |
| `Alt + S` | Volume shaping    |
| `O`       | Soft transitions  |
| `R`       | Rotate skull mass |

### High-Level Adjustments

* Select back of head → `Alt + S` to fix flat skulls
* Light Sculpt Mode → Smooth **only** for final relaxation

**Rule:** Faces are volumetric, not flat planes.

---

## 6. Ears (Simplified, Clean Topology)

### Essentials

| Shortcut            | Use             |
| ------------------- | --------------- |
| `E`                 | Extrusion       |
| `Ctrl + R`          | Structure       |
| Loop Tools → Circle | Clean base      |
| Smooth Tool         | Stylized finish |

### Efficiency Tips

* `L` — Select entire ear
* `Alt + S` — Thickness
* `Ctrl + B` — Inner ridge definition

**Note:** Stylized ears should remain simple and readable.

---

## 7. Neck & Head Transitions

### Core

| Shortcut               | Use            |
| ---------------------- | -------------- |
| `E`                    | Neck extrusion |
| Loop Tools → Circle    | Clean base     |
| `Alt + S`              | Thickness      |
| `Ctrl + F → Grid Fill` | Clean topology |

### Cleanup

* `V` — Rip to resolve congestion
* `Shift + N` — Recalculate normals

---

## 8. Eyelids & Shape Keys (Pro-Level Check)

### Essentials

| Tool       | Use           |
| ---------- | ------------- |
| Shape Keys | Blink testing |
| `S + Z`    | Close eyelids |
| `O`        | Smooth motion |

### Rigging Prep

* `Alt + S` — Eyelid thickness
* `Ctrl + R` — Extra deformation loops

**Golden Rule:**
If eyelids blink cleanly, the topology is correct.

---

## 9. Cleanup & Final Polish

### Core Cleanup

* Mesh → Clean Up → **Merge by Distance**
* `Shift + N` — Fix normals
* Smooth Tool — Relax pinching

### Final Checks

* Overlay → **Face Orientation**
* Shade Smooth + Auto Smooth
* Apply Mirror Modifier **last**

---

## Modeling Mindset (Most Important)

### Do

* Block **multiple heads**, not one perfect model
* Work **without subdivision first**
* Constantly check **front, side, and 3/4 views**

### Avoid

* Adding loops too early
* Sculpting instead of modeling
* Chasing perfection in the first pass

---




---

# Blender Character Body / Torso Modeling

### Practical Shortcut Reference (Block → Structure → Transitions → Refinement)

This document lists the **actual Blender shortcuts and workflows** used by character artists when blocking and structuring a torso.
It focuses on **body mass, shoulder/hip transitions, and topology flow**, not beginner explanations.

Use it as a **modeling checklist or quick-reference** while working.

---

## 1. Initial Torso Block (Low-Resolution Start)

### Core Shortcuts

| Shortcut                  | Purpose                        |
| ------------------------- | ------------------------------ |
| `Shift + A → Mesh → Cube` | Fast, clean torso base         |
| `Tab`                     | Switch Object / Edit Mode      |
| `Ctrl + R`                | Add central loop for symmetry  |
| `X → Vertices/Faces`      | Delete half before mirroring   |
| Mirror Modifier           | Enforce symmetry               |
| `Numpad 1 / 3`            | Front & side proportion checks |
| `G / S`                   | Shape overall body mass        |

### Efficiency Boosters

| Shortcut           | Reason                            |
| ------------------ | --------------------------------- |
| `.` (Period)       | Focus view on torso               |
| `Alt + Z`          | X-Ray for volume judgment         |
| `Ctrl + A → Scale` | Prevents deformation issues later |

---

## 2. Establishing Torso Curvature (Chest → Back → Hips)

### Actively Used

| Shortcut              | Use                                 |
| --------------------- | ----------------------------------- |
| `Ctrl + R` (multiple) | Separate chest, abdomen, hips       |
| `G G`                 | Adjust curvature without distortion |
| `R`                   | Tilt loops for spine flow           |
| `Alt + S`             | Push/pull volume cleanly            |

### Pro-Level Control

| Shortcut        | Why                               |
| --------------- | --------------------------------- |
| `O`             | Smooth transitions between masses |
| `Shift + O`     | Change falloff (Sharp for waist)  |
| `S + Shift + Z` | Scale width without depth change  |

---

## 3. Torso → Hip Transition (“Undergarment” Mental Model)

### Core Tools

| Shortcut          | Use                          |
| ----------------- | ---------------------------- |
| Face Select (`3`) | Work in faces for clean flow |
| `E`               | Extrude hip base             |
| `F`               | Fill gaps                    |
| `Ctrl + B`        | Establish groin edge flow    |

### Cleanup & Precision

| Shortcut            | Reason                   |
| ------------------- | ------------------------ |
| `Alt + Click`       | Select hip loops quickly |
| Loop Tools → Circle | Even groin opening       |
| `Alt + S`           | Control hip thickness    |

---

## 4. Shoulder Transition (Topology-Critical Area)

### Required

| Shortcut              | Use                                 |
| --------------------- | ----------------------------------- |
| `Ctrl + R`            | Shoulder support loops              |
| `G G`                 | Slide verts without collapsing form |
| `E`                   | Shoulder extrusion                  |
| `M → Merge at Center` | Redirect edge flow                  |

### Advanced Fixes

| Shortcut               | Purpose                 |
| ---------------------- | ----------------------- |
| `K` (Knife)            | Manual edge redirection |
| `Ctrl + E → Edge Flow` | Repair distorted loops  |
| `Alt + S`              | Shoulder roundness      |

**Topology Rule:**
Shoulder loops must flow **into the arm**, not terminate at the torso.

---

## 5. Hip & Leg Attachment Preparation

### Core

| Shortcut    | Use                     |
| ----------- | ----------------------- |
| `X → Faces` | Remove bottom faces     |
| `E`         | Extrude hip socket      |
| `Ctrl + B`  | Define groin transition |
| `Ctrl + R`  | Add transition loops    |

### Speed Tools

| Shortcut  | Why                       |
| --------- | ------------------------- |
| `L`       | Select entire hip section |
| `Alt + S` | Leg socket thickness      |
| `G G`     | Even loop spacing         |

---

## 6. Cleanup, Flow Fixes & Control

### Essential Cleanup

| Shortcut          | Use                 |
| ----------------- | ------------------- |
| `Shift + N`       | Recalculate normals |
| Merge by Distance | Remove overlaps     |
| Shade Smooth      | Read form clearly   |

### Light Relaxation

| Shortcut                          | Use                |
| --------------------------------- | ------------------ |
| Sculpt Mode → Smooth (very light) | Relax pinching     |
| Disable Subdivision while editing | See true topology  |
| `Ctrl + 2`                        | Quick SubD preview |

---

## 7. Volume & Proportion Checks (Daily Habits)

| Shortcut       | Purpose                |
| -------------- | ---------------------- |
| `Numpad 5`     | Orthographic accuracy  |
| MMB Rotate     | Silhouette inspection  |
| `Alt + Z`      | Internal volume checks |
| Constant `G G` | Micro-adjustments      |

---

## High-Level Modeling Principles (Not Keybinds)

These save more time than any shortcut:

* Low resolution = faster decisions
* Fix transitions **before** adding limbs
* Silhouette > surface detail
* If SubD looks bad, the base mesh is bad
* Topology follows **movement**, not anatomy charts

---

