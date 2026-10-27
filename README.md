# VTBIM — BIM and architectural documentation inside SketchUp

VTBIM turns SketchUp into an **Archicad-style** workflow: model with real BIM elements (walls, columns, beams,
slabs, roofs, doors, stairs…), draft 2D directly on the floor plan, **generate a full drawing set automatically**
(plans, elevations, sections, details, schedules), lay it out on sheets and export to **PDF / DWG**, all in one
SketchUp file.

## ⬇ Download

**[Download VTBIM 3.2.4 (.rbz)](https://github.com/mencom95/vtbim/releases/download/v3.2.4/vtbim_3.2.4.rbz)**

All versions: [Releases](https://github.com/mencom95/vtbim/releases)

**Requirements:** SketchUp 2024 or later, Windows.

## Installation

1. Open SketchUp → **Extensions → Extension Manager**.
2. Click **Install Extension** and pick the downloaded `vtbim_3.2.4.rbz`.
3. Restart SketchUp. The **VTBIM** menu and toolbar appear.

---

## Features

### 🧱 BIM modeling
- **Walls**: layered build-ups, automatic L / T joins, automatic door and window openings.
- **Columns, beams, slabs, roofs, ceilings**: parametric; change a parameter and the model rebuilds.
- **Doors, windows, openings, curtain walls**: snap to walls, live preview while hovering.
- **Stairs + railings**: concrete or steel stairs, landings, winders, continuous handrails.
- **Sanitary fixtures**: placed on the plan, with 2D symbols and 3D models.
- **Zones / rooms**: name, area, room stamp.
- **Element types**: layered assemblies, profiles, building materials; custom element definitions.
- **Stories**: story levels, copy elements between stories.

### ✏️ Archicad-style 2D drafting
- Live 2D floor plan straight from the model (Plan Viewer): lines, arcs, polylines, text, labels, images.
- **Fills / hatches** by material, hatch pattern library, line types, **pen sets** (print line weights).
- **Dimensions**: associative dimension chains, level markers, dimension trimming and arranging.
- **Grids** (with auto grid), section / elevation markers, custom symbols.
- Archicad muscle memory: Ctrl + click to trim, eyedropper / injector for properties, SketchUp-style grips,
  reference story (Trace), magnifier, copy 2D to another story.
- **Vietnamese SHX fonts** (Vnsimli…), TCVN3 and TrueType.

### 📐 Plans, elevations, sections
- **Sections, elevations and interior elevations** generated from the model with hidden-line removal.
- Cut walls / columns hatched by material.
- Each drawing keeps its own scale; text, dimensions and grid bubbles scale automatically.

### 📚 Automatic documentation
One command builds the architectural drawing set:
- **Architectural floor plans** and sub-plans: masonry walls & openings, column layout, beam layout,
  door layout, floor finishes, reflected ceiling & lighting.
- **Elevations, sections**, **stair** plans and sections, **restroom** drawings (one sheet per restroom).
- Automatic **multi-tier exterior dimensions**, grid bubbles, level markers, room stamps,
  door / slab tags that avoid overlapping each other.
- **Schedules** for columns, doors and fixtures that stay up to date; automatic beam layout.
- **Documentation check**: flags drawings that overflow the sheet, empty views and overlaps.

### 🗂 Sheet layout (LayoutBook) and publishing
- Sheets, **title blocks**, master layouts, project info, big views spanning several frames.
- Drawings on sheets update when the model changes.
- **PDF export** of the whole set at true scale; **DXF/DWG export** per sheet.
- Drawing management: Project Map, Navigator, Views, Revisions.

### 🔁 AutoCAD DWG / DXF
- **DWG/DXF import**: keeps layers, blocks, text, dimensions, hatches; layer mapping table.
- **DXF export** that opens cleanly in AutoCAD: real hatch, dimension and text entities,
  components exported as shared BLOCKs.

### 🏢 Facades and details
- **Facade** builder with profiles, materials and textures.
- **Detail library** of construction details, reusable in the drawing set.

### 🤖 AI control
- Built-in **MCP** server: Claude, ChatGPT / Codex… can read the model, create elements,
  and build and check the drawing set from natural-language instructions.

---

## Feedback and bug reports

Open an [Issue](https://github.com/mencom95/vtbim/issues) to report a bug or request a feature.
